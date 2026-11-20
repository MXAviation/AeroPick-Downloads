# AeroPick 翼选 · 下载

面向航展 / 飞机摄影 / 演唱会连拍的 macOS 原生挑片工具。
**作者：KYO4926** · 全部运算在本机离线完成，不联网、不上传任何图像。

## 下载

| 版本 | 说明 | SHA-256 |
|---|---|---|
| [AeroPick-1.0.3.dmg](releases/tag/v1.0.3) | 最新版（推荐） | `2b33d8dc0bd4fe37263e463359ccd8145aaf090577c4871ec03b548335827af0` |
| [AeroPick-1.0.2.dmg](releases/tag/v1.0.2) | 早期版本 | `aea1fe5045e18c2d1f0bc14a0e98488f6fb7c51b27654e97d34e29dd1495524d` |
| [AeroPick-1.0.1.dmg](releases/tag/v1.0.1) | 早期版本 | `0341d670641c086134d13181fba3d240ec7e77e1ce1297408ce7dd7c12c3e2e6` |
| [AeroPick-1.0.0.dmg](releases/tag/v1.0.0) | 首个公开版 | `2fb35bd96c29d18e485334d4957c828be9be00f37f7d9a2887eae2e128117bb0` |

### 1.0.3 更新内容

- 左侧缩略图区自适应排布，消除图片左右黑边
- 取景框加粗并增加四角白色角标，更容易看清框选范围
- 主画布支持鼠标滚轮缩放，右上角缩放控件增加加减按钮
- 提升画面对比度与全局字号，弱文字更清晰

安装：打开 DMG，把 AeroPick 拖进「应用程序」即可。

要求 **macOS 14+ / Apple Silicon (arm64)**。应用为 ad-hoc 签名、未公证；
首次打开若被 Gatekeeper 拦截，在访达中右键 AeroPick →「打开」，或执行：

```bash
xattr -dr com.apple.quarantine /Applications/AeroPick.app
```

## 隐私

- 应用**完全离线**运行，不联网、不上传任何图像
- 安装包内不含任何个人路径、账号或素材信息
- 本仓库**只提供编译好的安装包**，不公开源代码

## 致谢

图标由 `Tools/make_appicon.py` 思路生成；Vision / Metal / ImageIO 均为 Apple 系统框架。
