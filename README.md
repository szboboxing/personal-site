# 杰克陈 · 个人站点（personal-site）

独立开发者作品集网站，**一套内容 × 八种视觉主题**，部署在 Cloudflare Pages：**https://szjack.pages.dev**

纯静态 HTML 单文件架构（每页一个 HTML，零构建、零依赖、CDN 直出），包含完整的深色/浅色双主题、移动端适配、留言板与版本时间线等交互。

## 八个主题风格页

同一份作品集内容，八种完全不同的视觉语言，每页独立配色、动效与排版：

| 文件 | 主题 | 风格关键词 | 主色 |
|---|---|---|---|
| [index.html](index.html) | 鎏金 · Obsidian Gold | 金属锥形描边、鎏金玻璃卡片、暗色奢华 | `#D9B57D` |
| [index2.html](index2.html) | 几何 · Geometry | 六边形脉冲、轨道旋转、终端青线条 | `#38BDF8` |
| [index3.html](index3.html) | 电路 · Circuit | PCB 走线装饰、电路板纹理 | `#2DD4BF` |
| [index4.html](index4.html) | 紫玻璃 · Purple Glass | 毛玻璃层叠、紫色渐变光晕 | `#8B5CF6` |
| [index5.html](index5.html) | 极光 · Aurora | 极光带模糊流动、青绿光晕 | `#5EEAD4` |
| [index6.html](index6.html) | 终端 · Terminal | 命令行窗口、等宽字体、终端青 | `#22D3EE` |
| [index7.html](index7.html) | 霓虹 · Neon AI Core | AI 芯片质感、霓虹粉紫渐变 | `#F472D0` |
| [index8.html](index8.html) | 北欧 · Nordic | 唯一浅色主题、无阴影无圆角、细线留白 | `#A8A29E` |

### 每页通用能力

- **作品集**：7 个项目卡片（含痛点 PAIN / 方案 FIX / 技术栈 chips / GitHub 与在线演示双按钮）
- **版本时间线**：桌面端 RELS 数据渲染 + 移动端时间线，直达各项目 GitHub Release
- **悬浮快捷导航**：八主题一键互切 + 项目演示直达
- **留言板**：本地暂存 + 打赏二维码弹窗
- **深色/浅色切换**（index8 为常亮浅色）
- **响应式**：桌面 / 平板 / 手机三档适配

## 附属页面

| 文件 | 说明 |
|---|---|
| [404.html](404.html) | 404 页面，含八主题风格的 APPS 导航 |
| [property-ledger.html](property-ledger.html) | 物业管理台账在线版（HTML 单文件版） |
| [radio.html](radio.html) | 音波陪伴（网络收音机） v1.4 在线版 |
| [switcher-preview.html](switcher-preview.html) | 风格切换器两款方案预览 |

## 收录作品（7 个）

| 项目 | 版本 | 更新 | 仓库 |
|---|---|---|---|
| 物业管理台账 Property Ledger（Docker 版） | v2.4 | 2026-10-14 | [property-ledger](https://github.com/szboboxing/property-ledger) |
| 物业管理台账 HTML 单文件版 | v1.4 | 2026-10-14 | [property-ledger-html](https://github.com/szboboxing/property-ledger-html) |
| 物业管理台账 PHP 版 | v1.0 | 2026-10-16 | [property-ledger-php](https://github.com/szboboxing/property-ledger-php) · [在线演示](http://chinacn.gt.tc) |
| 下载流程优化工具 | v3.18 | 2026-09-25 | [download-optimizer](https://github.com/szboboxing/download-optimizer) |
| 鼠标手势动作小工具 | V2.5 | 2026-10-05 | [mouse-gesture-actions](https://github.com/szboboxing/mouse-gesture-actions) |
| 音波陪伴（网络收音机） | v1.4 | 2026-10-24 | [Radio-Box](https://github.com/szboboxing/Radio-Box) |
| 鼠标Pro MousePro | v1.0.1 | 2026-10-08 | [MousePro](https://github.com/szboboxing/MousePro) |

## 技术栈

- 纯 HTML / CSS / Vanilla JavaScript，单文件零构建
- Tailwind CSS（CDN）+ 每页独立 CSS 变量主题系统
- Chart.js（账单可视化）、Google Fonts（Noto Sans SC / JetBrains Mono / Space Grotesk 等按页各异）
- 部署：Cloudflare Pages（`wrangler pages deploy`），源仓库 CNB `szjack/personal-site`

## 本地预览与部署

```bash
# 直接双击任意 index*.html 即可预览，或起一个静态服务
python -m http.server 8080
```

```bash
# Cloudflare Pages 部署
wrangler pages deploy . --project-name=szjack --branch=main
```

## 仓库镜像

- CNB：https://cnb.cool/szjack/personal-site
- GitHub：https://github.com/szboboxing/personal-site

---

© 2025–2026 杰克陈 · 欢迎访问个人站点 https://szjack.pages.dev 有彩蛋哦~
