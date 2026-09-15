# 偶然AI 桌面版下载与更新

本公开仓库仅用于分发偶然AI安装包、版本说明与签名更新清单，不存放项目源码，不执行源码构建，不包含 AI API Key、Codex 登录信息或用户数据。

## Windows x64

从 [Releases](https://github.com/bf13020130-prog/ouran-ai/releases/latest) 下载完整 ZIP，解压后运行 payload/偶然AI.exe。首次使用自行配置 AI 渠道。

v0.18.0 首次升级需备份并保留原 data 目录，换用新版完整程序文件。v0.18.6 起支持从应用版本入口检查更新。

客户端读取 main/latest.json 和 latest.json.sig，验证独立 Ed25519 签名、安装包 SHA-256 与逐文件校验后安装。更新不包含用户 data。

## macOS

Intel x64 与 Apple Silicon ARM64 DMG 暂未发布。

## 发布边界

安装包由本地或私有构建环境生成，公开仓库只接收已验证成品和更新元数据。GitHub 自动附带的 Source code 压缩包只应包含此分发仓库的元数据。
