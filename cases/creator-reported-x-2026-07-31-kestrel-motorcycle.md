# CR-75｜Kestrel 暗黑奇幻摩托追逐：五参考图、12 镜头、30 秒

> **证据等级：** `creator-reported`。RafaSimon 在公开 X 线程中明确标注“Seedance 2.5 720p 30s Full Prompt”，发布成片、完整 prompt 与五张参考图的职责约束。此条不是字节官方发布，也没有独立复现。
>
> **模型/版本：** Seedance 2.5（作者明确标注）；**模式：** 多图参考生成；**Prompt 状态：** `full`；**发布日期：** 2026-07-31；**验证日期：** 2026-08-10；**证据截止日：** 2026-08-10。

- **作者**：RafaSimon（rafalors）
- **效果视频与原始来源**：[X 原帖与线程（含成片、参考图与完整 prompt）](https://x.com/rafalors/status/2083119527848751220)
- **参考素材用途**：Image 1/5 为两名无面甲追赶骑手；Image 2 为 Kestrel 的炭灰色快递摩托；Image 3 为追赶者摩托；Image 4 为 Kestrel 的身份、服装与外观。原始参考资产未作为可独立下载文件提供，复现时应以自有原创图替代。
- **公开生成说明**：720p、30 秒、12 镜头的高密度追逐；作者要求无背景音乐，若生成音频则仅保留引擎、风、能量脉冲与路面撞击等效果声。未公开 seed、生成次数和完整调用参数。

## 公开 prompt（`full`）

```text
Use the provided references consistently across the full 30 seconds: Image 1 is the first faceless black-armored chaser rider; Image 2 is Kestrel's charcoal courier motorcycle with amber light strip; Image 3 is the dark chaser motorcycle with red taillight and no amber; Image 4 is Kestrel, the broad-shouldered slicked-back male hero in a single-shouldered charcoal jacket with an amber sash; Image 5 is the second faceless black-armored chaser variant. Kestrel stays in front and the two dark pursuit riders stay behind or beside him as visual pressure. Create an original high-speed dark-fantasy motorcycle pursuit scene, 30 seconds, very fast-paced, readable, designed as an edit-friendly trailer cut with rapid cinematic shots. No background music, no soundtrack music, no subtitles, no text, no logos.

Setting: elevated highway through a dense dystopian megacity, monolithic concrete arcologies, industrial haze, flat overcast daylight, no rain, imposing and orderly rather than chaotic. Empty roadway, brutal concrete barriers, smoke, sparks, glowing energy trails, and stylized road-impact flashes.

FAST 12-SHOT STRUCTURE:

SHOT 1, 0:00–0:02 — Cold open. A bright energy flare streaks past the camera toward the highway, motion-blurred, then blooms behind Kestrel's bike in a dramatic orange-black shockwave. Camera shakes. Kestrel is already in front, escaping.

SHOT 2, 0:02–0:04 — High aerial reveal. Three motorcycles tear along the elevated highway far below, Kestrel's amber light strip visible at the front, two matte-black pursuit bikes behind in staggered formation. Camera dive accelerates downward.

SHOT 3, 0:04–0:06 — Extreme low road-level shot. The hero bike blasts over the lens, amber strip streaking; two dark pursuit bikes thunder after him with red taillights and black armor. Heavy motion blur, road grit, heat shimmer.

SHOT 4, 0:06–0:08 — Close-up on Kestrel. Slicked-back wet ash-grey hair, sharp masculine face, amber sash whipping violently, gloved hand twisting the throttle. His eyes stay calm while light flashes bloom behind him.

SHOT 5, 0:08–0:11 — Rear chase cam. The left pursuit rider closes in tight and releases a bright warning energy streak. Kestrel drops his shoulder and leans the bike underneath it; the streak passes his shoulder and showers sparks from the concrete barrier.

SHOT 6, 0:11–0:14 — Side-by-side pressure. The right pursuit rider surges up beside Kestrel and forces him toward the lane edge. Kestrel kicks the side of his bike frame and snaps the bike sideways in a controlled drift, narrowly avoiding contact while staying ahead. The camera whip-pans with the movement.

SHOT 7, 0:14–0:17 — Front tracking angle looking backward. A heavier guided light trail launches from behind, weaving between the bikes with a bright trail. Kestrel cuts through a narrow gap between broken road plates. The guided light hits the road ahead and erupts into concrete dust, debris mist, and black smoke.

SHOT 8, 0:17–0:20 — Hero stunt beat. Kestrel and the charcoal motorcycle punch through the blast wash. The bike performs one clean slow-motion barrel-roll through smoke and flying road dust, amber strip glowing, then lands hard with sparks and instantly accelerates. Make the rotation clean and physically readable.

SHOT 9, 0:20–0:22 — Pursuit rider close-ups. Rapid cuts: faceless black mirrored visor reflecting Kestrel's amber light; armored gauntlet gripping throttle; red taillight streak; tire sliding through sparks. The two pursuit riders regroup behind him, still closing.

SHOT 10, 0:22–0:25 — Power reveal. Low side profile at extreme speed. Kestrel rises upright on the moving bike, balanced and confident, turning backward toward the two riders. Four compact golden magical sigils bloom around his shoulders and hands, spinning like hot geometric halos. The road and city blur around him.

SHOT 11, 0:25–0:28 — Climax escape. The golden sigils fire concentrated beams backward down the highway. The beams carve glowing lines through the haze and strike the road around the pursuing bikes, creating a wall of golden-orange light, smoke, sparks, and shockwave energy. The two pursuit riders disappear into the smoke and fall far behind, ending the chase. Keep it stylized, non-graphic, cinematic, and readable.

SHOT 12, 0:28–0:30 — Final hero exit. Medium rear tracking beside Kestrel. He drops back into the seat, leans low over the charcoal bike, gives a small confident smirk, then rockets away down the elevated highway. Smoke columns recede behind him. End with forward acceleration, no title card.

Visual style: original premium dark-fantasy action cinema, high quality Unreal Engine cinematic render, modern high-end fantasy game visual quality, not copying any existing franchise characters, armor, weapons, symbols, or scenes. Anamorphic lens, speed-ramped action, rapid cinematic cuts, whip-pan transitions, camera shake from road impacts, heavy motion blur, atmospheric haze, film grain, cinematic color grade, strong silhouettes, consistent character and vehicle design, dynamic but readable action, no rain.

Audio instruction: no background music, no soundtrack music. If audio is generated, use only sparse cinematic sound effects such as engine roars, wind rush, energy pulses, road-impact booms, tire skids, debris impacts, and magical beam crackle.
```

## 复现步骤

1. 用五张自有原创参考图分别承担角色、主车、追赶者车、主角身份与第二追赶者身份；不要把所有信息塞入一张图，以免车辆或人物职责互相漂移。
2. 先测试 Shot 5–8 的并行逼近、横移漂移和空翻落地，验证三车位置、车灯色与车辆结构；再运行完整 12 镜头。
3. 按时间码检查主角是否始终在前、追赶者是否维持两人、无面盔甲与车辆灯色是否一致、空翻物理是否可读，以及输出是否误加音乐、字幕、文字或 logo。

## 限制与风险

- 12 个镜头压缩进 30 秒，尤其并车、爆炸穿越和空翻落地的空间连续性可能失败；作者未公开失败样本、seed 与重试次数。
- 五张原始参考图不能独立获取，完整 prompt 不等于逐资产可复现；需以拥有权利的原创角色、车辆和场景图替代。
- 虽为虚构非写实伤害的追逐场景，仍应避免模拟真实交通事故，遵守平台的暴力、危险驾驶与合成内容标识规则。
- 成片只在原 X 帖播放；本仓库不下载、镜像或再发布第三方视频与参考资产。
