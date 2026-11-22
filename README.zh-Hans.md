# 乐理与乐器工具站

面向练琴、乐理学习，以及多品牌器材序列号与部件日期码查询的在线工具站点。

网站：[https://heiguozhi.wang](https://heiguozhi.wang)

其他语言：[English](./README.md) · [繁體中文](./README.zh-Hant.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [Español](./README.es.md) · [Tiếng Việt](./README.vi.md) · [Bahasa Indonesia](./README.id.md) · [Português (Brasil)](./README.pt-BR.md) · [ภาษาไทย](./README.th.md)

## 工具

- [调音器](https://heiguozhi.wang/tools/tuner.html) — 通过麦克风实时检测音高，适用于吉他、贝斯、小提琴等乐器；支持调节全站共用的 A4 标准音（392–470 Hz）。
- [节拍器](https://heiguozhi.wang/tools/metronome.html) — 在线节拍器，支持拍号、拍速点选与可选语音提示，用于日常练习与节奏训练；页内另提供面向手表、小屏与旧浏览器的轻量版入口。
- [五度圈](https://heiguozhi.wang/tools/circle-of-fifths.html) — 可视化五度圈，覆盖七种教会调式，用于理解调性五度关系、大小调相对关系与常见和弦进行。适用于作曲、编曲与乐理学习。
- [试音场](https://heiguozhi.wang/tools/tone-playground.html) — 电吉他 / 电贝司信号链沙箱：可组合效果器、箱头、箱体 IR 与 DI，支持 A/B 对比、全链直通、干湿波形对照与链接分享音色链。部分箱头支持 NAM 采样音色；亦可接入麦克风或上传本地干声。属教学向仿真，并非任何品牌的官方产品。
- [和弦字典](https://heiguozhi.wang/tools/chord-dictionary.html) — 吉他与尤克里里和弦参考，涵盖大三、小三、七和弦、挂留等类型，提供开放把位与可移动指法、SVG 指法图、构成音与音频试听。
- [指板可视化](https://heiguozhi.wang/tools/fretboard.html) — 交互式指板，支持吉他、贝斯、尤克里里、曼陀铃、班卓琴，以及柳琴、琵琶、中阮、大阮、月琴等多种调弦，提供音阶与和弦模板、12 品教学窗 / 全品切换及音频预览。
- [音高频率参考](https://heiguozhi.wang/tools/pitch-frequency.html) — 基于十二平均律的频率表，A4 可在 392–470 Hz 间调节，列出 C0–C10 全部半音的理论频率，并支持逐音试听。
- [音阶探索器](https://heiguozhi.wang/tools/scale-explorer.html) — 收录二十余种音阶类型（大调、小调、五声、布鲁斯、对称与异域音阶等），支持多乐器定弦的指板可视化（12 品 / 全品）与音频试听。
- [和弦进行构建器](https://heiguozhi.wang/tools/progression-builder.html) — 按级数编排和弦进行，支持自定义序列、常见预设、BPM 调节与音频播放。
- [鼓机](https://heiguozhi.wang/tools/rhythm-patterns.html) — 按风格分类的鼓机节奏型库（摇滚、放克、桑巴、雷鬼等），支持 BPM 调节与可视化播放。
- [音程听辨](https://heiguozhi.wang/tools/ear-training.html) — 音程识别训练，提供多种音程集合与难度，支持上行、下行与和声播放，并统计正确率。
- [线规转换器](https://heiguozhi.wang/tools/wire-gauge-converter.html) — 面向乐器与音频布线场景，在 AWG、SWG、公制/英制线径与截面积之间换算。

## 器材序列号查询

精选高优先级品牌（与站点预设序一致）。其余乐器、音箱与效果器品牌见[首页](https://heiguozhi.wang/)或 `/sn-decoders/{brand}.html`。

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

### 部件日期码

- [Celestion](https://heiguozhi.wang/sn-decoders/celestion.html) — 吉他喇叭出厂日期码查询与生产年份参考（厂家字母码，非 EIA 体系）。
- [电位器](https://heiguozhi.wang/sn-decoders/pot.html) — 电吉他 / 贝斯电位器美制 EIA 源日期码查询，给出厂商与生产年周。
- [喇叭 EIA 日期码](https://heiguozhi.wang/sn-decoders/speaker-eia.html) — 吉他音箱美产喇叭（Jensen、Rola、Oxford、Utah、Eminence 等）EIA 源日期码查询。
- [变压器 EIA 日期码](https://heiguozhi.wang/sn-decoders/transformer-eia.html) — 美产复古吉他音箱电源牛、输出牛与扼流圈（Schumacher、Triad、Stancor 等）EIA 源日期码查询。

查询结果为生产年份及相关属性的估算（部件日期仅构成整机生产日期的下界），不构成真伪鉴定或估价依据。

## 关于

- [关于本站](https://heiguozhi.wang/about/site.html)
- [关于站长](https://heiguozhi.wang/about/author.html)
- [支持本站](https://heiguozhi.wang/about/support.html)

维护者：[BlameMagnet](https://github.com/BlameMagnet)（黑锅之王）。

## 反馈

解码结果错误、功能缺陷或功能建议，请通过 [GitHub Issues](https://github.com/BlameMagnet/music-instrument-tools/issues) 提交，并附页面 URL 与简要说明。
