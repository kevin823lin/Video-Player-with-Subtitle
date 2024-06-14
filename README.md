EN | [正體中文](./README_TW.md)

# Video Player with Subtitle

## Usage

1. Name the video and subtitle files as `1.mp4`, `2.mp4`, `1.vtt`, `2.vtt`, and so on, and place them in the `./video/` and `./sub/` directories, respectively.

1. Modify the value of `max` in `index.html` to the number of videos.

1. Start a simple HTTP server (e.g., `http-server -p 80` or `python -m http.server 80`).

1. Go to <http://127.0.0.1> to see all video links.

1. Click on the video link to go to the video player.

1. Use the `spacebar` to toggle play/pause; use the `F/f key` to toggle fullscreen.
