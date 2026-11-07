# 3DSFormat 发布与更新

这里提供 Windows 版 3DSFormat 的公开下载和程序内更新。

## 下载

打开 [Releases](https://github.com/Tuohai-Li/3DSFormat-Releases/releases)，选择需要的版本：

- `3DSFormat-Integrated-版本-win64.zip`：完整运行包，解压后运行 `3DSFormat-Native.exe`。请保留同目录更新器、DLL、资源和许可证。
- `3DSFormat-Integrated-版本-source.zip`：与该发行对应的完整源码、构建脚本与说明。
- `SHA256SUMS-integrated.txt`：运行包和源码包的校验值。
- `update.json`、`update.json.sig`：程序自动更新使用的签名清单，无需手动打开。

初次启用自动更新，请手动安装 `2.3.0-preview.4` 或之后的版本；随后进入 **设置 → 更新**。预览版更新需要选择“预览版”渠道。程序默认每天后台检查，下载后由用户选择重启安装，后台任务进行时不会安装更新。

## 功能与资料

工具箱整合格式转换、解密、导出、打包、SD 安装和真机 Client；“我的 3DS”提供 HOME 布局编辑。详细操作、安装收尾、构建与数据安全说明在下载包的 `docs` 目录中。

许可证和第三方通知随运行包、对应源码包一并提供。更新签名只发布公钥，维护者私钥不在仓库中。

## 名称与更新地址

当前名称暂定为 3DSFormat。以后更改软件显示名时，可继续使用本仓库作为稳定更新入口。若发布仓库也需要迁移，会先提供兼容旧客户端的迁移版本。
