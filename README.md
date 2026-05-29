# Dash social media images (host these for Zernio)

48 cards (24 designs x portrait 1080x1350 + story 1080x1920), flat filenames, no spaces, so they make clean public URLs.

## Fastest way to host (GitHub raw)
1. Create a new GitHub repo, e.g. `dash-social-media` (public).
2. Upload everything in this folder to the repo root (drag-and-drop in github.com works).
3. Each image is then public at:
   https://raw.githubusercontent.com/<your-username>/dash-social-media/main/<filename>
   e.g. https://raw.githubusercontent.com/<your-username>/dash-social-media/main/blog_playbook_portrait.png
4. Send me your username/repo and I'll fill the "Image URL" column in Dash Social Calendar.xlsx automatically.

## Alternative: GitHub Pages
Enable Pages on the repo (Settings -> Pages -> main branch). URLs become:
   https://<your-username>.github.io/dash-social-media/<filename>

## Notes
- manifest.csv lists every file and its eventual URL (replace USERNAME/dash-social-media with your actual repo).
- Use the portrait files for IG + Facebook feed, story files for IG/FB Stories.
- Once hosted, these URLs go straight into Zernio (posts_create media_urls=...).
