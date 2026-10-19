# Nodri supported platforms and AI models

[Home](../README.md) · [简体中文](./zh-CN/supported-models.md)

Applies to **Nodri v0.1.1** ([download and release](https://github.com/imaoda/nodri-canvas/releases/tag/v0.1.1)). Last reviewed: **2026-10-19**. The tables describe the capabilities built into that release.

Nodri connects **Jimeng (即梦), Xiaoyunque (小云雀) and LibTV** accounts for image, video and audio generation. The table describes the app's integration scope. Access, credits, pricing and current service availability depend on the platform and your account.

## Platform support

| Platform | Image models | Video models | Audio models |
| --- | --- | --- | --- |
| Xiaoyunque / 小云雀 | Image 2.5 Sunburst; Seedream 5.0 Pro / Flash | Seedance 2.5, 2.0, 2.0 Fast, 2.0 Mini; MiniMax H3 | Seed Audio 1.0 / 1.5 |
| Jimeng / 即梦 | Seedream 5.0 Pro / Flash | Seedance 2.5, 2.0, 2.0 Fast, 2.0 Mini; MiniMax H3 | Seed Audio 1.0 |
| LibTV | Image 2.5 Sunburst; Seedream 5.0 Pro | Seedance 2.5, 2.0, 2.0 Fast, 2.0 Mini; MiniMax H3 | Seed Audio 1.0 |

Connecting a platform does not expose all of its website features or future models. The generation panel shows the options for the selected account and model.

## References and limits

| Model | Supported references | Duration and resolution |
| --- | --- | --- |
| Seedance 2.5 | Text; up to 30 images, 10 videos and 10 audio clips; at most 50 media references total | 4–30 s; 480p / 720p / 1080p |
| Seedance 2.0 | Text; up to 9 images, 3 videos and 3 audio clips; audio requires a visual reference | 4–15 s; 480p / 720p / 1080p / 4K |
| Seedance 2.0 Fast / Mini | Same reference rules as Seedance 2.0 | 4–15 s; 480p / 720p |
| MiniMax H3 | Same reference rules as Seedance 2.0 | 4–15 s; 720p / 2K; minimum 5 s on LibTV |
| Image 2.5 Sunburst | Images and text | 1K / 2K / 4K; up to 14 images on LibTV |
| Seedream 5.0 Pro / Flash | Images and text | Pro: 2K / 4K; Flash: 2K. LibTV Pro: 2K only, up to 10 images |
| Seed Audio 1.0 / 1.5 | Text and up to one audio clip | Follow the connected platform's output |

The app also limits a submission to 64 reference entries, including text. A listed limit is not a promise that every account or input will be accepted; platform validation still applies.

## Is Image 2.5 Sunburst the same as GPT Image 2.5?

The app labels its option **Image 2.5 Sunburst**, shortened to **Image 2.5 Pro**, and provides it through Xiaoyunque or LibTV. Nodri v0.1.1 does not include a direct OpenAI image API connection. Confirm the underlying model and version using the connected platform's description; the app's display name alone does not establish equivalence with GPT Image 2.5.

## Accounts, local files and downloads

Sign in with your own platform account. Balances are separate, and switching accounts affects later submissions. Projects and imported/generated assets are stored locally; generation runs online and reference media is uploaded to the selected platform. Platform names describe compatibility, not an official partnership.

v0.1.1 downloads: **macOS Apple silicon** from the release page above, or the [Windows 11 x64 installer](https://github.com/imaoda/nodri-canvas/releases/download/v0.1.1/Nodri-0.1.1-win-x64.exe). The Windows installer is unsigned.

Continue with [Jimeng and Xiaoyunque workflows](./jimeng-xiaoyunque-workflow.md) or [Seedance image-to-video](./seedance-image-to-video.md).
