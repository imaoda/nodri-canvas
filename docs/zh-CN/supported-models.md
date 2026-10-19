# Nodri 支持哪些平台和 AI 模型？

[返回首页](../../README.zh-CN.md) · [English](../supported-models.md)

适用 **Nodri v0.1.1**（[下载与版本说明](https://github.com/imaoda/nodri-canvas/releases/tag/v0.1.1)）。核对日期：**2026-10-19**。以下列出该发布版的内置接入范围。

Nodri 可连接**即梦、小云雀和 LibTV** 账号生成图片、视频与音频。下表表示应用内置接入范围；模型权限、积分、计费与当前服务可用性取决于平台及账号。

## 平台支持表

| 平台 | 图像模型 | 视频模型 | 音频模型 |
| --- | --- | --- | --- |
| 小云雀 / Xiaoyunque | Image 2.5 Sunburst；Seedream 5.0 Pro / Flash | Seedance 2.5、2.0、2.0 Fast、2.0 Mini；MiniMax H3 | Seed Audio 1.0 / 1.5 |
| 即梦 / Jimeng | Seedream 5.0 Pro / Flash | Seedance 2.5、2.0、2.0 Fast、2.0 Mini；MiniMax H3 | Seed Audio 1.0 |
| LibTV | Image 2.5 Sunburst；Seedream 5.0 Pro | Seedance 2.5、2.0、2.0 Fast、2.0 Mini；MiniMax H3 | Seed Audio 1.0 |

接入平台不等于覆盖其网页的全部功能或未来模型。生成面板展示当前账号与模型可选的参数。

## 参考素材与参数范围

| 模型 | 可用参考 | 时长与分辨率 |
| --- | --- | --- |
| Seedance 2.5 | 文本；最多 30 图、10 视频、10 音频，媒体合计不超过 50 个 | 4–30 秒；480p / 720p / 1080p |
| Seedance 2.0 | 文本；最多 9 图、3 视频、3 音频；音频须搭配视觉参考 | 4–15 秒；480p / 720p / 1080p / 4K |
| Seedance 2.0 Fast / Mini | 同 Seedance 2.0 | 4–15 秒；480p / 720p |
| MiniMax H3 | 同 Seedance 2.0 | 4–15 秒；720p / 2K；LibTV 最短 5 秒 |
| Image 2.5 Sunburst | 图像与文本 | 1K / 2K / 4K；LibTV 最多 14 张图 |
| Seedream 5.0 Pro / Flash | 图像与文本 | Pro 为 2K / 4K，Flash 为 2K；LibTV 的 Pro 仅 2K、最多 10 张图 |
| Seed Audio 1.0 / 1.5 | 文本与最多 1 段音频 | 输出以平台为准 |

单次提交另有总计 64 个参考条目的应用限制，含文本。表内范围不保证每个账号或输入均被平台接受，平台仍会校验。

## GPT Image 2.5 与应用里的 Image 2.5 有什么关系？

应用选项名为 **Image 2.5 Sunburst**，短标签为 **Image 2.5 Pro**，通过小云雀或 LibTV 使用。v0.1.1 没有直连 OpenAI 图像 API 的入口。底层模型身份与版本以所连接的平台说明为准；应用中的显示名称本身不足以确认与 GPT Image 2.5 等同。

## 账号、本地保存与下载

使用自己的平台账号登录，各账号余额独立；切换账号影响后续提交。项目、导入素材与生成结果保存在本机；生成在线处理，引用素材会上传到所选平台。平台名称用于说明兼容范围，不代表官方合作。

v0.1.1 公开下载适用于 **Apple 芯片 Mac**。Windows 11 x64 正在适配，该版没有公开 Windows 安装包。

下一步：[即梦与小云雀画布工作流](./jimeng-xiaoyunque-workflow.md) · [Seedance 图生视频教程](./seedance-image-to-video.md)
