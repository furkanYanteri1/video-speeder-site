# video-speeder-site

Legal and support pages for **Video Speeder**, a Canva app that speeds up a video already placed on the canvas beyond Canva's native 2x limit, up to 50x, and replaces it in place with the processed result.

| Page | Link |
|---|---|
| Terms and Conditions | https://furkanyanteri1.github.io/video-speeder-site/terms.html |
| Privacy Policy | https://furkanyanteri1.github.io/video-speeder-site/privacy.html |
| Support | https://furkanyanteri1.github.io/video-speeder-site/support.html |

Static HTML, hosted on GitHub Pages. Canva requires every submitted app to link to publicly reachable terms, privacy and support pages, and these are the ones registered in the Canva Developer Portal listing.

## About the app itself

Video Speeder is built with React and TypeScript on the Canva Apps SDK, with a Node.js and Express backend running native FFmpeg in Docker. Processing happens server side because Canva's content security policy blocks Web Workers, which rules out in browser encoding with ffmpeg.wasm. The app is currently in Canva's review queue.

The app source is kept in a separate repository. This one holds only the published pages.
