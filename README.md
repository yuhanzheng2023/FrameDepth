# FrameDepth

FrameDepth 是一个将视频转换为灰度深度视频的 Windows 桌面工具。

## 下载和使用

在本仓库的 Releases 下载 `FrameDepth_V1.zip.part1` 和 `FrameDepth_V1.zip.part2`，放在同一个文件夹。打开 Windows 命令提示符，进入该文件夹，运行：

```bat
copy /b FrameDepth_V1.zip.part1+FrameDepth_V1.zip.part2 FrameDepth_V1.zip
```

合并完成后，完整解压 `FrameDepth_V1.zip`，双击 `FrameDepth启动.exe`。不要只复制启动程序。

合并后的 ZIP SHA-256：`b257fbfd2365cb0b8f30053fe1458ff4f9c29e6e6a2c5b91dba8007bd34db90b`。可用 PowerShell 命令 `Get-FileHash .\FrameDepth_V1.zip -Algorithm SHA256` 校验。

程序需要 Windows 64 位；有兼容 NVIDIA 显卡可使用 GPU，无可用显卡时可以使用 CPU。视频较长时需要更多处理时间和磁盘空间。

## 第三方组件

本工具基于 Depth Studio 和 Video-Depth-Anything，并包含其他第三方软件、模型及运行库。各组件版权和许可声明保留在下载包的 `_internal/licenses` 等目录。请遵守各自适用的许可；本仓库不改变第三方组件的许可。

## 说明

本仓库发布的是 Windows 程序包分卷，不包括项目完整源代码。
