# Simon Lecoq Portfolio — GitHub Pages copy

This folder is a static copy assembled from the supplied `Lecoq.io___Simon_Lecoq_s_online_portfolio_resources.zip` archive.

## Run locally

From this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## GitHub Pages

Upload the contents of this folder to a GitHub repository. In **Settings → Pages**, deploy from the branch/folder containing `index.html`.

The original site used root-absolute URLs (`/as/...`, `/@/...`). They have been changed to relative paths so the site also works when GitHub Pages serves it from a repository subpath such as `/my-portfolio/`.

## Included

- `index.html` — main portfolio page
- `as/v4/css/` — original CSS plus canonical filenames expected by the HTML
- `as/v4/js/` — original JavaScript libraries and portfolio code
- `as/v4/content/` — JSON content, artwork, feed images/videos
- `@/medias/` — local media/assets
- `access/`, `brain/`, `gamejam/`, `quadtree/`, `sound/` — captured project assets/pages
- `_external/` — captured external resources from the supplied archive

Some services remain external by design (for example Apple Music embeds and external GitHub/LinkedIn links); they are not recreated as local applications.
