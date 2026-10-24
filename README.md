# FDE2E Releases · 官方发行通道

> 昭智羽名(厦门)科技有限公司 · FDE2E™ 官方安装包与生态组件分发（GitHub Releases）。
> 完整下载中心：<https://www.fde2e.com/downloads> · 本仓只挂产物与校验值。

## 下载

| 产物 | 版本 | 平台 | 直链 |
|---|---|---|---|
| FDE2E Center（本机软件工具中心） | v0.1.2 | macOS · Apple Silicon（Developer ID 签名＋公证） | [`FDE2E-Center-0.1.2-arm64.dmg`](https://github.com/jixoai/fde2e-releases/releases/download/center-v0.1.2/FDE2E-Center-0.1.2-arm64.dmg) |
| FDE2E Center（本机软件工具中心） | v0.1.2 | Windows · x64 | [`FDE2E-Center-Setup-0.1.2.exe`](https://github.com/jixoai/fde2e-releases/releases/download/center-v0.1.2/FDE2E-Center-Setup-0.1.2.exe) |
| FDE2E BU Bridge（多控浏览器插件） | v1.5.1 | Chromium 扩展（unpacked zip） | [`fde2e-bu-bridge-v1.5.1.zip`](https://github.com/jixoai/fde2e-releases/releases/download/bu-v1.5.1/fde2e-bu-bridge-v1.5.1.zip) |
| FDE2E Computer Use Agent（桌面控制组件） | v0.2.0 | Windows · x64 | [`FDE2E-CU-windows-x64-setup.exe`](https://github.com/jixoai/fde2e-releases/releases/download/cua-v0.2.0/FDE2E-CU-windows-x64-setup.exe) |
| FDE2E Computer Use Agent（桌面控制组件） | v0.1.0 | macOS · Apple Silicon（签名＋公证） | [`FDE2E-CU-macos-arm64.dmg`](https://github.com/jixoai/fde2e-releases/releases/download/cua-v0.1.0/FDE2E-CU-macos-arm64.dmg) |

每个 Release 附 `SHA256SUMS.txt`——下载后请校验（macOS：`shasum -a 256 <文件>`；Windows：`Get-FileHash <文件> -Algorithm SHA256`）。

## 国内加速

GitHub 直链境内可能缓慢，可在直链前加加速前缀（第三方公益服务，稳定性无担保；不可用时请回退 GitHub 直链）：

```
https://ghfast.top/<GitHub 直链>
https://ghproxy.net/<GitHub 直链>
```

示例（Center dmg）：

```
https://ghfast.top/https://github.com/jixoai/fde2e-releases/releases/download/center-v0.1.0/FDE2E-Center-0.1.0-arm64.dmg
```

## 说明

- 本仓**只存放公开发布的安装产物与校验清单**——源代码在各产品仓库（私有）；不受理 Issue，问题经 <https://www.fde2e.com> 渠道反馈。
- Center 的自动更新通道（electron-updater）元数据仍在 <https://center.fde2e.com/center-shell/>，大文件由本仓承载。
- 品牌：FDE2E™ / fde2e / 昭智羽名。