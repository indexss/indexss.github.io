# Personal Homepage Usage Guide

This repository powers the personal homepage at:

https://indexss.github.io

## Local preview

Start the local Jekyll server:

```bash
bash run_server.sh
```

Then open:

```text
http://127.0.0.1:4000
```

Most content changes will refresh automatically. If you edit `_config.yml`, restart the server.

## Common files to edit

- `_pages/about.md`: main homepage content, including About, News, Publications, Projects, Honors, Education, and Experience.
- `_config.yml`: site title, author profile, avatar, email, GitHub, LinkedIn, favicon-related metadata, and repository settings.
- `_data/navigation.yml`: top navigation items and section anchors.
- `assets/css/main.scss`: custom page styles.
- `_sass/_sidebar.scss`: profile/sidebar styles.
- `images/`: avatar, favicon, project images, and other static images.

## Deploy

After making changes:

```bash
git status
git add _pages/about.md _config.yml _data/navigation.yml assets/css/main.scss _sass/_sidebar.scss images/your-image.png
git commit -m "Update homepage"
git push origin main
```

Adjust the `git add` command to include only the files you actually changed. Avoid blindly adding unused large images.

GitHub Pages will rebuild automatically after the push. The public site usually updates within a few minutes:

```text
https://indexss.github.io
```

If the old page still appears, wait a few minutes or hard-refresh the browser. GitHub Pages and CDN caching can lag briefly.

## Notes

- Do not commit local dependency folders such as `vendor/` or `.gems/`.
- The local preview URL is always `http://127.0.0.1:4000`; source files such as `_pages/about.md` are not preview URLs.
- Unused large images should be kept out of git unless they are actually used by the site.
