# CoPlay 可陪 · 桌面客户端下载 / Desktop Downloads

这里是 CoPlay 可陪 桌面客户端的官方安装包分发渠道。项目源码不开源，本仓库只发布安装包。
This is the official distribution channel for the CoPlay desktop client installers. The project is closed-source; this repository publishes installers only.

客户端界面由服务器实时下发，安装一次后，重开或刷新即可使用最新功能。
The client loads its interface from the server, so after one install, reopen or refresh to get the latest features.

## 下载 / Download

| 版本 / Version | 平台 / Platform | 文件 / File | 大小 / Size | SHA-256 |
|---|---|---|---|---|
| [0.1.26（最新 / latest）](https://github.com/limdx9706/CoPlay-Desktop/releases/latest) | Windows x64 | [CoPlay-Core-Setup-0.1.26-x64.exe](https://github.com/limdx9706/CoPlay-Desktop/releases/download/v0.1.26/CoPlay-Core-Setup-0.1.26-x64.exe) | 100,490,605 字节 / bytes | `5e39bdcab1769a1d5f0f5902b87d7410e6cab8b41aa076e2d94baba206bbfe0e` |
| [0.1.26](https://github.com/limdx9706/CoPlay-Desktop/releases/tag/v0.1.26) | macOS x64 | [CoPlay-Core-0.1.26-mac-x64.dmg](https://github.com/limdx9706/CoPlay-Desktop/releases/download/v0.1.26/CoPlay-Core-0.1.26-mac-x64.dmg) | 152,957,067 字节 / bytes | `2a7bc74c7e7a685848ea0a8641b7b8399056c8aa7cbf2841156e9b4365b9d33c` |
| [0.1.25](https://github.com/limdx9706/CoPlay-Desktop/releases/tag/v0.1.25) | Windows x64 | [CoPlay-Core-Setup-0.1.25-x64.exe](https://github.com/limdx9706/CoPlay-Desktop/releases/download/v0.1.25/CoPlay-Core-Setup-0.1.25-x64.exe) | 100,491,426 字节 / bytes | `a6621c37bd3ccd94a0e89141ee48118aecb1f6a2cb6aa5bda48b4c1cbb072a8a` |
| [0.1.22](https://github.com/limdx9706/CoPlay-Desktop/releases/tag/v0.1.22) | macOS x64 | [CoPlay-Core-0.1.22-mac-x64.dmg](https://github.com/limdx9706/CoPlay-Desktop/releases/download/v0.1.22/CoPlay-Core-0.1.22-mac-x64.dmg) | 152,956,811 字节 / bytes | `3c19954733d825c648a522e309ce508a4c2b9941c8f6a13751ce42c335fecacf` |

安装前可核对文件校验和；每个 Release 附带 `.sha256` 文件与构建清单（来源提交、字节数）。
Verify checksums before installing; each release ships a `.sha256` file and a build manifest (source commit and byte count).

## 使用要求 / Requirements

- 安装后需要登录 CoPlay 账号；账号由服务端管理。
  Sign in with a CoPlay account after installing; accounts are managed server-side.
- 不使用真实麦克风或屏幕采集时，客户端不会录制任何内容。
  The client records nothing unless you use dictation or screen sharing yourself.

## 许可 / License

安装包按 [LICENSE](LICENSE)（专有二进制许可）提供：可自由下载和 personal use，禁止再分发、修改与逆向工程；捆绑的第三方开源组件依其自带许可。
The installers are provided under the [LICENSE](LICENSE) (proprietary binary license): free download and personal use; redistribution, modification, and reverse engineering are not permitted. Bundled third-party open-source components remain under their own licenses.
