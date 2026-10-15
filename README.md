# 小说推文长视频流水线 macOS · 发布与更新通道

提供 macOS 桌面版的更新包、版本说明和在线更新清单。应用把小说文本制作为旁白、分镜图片、字幕和视频，并支持小说项目管理、角色视觉资料复用及可选的 YouTube 上传。

- [macOS 源码与完整使用说明](https://github.com/1951779219/novel_video_pipeline_mac)
- [最新 macOS 更新](https://github.com/1951779219/novel_video_pipeline_mac_release/releases/latest)
- [全部版本](https://github.com/1951779219/novel_video_pipeline_mac_release/releases)
- [问题反馈](https://github.com/1951779219/novel_video_pipeline_feedback/issues/new/choose)

## 首次使用

1. 获取上方 macOS 源码仓库，进入项目目录。
2. 按源码 README 运行 `scripts/setup_macos.sh` 准备依赖。
3. 双击 `Open_GUI.command` 启动桌面应用。
4. 导入 TXT 或粘贴文本，填写自己的 TTS、文本模型和图片服务配置。
5. 先用一小段正文验证配音、生图、字幕和视频合成，再处理长文本。

详细依赖、Tkinter 兼容问题和上传配置，请以源码仓库文档为准。

## 已有安装如何更新

优先使用应用内的在线更新。手动更新前，请先关闭应用并备份配置、任务和项目数据，然后按对应版本说明使用 **Assets** 中的更新附件。

附件名中的 `mac-update` 表示更新包，需要已有安装环境。GitHub 自动提供的 **Source code (zip/tar.gz)** 仅包含本发布通道的仓库文件，完整应用源码请到源码仓库获取。

## 更新清单

```text
https://github.com/1951779219/novel_video_pipeline_mac_release/releases/latest/download/latest.json
```

`latest.json` 是应用使用的更新元数据，无需双击运行。发布包不应包含个人 API Key、任务、项目或浏览器登录资料；这些内容请仅保存在自己的设备上。


## 许可

本仓库的自有代码和文档按 [MIT License](LICENSE) 提供。应用发行包中的第三方组件、工具和模型仍遵循各自许可。
