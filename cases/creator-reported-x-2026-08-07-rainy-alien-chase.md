# CR-73｜雨夜爆炸街头：低机位外星追逐

> **证据等级：** `creator-reported`。Snow 在公开 X 帖中发布成片与完整 prompt；prompt 首句直接标注 Seedance 2.5。此条不是字节官方发布，也没有独立复现。
>
> **模型/版本：** Seedance 2.5（作者在 prompt 中明确标注）；**模式：** Image-to-video（`image_1.png` 定义男子身份）；**Prompt 状态：** `full`；**发布日期：** 2026-08-07；**验证日期：** 2026-08-10；**证据截止日：** 2026-08-10。

- **作者**：Snow（iamrealsnow）
- **效果视频与原始来源**：[X 原帖（含成片与 prompt）](https://x.com/iamrealsnow/status/2085560726912147897)
- **参考素材用途**：`image_1.png` 定义被追赶男子的身份与蓝色眼睛；原始参考图未以可复用独立文件公开，复现时必须改用已获授权的成年人原创肖像。
- **公开生成说明**：15 秒、低机位动态跟拍的雨夜都市追逐；未公开 seed、比例、分辨率、生成次数或后期处理记录。

## 公开 prompt（`full`）

```text
A high-definition, cinematic 15-second Seedance 2.5 video prompt: A desperate, low-angle tracking shot following the man from image_1.png, maintaining his likeness and blue eyes, now clad in tactical black gear, sprinting through a rain-soaked, chaotic downtown street at night. Just behind him, a double-decker city bus is captured in the middle of a massive, fiery explosion, sending debris and orange flames into the air. Above the burning cityscape, a colossal biomechanical alien mothership of intricate metallic design descends through the storm clouds, its blue lights pulsing. To the right, emerging from the shadows and wrecked cars, a sleek Alien Predator lunges in pursuit. The camera dynamically retreats and pans to show the scale of the destruction, ending on a wide view of the entire scene. Dramatic lighting with deep contrast between the firelight and cool night tones. Rain pours heavily, creating reflective puddles. No text.
```

## 复现步骤

1. 使用拥有肖像授权的成年原创人物图替代 `image_1.png`，仅将其用作身份锚点；将服装、蓝色眼睛和街景的具体细节写入 prompt。
2. 为避免复刻受保护角色，把 “Alien Predator” 替换为原创的“隐形装甲外星追猎者”，并自行设计剪影、面罩、武器和生物特征。
3. 生成后检查人物身份、追赶者数量、巴士/爆炸的空间关系、雨水反射与结尾广角是否连续；在公开发布时标注合成内容。

## 限制与风险

- 原 prompt 使用了 “Alien Predator” 这一受保护角色名称；它可作为原帖证据保存，**不应**原样用于商业或公开复刻。请采用原创替代设定。
- 含爆炸、追逐和灾难现场；应遵守目标平台对暴力/惊悚内容与受众分级的规则，避免模拟真实突发事件。
- 原始身份图、seed、参数与失败样本未公开；即使 prompt 为 `full`，也不能期待稳定复现同一人物或物理效果。
- 成片仅在原 X 帖播放；本仓库不下载、镜像或再发布第三方视频与参考资产。
