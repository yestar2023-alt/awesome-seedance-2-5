# CR-71｜Cloudstitcher：双参考图驱动的 30 秒云城动作 RPG 镜头

> **证据等级：** `creator-reported`。创作者 STΛRJUPI 在公开 X 帖中发布成片、两张参考图的角色说明与完整 prompt，并以 `#Seedance25`、`#DreaminaAI` 标识本次测试。此条不是字节官方发布，也没有独立复现。
>
> **模型/版本：** Seedance 2.5（作者标注 `#Seedance25`）；**模式：** 多图参考生成（`@Image1` 身份参考 + `@Image2` 分镜/运镜参考）；**Prompt 状态：** `full`；**发布日期：** 2026-08-03；**验证日期：** 2026-08-10；**证据截止日：** 2026-08-10。

- **作者**：STΛRJUPI（StarjupiAI）
- **效果视频与原始来源**：[X 原帖（含成片、参考图和 prompt）](https://x.com/StarjupiAI/status/2084368396288700836)
- **参考素材用途**：`@Image1` 定义 Cloudstitcher 与云伙伴的身份、服装、道具和材质，且要求忽略其工作室背景；`@Image2` 只定义 1–8 格中的动作顺序、构图和镜头方向，不继承格线、编号或文字。原始参考图在作者帖子中展示；本仓库不复制或镜像它们。
- **公开生成说明**：作者将其称为实验 01；成片为 30 秒、无对白的风格化 3D 奇幻动作 RPG 片段。未公开 seed、比例、分辨率、生成次数、调用参数或原始项目文件。

## 公开 prompt（`full`）

```text
@ Image1 defines one Cloudstitcher and one cloud companion. Preserve their exact faces, colors, proportions, costume, ornaments, needles, staff and materials. Never duplicate, merge or redesign them. Ignore the studio background.

@ Image2 defines the action order, compositions and camera direction only. Follow panels 1–8 from left to right, top row first. Do not inherit panel borders, numbers, captions or storyboard formatting.

0–2s — Full-body frontal shot of Cloudstitcher on a fractured platform above a vast cloud city. The hero raises the golden needles while the cloud companion waits behind.

2–5s — A colossal brass Storm Sentinel lands and slams both fists into the platform. A circular shockwave tears through stone and cloud.

5–8s — Cloudstitcher performs one powerful forward jump over the approaching shockwave. Side-tracking camera follows the movement.

8–12s — The hero lands on the Sentinel’s arm and runs upward toward its exposed storm core.

12–16s — Suspended beside the core, the hero throws both needles around it. Coral-red threads cross and tighten like magical stitches.

16–20s — The Sentinel releases an energy blast. The same cloud companion expands into a dragon-like cloud formation and intercepts it.

20–26s — Cloudstitcher dives toward the core and pulls the crossed threads tight, sealing it like a stitched wound.

26–30s — The hero lands beside the companion. The sealed Sentinel becomes motionless as the storm clears above the city.

Premium stylized 3D fantasy action-RPG cinematic. Dynamic but coherent game-trailer cameras, physical cloth and cloud movement, brass machinery, turquoise, cream, coral-red and gold.

Thunder, stone impacts, wind, machinery, thread tension and orchestral percussion. No dialogue, narration, subtitles, UI, text or logos.
```

## 复现步骤

1. 使用拥有权利的原创角色/道具身份图作为 `@Image1`；单独准备一张 8 格以内的动作与镜头设计板作为 `@Image2`，不要把分镜中的编号、文字或边框当成要保留在成片中的元素。
2. 保持两个参考的职责隔离：身份与材质只由 `@Image1` 约束；动作顺序与镜头只由 `@Image2` 约束。先测试 0–8 秒的跳跃与冲击波段，再运行完整时间轴。
3. 回看时逐项检查角色是否重复/合并、针具与云伙伴持续性、冲击波接触关系、镜头是否遵循侧向跟拍、以及 20–30 秒的核心封合与天气转换是否连贯。

## 限制与风险

- 未公开 seed、比例、分辨率、采样次数和失败样本；完整 prompt 也不保证能用不同参考图稳定复现同一效果。
- 成片仅通过原 X 帖访问；本仓库不下载、镜像或再发布第三方视频与参考资产。
- 请使用原创角色、场景、音效和分镜，不要以参考图输入未授权游戏、美术资产或真实人物。成片如用于公开传播，应按平台规则标识合成内容。
