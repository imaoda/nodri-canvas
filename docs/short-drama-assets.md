# How to organize AI short-drama assets on a canvas

[Home](../README.md) · [简体中文](zh-CN/short-drama-assets.md)

Use Nodri to keep reusable character and scene references beside storyboard images and generated clips. Imports are copied into a local project, and generated media downloads there too. Connections or `@` references let you reuse those assets for another generation without manually finding and uploading each file again.

Applies to **Nodri v0.1.1**. Last reviewed: **2026-10-19**.

## Arrange the project by creative purpose

Create a project, then drag in your reference images. A simple left-to-right layout keeps a small production readable:

| Area | What to place there | What it helps answer |
| --- | --- | --- |
| Characters | Chosen appearance and wardrobe references | Who is in this shot? |
| Scenes | Location and lighting references | Where does it happen? |
| Storyboards | Still images for each intended shot | What is the composition? |
| Results | Generated clips near their inputs | Which take should I use? |

This is a suggested layout, not an automatic folder or timeline structure. Drag nodes to arrange them and use text nodes for shot notes.

![Characters, scenes, storyboards and clips on a Nodri canvas](../assets/readme/hero.png)

*Actual app screenshot with imported demo media.*

## Give each shot a small brief

For each shot, record a shot number, action and desired framing. Put the relevant references nearby, then create an image or video node. Connect only the needed assets, or select them with `@` in the generation input.

Example shot brief:

> Shot 02 — rainy café, medium shot. Use the selected character for appearance and clothing and the café image for the setting. The character opens a red envelope and notices something unexpected. Keep the background quiet.

The example text is only a prompt: references must also be selected through connections or `@`.

Check the current generation account, choose the node's model, review the parameters, and submit. Jimeng (即梦), Xiaoyunque (小云雀) and LibTV offer different model sets; check the [support table](supported-models.md) before planning a workflow around a model.

## Review and reuse results

1. Wait for generation and local download to finish before using a result as a reference.
2. Check appearance, composition and motion against the shot brief.
3. Keep useful results near the references that explain them. For another shot, create its own node and deliberately select the references again.
4. If you want to compare a new attempt beside an old one, create another node before submitting it.

Imported files remain available if you move their original source files. Keep the project and its managed files intact.

## Limits and next step

Canvas organization helps you inspect continuity; it does not guarantee consistent characters or automatically assemble a finished drama. Reference types and counts vary by model. Generation sends the selected references to online services and follows their account rules.

Use your video editor to assemble and finish the selected clips. Continue with the [Seedance image-to-video guide](seedance-image-to-video.md) or the [Jimeng and Xiaoyunque workflow](jimeng-xiaoyunque-workflow.md).
