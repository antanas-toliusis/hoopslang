# hoopslang.com

The website at **https://hoopslang.com**: a basketball jargon dictionary, drill library and coaching guide.

This repo is **public**, and GitHub Pages publishes everything in it, so keep it to files visitors need. The tools, notes and Claude skills behind the site are in the private repo `hoopslang-studio` (see its README).

## Files

| File | What |
|---|---|
| `index.html` | The whole site: one page with inline CSS and JS, no build step. |
| `*.mp4` | Videos played on the site. `intro.mp4` is the default clip; a term with its own video is listed in `VIDEOS` in `index.html`. |
| `og-image.png` | The picture shown when someone shares a hoopslang.com link (1200×630, logo B). |
| `apple-touch-icon.png` | The icon when someone adds the site to an iPhone home screen (180×180, logo B). |
| `CNAME` | Connects the domain. **Never delete or rename it**, or hoopslang.com goes offline. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. Keep it. |

## Publishing

Pushing to `main` puts changes live within about a minute. Nothing pushes this repo automatically, so every change goes live only when you push it.

- Never force-push.
- Keep each video under about 2 MB, because most visitors watch on phones.
