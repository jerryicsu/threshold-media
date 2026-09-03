# threshold-media

THRESHOLD 影片系列的媒體資產。透過 GitHub Pages 提供，供
[threshold.pages.dev](https://threshold.pages.dev) 的捲動頁以 Range 請求 scrub。

GitHub Pages 支援 Range 請求（實測 206 Partial Content + `Accept-Ranges: bytes`），
單檔上限 100 MB——這是捲動頁能運作的前提，沒有 Range 就沒有 scrub。

| 集 | 檔 | 大小 |
|---|---|---|
| 01 THE WAREHOUSE | `the-warehouse/CutB_720p_web.mp4` | 35.3 MiB · 76s · 720p · `-g 4` |
| 02 THE CONTAINER SHIP | `the-container-ship/CutB_720p_web.mp4` | 28.3 MiB · 76.04s · 720p · `-g 4` |

影片畫面由 AI 生成，僅供示意。
