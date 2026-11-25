# 上架自检清单（itch.io · HTML5 项目）

## 一、打包前

- [ ] `index.html` 放在 zip 的**根目录**，不是子文件夹里（itch 只认根目录的 index.html）。
- [ ] 压缩包内没有中文文件名路径（`README.md` / `THIRD_PARTY.md` 已是英文名）。
- [ ] 单文件能 `file://` 双击直接进主菜单，`继续前缘` 后控制台无报错。
- [ ] 断网打开仍可玩（three.js 已内联，无外链）。
- [ ] 包体 < 500 MB（当前约 2.5 MB，远低于上限）。

## 二、项目设置（Project details）

- [ ] Kind of project：`HTML`
- [ ] Pricing：先设 `No payment required`（或勾 `$0 or more`，让喜欢的人打赏）
- [ ] Title：`南海仙岛 · 鹿回头（3D 探索版）`
- [ ] Short description（一句话，≤ 60 字）：海南鹿回头半岛的低多边形夜游，五处地标、十六条岛志，把停过的地方刻成一张卡。
- [ ] Classification：`Game`；Genre：`Adventure` / `Exploration`
- [ ] Tags：`chinese`、`low-poly`、`exploration`、`hainan`、`mythology`
- [ ] Inputs：`Keyboard`、`Mouse`
- [ ] Player count：`Single player`
- [ ] AI 生成声明：封面/概念图为 AI 生成，勾选 itch 的 `AI generated assets`（不勾会被举报下架）

## 三、上传与显示

- [ ] 上传 zip 后，勾 `This file will be played in the browser`
- [ ] Embed 尺寸建议 `1280 × 720`，勾 `Fullscreen button`、`Mobile friendly`（可选）
- [ ] Viewport：`Landscape`，并勾 `Enable scrollbars` 关掉（游戏自己处理滚动）
- [ ] 试玩一下：能进菜单、能继续存档、能读岛志、能导出 PNG
- [ ] 封面：上传 `cover_630x500.png`（itch 封面位要求 ≥ 315×250，推荐 630×500）
- [ ] 页首图：上传 `cover_1200x630.png` 作为 banner
- [ ] 截图：3–5 张，建议 1280×720（主菜单、3D 场景、岛志长图、卡背摘录卡、图鉴）

## 四、发布前最后 5 分钟

- [ ] 描述里写清操作键位（WASD / 鼠标 / E / 长按回卷首），免得玩家一进来就退。
- [ ] 描述里写“存档在浏览器本地，换设备会丢”，降低差评。
- [ ] 标注“非官方文旅产品，题材取自鹿回头传说”。
- [ ] 页面 URL 用自定义短名，例如 `xxx.itch.io/luhuitou-3d`。
- [ ] 发布后自己用手机浏览器再开一次，确认 iframe 里能玩。

## 五、国内平台（另案，别混在一起）

- 微信/抖音小游戏需小游戏备案；含虚拟支付还需版号 + 软著，主体基本须企业。
- 想在国内大流量渠道曝光，先走“B 站/小红书视频 + 网页链接”的软路径，不必先做小游戏改造。
