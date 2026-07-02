# EE.CD - 3D Gravity Ball Domain Name Search Tool 🚀
### EE.CD - 3D 鼠标重力球域名查询工具 🚀

A futuristic, interactive domain registration status lookup interface featuring a high-density 3D particle sphere driven by a web-based physics engine. 
一款充满未来感、兼具强交互性的域名注册状态查询界面。右侧搭载了由纯前端物理引擎驱动的高密度 3D 粒子重力球。

---

## 🌟 Key Features / 核心特性

### 🇬🇧 English
* **Immersive 3D Gravity Sphere**: Built using a Fibonacci sphere algorithm, embedding domain suffixes into a dense 3D constellation that dynamically warps and flows toward your mouse cursor.
* **Smart Energy-Saving Physics**: The 3D animation and gravitational fluid simulation auto-lock and freeze perfectly when the mouse leaves the canvas, saving hardware resources.
* **Enhanced Spatial Perspective**: Tuned focal length, depth-of-field (DoF) blurring, and dynamic neon text-shadows combined to achieve an outstanding stereoscopic 3D visual hierarchy.
* **Real-time Lookup & Quick Linkage**: Seamlessly integrated with a RDAP/Whois API backend for checking availability. Clicking any floating suffix on the sphere syncs directly with the selection panel without unexpected API overhead.
* **Fully Responsive Layout**: Adapts gracefully across desktop and mobile viewing ports.

### 🇨🇳 中文
* **沉浸式 3D 重力流星球**：基于斐波那契球面算法，将指定的高价值域名后缀渲染为高密度的 3D 星群，随鼠标指针的移动产生酷炫的引力扭曲与吸附效果。
* **智能静止节能策略**：精心优化的物理引擎。当鼠标离开球体感应区时，3D 动效与自转完全静止锁定，极大地降低了硬件资源的开销。
* **极致的空间立体感**：通过调校透视焦距、引入景深模糊（Blur）算法以及前排高光霓虹滤镜，打造出极强的前大后小 3D 层次。
* **实时查询与无感联动**：内置 RDAP/Whois 异步查询接口；点击球体中的任意纯后缀可直接联动切换左侧的下拉框，而不会错误触发冗余的 API 请求。
* **完全响应式布局**：完美适配桌面端和移动端，在窄屏设备下自动切换为单列紧凑排版。

---

## 🛠️ Tech Stack / 技术栈

* **HTML5 & CSS3** (Vanilla CSS Grid, Flexbox, Perspective 3D Transforms)
* **Vanilla JavaScript** (ES6+, HTML5 `requestAnimationFrame` Physics Engine)
* **API Interface**: Asynchronous RDAP domain lookup via `fetch`

---

## 🚀 Quick Start / 快速开始

### 🇬🇧 English
1.  Clone this repository or just download the `index.html` file.
2.  Open `index.html` directly in any modern web browser (Chrome, Edge, Safari, Firefox).
3.  Type a domain prefix in the input box, hover over the 3D sphere to interact, and click the search button!

### 🇨🇳 中文
1.  克隆本仓库，或直接下载 `index.html` 单文件。
2.  在任何现代浏览器（Chrome、Edge、Safari、Firefox）中直接双击打开 `index.html`。
3.  在输入框中输入你想要注册的域名前缀，将鼠标移入右侧 3D 球体享受交互，并点击搜索！

---

## 📂 Project Structure / 项目结构

```text
├── index.html        # Main codebase including HTML structure, CSS styling, and JS physics engine.
└── README.md         # Project documentation (This file).
```
## ⚙️ Physics Customization / 物理参数自定义
### You can easily tweak the sphere's behavior by modifying these constants in the <script> tag:
你可以在 <script> 标签中通过修改以下常量轻松调整重力球的表现：
```text
const DENSITY = 210;         // Number of suffixes inside the sphere / 球体内粒子总数
const SPHERE_RADIUS = 210;   // Base radius of the 3D sphere / 球体基础半径
const MOUSE_GRAVITY = 0.25;  // Gravitational attraction strength / 鼠标吸附重力系数
const DAMPING = 0.92;        // Velocity damping factor / 速度物理阻尼
const SPRING_STRENGTH = 0.04;// Elastic spring return strength / 弹性回复系数
```
## 📄 License / 开源协议
### This project is licensed under the MIT License - feel free to use, modify, and redistribute it.
本项目基于 MIT 协议开源 - 你可以自由地使用、修改和分发它。
