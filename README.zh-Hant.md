# 樂理與樂器工具站（黑鍋之王）

面向愛樂者的免費工具站：[https://heiguozhi.wang](https://heiguozhi.wang) —— 樂理與練琴小工具，以及多品牌樂器序號查詢與年份參考。

英文產品名：**Music & Instrument Tools** · 站長：**[BlameMagnet](https://github.com/BlameMagnet)**（中文署名：黑鍋之王）

本倉庫提供多語官網導覽，以及用於回饋的 [Issues](https://github.com/BlameMagnet/music-instrument-tools/issues)。**不含站點原始碼**；線上站點另行維護。

## 語言

| 語言 | 文件 |
| --- | --- |
| English（預設入口） | [README.md](./README.md) |
| 简体中文 | [README.zh-Hans.md](./README.zh-Hans.md) |
| 繁體中文 | [README.zh-Hant.md](./README.zh-Hant.md) |

線上站點為三語：`zh-Hans` 在站點根路徑，另有 `en` 與 `zh-Hant`。下列連結為簡體中文地址；同一路徑在 `/en/`、`/zh-Hant/` 下也有對應頁（例如 `https://heiguozhi.wang/zh-Hant/tools/tuner.html`）。

例外：`/about/support.html`（自願打賞）僅中文語言提供，頁面展示**微信**收款碼。`/en/about/support.html` 會跳轉到 `/en/about/site.html`。

## 工具

- [調音器](https://heiguozhi.wang/zh-Hant/tools/tuner.html) — 透過麥克風即時偵測音高，支援各類樂器調音。
- [節拍器](https://heiguozhi.wang/zh-Hant/tools/metronome.html) — 帶語音提示的節拍器，適合日常練習與節奏訓練。
- [五度圈](https://heiguozhi.wang/zh-Hant/tools/circle-of-fifths.html) — 可視化五度圈，幫助理解調號、相對大小調與常見和弦進行。
- [試音場](https://heiguozhi.wang/zh-Hant/tools/tone-playground.html) — 自由組合效果器、箱頭、箱體與 DI，線上試聽電吉他/電貝斯訊號鏈。
- [和弦字典](https://heiguozhi.wang/zh-Hant/tools/chord-dictionary.html) — 吉他 / 烏克麗麗多種和弦類型的主流指法圖與構成音，可試聽。
- [指板可視化](https://heiguozhi.wang/zh-Hant/tools/fretboard.html) — 吉他 / 貝斯 / 烏克麗麗互動式指板，支援多種調弦、音階和弦模板與試聽。
- [音高頻率參考](https://heiguozhi.wang/zh-Hant/tools/pitch-frequency.html) — 基於可調 A4 標準音的 C0–C10 音名頻率表，可試聽。
- [音階探索器](https://heiguozhi.wang/zh-Hant/tools/scale-explorer.html) — 探索 20+ 種音階，支援指板可視化與試聽。
- [和弦進行建構器](https://heiguozhi.wang/zh-Hant/tools/progression-builder.html) — 自訂級數排列與常見預設，支援 BPM 與播放。
- [鼓機](https://heiguozhi.wang/zh-Hant/tools/rhythm-patterns.html) — 多種風格鼓機 Pattern，支援 BPM 調節與可視化播放。
- [音程聽辨](https://heiguozhi.wang/zh-Hant/tools/ear-training.html) — 音程聽辨練習，支援多種難度與播放模式。
- [線規轉換器](https://heiguozhi.wang/zh-Hant/tools/wire-gauge-converter.html) — 在 AWG、SWG、公制/英制線徑與橫截面積之間快速換算。

## 序號查詢

以下為站點預設序中的重點品牌。更多品牌見[首頁](https://heiguozhi.wang/zh-Hant/)或 `/zh-Hant/sn-decoders/{brand}.html`。

- [Gibson](https://heiguozhi.wang/zh-Hant/sn-decoders/gibson.html)
- [Fender](https://heiguozhi.wang/zh-Hant/sn-decoders/fender.html)
- [Epiphone](https://heiguozhi.wang/zh-Hant/sn-decoders/epiphone.html)
- [Squier](https://heiguozhi.wang/zh-Hant/sn-decoders/squier.html)
- [Ibanez](https://heiguozhi.wang/zh-Hant/sn-decoders/ibanez.html)
- [PRS](https://heiguozhi.wang/zh-Hant/sn-decoders/prs.html)
- [Martin](https://heiguozhi.wang/zh-Hant/sn-decoders/martin.html)
- [Taylor](https://heiguozhi.wang/zh-Hant/sn-decoders/taylor.html)
- [ESP / LTD](https://heiguozhi.wang/zh-Hant/sn-decoders/esp-ltd.html)
- [Edwards / GrassRoots](https://heiguozhi.wang/zh-Hant/sn-decoders/edwards-grassroots.html)

## 關於與支持

- [關於本站](https://heiguozhi.wang/zh-Hant/about/site.html)
- [支持本站](https://heiguozhi.wang/zh-Hant/about/support.html) — 僅中文語言；微信收款碼
- [關於站長](https://heiguozhi.wang/zh-Hant/about/author.html)
- [Sitemap](https://heiguozhi.wang/sitemap.xml) — 可索引 URL 全表
- [llms.txt](https://heiguozhi.wang/llms.txt) — 給 AI 爬蟲用的精選導覽

## 回饋

請透過 [GitHub Issues](https://github.com/BlameMagnet/music-instrument-tools/issues) 提交 bug、糾錯（含解碼結果問題）、功能建議或文案問題。

提交時盡量寫明：

1. 頁面 URL（若非簡體，請帶上語言路徑）
2. 預期行為與實際現象
3. 若像用戶端問題，附上瀏覽器 / 裝置資訊

## 說明

- 頁面均為靜態預渲染 HTML。
- 請勿抓取 `/7d/tone-playground/` 下的媒體、NAM 模型或 WASM（見站點 `/robots.txt`）。
- 序號查詢用於年份 / 產地等參考，**不是**真偽鑑定證書。
- 試音場為教學向仿真，並非各品牌官方產品。
