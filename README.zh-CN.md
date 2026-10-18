<p align="center">
  <img src="./assets/readme/app-icon.png" width="72" height="72" alt="Nodri 应用图标" />
</p>

<h1 align="center">Nodri</h1>

<p align="center"><strong>用于 AI 图像与视频创作的本地画布。</strong></p>

<p align="center">
  把角色、场景、分镜和生成结果放在一起，<br />
  减少在多个网站和文件夹之间来回切换。
</p>

<p align="center">
  <a href="./README.md">English</a> · 简体中文
</p>

<p align="center">
  <a href="https://github.com/imaoda/nodri-canvas/releases/latest"><strong>下载 Mac 版</strong></a><br />
  <sub>Apple 芯片 · Windows 版适配中</sub>
</p>

<p align="center">
  <img src="./assets/readme/hero.png" width="1080" alt="Nodri 短剧项目中的角色、场景、分镜与镜头片段" />
  <br /><sub>真实应用截图 · 原创短剧演示，素材导入搭建</sub>
</p>

适合制作短剧、抖音短视频，以及需要复用角色和场景参考的创作。

## 素材保存在项目里，可以跨平台复用

拖入图片、视频或音频后，Nodri 会把文件复制到本地项目目录。移动原文件不会影响已导入的素材；画布生成的结果也会下载到项目里。

素材可以跨平台用作生成参考，减少反复下载、查找和手动上传。

## 在画布上浏览和整理素材

支持平移、缩放、多选和拖拽，方便查看整体结构或单个镜头。性能优化围绕**上百节点**时的常用操作展开。以下为真实操作录屏。

<p align="center">
  <img src="./assets/readme/interaction.gif" width="960" alt="Nodri 实时操作录屏：平移缩放画布、选择并拖动节点" />
</p>

## 不同平台使用同一套生成操作

用连线或 **@ 引用**指定参考素材，在节点中填写提示词、选择模型和参数。换平台后仍使用这套操作，具体参数按模型提供。

例如，把角色图和场景图用于生成分镜，再把分镜作为视频参考。素材、提示词和结果留在一起，方便调整下一版。

<p align="center">
  <img src="./assets/readme/workflow.png" width="960" alt="短剧创作近景：人物与场景参考连接到竖屏镜头的生成提示词" />
</p>

## 集中切换账号、领取每日积分

支持**小云雀、即梦、LibTV**。在下拉菜单中选择平台和账号，切换只影响后续提交，正在执行的任务仍使用原账号。

账号页可以**一键批量领取每日免费积分**，不用逐个平台操作。领取范围为已添加账号，实际发放以平台规则为准。

<p align="center">
  <img src="./assets/readme/accounts.png" width="640" alt="添加账号菜单中的小云雀、即梦与 LibTV 平台入口" />
</p>

## 开始使用

安装后新建项目，点击顶部的「添加生成账号」连接所用平台。

1. **放入参考。** 拖入角色图与场景图，双击画布空白处新建图像或视频节点。
2. **描述镜头。** 为新节点连线参考素材，或在生成输入框中用 `@` 引用，描述构图与人物动作。
3. **开始生成。** 选择模型、确认参数。得到分镜图或镜头片段后，可以继续把它用作参考。

<p align="center">
  <img src="./assets/readme/quickstart.png" width="960" alt="三步教程：放入人物与场景参考，描述镜头，选择模型后生成" />
</p>

## 深浅主题

可在设置中选择**浅色、深色或跟随系统**。

<p align="center">
  <img src="./assets/readme/appearance.png" width="960" alt="同一项目的浅色与深色外观对照" />
</p>

扩展能力通过插件集成；目前插件随应用提供，尚未开放用户安装。

---

**当前可用：** Apple 芯片 Mac。Windows 11 x64 版正在适配，实机验收尚未完成。

本仓库提供产品介绍与应用下载。**源码暂未公开**，后续可能逐步开放。

[下载最新版本](https://github.com/imaoda/nodri-canvas/releases/latest) · [查看更新](https://github.com/imaoda/nodri-canvas/releases) · [反馈与建议](https://github.com/imaoda/nodri-canvas/issues)
