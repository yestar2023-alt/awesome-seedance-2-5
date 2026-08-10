# CR-65 ～ CR-68｜X 创作者公开实测（2026-08）

> **证据等级：** `creator-reported`。每条均由原作者在 X 公开发布成片和 prompt 文本，并在帖文中明确标明 Seedance 2.5 或其生成入口；各条 prompt 完整度单独标注。本仓库不将其视为字节官方或独立复现结果。
>
> **验证日期 / 证据截止日：** 2026-08-10。效果视频在原 X 帖中播放；为方便审计，保留了[公开数据记录](https://github.com/renoise-ai/awesome-seedance-2-5-prompts/tree/main/data/prompts)，但仓库不链接、下载或镜像其中代理的视频文件。

## CR-65｜1990 年代奇幻电视剧：逼近的机器人军团

- **作者**：Brent Lynch
- **模型/版本**：Seedance 2.5（作者明确标为同帖的第 1 支视频）；**模式**：Image-to-video；**Prompt 状态**：`full`
- **发布日期**：2026-08-01
- **效果视频与原始来源**：[X 原帖（含三模型对比；第 1 支为 Seedance 2.5）](https://x.com/BrentLynch/status/2083637290652623341)
- **参考素材用途**：prompt 将“提供的图片”作为精确首帧，锁定金发女性、装甲士兵和实景机器人助手；该参考图未被单独公开。

```text
Use the supplied image as the exact opening frame. Preserve the blonde woman, armored male soldier, and practical robot assistant with identical faces, costumes, proportions, metallic materials, lighting, and spatial positions.

Create an authentic late-1990s live-action syndicated fantasy action-adventure television scene, photographed on 35mm film and transferred through period telecine. Gritty film grain, slight gate weave, practical torchlight, cool moonlight, deep nighttime shadows, handmade armor, physical robot mechanisms, real locations, miniature armies, matte paintings, forced perspective, and restrained optical compositing. No modern CGI, no digital creatures, no costume redesigns, no face changes, no morphing, no extra foreground characters.

00:00–00:03.8 — Shocked question

Begin in the existing tight three-character composition.

The chrome-and-gold armored male soldier stares at the blonde woman in disbelief. His eyes widen, his jaw tightens, and he leans slightly toward her. His helmet and armor catch the flickering orange torchlight.

With urgent, shocked delivery and accurate lip synchronization, he says:

ARMORED SOLDIER:
“Are you saying Seedance and Minimax were only the first wave?”

The woman holds intense eye contact. The robot remains alert beside him, making subtle mechanical head movements.

00:03.8–00:07.0
Woman’s urgent warning

Cut to an intense close-up of the blonde woman’s face. She is sweaty, breathless, frightened but determined. Wind moves a few strands of her hair. Torchlight and blue moonlight shape her face.

She answers urgently and passionately, with precise lip synchronization:

WOMAN:
“Yes! There are countless more AI models approaching!”

She immediately turns her head toward something beyond the camp and gestures sharply for the soldier and robot to follow her.

00:07.0–00:10.2 Rush toward the cliff

A fast handheld tracking shot follows all three as they hurry several steps toward the edge of a rocky cliff.

The woman leads. The armored soldier follows closely, still stunned. The practical robot assistant stomps behind them with heavy mechanical movement, pistons compressing and metal joints rotating.

The woman reaches the cliff edge and points forcefully into the distance.

00:10.2–00:13.2 Reveal the approaching armies

Cut to a dramatic wide shot from behind the three heroes as they stare across a vast nighttime valley.

In the distance, reveal multiple visibly different armies of robots approaching in organized formations:

- tall chrome humanoid soldiers carrying illuminated staffs
- squat industrial robots with rotating sensor heads
- skeletal brass automatons marching in ranks
- enormous tracked mechanical siege machines
- distant flying mechanical scouts crossing the moonlit sky

The armies must look like physical miniatures, full-scale robot suits, animatronics, forced-perspective formations, matte-painted extensions, and late-1990s optical effects—not modern digital animation.

Hundreds of tiny mechanical lights advance through fog and dust. The ground vibrates faintly beneath the heroes.

00:13.2–00:15.0 Defiant reaction

Cut to a close three-shot.

The armored soldier looks overwhelmed. The woman remains fiercely focused. The robot assistant rotates its optical lenses, locks its mechanical arms into combat position, and produces a loud hydraulic charging sound.

The robot leans forward confidently and says in a rough, humorous synthesized voice:

ROBOT:
“Bring them on.”

End on the three heroes facing the approaching armies as dramatic orchestral action music surges.

Audio: Period fantasy-action orchestral score, distant mechanical marching, wind, torch crackle, metallic armor movement, hydraulic robot sounds, and clean dialogue.

Performance: Serious stakes with a restrained pulpy syndicated-TV energy.
```

**复现与限制**：以自有首帧重建三人关系和构图；逐项核验人物、道具、画面方向、口型、队伍连续性与无形变。该帖同时含 Minimax H3 与 Seedance 2.0 对比，不能把第 2、3 支视频误标为 2.5；未公开 seed、比例、分辨率和重试次数。

## CR-66｜雨夜跨海桥：机甲摩托追逐与空中变形

- **作者**：ViralOps
- **模型/版本**：Seedance 2.5（作者称 Dreamina web 示例）；**模式**：Text-to-video；**Prompt 状态**：`full`
- **发布日期**：2026-08-02
- **效果视频与原始来源**：[X 原帖（含视频）](https://x.com/ViralOps_/status/2083889667020411000)
- **参考素材用途**：未声明参考输入。

```text
Seedance 2.5 example on Dreamina web;

30-Second One-Shot (Sci-Fi Mecha Chase and Transformation)
[Global Setting]Base Environment & Texture: A cyberpunk-style futuristic cross-sea bridge in 2077. Heavy rain is pouring down, and the road surface is severely waterlogged. Emphasize extreme, realistic physical textures (rain reflections on metal surfaces, water splashed by tires, and the specular refraction of exhaust flames must strictly obey real-world physics).Visual Style: Hardcore sci-fi cinematic feel, high-contrast neon dark tones (cyber-pink and icy blue as primary colors), high-speed shutter (to clearly capture splashing raindrops and sparks).Camera Language: High-speed subjective drone POV, delivering a strong sense of velocity impact and the turbulence of cutting through airflow. One continuous shot.Subject Styling: A silver-and-black concept mecha motorcycle, extremely streamlined with a heavy-industry, heavily armored vibe. Its exhaust pipes are blasting eerie blue plasma flames.Core Performance (Action): Focus on the center-of-gravity shifts during high-speed driving, the physical friction/grip of the tires, and the heavy-industry mechanical aesthetics of precision gears interlocking tightly during mid-air transformation.[Negative Prompts]: No soft-body or mollusk-like twisting/clipping of the mecha structure during movement (must maintain metallic rigidity); no human entities; strictly remove irrelevant subtitles; force mute/no default BGM; avoid copyrighted IP elements like Transformers or Tron.
[Timestamp Storyboard]
[00:00 - 00:08] [Extreme Speed Drive] — Piercing the WindAction / Physics Directives: The camera skims tightly over the waterlogged road, following closely behind and to the side of the mecha motorcycle at extreme speed. The motorcycle races through the heavy rain. The rapidly spinning wide tires kick up massive water curtains several meters high. The blue plasma exhaust flames drag long light trails through the nighttime rain curtain. Camera Subtext: Conveys an extreme sense of speed to the AI, focusing on the physical interaction between the rain, puddle reflections, and engine flames.
[00:09 - 00:16] [Extreme Evasion] — Shift of GravityAction / Physics Directives: The camera instantly pulls up for a high-angle tilt-down shot (spatial perspective switch). A chain-explosion of abandoned vehicle wreckage suddenly appears as an obstacle ahead. The motorcycle leans extremely far over, almost touching the ground. The tires grind against the road, sparking dazzling orange friction sparks, executing a perfect, tight "S" curve to weave through the burning debris. Camera Subtext: Presents the shift in the center of gravity during high-speed maneuvering, showcasing the gravity feedback and spark VFX of extreme tire-to-ground friction.
[00:17 - 00:24] [Mid-Air Reassembly] — Mechanical TransformationAction / Physics Directives: The mecha motorcycle charges off a broken section of the bridge, launching into the air. The camera leaps into the air with it, orbiting the subject. During hang time (slow-mo suspension), the motorcycle's armor rapidly flips, deconstructs, and reassembles. The wheels retract to become thrusters, and the chassis unfolds to extend steel limbs, instantly transforming from a motorcycle form into a heavily armored humanoid combat mecha. Camera Subtext: Showcases pure mechanical heavy-industry aesthetics, emphasizing the precise interlocking and volumetric mass of the parts during assembly, strictly rejecting "noodle-like" soft-body transformation.
[00:25 - 00:30] [Heavy Landing] — Frozen PowerAction / Physics Directives: The camera plummets rapidly to a low-angle extreme close-up (in-your-face shot). The humanoid mecha lands heavily on the highway, dropping to one knee. The massive tonnage impact causes the bridge surface to shatter into a spider-web pattern. The concussive shockwave instantly blows away the surrounding rain curtain (exploding outward in a ring). The mecha slowly raises its head, its tactical eye-lights flashing glowing crimson red, staring directly into the camera as it freezes. Camera Subtext: Creates a visually explosive "Superhero Landing", conveying the mecha's terrifying weight and destructive power to the audience through the shattered road and expelled shockwave.
```

**复现与限制**：按 0–8 / 9–16 / 17–24 / 25–30 秒检查水花、轮胎抓地、部件硬质连接、镜头空间连续性与静音约束。作者未公开 seed、比例、分辨率、生成次数或项目文件；不得使用 Transformers、Tron 等受保护 IP 作为替代提示。

## CR-67｜10 秒竖幅高端披萨广告

- **作者**：Jahan Zaib
- **模型/版本**：Seedance 2.5（作者在 prompt 首行标明）；**模式**：Image-to-video；**Prompt 状态**：`full`
- **发布日期**：2026-08-02
- **效果视频与原始来源**：[X 原帖（含视频）](https://x.com/jzaib4269/status/2083803694886506640)
- **参考素材用途**：提供的人像图用于锁定女性的五官、发型、妆容、蓝格纹连衣裙和珠宝；原始参考图未单独公开。

```text
Seedance 2.5 – 10s Viral Premium Pizza Commercial (3:4)
Aspect Ratio: 3:4 (1080×1440)
Duration: 10 seconds
Style: Ultra-photorealistic, cinematic, luxury food commercial, Hollywood-quality, stop-scrolling, viral social media advertisement.
Use the provided image as the identity reference for the woman. Preserve her facial features, hairstyle, makeup, blue gingham dress, and jewelry consistently throughout the video.
Create an ultra-premium pizza commercial with warm golden lighting, realistic steam, floating flour particles, creamy bokeh, HDR, 8K textures, macro food cinematography, and flawless skin rendering.
Scene 1 (0–2.5s)
Open with an extreme macro shot of a premium wood-fired pizza fresh from the oven. Cheese bubbles, pepperoni glistens, basil sparkles with tiny water droplets, dramatic steam rises, and orange flames flicker in the background. Hyper-realistic food styling.
Scene 2 (2.5–5s)
Smooth cinematic dolly-in reveals the woman seated beside the pizza in a luxurious Italian restaurant. Warm amber lighting, blurred "PREMIUM PIZZA" neon sign behind her. She gives a confident smile while maintaining eye contact. Hair gently moves in a soft breeze.
Scene 3 (5–7.5s)
She lifts a pizza slice into a spectacular slow-motion cheese pull. Long stretchy mozzarella strands shimmer under cinematic lighting while oregano and parmesan fall in slow motion. Camera performs a smooth orbit around the pizza.
Scene 4 (7.5–10s)
She takes one elegant bite, smiles naturally, then the camera transitions into a dramatic hero shot of the rotating pizza surrounded by floating basil, tomatoes, olives, parmesan, chili flakes, and flour dust. Finish with a cinematic push-in on the pizza.
Ending Text
"ONE BITE. PURE PERFECTION."
Premium gold typography with a subtle glow and elegant cinematic fade.
Camera
Cinema-grade gimbal movements, macro food cinematography, 85mm portrait lens, smooth dolly shots, slow orbit, rack focus between the pizza and the model, subtle handheld micro-movements, premium advertising composition.
Lighting
Golden-hour cinematic lighting, warm practical restaurant lights, volumetric rays, HDR reflections, realistic shadows, glowing cheese highlights, luxury commercial color grading.
Quality Tags
Ultra-realistic, 8K, HDR, IMAX quality, Netflix-style commercial, luxury food advertisement, premium restaurant branding, hyper-detailed textures, realistic physics, flawless facial consistency, physically accurate cheese stretch, realistic steam simulation, cinematic color grading, ray tracing, global illumination, masterpiece, stop-scrolling, viral-quality commercial.
```

**复现与限制**：以已获授权的人像和自有产品图替换参考，逐项检查披萨形状、奶酪拉丝、手部、人像一致性和字幕清晰度。作者未公开 seed、生成次数及参考图；prompt 内要求可读品牌文案，而模型可能生成乱码，实际商用应后期叠加已授权文字与品牌资产。

## CR-68｜东京“一卷胶片”日夜旅行 Vlog

- **作者**：Ciri
- **模型/版本**：Seedance 2.5（作者在 prompt 首行标明）；**模式**：Reference generation；**Prompt 状态**：`partial`
- **发布日期**：2026-08-04
- **效果视频与原始来源**：[X 原帖（含视频）](https://x.com/Ciri_ai/status/2084527179006660713)
- **参考素材用途**：首行要求用未展示的主角参考图锁定身份、发型、身材、肤色、服装和配饰。

```text
Create a travel vlog using Seedance 2.5 on

Main subject from — lock her completely. Face, hairstyle, body proportions, skin tone, outfit, accessories, and overall appearance must remain perfectly identical throughout the entire video.

She is a sweet and naturally beautiful Indonesian girl, 18 years old, soft warm tan skin, expressive dark brown eyes, long black hair tied into a casual messy bun with loose bangs, youthful smile, minimal makeup, wearing a simple white oversized T-shirt, light blue denim jeans, white sneakers, and carrying a vintage brown canvas camera bag. Around her neck hangs a classic 35mm analog film camera.

**Theme:**
"Tokyo, One Roll of Film" — An epic solo day-to-night journey through Tokyo in 2026, from a quiet morning backstreet to the electric scale of the city at night. Still intimate and personal, never staged or trailer-like, but the density and energy of the city give it an epic, larger-than-life feeling.

Everything takes place across modern Tokyo in 2026: a quiet residential alley near a train station, a local shrine, a busy pedestrian scramble crossing, a narrow ramen-shop street, an elevated train platform, and a rooftop/observation deck overlooking the neon skyline at night.

The entire video must look like it was filmed naturally by her best friend walking beside her, using a modern mirrorless camera. No posing, no influencer behavior, no scripted acting. Every glance and movement feels spontaneous and real.

**Camera language is the highest priority:**
- Natural handheld movement
- Documentary-style walking tracking shots
- Gentle camera sway
- Occasional focus breathing
- Real autofocus adjustments, especially in low light
- Slight framing imperfections
- Natural motion blur from crowds and passing trains
- Soft depth of field
- Authentic available light — hard daylight, then neon and streetlight glow at night
- Premium lifestyle/urban-explorer vlog aesthetic

**Sequence:**

1. Early morning, she steps out of a small apartment building into a quiet Tokyo alley, adjusting her camera strap as soft light filters between buildings.
2. She walks past a local shrine, pausing to photograph torii gates, stone lanterns, and falling leaves with quiet curiosity.
3. She rides a local train, looking out the window, camera resting on her lap; passing cityscape reflected on the glass.
4. She steps off at a busy station and photographs the famous scramble crossing — hundreds of people in motion, her small figure calm at the edge of the chaos.
5. She wanders into a narrow street lined with tiny ramen shops and vending machines, photographing steam, signage, and everyday details.
6. Afternoon fades; she sits at a small counter, eating quickly, reviewing her shots on the back of her camera, smiling.
7. Blue hour arrives. She climbs to a rooftop or observation deck as the city lights begin switching on beneath her.
8. Wide epic shots of her small figure against the vast glowing skyline — Tokyo Tower or skyscrapers lit up, neon reflections, natural lens flare from distant lights.
9. She raises her camera and takes a few final shots of the skyline, hair lightly moving in the night breeze.
10. She notices the person filming her, laughs, turns, and lifts her analog camera toward the lens as if taking one last photo of the viewer, city lights glowing behind her.
11. The camera lowers slowly, she turns back to the view, still smiling.
12. Recording cuts off mid-motion, like a real city vlog ending.

**Lighting:**
Soft cool morning light transitioning through natural daylight into deep blue hour and warm artificial neon glow at night.

**Color:**
Natural realistic skin tones. Cooler ambient tones with warm neon accents at night. Subtle filmic contrast. No exaggerated grading.

**Audio is strictly natural:**
- Train announcements and platform chimes
- Footsteps on pavement
- Crosswalk signal beeping
- Crowd chatter and distant conversation
- Camera shutter clicks
- Film advance lever
- Vending machine hum
- City ambience and distant traffic at night
- No music, no narration, no subtitles, no logos, no watermark

Ultra-realistic. Looks exactly like a real solo city vlog filmed in 2026.
```

**复现与限制**：首行的参考图标识在可访问文本中缺失，故此条不得视为可完整复跑的配方。仅用成年、已授权的合成或真实人物参考；发布时标注合成旅行内容，避免冒充真实旅行记录。原帖未公开实际参考图、seed、比例、时长、生成次数与项目文件；“18 years old”在不同地区可能带来平台与广告合规限制，建议将复现角色改为明确成年且不含可识别真人身份的自有角色。
