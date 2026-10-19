# Use Jimeng and Xiaoyunque in one AI video canvas

[简体中文](./zh-CN/jimeng-xiaoyunque-workflow.md) · [Nodri overview](../README.md)

Applies to Nodri v0.1.1 · Documentation checked: 2026-10-19

Nodri lets you connect Jimeng (即梦) and Xiaoyunque (小云雀) accounts, keep their images and video clips in one local project, and reuse an image as a reference for another generation. Choose the account in the toolbar and the model in each node. Credits and model access remain with each provider account.

## Connect the accounts

1. Create a project. Open **设置 → 账号管理** (Settings → Account management).
2. On the accounts page, open **添加账号** (Add account), choose Jimeng or Xiaoyunque, and finish signing in in the login window. Repeat for the other platform.
3. Return to the canvas. Use the toolbar account menu to select the account for your next submission.

Switching accounts affects new submissions. Tasks already submitted continue with their original account. See [supported providers and models](./supported-models.md) before choosing a model.

## Example: a character reference becomes a video shot

Prepare a character image and a scene image that you have permission to use.

1. Drag both images into the canvas. Nodri copies imported files into the local project.
2. Select a Jimeng account. Double-click empty canvas space to create an image node. Connect the references to it, or type `@` in its generation input and select the reference nodes.
3. Choose an image model and its available settings. Add a prompt such as: “Vertical medium shot. The referenced character stands at the doorway of the referenced room, looking toward the camera.” Submit and inspect the result.
4. Select a Xiaoyunque account. Create a video node, reference the chosen storyboard image, and choose an available video model. Describe a small action, for example: “The character slowly turns toward the window. Fixed camera.” Check the reference requirements and duration before submitting.
5. Review the clip. Keep the inputs and results together for revisions; generated canvas results are downloaded into the local project.

The same reference may be reused across providers when the selected model accepts that input. A reference helps guide generation; it does not guarantee identical characters or motion.

![Nodri canvas showing character and scene references beside a shot prompt](../assets/readme/workflow.png)

*Actual app screenshot with imported demo media, illustrating canvas arrangement.*

## Scope and limits

- Suitable for organizing reference images, storyboards, and clips across accounts. The canvas does not automatically execute an entire connected graph or edit clips into a finished film.
- Generation requires an online provider and a usable account. Credits are not pooled or transferred between accounts; charges and access follow provider rules.
- Local project storage does not mean offline inference or that references never leave your computer. References used for generation are sent to the selected provider as needed.
- Nodri is an independent tool, not an official Jimeng or Xiaoyunque client. Provider names do not imply partnership or endorsement.

[Nodri vs. provider websites](./nodri-vs-provider-websites.md) · [Download](https://github.com/imaoda/nodri-canvas/releases/latest)
