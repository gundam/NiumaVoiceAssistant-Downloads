# 牛马语音助手下载

这里是牛马语音助手的公开下载与自动更新仓库，不包含应用源码。

- [下载最新版本](https://github.com/gundam/NiumaVoiceAssistant-Downloads/releases/latest)
- `appcast.xml` 是 App 内“检查更新”使用的签名更新清单。
- Release 中的 `NiumaVoiceAssistant-macos.zip` 不包含 Whisper 或 Ollama 模型。
- 更新包经过 Sparkle Ed25519 签名；App 会先验证签名再安装。

源码在单独的私有仓库维护。首次安装后，可在牛马菜单中选择“检查更新…”，以后不必再手工传安装包。

> 当前构建使用临时 macOS 代码签名，没有 Apple Developer ID 公证。首次从浏览器安装时，
> 请使用项目提供的安装脚本处理这个应用自身的隔离属性。App 内后续更新由 Sparkle 签名验证。
