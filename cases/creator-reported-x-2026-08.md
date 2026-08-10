# CR-65 ～ CR-70｜X 创作者公开实测（2026-08）

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

## CR-69｜比萨斜塔工程图：模块化搭建与倒放拆解

- **作者**：Lee Lin | AI
- **模型/版本**：Seedance 2.5（prompt 明确要求）；**模式**：Image-to-video + 后期倒放；**Prompt 状态**：`full`
- **发布日期**：2026-07-31
- **效果视频与原始来源**：[X 原帖（含视频）](https://x.com/LeeLinAI123/status/2083305831404044545)
- **参考素材用途**：上传的比萨斜塔工程示意图是唯一输入，锁定背景、材料、构图、基础模块、图纸层与建筑倾斜轴；该图片未单独公开。

```text
Execute immediately. Do not restate the prompt, explain capabilities, offer options, or ask questions.

Use the uploaded Leaning Tower of Pisa construction diagram as the only input image. Generate one 15.0-second Seedance 2.5 image-to-video source clip, native 16:9, 720p.

This is an architectural construction-teaching video. Preserve the warm-white studio background, marble materials, engineering-diagram aesthetic, lighting, framing, and all existing shapes from the input image. Do not redesign or invent a new tower.

Asset roles

The partially built circular base at the lower center is the fixed construction anchor. It includes the existing stairs, entrance, cutaway masonry, and foundation. It never moves, rotates, scales, or breaks apart.

Only these existing 3D elements are allowed to assemble:

the curved column module and curved arch module at mid-left;
the five C-shaped masonry-and-gallery modules in the center-left column;
the five matching open arcade rings in the center-right column;
the upper-right transition platform, bell-chamber arch ring, and finished bell-chamber crown.

Everything else is a teaching-reference layer only:

the elevation, plans, sections, diagrams, callouts, labels, leader lines, and dimension marks;
the upper-left material samples;
the separate entrance sample and spiral-stair sample;
the loose group of seven bells at lower right.

The teaching-reference layer never joins the building. It only fades out and later fades back in at exactly its original position. Its own shadows fade with it.

Motion rules

This must feel like the Huanghelou construction video: only one construction group moves at a time. The active group stays at full brightness; all waiting construction groups remain visible but dimmed to about 60% brightness.

Every moving group keeps its original material, scale, orientation, and rigid shape. It moves along one short, clean, unobstructed path toward its final interface. No random flight, free rotation, melting, morphing, stretching, duplicate copies, or geometry left behind at the original location.

Each group eases in, slows down before contact, locks perfectly into place, and pauses for about 0.12 seconds before the next group starts.

The final tower follows the leaning direction indicated by the red “actual axis” in the left elevation drawing. The lean is stable architecture, not a collapse: do not straighten it, increase the lean, wobble, bend, or shake it.

Source-clip timeline

0.00–0.55s — Hold the first frame
Keep the full diagram perfectly still so the viewer can read the exploded structure.
0.55–1.15s — Reference layer fades out
Fade out all diagrams, material samples, loose entrance and stair samples, loose seven-bell group, labels, callouts, and leader lines.
Do not fade the warm-white background, the fixed central anchor, or the actual construction modules.

1.15–2.05s — First arcade level
Move the curved column module into the open receiving interface on top of the fixed anchor and lock it.
Then move the curved arch module into the same level, completing the first arcade layer.
2.05–7.05s — Five upper arcade levels
Build the remaining five levels from bottom to top. For each horizontal pair:
Move the matching C-shaped masonry-and-gallery module into place first.

Move the matching open arcade ring second. It first aligns on the same leaning local axis, then descends coaxially around the masonry module and locks.
Complete one full level before starting the next. Do not let upper layers move early. After this stage, the tower must show exactly six open arcade levels in total.
7.05–8.45s — Bell chamber
Move the circular transition platform onto the sixth arcade level, keeping its central opening aligned with the tower.
Then install the bell-chamber arch ring.
Finally install the finished bell-chamber crown containing the bell already visible in the reference image.

The loose seven bells remain part of the teaching-reference layer and never fly into the tower.
8.45–9.20s — Clean completed tower
Hold the completed Leaning Tower of Pisa completely still on the warm-white background. No diagrams or reference samples are visible.

9.20–10.30s — Teaching layer returns
While the completed tower remains absolutely motionless, fade the original diagrams, material samples, loose stair and entrance samples, loose bells, labels, and callouts back to their exact first-frame positions.
10.30–15.00s — Stable display
Keep the completed tower and restored teaching-reference layer perfectly still.

Final 15-second loop

After generating source clip A, use the same project timeline:
Keep source A from 0.00 to 10.30 seconds at normal speed.
Duplicate that exact 0.00–10.30-second section.
Mute the duplicated section.

Reverse it and speed it up evenly to 4.70 seconds.

Place it immediately after 10.30 seconds.
Use a direct same-frame cut at the join: no dissolve, flash, black frame, or transition.

Do not generate a second AI video for the disassembly.
The reverse section must naturally show: reference layer fades out → bell chamber leaves → the six arcade levels leave in reverse order → the first arcade modules return → all construction modules return to their exact first-frame positions → teaching layer restores → final frame matches the uploaded first frame.

The reverse disassembly should feel fast and exciting, but never like an explosion. Every module follows its exact original path backward.
Camera, background, and audio

Lock the original camera position, focal length, perspective, horizon, roll angle, exposure, and frame. No zoom, orbit, pan, tilt, push-in, pull-back, or camera correction of the tower lean.

Keep the warm-white background, floor, shadow direction, and brightness continuous for the entire video. Never use black, dark gray, vignetting, a new location, a white flash, or a full-frame fade-out.

No voiceover, dialogue, subtitles, lyrics, logos, watermarks, platform UI, or end card. Use only a subtle continuous room tone and very light stone-contact sounds. Mute the reversed clip audio.
Deliver one final 15.0-second native 16:9 video and report the result briefly in Simplified Chinese.
```

**复现与限制**：先用自制/已获授权的建筑拆解图，严格分离“固定锚点、可移动模块、仅教学显示层”，并逐项检查模块数量、安装顺序、斜轴、阴影和倒放回归首帧。最终交付由 10.3 秒 Seedance 源片加复制、静音、倒放、加速的编辑步骤组成；不得把它误称为单次模型输出。原帖未公开输入图、seed、实际项目时间线或生成次数；复现时也避免将“Leaning Tower of Pisa”用于未经许可的商业品牌暗示。

## CR-70｜《每一日》：粤语双人对白与微表情测试

- **作者**：John（@johnAGI168）
- **模型/版本**：Seedance 2.5（作者明确标注）；**模式**：Text-to-video；**Prompt 状态**：`full`
- **发布日期**：2026-08-05
- **效果视频与原始来源**：[X 原帖（含视频）](https://x.com/johnAGI168/status/2084918554181206410)
- **参考素材用途**：无；以文本锁定两个原创角色、座位、服装、声音与视线关系。

```text
《每一日》——15秒王家卫风格男女对手戏

SEEDANCE 2.5 演员表演提示词

【全局设置】
时长15秒，16:9横屏。原生生成自然香港粤语对白，严格区分男女声线并准确同步粤语口型。无字幕、旁白、配乐；只保留窗外雨声、远处车辆掠过、旧空调低鸣、玻璃杯轻响与真实呼吸。

【影像风格】
原创人物、原创对白，采用王家卫式香港爱情电影作为审美锚点：1990年代潮湿夜色，深青绿色阴影、浓郁酒红与洋红霓虹、脏黄色钨丝灯，肤色温暖但略欠曝；高反差、柔化高光、明显35毫米胶片颗粒、玻璃反射、浅景深、局部遮挡。摄影机贴近人物，轻微手持呼吸感。仅在对白结束后的沉默中使用轻微抽帧与低快门拖影；说话时保持正常运动与清晰口型。不要复刻任何具体电影角色、台词或镜头。

【人物与潜台词】
阿衡：29岁香港男性，短黑发，深色衬衫，低沉略哑的粤语声线。他一直把分手归结为自己某个晚上离开，以为只要改写那个晚上，一切就能恢复。
嘉敏：28岁香港女性，黑色齐肩发，暗红针织外套，声音轻而稳定。她仍然爱他，但已经明白，真正毁掉关系的不是某个晚上，而是之后无数次没有被选择。
两人隔着一张窄桌相对而坐，玻璃窗上的霓虹倒影从两张脸之间穿过。保持脸型、发型、服装、声线、座位、视线方向、玻璃反光与色调一致。

情绪曲线：试探过去→看穿问题→男人自我辩护→女人温柔纠正→男人无声失去支撑。全片不喊叫、不落泪；最大表演峰值是最后一句以后男人的沉默反应。

【镜头一｜0.0–4.0秒】
85mm人像镜头，阿衡胸部以上侧面近景，面向画面右侧。嘉敏肩膀为右下角虚化前景。霓虹倒影将阿衡半张脸切成深青与暗红两部分。摄影机近乎固定，只做极慢推近。

阿衡想把问题缩小成一个可以修正的晚上。开口前用拇指缓慢摩擦玻璃杯边缘一次，嘴唇压紧后松开，目光停在嘉敏脸上，却不敢完全直视她的眼睛。低声问：

阿衡：「如果嗰晚我冇走，你會唔會留低？」

“嗰晚”轻微加重；“我冇走”说得很慢，像在脑中重新演一遍；“你會唔會”声音更轻；“留低”句尾不上扬，更像请求而不是提问。说完手指停止，终于看进她的眼睛。禁止哭腔、讨好微笑或伸手触碰。

【镜头二｜4.0–9.0秒】
硬切嘉敏正面紧密特写，85mm镜头感。阿衡肩膀为左侧模糊前景。窗外红色车灯缓慢掠过她的眼睛，但摄影机和焦点保持稳定。

4.0–6.5秒：嘉敏听见“嗰晚”时，嘴角出现不足0.25秒的苦笑，笑意不进入眼睛。她先看着他0.3秒，再轻声说：

嘉敏：「你每次都淨係問嗰一晚。」

“每次”不带指责，只有疲惫；“淨係”轻微加重；“嗰一晚”逐词放慢。说完目光没有躲开，下巴出现轻微支撑（AU17-A）。

6.5–9.0秒：镜头仍留在嘉敏脸上。阿衡画外短促吸气，用被误解后的防御语气回答：

阿衡（画外）：「因為我只係錯咗一次。」

“只係”明显加重；“一次”变快，像急着证明事情没有她说得那么严重。听到“一次”时，嘉敏眼睑轻微收紧后松开；她的苦笑完全消失，嘴唇张开0.2秒却没有立刻发声。此时不能湿眼。

【镜头三｜9.0–15.0秒】
50mm侧面双人近景，两张脸分别位于画面左右，玻璃反射叠在两人之间。前景偶尔有模糊行人掠过，但不能遮住嘴部。两张脸保持清晰，摄影机不切镜。

9.0–12.8秒：嘉敏终于纠正他。她先用鼻子轻轻吸气，身体没有前倾，声音比之前更温柔：

嘉敏：「唔係。係之後每一日，你都冇揀過我。」

“唔係”很轻、很清楚；停0.25秒。“之後每一日”明显减速，每个字都像在回忆一次具体失望；到“你都”时目光短暂向下离开不足0.2秒，再看回他；“冇揀過我”音量逐词降低，只允许在最后一个“我”出现一次极细的气息卡顿，不能形成哭腔。眉毛内侧轻微上抬，下巴绷紧（AU1-A、AU17-B），眼眶只出现微弱水光，不落泪。

12.8–15.0秒：嘉敏说完后保持直视，不等待解释。阿衡的嘴唇张开，像要说“不是”，却没有声音；原本握住玻璃杯的手慢慢松开，下颌向侧面移动，完成一次克制吞咽。他第一次移开目光，看向玻璃里两人的重叠倒影，却发现倒影已经被经过的车灯分开。

此时才允许背景出现轻微抽帧和拖影，人物面部仍清晰。最后0.8秒只保留空调低鸣、雨声和一次失败的吸气；两人都不离开，也不和解，直接结束。

【总体表演约束】
粤语对白逐字保留，不增删、不换人；使用自然香港粤语，不要普通话口音、配音腔或朗诵腔。阿衡不是故意伤害她，他真心相信自己只错了一次；嘉敏不是报复，而是终于说出两人对“失去”的理解从来不同。表演依靠停顿、目光、手指停止、微笑消失和吞咽完成，禁止用喊叫代替情绪。

【负面提示词】
禁止复制王家卫电影原台词、角色造型或具体镜头；禁止全程慢动作、说话时抽帧、嘴部拖影、喊叫、哭泣、落泪、歇斯底里、扇耳光、指人、拉扯、拥抱、强吻、夸张苦笑、舞台剧表演、机器人粤语、普通话口音、对白改写、口型漂移、双嘴、人物冻结、霓虹过曝、赛博朋克、廉价MV质感、过度美颜、塑料皮肤、五官或肢体异常、人物/服装/座位/机位/视线漂移、字幕、水印、标志、乱码。
```

**复现与限制**：逐项检查粤语口型、两人声线、镜头切换、微表情、人物/座位持续性和“对白段不抽帧”的约束。作者使用在世导演王家卫的姓名作为美术锚点，即便 prompt 禁止复刻具体电影元素，复现/商用仍应改写为不指向具体创作者的原创湿润都市爱情片美术方向；不得使用任何真实演员的肖像或声音。原帖未公开 seed、比例外的参数、生成次数及项目文件。
