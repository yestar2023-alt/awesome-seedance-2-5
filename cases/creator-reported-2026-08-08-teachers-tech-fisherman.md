# CR-31｜渔夫与大白鲨：30 秒分段叙事、对白与声音

- **证据等级**：`creator-reported`
- **Prompt 状态**：`full`
- **模型/版本**：Seedance 2.5（Higgsfield 的 Seedance 2.5 入口）
- **作者**：Teacher's Tech
- **发布日期**：2026-08-08
- **验证日期**：2026-08-10
- **模式**：Reference-to-video / 30 秒连续序列；含人物外观参考、同步对白和环境音
- **效果视频与原始帖**：[YouTube：The Prompting Technique That Makes Seedance 2.5 Actually Work](https://www.youtube.com/watch?v=AvB-dfxTMgE)
- **模型入口**：[Higgsfield Seedance 2.5](https://higgsfield.ai/s/seedance-2-5-teacherstech-aaOosu)

视频作者在公开描述中写明“Prompt I used”，并说明视频是在 Higgsfield 的 Seedance 2.5 中生成；该视频本身公开展示了流程和结果。下列文字为描述栏中公开的原文，不是根据画面回推。

## Prompt（原文）

```text
Cinematic short film scene, one continuous 30-second sequence with synchronized dialogue and sound.

[0-6 SECONDS]
The fisherman wearing a worn flannel shirt and canvas fishing vest stands at the stern of a small fishing boat on a deep blue ocean, gripping a fishing rod bent hard toward the water. Medium shot from the side, golden late-afternoon sunlight reflecting off gentle swells. The rod tip jerks and the reel screams as line pulls out fast. He plants his feet wide on the deck, leans back, and says, "Oh no no no, you are not getting away from me. Not today."

[6-12 SECONDS]
Close-up of his hands gripping the rod, cranking the reel. The line cuts through the water in sharp zigzags, spraying mist. The boat rocks and tilts, water sloshing across the deck around his boots. He stumbles, catches himself on the railing, pulls the rod back up, laughs and says, "What did I hook, a truck?"

[12-17 SECONDS]
Slow aerial pull-back to a wide shot showing the small boat alone on the vast open ocean, the fishing line stretched tight into dark water. The unseen catch pulls the boat forward, leaving a wake. He braces against the stern, reeling one crank at a time.

[17-21 SECONDS]
Medium shot. The water off the port side of the boat begins to churn and bubble about thirty feet out. He looks toward it, eyes wide, and says, "Wait. That is not a fish."

[21-26 SECONDS]
The camera drops to water level, positioned so fisherman is in the lower right foreground with the open ocean behind him. In dramatic slow motion, a massive great white breaches thirty feet off the port side and arcs across the frame from left to right behind the boat, seawater streaming off its body, briefly eclipsing the sun. Spray crashes across the deck as the shark slams back into the ocean with a thundering splash.

[26-30 SECONDS]
Wide shot as the spray settles. He stands soaking wet, rod still in hand, staring at the calm water. He turns to the camera, stunned, and says quietly, "I am going to need a bigger boat." Slow push-in on his face as the scene fades toward the golden horizon.

STYLE
Cinematic color grading with deep ocean blues and warm golden sunlight. Film grain, shallow depth of field on close-ups, smooth deliberate camera movement. Synchronized audio throughout: creaking hull, screaming reel, sloshing water, the thundering breach impact, and clear natural dialogue matched to lip movement. The man's face, hair, and build match the reference exactly in every shot, including the wide aerial.
```

## 复现

1. 在 Seedance 2.5 的支持入口创建视频，并上传一张已获授权的人物外观参考。
2. 选择 30 秒、带音频的生成配置；比例、分辨率、seed 未由作者公开，需自行记录。
3. 粘贴完整 prompt，重点检查人物在中景、近景和航拍间的一致性，以及各句对白是否落在指定时间段。
4. 多次生成后再判断大白鲨跃出、船体受力、水花、口型和声音是否满足项目标准。

## 限制与风险

- 作者公开的是单个演示工作流，并无 seed、输入参考图、费用或多次抽样结果；复现层级为 `documented`，非独立验证。
- 人脸参考须取得本人同意；不要将合成视频冒充真实野生动物、海事或新闻纪录。
- 高速水体、动物跃起、远景身份保持和口型同步均为高难度组合，不应从单一案例推断稳定成功率。

## 证据

- [原始视频与完整 prompt](https://www.youtube.com/watch?v=AvB-dfxTMgE)（作者、发布时间、示范输出、描述栏 prompt 与模型主张）。
- [Higgsfield Seedance 2.5 入口](https://higgsfield.ai/s/seedance-2-5-teacherstech-aaOosu)（作者在原视频描述中提供）。
