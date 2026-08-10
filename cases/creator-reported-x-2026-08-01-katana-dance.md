# CR-74｜影狼与单刀舞：高速动作的首测失真记录

> **证据等级：** `creator-reported`。Kōda 在公开 X 帖中发布 Seedance 2.5 首测成片，并在同帖线程公开角色图的 Midjourney prompt 与完整 Seedance 2.5 prompt。作者还记录了高速动作中发生的形变/道具消失后又出现问题；此条不是字节官方发布，也没有独立复现。
>
> **模型/版本：** Seedance 2.5（作者明确称“First Test”）；**模式：** Image-to-video（`@[character ref]` 作为舞者身份参考）；**Prompt 状态：** `full`；**发布日期：** 2026-08-01；**验证日期：** 2026-08-10；**证据截止日：** 2026-08-10。

- **作者**：Kōda（aimikoda）
- **效果视频与原始来源**：[X 原帖与线程（含成片、角色图 prompt、Seedance prompt）](https://x.com/aimikoda/status/2083371107755692388)
- **角色参考素材用途**：作者先公开角色图的 Midjourney prompt：`beautiful female contemporary dancer with a katana --chaos 30 --ar 9:16 --exp 30 --profile 2fepykr`；Seedance prompt 使用 `@[character ref]` 绑定舞者。角色成图未作为可复用原文件单独公开，复现时须自行生成或使用已授权的成年人原创角色图。
- **公开生成说明**：作者称其为 30 秒一次生成的首测，并观察到高速动作场景有形变；成片中一把武器曾消失后又出现。未公开 seed、分辨率、比例、生成次数或调用参数。

## 公开 prompt（`full`）

```text
High-end cinematic 3D realism fused with rapid contemporary dance and spectral blade combat. Explosive turns, deep backbends, floor slides, aerial contractions and sharp limb extensions flow directly into precise single-katana strikes, creating choreography that feels graceful, feral and impossibly fast. Dense shadow matter forms predatory silhouettes, lunging smoke trails and collapsing black shockwaves, while every blade arc tears crimson fabric-like energy through the air and disintegrates impacts into ink-dark particles. Aggressive orbiting camera movement, low-angle tracking, extreme foreshortening, sudden lateral acceleration, cold volumetric haze and wet reflective surfaces amplify the performance without sacrificing silhouette clarity. Realistic cloth dynamics, controlled motion blur, physical blade weight and feature-film rendering preserve elegance, danger and scale.

The performance begins mid-attack as a shadow wolf leaps through the smoke and the dancer @[character ref] folds beneath it in a violent backbend, drawing her single katana through its body during the recovery. More wolves circle and attack from every direction as she accelerates through spins, floor sweeps, aerial kicks and whipping turns, each movement becoming a clean blade strike that shreds them into black vapor and crimson fragments. The camera spirals through the pack with her, ending in full motion as she launches into another rotating slash against the final wave.
```

## 复现步骤

1. 先用原创、明确成年的舞者角色图作为 `@[character ref]`；不要使用未获授权的人脸、现有游戏角色或真人舞者肖像。
2. 先单独生成 5–10 秒的“后弯 + 单刀 + 影狼”动作，检查持刀手、刀身、肢体和角色身份是否稳定；再扩展到完整 30 秒群狼段。
3. 对每次结果标注刀具是否消失/复制、人物形变、影狼数量、镜头旋转与动作可读性。必要时减慢镜头加速度和动作密度，而非把异常结果当作成功复现。

## 限制与风险

- 原作者已报告高速动作时的形变以及道具消失后重现；这正是此案例的关键验证点，不能只截取正常帧评价效果。
- 角色图本身未作为原始资产公开，无法逐像素复现；Midjourney prompt 中的 profile 参数也未必对其他账户可用。
- 成片含虚构武器战斗。请避免真实人物、真实场所或可识别品牌，并遵守平台的暴力内容与合成媒体标识规则。
- 成片仅在原 X 帖播放；本仓库不下载、镜像或再发布第三方视频与参考资产。
