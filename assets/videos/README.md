# Videos

Place tutorial video files here (e.g. `getting-started.mp4`).

## How to add a video to the site

1. Add your `.mp4` file to this folder, for example `assets/videos/getting-started.mp4`.
2. In `index.html`, inside the `#tutorials` section (`.video-grid`), copy an existing
   `.video-card` block and update:
   - `<source src="assets/videos/getting-started.mp4" type="video/mp4" />`
   - the `<h4>` title
   - the `<p>` description
   - (optional) add a poster image: `<video controls preload="metadata" poster="assets/videos/getting-started.jpg">`

## Notes

- The site is static (GitHub Pages / plain HTML), so videos are served directly
  from the repository. Keep file sizes reasonable; GitHub recommends files under
  100 MB and warns above 50 MB.
- Recommended format: MP4 (H.264 + AAC) for broad browser support.
