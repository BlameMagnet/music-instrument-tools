# 乐理与乐器工具站（黑锅之王）

面向爱乐者的免费工具站：[https://heiguozhi.wang](https://heiguozhi.wang) —— 乐理与练琴小工具，以及多品牌乐器序列号查询与年份参考。

英文产品名：**Music & Instrument Tools** · 站长：**[BlameMagnet](https://github.com/BlameMagnet)**（中文署名：黑锅之王）

本仓库提供多语官网导览，以及用于反馈的 [Issues](https://github.com/BlameMagnet/music-instrument-tools/issues)。**不含站点源码**；线上站点另行维护。

## 语言

| 语言 | 文档 |
| --- | --- |
| English（默认入口） | [README.md](./README.md) |
| 简体中文 | [README.zh-Hans.md](./README.zh-Hans.md) |
| 繁體中文 | [README.zh-Hant.md](./README.zh-Hant.md) |

线上站点为三语：`zh-Hans` 在站点根路径，另有 `en` 与 `zh-Hant`。下列链接为简体中文地址；同一路径在 `/en/`、`/zh-Hant/` 下也有对应页（例如 `https://heiguozhi.wang/en/tools/tuner.html`）。

例外：`/about/support.html`（自愿打赏）仅中文语言提供，页面展示**微信**收款码。`/en/about/support.html` 会跳转到 `/en/about/site.html`。

## 工具

- [调音器](https://heiguozhi.wang/tools/tuner.html) — 通过麦克风实时检测音高，支持各类乐器调音。
- [节拍器](https://heiguozhi.wang/tools/metronome.html) — 带语音提示的节拍器，适合日常练习与节奏训练。
- [五度圈](https://heiguozhi.wang/tools/circle-of-fifths.html) — 可视化五度圈，帮助理解调号、相对大小调与常见和弦进行。
- [试音场](https://heiguozhi.wang/tools/tone-playground.html) — 自由组合效果器、箱头、箱体与 DI，在线试听电吉他/电贝司信号链。
- [和弦字典](https://heiguozhi.wang/tools/chord-dictionary.html) — 吉他 / 尤克里里多种和弦类型的主流指法图与构成音，可试听。
- [指板可视化](https://heiguozhi.wang/tools/fretboard.html) — 吉他 / 贝斯 / 尤克里里交互式指板，支持多种调弦、音阶和弦模板与试听。
- [音高频率参考](https://heiguozhi.wang/tools/pitch-frequency.html) — 基于可调 A4 标准音的 C0–C10 音名频率表，可试听。
- [音阶探索器](https://heiguozhi.wang/tools/scale-explorer.html) — 探索 20+ 种音阶，支持指板可视化与试听。
- [和弦进行构建器](https://heiguozhi.wang/tools/progression-builder.html) — 自定义级数排列与常见预设，支持 BPM 与播放。
- [鼓机](https://heiguozhi.wang/tools/rhythm-patterns.html) — 多种风格鼓机 Pattern，支持 BPM 调节与可视化播放。
- [音程听辨](https://heiguozhi.wang/tools/ear-training.html) — 音程听辨练习，支持多种难度与播放模式。
- [线规转换器](https://heiguozhi.wang/tools/wire-gauge-converter.html) — 在 AWG、SWG、公制/英制线径与横截面积之间快速换算。

## 序列号查询

以下为站点预设序中的重点品牌。更多品牌见[首页](https://heiguozhi.wang/)或 `/sn-decoders/{brand}.html`。

- [Gibson](https://heiguozhi.wang/sn-decoders/gibson.html)
- [Fender](https://heiguozhi.wang/sn-decoders/fender.html)
- [Epiphone](https://heiguozhi.wang/sn-decoders/epiphone.html)
- [Squier](https://heiguozhi.wang/sn-decoders/squier.html)
- [Ibanez](https://heiguozhi.wang/sn-decoders/ibanez.html)
- [PRS](https://heiguozhi.wang/sn-decoders/prs.html)
- [Martin](https://heiguozhi.wang/sn-decoders/martin.html)
- [Taylor](https://heiguozhi.wang/sn-decoders/taylor.html)
- [ESP / LTD](https://heiguozhi.wang/sn-decoders/esp-ltd.html)
- [Edwards / GrassRoots](https://heiguozhi.wang/sn-decoders/edwards-grassroots.html)

## 关于与支持

- [关于本站](https://heiguozhi.wang/about/site.html)
- [支持本站](https://heiguozhi.wang/about/support.html) — 仅中文语言；微信收款码
- [关于站长](https://heiguozhi.wang/about/author.html)
- [Sitemap](https://heiguozhi.wang/sitemap.xml) — 可索引 URL 全表
- [llms.txt](https://heiguozhi.wang/llms.txt) — 给 AI 爬虫用的精选导览

## 反馈

请通过 [GitHub Issues](https://github.com/BlameMagnet/music-instrument-tools/issues) 提交 bug、纠错（含解码结果问题）、功能建议或文案问题。

提交时尽量写明：

1. 页面 URL（若非简体，请带上语言路径）
2. 预期行为与实际现象
3. 若像客户端问题，附上浏览器 / 设备信息

## 说明

- 页面均为静态预渲染 HTML。
- 请勿抓取 `/7d/tone-playground/` 下的媒体、NAM 模型或 WASM（见站点 `/robots.txt`）。
- 序列号查询用于年份 / 产地等参考，**不是**真伪鉴定证书。
- 试音场为教学向仿真，并非各品牌官方产品。
