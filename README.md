# 古河渚 (Furukawa Nagisa) Theme for CF-Server-Monitor

🌸 为 [CF-Server-Monitor](https://github.com/huilang-me/CF-Server-Monitor) 量身定制的《CLANNAD》古河渚主题。

> *“在光与樱花之间，守候每一次连接。”*

---

## ✨ 主题特性

- **专属角色主视觉**：古河渚（Nagisa Furukawa）同人立绘、双呆毛、光坂制服、粉色团子、樱花坡道与光玉氛围。
- **双配色系统**：
  - **晴空（Light Mode）**：樱瓣白 (`#f4f7fb`) 底色、和纸浅白卡片 (`#fffdfb`)、天蓝边框 (`#d6e1eb`) 与深青黛文字。
  - **月夜（Dark Mode）**：幻想深海夜蓝 (`#0d1527`)、暮光卡片 (`#152338`)、金曜光玉高光 (`#f6e2b5`)。
- **全端响应式**：针对桌面端（1440px+）与移动端（320px / 390px+）深度优化，触控目标 ≥ 38px，人物立绘自适应避让不挡文字。
- **动效与无障碍**：支持柔和光玉浮动与团子组件，完整兼容 `prefers-reduced-motion: reduce`。
- **100% 官方契约兼容**：无缝支持实时 WebSocket 推送、多节点筛选、条形/环形/列表/地图四重视图、历史指标图表及 `/admin#admin` 统一管理后台跳转。

---

## 🚀 安装与使用

### 方式一：在后台主题管理中加载（推荐）

1. 进入 CF-Server-Monitor 管理后台（`/admin#admin`） -> **外观设置 / 主题商店**。
2. 在 **自定义第三方主题** 输入框中粘贴本仓库地址：

```text
https://github.com/Asakushen/cfsm-theme-nagisa/tree/main
```

3. 点击 **保存并应用** 即可生效！

*(提示：也可以使用固定的 Commit ID 地址以防止意外变更)*

---

## 📦 目录结构规范

符合 CF-Server-Monitor 官方第三方主题规范：

```text
cfsm-theme-nagisa/
├── index.html        # 主题入口
├── assets/           # CSS、JS、WebP 字体与静态资产
├── README.md
└── LICENSE
```

---

## 布局与动效更新

- 桌面环形视图采用统一横向信息卡：左侧节点身份、状态与规格，中间紧凑 CPU / RAM / Disk 三环，右侧流量及三网质量。单节点与多节点分组保持同一列宽；700–1099px 两列加底部网络区，窄屏保留紧凑单列。
- 团子采用固定正圆底座，完整保留五只团子，不拉伸图片。
- 支持半透明磨砂表面、非线性缓动与页脚缓慢流光；不支持背景模糊时保留不透明底色。系统开启减少动态效果时，同时停用 CSS 与详情图表动画。
- 验证：320 / 390 / 768 / 1024 / 1440 / 1920px、浅色与深色、单/多节点及三网历史；34 项 Chromium 浏览器测试、1 项主题契约测试、37 项项目测试通过，20 份视口/配色 axe 检查无违规。测试使用本地演示数据，不代表真实节点状态。
- 发布保留上一版哈希资源，避免旧缓存页面在切换期间加载失败。上一版回滚地址：`https://github.com/Asakushen/cfsm-theme-nagisa/tree/ecb78afa2d093ecbc15560436eaa04a3e1716033`。

## 📄 声明与许可

- 本项目基于 [MIT License](LICENSE) 开源。
- 视觉元素为同人致敬创作，非官方商业素材。
