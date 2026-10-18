<div align="center">

<img src="./assets/banner.svg" width="100%" alt="JS-PACKAGE.XYZ — The JS Package Storage" />

<br />

[![UPLINK](https://img.shields.io/badge/UPLINK-js--package.xyz-3cf2ff?style=for-the-badge&labelColor=05060f)](https://js-package.xyz)
[![SIGNAL](https://img.shields.io/badge/SIGNAL-js%40yustellar.dev-ff4fd8?style=for-the-badge&labelColor=05060f)](mailto:js@yustellar.dev)

![TypeScript](https://img.shields.io/badge/TypeScript-05060f?style=flat-square&logo=typescript&logoColor=3cf2ff)
![JavaScript](https://img.shields.io/badge/JavaScript-05060f?style=flat-square&logo=javascript&logoColor=f7df1e)
![Node.js](https://img.shields.io/badge/Node.js-05060f?style=flat-square&logo=nodedotjs&logoColor=38ff9c)
![WebGPU](https://img.shields.io/badge/WebGPU-05060f?style=flat-square&logo=webgpu&logoColor=9d7bff)
![WebRTC](https://img.shields.io/badge/WebRTC-05060f?style=flat-square&logo=webrtc&logoColor=ff4fd8)

<sub><code>&gt;_ 一座漂浮在 Web 星系裡的 JavaScript / TypeScript 套件倉庫 —— AI、即時通訊、遊戲引擎、音訊合成、專案規劃與主機監控，全部在同一條軌道上運行。</code></sub>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## 🛰️ BOOT SEQUENCE

```text
[ 0.000 ] JS-PACKAGE.XYZ :: cold boot initiated
[ 0.042 ] mounting sector 0x01 INTELLIGENCE ......... Neko.js · WebChatMCP.js · Gauge.js
[ 0.117 ] mounting sector 0x02 SIMULATION ........... XYZ.js · Beacon.js
[ 0.203 ] mounting sector 0x03 SIGNAL ............... Stage.js · OPM.js · LINE.js
[ 0.288 ] mounting sector 0x04 OPERATIONS ........... CProject.js · Pulse.js
[ 0.330 ] mounting sector 0x05 TESTBED .............. demos
[ 0.342 ] uplink -> https://js-package.xyz .......... [ OK ]
[ 0.343 ] all systems nominal. welcome aboard, pilot.
```

## 🌌 STAR MAP

### `0x01` INTELLIGENCE — 智能核心

| MODULE | CORE | TRANSMISSION | PORTAL |
| :-- | :-: | :-- | :-: |
| 🟢&nbsp;**[Neko.js](https://github.com/JS-PACKAGE/Neko.js)** | `TS` | 本機多模態推論 SDK：在 Node.js 與 WebGPU 瀏覽器上跑文字／影像推論、PDF 擷取、OCR 與文件查詢，Qwen × ONNX 驅動。 | [⟶](http://neko.js-package.xyz/) |
| 🟢&nbsp;**[WebChatMCP.js](https://github.com/JS-PACKAGE/WebChatMCP.js)** | `JS` | 內建瀏覽器的 MCP server，串接 ChatGPT／Claude／Grok／Gemini，嘗試使用臨時／私密對話；提供 OMP、Pi、Codex、Claude Code、Grok Build 與 Hermes 外掛及本機工具往返，訪客模式限 ChatGPT／Gemini，資料保留依各服務政策。 | [⟶](https://webchatmcp.js-package.xyz) |
| 🟢&nbsp;**[Gauge.js](https://github.com/JS-PACKAGE/Gauge.js)** | `TS` | 自架 AI 訂閱額度儀表板（Antigravity、Codex、Claude、Grok），PWA + Web Push 警報，零 runtime 依賴。 | [⟶](http://gauge.js-package.xyz/) |

### `0x02` SIMULATION — 模擬引擎

| MODULE | CORE | TRANSMISSION | PORTAL |
| :-- | :-: | :-- | :-: |
| 🟣&nbsp;**[XYZ.js](https://github.com/JS-PACKAGE/XYZ.js)** | `TS` | 瀏覽器原生 2D／3D 遊戲引擎：WebGPU／WebGL2 渲染、Canvas2D 的 2D 降級、ECS、glTF／PBR 與 OPM 音訊整合。 | [⟶](http://xyz.js-package.xyz/) |
| 🟣&nbsp;**[Beacon.js](https://github.com/JS-PACKAGE/Beacon.js)** | `TS` | WSS + OAuth 多人遊戲大廳：SQLite 持久房間、隊伍、配對、聊天與 TypeScript client SDK，可選 etcd 協調跨主機 HA。 | [⟶](http://beacon.js-package.xyz/) |

### `0x03` SIGNAL — 訊號與音訊

| MODULE | CORE | TRANSMISSION | PORTAL |
| :-- | :-: | :-- | :-: |
| 🔵&nbsp;**[Stage.js](https://github.com/JS-PACKAGE/Stage.js)** | `TS` | 可自架、可嵌入網站的多人音訊舞台：WebRTC 音訊 × WebSocket 控制，伺服器端 Opus 混音、多房間、舉手上台與主控管理，附瀏覽器 SDK、Web Component 與範例前端。 | — |
| 🔵&nbsp;**[OPM.js](https://github.com/JS-PACKAGE/OPM.js)** | `TS` | 4-op FM 合成引擎，向 Yamaha YM2151 致敬。 | [⟶](http://opm.js-package.xyz/) |
| 🔵&nbsp;**[LINE.js](https://github.com/JS-PACKAGE/LINE.js)** | `TS` | 非官方本機 LINE 網頁客戶端：QR 登入、即時聊天、群組／OpenChat、媒體傳送、CLI 與 WebSocket 機器人 API；可選 AI 詐騙機率分析，使用非官方 API 有帳號風險。 | [⟶](http://line.js-package.xyz/) |

### `0x04` OPERATIONS — 工作區與監控

| MODULE | CORE | TRANSMISSION | PORTAL |
| :-- | :-: | :-- | :-: |
| **[CProject.js](https://github.com/JS-PACKAGE/CProject.js)** | `TS` | 自架行事曆與專案規劃工具：React + Node.js／SQLite 共享工作區，支援任務依賴、重複事件、提醒與多語介面，需連線後端使用。 | — |
| **[Pulse.js](https://github.com/JS-PACKAGE/Pulse.js)** | `TS` | 自架 Linux／macOS 多主機即時監控：CPU、記憶體、多 GPU、磁碟、網路與系統更新提醒，搭配 React 面板、Node.js agents 與 Cloudflare Zero Trust 存取保護。 | [⟶](https://js-package.github.io/Pulse.js/) |

### `0x05` TESTBED — 試驗場

| MODULE | CORE | TRANSMISSION | PORTAL |
| :-- | :-: | :-- | :-: |
| 🟡&nbsp;**[demos](https://github.com/JS-PACKAGE/demos)** | `TS` | 各模組的示範與實驗場。 | [⟶](http://demos.js-package.xyz/) |

## 📡 OPEN CHANNEL

> [!TIP]
> 發現異常訊號？歡迎到各模組的 Issues 回報，或直接 PR 加入航線。

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">
<sub><code>// END OF TRANSMISSION ▪ JS-PACKAGE.XYZ ▪ THE JS PACKAGE STORAGE</code></sub>
</div>
