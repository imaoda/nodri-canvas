# Seedance image-to-video workflow: character references to multiple shots

[Home](../README.md) · [简体中文](zh-CN/seedance-image-to-video.md)

Nodri lets you keep character images, scene references, storyboard images and Seedance video results on one canvas. Connect a reference to a video node, or select it with `@` in the generation input, then select the current generation account and a Seedance model. Build several shots by creating and submitting a video node for each shot.

Applies to **Nodri v0.1.1**. Last reviewed: **2026-10-19**. See [supported platforms and models](supported-models.md) for the versioned scope.

## Prepare two references

1. Create a project. In Settings → Account management → Add account, choose Jimeng (即梦) or Xiaoyunque (小云雀) and log in through the separate window. Select it as the current generation account.
2. Drag in a character image and a scene image. Imports are copied into the local project.
3. Keep the character's appearance, clothing and the scene's lighting easy to distinguish. Start with a small set of relevant references.

![Character and scene references connected to a generation input](../assets/readme/workflow.png)

*Actual app screenshot with imported demo media.*

## Make a storyboard, then describe motion

If you need to settle composition first, create an image node and reference the character and scene. Choose an available image model and generate a still. Review it before using it for video.

Example storyboard prompt:

> Use the selected character for appearance and clothing, and the scene for the setting. Vertical medium shot: the character stands beside a rainy café window, holding a red envelope. Soft evening light, readable hands, no text.

Create a video node. Connect the approved still, or select it from the `@` menu. Check the current generation account, select an available Seedance model, and check aspect ratio, duration and resolution before submitting.

Example video prompt:

> Use the referenced image for the character and setting. The character slowly opens the red envelope, pauses, then looks toward the café door. Gentle camera push-in, restrained movement, one continuous shot.

Here, “referenced image” means a real canvas reference selected through a connection or `@`; typing its filename alone does not attach it.

## Expand into three shots

Use a separate video node for each shot and submit each deliberately:

| Shot | References | Prompt focus |
| --- | --- | --- |
| 01: establish | Character + café | Wide view; character enters the café |
| 02: reveal | Approved envelope still | Medium shot; open the envelope |
| 03: reaction | Character + café | Close-up; look toward the door |

Completed results download into the project and can be referenced again. Keep the inputs beside each result so you can revise an individual shot. Inspect character details, motion and continuity yourself before continuing.

## Limits and next step

References guide generation; they do not guarantee character consistency. Available parameters and reference limits depend on the selected model and platform. Generation sends the selected references to the online provider and requires an account, credits and service availability; local storage does not make generation offline.

This workflow produces individual clips. Assemble the final sequence in your video editor.

Next: [organize short-drama assets](short-drama-assets.md), or follow the [Jimeng and Xiaoyunque workflow](jimeng-xiaoyunque-workflow.md).
