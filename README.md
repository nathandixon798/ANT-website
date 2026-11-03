# A New Thing London — Start Here page

A one-page landing site for the QR code on our evangelism cards.

## Editing links
Every button reads from the `LINKS` object near the top of the `<script>` in `index.html`.
Paste a full URL (Google Drive, Canva, YouTube…) or a path to a file in this folder.

The **New to Faith Guide** points to `resources/new-to-faith-guide.pdf` — create a `resources`
folder here and drop the PDF in with that exact name (or swap in a Drive link).

## Going live
No build step: upload this whole `site` folder (index.html + assets/) to any static host,
e.g. Netlify Drop (app.netlify.com/drop), GitHub Pages or Cloudflare Pages.
Point the QR code at the final URL (ideally a custom domain you control, so the printed
cards keep working even if you change host).
