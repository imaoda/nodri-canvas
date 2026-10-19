<p align="center">
  <img src="./assets/readme/app-icon.png" width="72" height="72" alt="Nodri app icon" />
</p>

<h1 align="center">Nodri — AI Image &amp; Video Canvas</h1>

<p align="center"><strong>A local creative canvas for Jimeng, Xiaoyunque and LibTV.</strong><br />
支持即梦、小云雀的 AI 图像与视频创作画布。</p>

<p align="center">English · <a href="./README.zh-CN.md">简体中文</a><br />
<a href="https://github.com/imaoda/nodri-canvas/releases/latest"><strong>Download for Mac</strong></a> · Apple silicon</p>

Nodri is a desktop canvas for AI images, short dramas and video creation. Connect your **Jimeng (即梦), Xiaoyunque (小云雀) or LibTV** account, then organize character references, scenes, storyboards and generated clips in one local project.

![Nodri AI video canvas with character references, scenes and storyboards](./assets/readme/hero.png)

*Actual app · Imported demo media · Chinese UI.*

## From references to AI video

Connect nodes or use **@ references** in a generation prompt. Create a storyboard image, then reuse it as a video reference. Keep inputs and results together for the next revision.

![Character and scene references connected to a short-drama shot](./assets/readme/workflow.png)

Drag images, video or audio into the canvas. Imported files are copied into the project; generated results are saved there too. Moving the original imported files does not break these copies.

Pan, zoom, select and drag to move between the whole project and individual shots.

![Actual Nodri recording of canvas navigation and node selection](./assets/readme/interaction.gif)

## Supported platforms and models

Version **0.1.1** includes **Seedance 2.5 / 2.0**, **MiniMax H3**, **Seedream 5.0**, **Image 2.5 Sunburst** and **Seed Audio**, depending on the connected platform.

See the [platform and model support table](./docs/supported-models.md) for exact variants, reference limits and the GPT Image 2.5 naming question. Availability and credits depend on your platform account.

![Account menu with Xiaoyunque, Jimeng and LibTV](./assets/readme/accounts.png)

## Get started

1. Download the Mac app and create a project.
2. Open settings → account management → add account, choose a platform and sign in.
3. Drag in references. Double-click empty canvas space to create an image or video node.
4. Connect references or type `@`, describe the shot, select the current account and model, then submit.

![Add references, describe a shot and choose generation settings](./assets/readme/quickstart.png)

## Workflow guides

- [Use Jimeng and Xiaoyunque in one AI video canvas](./docs/jimeng-xiaoyunque-workflow.md)
- [Seedance image-to-video: character references to multiple shots](./docs/seedance-image-to-video.md)
- [Organize AI short-drama characters, scenes and results](./docs/short-drama-assets.md)
- [Nodri or provider websites: which workflow fits?](./docs/nodri-vs-provider-websites.md)

## Common questions

**Does local mean offline generation?** Projects and assets are local. Generation runs online through the connected platform, and reference media is uploaded to it.

**Are credits shared between providers?** Each account keeps its own balance. Switching accounts affects new submissions; existing tasks keep their original account. Daily credit claims follow each platform's rules.

**What else is included?** Text and audio generation, an optional Agent and `nodri` CLI automation. These need their own supported runtime or account setup. Light, dark and system themes are available.

![Nodri light and dark themes](./assets/readme/appearance.png)

Available for **macOS Apple silicon**. Windows 11 x64 is in progress; no Windows download is currently published. This repository hosts product information and releases; **source code is not public**.

[Releases](https://github.com/imaoda/nodri-canvas/releases) · [Feedback](https://github.com/imaoda/nodri-canvas/issues)
