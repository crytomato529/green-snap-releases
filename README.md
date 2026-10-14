# 青截 GreenSnap · 绿色版下载

给 AI 发图、快速记录屏幕的 Windows 截图工具。全屏或框选后，图片同时复制到剪贴板并保存为原尺寸 PNG，可自定义快捷键、命名规则和保存位置。

**[下载 1.2.1-rc.1 预览版](https://github.com/crytomato529/green-snap-releases/releases/tag/v1.2.1-rc.1)** · **[直接下载绿色 ZIP](https://github.com/crytomato529/green-snap-releases/releases/download/v1.2.1-rc.1/GreenSnap-v1.2.1-rc.1-portable.zip)** · [问题反馈](https://github.com/crytomato529/green-snap-releases/issues)

长期下载入口：[全部版本](https://github.com/crytomato529/green-snap-releases/releases)。当前为预览测试版，尚非正式稳定版。

## 开始使用

1. 下载 **GreenSnap-v1.2.1-rc.1-portable.zip**，完整解压到有写入权限的文件夹。
2. 双击 **GreenSnap.exe**。保留同目录的 GreenSnap.exe.config 和说明文件。
3. **Ctrl + Alt + F6** 截全屏，**Ctrl + Alt + F7** 框选截图；主面板也有两个对应按钮。
4. 框选拖动后松开即可复制并保存；按住 Shift 可选正方形，Esc、右键或切换窗口取消。
5. 在支持图片粘贴的输入框按 Ctrl + V；也可以直接上传保存的 PNG。

默认全屏范围为鼠标所在屏幕，图片保存在程序旁的 Captures。点「设置」可修改快捷键、前缀、命名规则、保存目录等，点击「保存设置」后生效。关闭主窗口会收起到托盘；完全退出请在托盘菜单选择「退出青截」。

程序无需安装或管理员权限，不联网、不上传截图、不添加开机启动。截图和设置保存在本机；系统剪贴板历史、云盘和你主动粘贴到其他服务的内容，由相应服务处理。见 [隐私说明](PRIVACY.md)。

## 环境与当前范围

目标环境为 Windows 10 / 11、.NET Framework 4.8；本版实际验收为 **Windows 11、单屏、175% 缩放**。Windows 10、真实混合 DPI 多屏、HDR 和长期运行尚未新增实机覆盖。软件未取得数字签名，不能保证 Windows 不显示发布者提示。

支持全屏与区域截图、同时复制保存、流水号、日期目录、命名预设、再次复制最近一张及重截上一选区。当前不包含 OCR、滚动长截图、标注、录屏或自动发送给 AI。

部分旧 .NET 客户端的 PNG 读取路径在剪贴板短暂占用时存在兼容限制；不接受粘贴时，可使用已经保存的 PNG 文件上传。受保护画面、安全桌面及 HDR 色彩不在本版完整验证范围。

## 升级与反馈

升级前先从托盘退出青截，备份原使用文件夹。新包先解压到另一个目录，再按包内说明替换程序和说明文件；保留原 settings.json、Captures 及自选保存目录。需要回退时恢复升级前的整个备份。

遇到问题请到 [Issues](https://github.com/crytomato529/green-snap-releases/issues) 提供版本、Windows 版本、屏幕数量和缩放比例、操作步骤，以及复制和保存各自的结果。可以使用软件「更多 → 关于与反馈」中的复制反馈信息；分享前请检查内容。不要公开个人截图、完整设置、剪贴板、客户资料或密钥。

## 版本与校验

当前绿色包于 **2026-10-11** 构建并验收，**2026-10-14** 首次开放公开预览下载。本次直接提供原验收包，SHA-256 保持一致：

```text
82A0463470BF525305B7B6BF44779016A3C445427E5A3397E226B671FB09BDDC  GreenSnap-v1.2.1-rc.1-portable.zip
```

详见 [本版更新与已知范围](releases/v1.2.1-rc.1.md)。包内部分说明保留了打包时“尚未公开”的状态和旧反馈入口；本次公开下载状态及反馈入口以本页面为准。包内隐私说明标注 1.2.0-rc.1，1.2.1-rc.1 的本机处理和不联网行为没有改变。

本仓库用于软件下载、说明与反馈，应用源码保存在私有仓库。GitHub 自动生成的 Source code 压缩包包含本下载仓库的说明文件；使用软件请下载名称含 **portable.zip** 的绿色包。公开下载不代表提供了开源许可证，见 [授权状态](LICENSE-STATUS.md)。
