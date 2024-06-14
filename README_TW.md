[EN](./README.md) | 正體中文

# Video Player with Subtitle

## 使用方法

1. 將影片檔與字幕檔按照 `1.mp4`、`2.mp4`、`1.vtt`、`2.vtt` 的方式命名，以此類推，分別放在 `./video/` 與 `./sub/` 裡面。

1. 將 `index.html` 中 `max` 的數值修改成影片數量。

1. 開個簡單的http伺服器。（像是 `http-server -p 80` 或是 `python -m http.server 80`）

1. 前往 <http://127.0.0.1> 查看所有影片連結。

1. 點擊影片連結前往影片播放器。

1. 使用 `空白鍵` 可以切換播放暫停；使用 `F/f 鍵` 可以切換全螢幕。
