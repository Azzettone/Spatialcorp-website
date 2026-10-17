# DWG Files

Place downloadable DWG files here (e.g. `system-layout.dwg`).

## How to add a download to the site

1. Add your `.dwg` file to this folder, for example `assets/dwg/system-layout.dwg`.
2. In `index.html`, inside the `#downloads` section (`.download-list`), copy an
   existing `.download-item` block and update:
   - `<a href="assets/dwg/system-layout.dwg" class="btn-download" download>Download</a>`
   - the `<h4>` title
   - the `<p>` description
   - the `<span class="download-file">` file name

## Notes

- The site is static (GitHub Pages / plain HTML), so files are served directly
  from the repository. Keep file sizes reasonable (GitHub warns above 50 MB).
- You can also bundle multiple files as a `.zip` if preferred.
