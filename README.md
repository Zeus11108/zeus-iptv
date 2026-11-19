# ZEUS IPTV starter

This is a first-stage personal IPTV web player prototype for an IPTV subscription you are authorized to use.

## Files
- `index.html`: responsive black-and-gold Xtream Codes web player prototype.
- `msx/start.json`: Media Station X start object.
- `msx/home.json`: MSX portal tile that opens the web player.

## Publish with GitHub Pages (phone-friendly)
1. Create a public GitHub repository named `zeus-iptv`.
2. Upload the files and folders from this ZIP, keeping the `msx` folder.
3. In repository Settings → Pages, deploy from the `main` branch and `/ (root)`.
4. Wait for GitHub Pages to publish. Your site will be `https://Zeus11108.github.io/zeus-iptv/`.
5. Replace `Zeus11108` in BOTH `msx/start.json` and `msx/home.json` with your GitHub username, then upload those two updated files.
6. In Media Station X, open Settings → Start Parameter → Setup. Enter:
   `https://Zeus11108.github.io/zeus-iptv`
   Confirm and choose Yes if prompted.

## Important limitations
- This is a prototype, not a certified LG webOS native app.
- Xtream API requests from a browser may fail if your provider does not allow CORS. Do not share your subscription credentials with anyone.
- Live playback depends on the provider's stream format and the TV browser's native codec support. The prototype uses HLS `.m3u8` for live streams and `.mp4` for movies.
- Series episode/season browsing and EPG are not implemented in this first stage.
- Credentials are held only in the current browser session; they are not saved by this project.
- Use only content you are legally entitled to access.
