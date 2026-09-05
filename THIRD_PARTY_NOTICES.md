# 第三方开源软件声明（Third-Party Notices）

ThingBoot Maker 桌面端在构建与运行中使用了以下第三方开源软件。本文件随安装包分发，
软件内"设置 → 关于"页展示同等内容。

> 免责声明：本文件仅为技术信息汇总，不构成法律意见。

---

## 运行时组件（随应用分发）

| 项目 | 许可证 | 用途 |
|---|---|---|
| React / React DOM | MIT | UI 框架 |
| zustand | MIT | 状态管理 |
| i18next / react-i18next | MIT | 国际化 |
| Monaco Editor | MIT | 代码编辑器 |
| @monaco-editor/react | MIT | Monaco 的 React 封装 |
| Tauri（runtime / api / plugins） | MIT 或 Apache-2.0（双许可） | 桌面应用框架 |
| serialport（Rust crate） | MIT | 串口通信 |
| Vite / esbuild / Rollup | MIT | 构建工具（不随应用分发，列此备查） |

## 关联分发物

- 设备固件的第三方声明见固件仓库 `thingboot-tools-maker-firmware/THIRD_PARTY_NOTICES.md`
  （MicroPython MIT、ESP-IDF Apache-2.0、tinyusb MIT、littlefs BSD-3-Clause 等）。
- 芯步 ThingBoot Device SDK 为专有许可，按其 LICENSE 条款链接分发。

## 合规说明

1. 以上开源组件均以 npm/cargo 包形式**原样引入，未修改源码**；各组件的许可原文见其官方仓库。
2. "MicroPython"等名称仅作事实性兼容性描述，不使用第三方商标/标识做产品营销。

## 许可证原文链接

- MIT: https://opensource.org/licenses/MIT
- Apache-2.0: https://www.apache.org/licenses/LICENSE-2.0
