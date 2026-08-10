# CR-23 ～ CR-30｜Krea Seedance 2.5 Prompt Gallery

> **证据等级：** `creator-reported`；**Prompt 状态：** `full`；**模型/版本：** Seedance 2.5；**作者/发布方：** Krea；**发布日期：** 页面未标注；**验证日期：** 2026-08-10。
>
> [Krea 的 Seedance 2.5 模型页](https://www.krea.ai/models/seedance-2-5) 将下列 prompt 与对应公开 MP4 在同一页面数据中绑定，并说明其示例提供用于生成的 exact prompt。视频文件均于本次核验中返回 `200 video/mp4`。未公开 seed、参数、参考素材或独立复现，故不标为 `official` 或 `verified`。

## CR-23｜咖啡液体微距与 ASMR

- **模式**：Text-to-video（具体时长/比例未公开）
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/macro_coffee_pour__extreme_macro_shot_of_espresso_pouring_into_a_ceramic_cup_in_slow_motion_thick_g_2icu5aq3vqjg32ykxoeg_1.mp4)

```text
Extreme macro shot of espresso pouring into a ceramic cup in slow motion, thick golden crema swirling and folding on the surface, steam rising against a dark background, shallow depth of field, warm studio lighting, ASMR-style sound of liquid hitting liquid.
```

**复现与限制。** 适合作为单动作、液体与音效对齐的短片起点；慢动作液体的物理稳定性和时长未公开，需自行多次抽样检查。

## CR-24｜水下红裙时装片

- **模式**：Text-to-video（具体时长/比例未公开）
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/_underwater_fashion__a_model_in_a_flowing_red_silk_dress_drifts_weightlessly_underwater_in_a_turquo_hck7mrzl1e54fw1tnptg_1.mp4)

```text
A model in a flowing red silk dress drifts weightlessly underwater in a turquoise cenote, sunlight beams piercing from the surface above, fabric billowing in slow motion, bubbles trailing upward, ethereal ambient soundtrack with muffled water sounds.
```

**复现与限制。** 以“服装、气泡、光束、隔水环境音”为验收对象；人脸、裙摆和水下物理在不同生成中可能漂移。

## CR-25｜曼谷街头食物微纪录片

- **模式**：Text-to-video，多镜头叙事
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/street_food_documentary__opens_on_a_tight_overhead_shot_of_hands_kneading_dough_on_a_flour-dusted_w_fxqs8y4t0gwi6banrgv0_1.mp4)

```text
Opens on a tight overhead shot of hands kneading dough on a flour-dusted wooden board in a dim Bangkok kitchen. Smash cut to a wok erupting in flames as garlic and chili hit hot oil, camera shaking slightly from the blast. Cut to a slow push-in on the finished pad thai being plated, steam curling upward. Reverse shot of a customer's face lit by the food stall's bare bulb, taking the first bite. Ambient night market noise throughout — sizzling, chatter, distant music, motorbike engines.
```

**复现与限制。** 这是多段剪辑式 prompt，不宜误判为单一连续镜头；若使用真实店铺、人脸或配乐，应自行处理授权。

## CR-26｜食材到意面：节奏化烹饪转场

- **模式**：Text-to-video，多镜头叙事
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/cooking_transformation__top-down_shot_of_raw_ingredients_arranged_in_a_grid_on_white_marble__tomato_vaha869606uf0091tx21_1.mp4)

```text
Top-down shot of raw ingredients arranged in a grid on white marble — tomatoes, basil, garlic, pasta, olive oil. Hands enter frame and begin chopping, quick rhythmic cuts synced to knife sounds: dice, slice, mince. Whip pan to a pot of boiling water, pasta dropping in. Time-lapse of sauce reducing in a pan, bubbling and thickening. Final shot: a slow overhead pour of sauce onto plated pasta, parmesan being grated over the top, steam rising. Pull focus from the dish to a candlelit dining table behind it. Each transition punctuated by the next cooking sound.
```

**复现与限制。** 可用于测试音画节奏与厨具/食材连续性；快切、延时和手部动作是潜在失败边界。

## CR-27｜布鲁克林清晨：室内外硬切与环境音演进

- **模式**：Text-to-video，含连续 Steadicam 与硬切
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/apartment_morning_routine__alarm_clock_hits_6-30_camera_starts_on_the_glowing_digits_and_pulls_back_uss8r4el8pn9e0hzm7c1_1.mp4)

```text
Alarm clock hits 6:30, camera starts on the glowing digits and pulls back through a sunlit Brooklyn apartment. Continuous Steadicam shot follows a man's hand turning off the alarm, panning to his feet touching hardwood floor, tracking him to the kitchen where he pours coffee. The camera drifts to the window — hard cut to the same window from outside, pulling back to reveal the full brownstone facade. Time-lapse clouds race overhead as morning light shifts across the building. Ambient sounds build from silence to a full city morning — birds, garbage truck, distant subway rumble.
```

**复现与限制。** 检查室内窗与外观窗的视觉关联、硬切时点和环境声递进；未提供 seed 或生成设置。

## CR-28｜猎豹追逐：高速动物动作与回归全景

- **模式**：Text-to-video，多镜头、慢动作
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/wildlife_predator_chase__wide_aerial_shot_of_a_golden_savanna_at_dawn_slow_push_toward_a_herd_of_ga_9ow2s68cb0awv70h8aec_1.mp4)

```text
Wide aerial shot of a golden savanna at dawn, slow push toward a herd of gazelles grazing. Quick cut to ground level: a cheetah crouched in tall grass, muscles tensed, ears flat. Extreme close-up of the cheetah's eye, pupil dilating. Smash cut to the sprint — ultra slow-motion side tracking shot at ground level, paws stretching and compressing, dust erupting with each stride. Cut between the cheetah's face and the fleeing gazelles. The herd scatters, the cheetah locks onto one. Final shot freezes at peak extension mid-leap, then slowly dissolves to the wide aerial, the savanna calm again. David Attenborough-style ambient: wind, hooves, heavy breathing, then birdsong returning.
```

**复现与限制。** 动物追逐涉及高速肢体、群体、切换与慢动作，失败风险显著高于静态场景；不应将结果视为野生动物事实记录。

## CR-29｜黄昏街球：负片效果与半调收束

- **模式**：Text-to-video，风格化剪辑
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/corner_basketball_at_dusk__wide_shot_of_a_chain-link_fenced_basketball_court_in_the_bronx_golden_ho_0ro19s06j4680a14t6d7_1.mp4)

```text
Wide shot of a chain-link fenced basketball court in the Bronx, golden hour light slicing through project buildings. A pickup game in progress — camera tracks a crossover dribble in slow motion, the ball leaving a motion trail like a long-exposure light painting. Hard cut to a layup: as the ball leaves the player's hand, the footage inverts to negative for two seconds, the ball arcing in silhouette. Back to normal as it swishes through the chain net. Freeze frame on the celebration, the image shatters into newspaper clipping-style halftone dots that slowly drift apart. Sound: sneakers squeaking on asphalt, ball bouncing, trash talk echoing, an ice cream truck jingle in the distance.
```

**复现与限制。** 适合研究“写明效果发生在具体动作节点”的方式；球体、人物与视觉特效之间仍可能出现不连续。

## CR-30｜画室磁带：画面外溢与局部动态壁画

- **模式**：Text-to-video，延时与局部动画
- **效果视频**：[播放](https://s.krea.ai/seedance-2-5-prompt-gallery/williamsburg_studio_session__opens_on_a_close-up_of_paint-stained_hands_pressing_play_on_a_vintage__l6ewvnl8lom0t987pq2d_1.mp4)

```text
Opens on a close-up of paint-stained hands pressing play on a vintage cassette player in a cluttered loft studio. Music kicks in — the camera pulls back to reveal canvases, scattered brushes, and a half-finished mural. As the artist paints a bold red stroke, the paint seems to spill past the canvas edge and streak across the actual film frame as a graphic element. Cut to a time-lapse of the mural progressing, but the rest of the room moves in real-time — people coming and going, light shifting through warehouse windows. The finished mural briefly animates: the figures in it move for three seconds, then freeze back into paint. Final shot: the artist steps back, the cassette clicks off, silence. Sound: lo-fi tape hiss, brush strokes on canvas, the cassette mechanism whirring, street noise leaking through the windows.
```

**复现与限制。** 重点复现“局部画面动画化、其他区域实时”的约束；人脸、画作、音乐和工作室素材须自行获得授权。

## 复核与风险

- **输出来源**：每个链接均为 Krea 原模型页数据中与相应 prompt 绑定的公开 MP4；原页：[Seedance 2.5 on Krea](https://www.krea.ai/models/seedance-2-5)。
- **复现层级**：`documented`，本仓库未独立生成，页面也未公布 seed、时长、分辨率和采样次数。
- **风险标签**：`rights-sensitive`（人脸/场所/音乐/作品）、`synthetic-media`；不得将示例用于冒充真实记录。
