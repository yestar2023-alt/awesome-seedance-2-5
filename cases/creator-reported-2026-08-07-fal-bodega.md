# CR-13｜雨天纽约杂货店一镜到底（Fal 实测）

- **证据等级**：`creator-reported`
- **Prompt 状态**：`full`
- **模型/版本**：Seedance 2.5（Fal endpoint：`bytedance/seedance-2.5/text-to-video`）
- **作者**：Ilker（fal.ai）
- **发布日期**：2026-08-07（页面抓取显示 2026-08-08 更新）
- **验证日期**：2026-08-10
- **模式**：Text-to-video，30 秒，单镜头，原生音频
- **效果视频**：[原始文章内嵌播放（Example：Bodega）](https://fal.ai/learn/devs/seedance-2-5-prompting-guide)
- **原始来源**：[Fal.ai — Seedance 2.5 Prompting Guide + Real Examples](https://fal.ai/learn/devs/seedance-2-5-prompting-guide)

原作者明确说明：页面下方 10 个视频均由 Fal 使用下方 prompt 生成，未剪辑、变速或后期加音频。视频以文章内嵌播放器形式公开；本仓库不下载或镜像媒体文件。

## Prompt（原文）

```text
30-second continuous single take inside a small New York City bodega on a rainy morning, all action at natural real-time speed. The same bike messenger wears a yellow rain jacket and carries one red bicycle helmet in the left hand throughout. 0-5 seconds: the door bell rings as the messenger enters, closes the glass door with the right hand, and shakes rain from the shoulders without dropping the helmet. 5-10 seconds: the camera follows from behind at chest height as the messenger walks to the drink cooler, opens the cooler with the right hand, removes one clear bottle of seltzer, and closes the door. 10-16 seconds: the messenger turns toward the counter and walks around one stationary customer without changing hands; red helmet remains in the left hand, bottle remains in the right. 16-22 seconds: the messenger sets only the bottle on the counter, taps a black phone once on the card reader, waits for one confirmation beep, then picks up the same bottle with the right hand. 22-27 seconds: the clerk gives a small nod; the messenger turns back toward the entrance while the camera backs up and keeps a medium full-body frame. 27-30 seconds: the messenger opens the door with the right forearm, exits into the rain, and the door closes behind. The camera stops inside the store. Keep the same messenger, jacket, helmet, bottle, phone, clerk, counter, cooler, and store layout from first frame to last. No cuts, no slow motion, no repeated entrance, no duplicated bottle or helmet, no object teleportation. Audio: rain outside, door bell, cooler hum, footsteps, bottle on counter, one card-reader beep, quiet store room tone, no music.
```

## 复现

1. 在 Fal 选择 `bytedance/seedance-2.5/text-to-video`。
2. 设置 `duration=30`、`resolution=720p`、`aspect_ratio=16:9`、`generate_audio=true`。
3. 粘贴上方 prompt，生成后对照原文章内嵌结果检查物体连续性。

## 限制与风险

- 这是 Fal 作者自报的单次生成案例，没有独立复现或公开 seed；应视为示范而非稳定性保证。
- 原始页面提供内嵌播放器而非稳定的独立 MP4 URL；链接失效时保留条目并标记 `link-rot`，不静默替换。
- 场景中的人物、商标和环境描述仅用于复现，使用时应替换为有权使用的素材。
