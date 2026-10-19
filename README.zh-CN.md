<p align="center">
  <img src="./assets/readme/app-icon.png" width="72" height="72" alt="Nodri 应用图标" />
</p>

<h1 align="center">Nodri — AI 图像与视频创作画布</h1>

<p align="center"><strong>连接即梦、小云雀与 LibTV，在本地画布里组织 AI 创作。</strong></p>

<p align="center"><a href="./README.md">English</a> · 简体中文<br />
<a href="https://github.com/imaoda/nodri-canvas/releases/latest"><strong>下载 Mac 版</strong></a> · Apple 芯片</p>

Nodri 是面向 AI 图像、短剧和视频创作的桌面画布工具。连接**即梦、小云雀或 LibTV** 账号，把角色参考、场景、分镜和生成结果放在同一个本地项目里，减少切换网站、查找文件和手动上传的操作。

![Nodri AI 视频画布中的角色、场景、分镜与镜头片段](./assets/readme/hero.png)

*真实应用截图，使用导入的演示素材搭建。*

## 从参考素材到 AI 视频

用连线或输入框中的 **@ 引用**指定参考，描述镜头、选择模型并提交。先生成分镜图，再把分镜作为视频参考；素材、提示词和结果留在一起，方便调整下一版。

![角色图与场景图连接到短剧镜头的生成提示词](./assets/readme/workflow.png)

拖入图片、视频或音频时，文件会复制到本地项目中；生成结果也会保存到项目。移动原始导入文件不会影响项目里的副本。

支持平移、缩放、多选和拖拽，方便查看整体结构和单个镜头。

![Nodri 实际操作录屏：平移缩放、选择和拖动节点](./assets/readme/interaction.gif)

## 支持哪些平台和模型？

**v0.1.1** 内置 **Seedance 2.5 / 2.0、MiniMax H3、Seedream 5.0、Image 2.5 Sunburst、Seed Audio** 等选项，具体范围取决于平台。

[平台与模型支持表](./docs/zh-CN/supported-models.md)列出准确型号、参考限制，并解释 GPT Image 2.5 与应用模型名称的关系。实际可用性、积分和计费以所连接的平台账号为准。

![添加账号菜单中的小云雀、即梦和 LibTV](./assets/readme/accounts.png)

## 开始使用

1. 下载 Mac 版，安装后新建项目。
2. 进入「设置 → 账号管理 → 添加账号」，选择平台并完成登录。
3. 拖入参考素材，双击空白处新建图像或视频节点。
4. 连线或输入 `@` 引用素材，描述镜头，选择当前账号和模型后提交。

![放入参考素材、描述镜头、确认生成设置](./assets/readme/quickstart.png)

## 创作教程

- [如何在同一画布中使用即梦和小云雀生成视频](./docs/zh-CN/jimeng-xiaoyunque-workflow.md)
- [Seedance 图生视频：从角色参考图到多个镜头](./docs/zh-CN/seedance-image-to-video.md)
- [AI 短剧素材管理：角色、场景、分镜与生成结果](./docs/zh-CN/short-drama-assets.md)
- [Nodri 和直接使用即梦、小云雀网页有什么区别？](./docs/zh-CN/nodri-vs-provider-websites.md)

## 常见问题

**本地画布可以离线生成吗？** 项目和素材保存在本机；生成通过所连接的平台在线处理，引用素材会上传到该平台。

**不同平台的积分互通吗？** 各账号余额独立。切换只影响后续提交，已有任务保留原账号。账号页支持领取每日积分，发放按平台规则执行。

**还有哪些能力？** 文本与音频生成、可选 Agent 和 `nodri` 命令行自动化；使用时需配置相应运行环境或账号。外观可选浅色、深色或跟随系统。

![同一项目的浅色与深色外观](./assets/readme/appearance.png)

当前提供 **Apple 芯片 Mac** 下载。Windows 11 x64 正在适配，尚无公开下载。本仓库提供产品介绍与发布产物，**源码暂未公开**。

[查看更新](https://github.com/imaoda/nodri-canvas/releases) · [反馈与建议](https://github.com/imaoda/nodri-canvas/issues)
