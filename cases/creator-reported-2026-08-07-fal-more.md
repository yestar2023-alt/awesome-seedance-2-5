# CR-14 ～ CR-22｜Fal Seedance 2.5 实测补充

> **共同来源与证据。** 作者 Ilker 在 [Fal.ai 原文](https://fal.ai/learn/devs/seedance-2-5-prompting-guide) 明确声明以下十例均“Generated using Seedance 2.5 on fal”，prompt 印在各输出下方，且未剪辑、变速或后期添加音频。本页收录 CR-13 以外的九例；CR-13（杂货店）见独立文件。
>
> **共同元数据。** 证据等级：`creator-reported`；Prompt 状态：`full`；模型/版本：Seedance 2.5（Fal 的 `bytedance/seedance-2.5` endpoints）；作者：Ilker（fal.ai）；发布日期：2026-08-07；验证日期：2026-08-10。所有输出均为公开链接，本仓库不下载或镜像视频。除文中明确给出的设置外，seed 与复现次数未公开。

## CR-14｜餐馆咖啡打翻：因果与液体物理

- **模式**：Text-to-video，15 秒，连续单镜头，原生音频
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55f6f/x_YPdg1Sfo4w1htOkxG7a_video.mp4)
- **观察结果**：作者把“托盘碰杯把 → 杯倒 → 咖啡流动 → 人反应”拆开描述，用来约束事件先后关系。

```text
15-second continuous single take inside a busy Brooklyn neighborhood diner in the morning, natural real-time speed. Eye-level medium-wide camera at the end of the counter. 0-4 seconds: a server places a full ceramic coffee cup beside an open sketchbook and walks away. 4-8 seconds: a busboy passes behind the seated customer; the edge of his tray lightly catches the cup handle. The cup tips only after contact, strikes the counter, and coffee begins spreading toward the sketchbook. 8-11 seconds: the customer hears the impact, looks down, then lifts the sketchbook just before the coffee reaches it. Nearby diners turn toward the sound at slightly different delays. 11-15 seconds: the server returns with a towel and stops the spill. The camera begins a slow 30-centimeter push-in only after the cup tips. Keep the same cup, sketchbook, server, customer, counter layout, and clothing throughout. Coffee follows the counter surface and never moves uphill. No cuts, no slow motion, no repeated action, no duplicated props, no music. Audio: ordinary diner room tone, dishes, the ceramic impact, liquid spill, chair movement.
```

**复现与限制。** 选择 Text-to-video，按 15 秒实时时长复现；无公开 seed，不能据此判断成功率。杯、液体和人物交互仍是高失败风险点。

## CR-15｜高架站台遮挡后的人物与行李连续性

- **模式**：Text-to-video，11 秒，固定广角，原生音频
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa56786/HZo4cen8YMHdx4TBI1921_woman-walking.mp4)
- **观察结果**：输出被设计为检验人物与红色行李箱完全被立柱遮住后能否以相同状态出现。

```text
11-second continuous locked wide shot on a Chicago elevated train platform in overcast afternoon light, natural real-time speed. A woman in a bright green wool coat pulls one small red rolling suitcase from frame left toward frame right. 0–3.2 seconds: she walks steadily beside the yellow platform line, right hand holding the extended suitcase handle, suitcase rolling one step behind her. 3.2–5.1 seconds: she passes completely behind one thick concrete support column; both woman and suitcase are fully hidden for just under two seconds. 5.1–9.5 seconds: the same woman emerges from the opposite side of the column with the same face, hair, green coat, black boots, red suitcase, extended handle, walking speed, and direction. 9.5–10.8 seconds: she continues toward the right edge and the shot ends mid-stride as she is about to exit frame. The camera never moves. The column remains fixed. No person or suitcase appears on both sides of the column at once. No identity change, clothing change, color change, duplication, jump cut, morph, slow motion, or disappearing luggage. Audio: light wind, distant city traffic, suitcase wheels on concrete, a far train announcement, no music.
```

**复现与限制。** 固定机位、绿外套与红箱是最小检查项；未见独立复跑或帧级评测，结论仅限作者公开输出。

## CR-16｜篮球传球：屏幕位置与球权交接

- **模式**：Text-to-video，14 秒，侧向跟拍，原生音频
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55fe3/EJ2XrewypX9eNf4R0x3BT_video.mp4)

```text
14-second continuous sideline tracking shot in a public high school basketball gym in Indiana, natural real-time speed. One player in a plain red jersey owns the ball at the start; one teammate in a plain white jersey waits near the right side of the lane. 0-5 seconds: the red-jersey player dribbles with the right hand from frame left toward the free-throw line. The camera moves parallel and keeps the red player in the left third of frame, with the hoop visible on the right. 5-8 seconds: the red player plants the left foot and makes one chest pass across frame. The camera does not pan until the ball has fully left both hands. 8-11 seconds: the camera pans right with the airborne ball; the white-jersey player catches it with both hands near the right block and takes one step toward the hoop. 11-14 seconds: the white player makes a right-handed layup, lands on both feet, and the ball drops through the net. Keep the basket on the same side of frame and never cross the court axis. Preserve both players, jersey colors, ball ownership, direction, court markings, and light. No cuts, no slow motion, no extra ball, no duplicated players, no impossible handoff. Audio: sneaker squeaks, two dribbles, pass impact, backboard and net, small gym crowd, no music.
```

**复现与限制。** 以红/白球员、一次球权转移和不越轴作为验收；快速多人运动容易出现额外球或肢体错误。

## CR-17｜双图参考：咖啡机产品与厨房环境分工

- **模式**：Reference-to-video，14 秒，`@Image1` 产品、`@Image2` 环境
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55f8b/mlTjMQIzpIZ1SJ6UU7zEJ_video.mp4)
- **参考素材用途**：产品图控制机器几何；厨房图控制台面、光线和布局。

```text
14-second continuous product demonstration in the Los Angeles kitchen from @Image2. @Image1 controls only the exact portable espresso maker: preserve its short cylindrical proportions, matte cobalt-blue shell, black rubber grip ring, circular copper button, and clear lower chamber. Do not copy @Image1's studio background. @Image2 controls only the kitchen layout, oak countertop, white cup, beige towel, plants, window light, and warm daylight. Do not add the studio surface from @Image1. Start on a wide frame matching @Image2 with the product standing to the left of the white cup. 0-4 seconds: the camera makes a slow, level push toward the product while it remains still. 4-7 seconds: one natural right hand enters from frame right and presses the copper button once. 7-11 seconds: dark espresso begins flowing into the clear lower chamber; the liquid level rises naturally while the product body stays rigid and unchanged. 11-14 seconds: the hand withdraws and the camera shifts slightly right to place the product and cup side by side in the final frame. Keep the cup, towel, plants, countertop, product geometry, button position, and lighting consistent. No logo, no text, no extra machine, no extra hands, no cuts, no slow motion. Audio: quiet apartment room tone, soft button click, gentle brewing sound, distant Los Angeles traffic, no music.
```

**复现与限制。** 上传同职责的两张自有素材并保持顺序；原图可访问但其使用权不随案例授予。真实品牌或包装需取得授权。

## CR-18｜滑板越锥：接触、受力与落地

- **模式**：Text-to-video，12 秒，低机位侧跟，原生音频
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55f74/VBrhsD1A8rz74NefjgNLb_video.mp4)

```text
12-second continuous low side-tracking shot at the Venice Beach skatepark in late afternoon, natural real-time speed. A skater wearing a faded red T-shirt rides a black skateboard toward one yellow traffic cone. 0-3 seconds: he pushes once with his right foot, places it back on the board, and centers his weight. 3-6 seconds: he bends both knees while approaching the cone; the camera moves parallel and keeps his full body centered. 6-8 seconds: the rear foot snaps the tail against the concrete, the board rises, the front foot slides forward, and both rider and board clear the cone together. 8-10 seconds: the front wheels contact first, then the rear wheels; his knees compress from the landing and his arms correct his balance. 10-12 seconds: he straightens and rides away without another trick. Preserve the same person, shirt, board, cone, direction of travel, and sunlight. Believable wheel rotation, board contact, gravity, and body weight. No cuts, no slow motion, no floating board, no duplicated limbs, no repeated jump. Audio: skateboard wheels on concrete, tail pop, landing impact, distant beach ambience, no music.
```

**复现与限制。** 逐段检查起跳、板尾接触、前后轮落地；高动态肢体与板体关系不可视为稳定保证。

## CR-19｜图控车身、视频控运镜的雨夜汽车广告

- **模式**：Reference-to-video，16 秒，`@Image1` 车身、`@Video1` 运镜
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55fef/54bY8s46mCunI3aASbdg1_video.mp4)

```text
16-second continuous automotive tracking shot. @Image1 controls only the exact fictional silver sports car: preserve its body shape, silver paint, front light signature, black roof, wheel-spoke design, proportions, vents, and ride height. Do not copy @Image1's sunny San Francisco waterfront or parked composition. @Video1 controls only the low side-tracking camera height, parallel motion, subject framing, and real-time movement rhythm. Do not copy the skater, skateboard, cone, clothing, beach, or concrete setting from @Video1. Place the car on a rain-wet downtown Seattle avenue at blue hour. 0-4 seconds: the car waits at a red traffic light while the camera holds a low front-side angle. 4-11 seconds: the light turns green and the car accelerates smoothly; the camera tracks parallel at door height while keeping the full car centered and sharp. Wheels rotate at the correct speed, suspension settles under acceleration, reflections move across the exact silver body, and water sprays backward from the tires. 11-16 seconds: the car eases into the right lane and maintains speed while the camera falls half a car length behind into a rear three-quarter view. Preserve one car and the same design in every frame. No cuts, no redesign, no extra spoiler, no logo, no copied human subject, no skateboard, no cone, no slow motion. Audio: wet tire noise, restrained electric motor whine, distant traffic, rain on road, no music.
```

**复现与限制。** 用无商标的自有车图和运动视频；参考图往往比文字约束更强，素材中的错误构图可能被继承。

## CR-20｜竖屏 UGC：对白时段与无漏杯测试

- **模式**：Text-to-video，12 秒，9:16，手持镜头，原生音频
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55f7d/aB__WHUenX7ROgBwAOAcH_video.mp4)

```text
12-second vertical 9:16 handheld phone video in a sunlit Austin apartment kitchen, natural real-time performance, one continuous take. A woman in her late twenties stands at the counter holding a small plain insulated travel cup with no logo. 0-3 seconds: she looks into the phone camera, briefly raises the cup, and says, "I bought this for the commute, but I use it at home every day." 3-6 seconds: she stops speaking, looks down, turns the lid one quarter turn with both hands, and waits until it clicks. 6-9 seconds: she tilts the sealed cup sideways over the sink for two seconds; no liquid leaks. 9-12 seconds: she returns the cup upright, looks back at the camera, and says, "That is the whole reason." Her mouth moves only during her own lines. Keep the same face, hair, shirt, cup, lid, kitchen, hand count, and daylight throughout. Subtle natural phone-camera shake, ordinary skin texture, no beauty filter, no cuts, no zoom, no slow motion, no extra products, no text, no logo, no music. Audio: clean lip-synced speech, quiet apartment room tone, soft lid click, distant traffic.
```

**复现与限制。** 逐项检查口型、两段对白和转盖时闭嘴；不要用未获同意的人脸或产品标识作为参考。

## CR-21｜煎饼糖浆：流体终态约束

- **模式**：Text-to-video，15 秒，21:9 微距，原生音频
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa55ff4/oRgq8W30Y5MKV_04nBuqQ_video.mp4)

```text
15-second continuous 21:9 macro food shot at a roadside diner breakfast counter, natural real-time speed. A stack of three plain buttermilk pancakes sits on one white ceramic plate with a square of butter centered on top and six blueberries around the base. 0-4 seconds: a small glass syrup pitcher enters from frame upper right and tilts above the butter; the camera begins a slow ten-degree clockwise arc around the plate. 4-9 seconds: one continuous amber stream lands on the butter, divides around it, and runs down the pancake edges under gravity. Syrup pools on the plate and does not flow uphill. 9-12 seconds: the pitcher tilts upright; the stream narrows, stretches, then breaks cleanly before the pitcher leaves frame. 12-15 seconds: the butter softens slightly and slides only a few millimeters before stopping; the syrup continues settling into one pool. Preserve the same three pancakes, butter, six blueberries, white plate, counter, and warm window light. No cuts, no slow motion, no extra fruit, no changing food count, no floating liquid, no text, no logo. Audio: quiet diner room tone, soft glass movement, syrup landing on food, distant dishes, no music.
```

**复现与限制。** 检查糖浆不断重播、果实数量变化与违反重力等问题；液体细节存在抽样波动。

## CR-22｜从煎饼末帧续写：不重复旧动作

- **模式**：Reference-to-video，12 秒，`@Image1` 为 CR-21 最终帧
- **效果视频**：[播放](https://v3b.fal.media/files/b/0aa56036/_-yTrxNeObfrxbdBDIstg_video.mp4)

```text
Use @Image1 as the exact first frame and continue forward from that moment. Preserve the same stack of three buttermilk pancakes, softened square of butter, six blueberries, white ceramic plate, amber syrup pool, counter, warm diner light, 21:9 framing, macro lens, and camera position. Do not replay or recreate the syrup pour that happened before this frame. 0-4 seconds: hold the same composition while the syrup pool makes only small natural settling movements. 4-8 seconds: one clean stainless-steel fork enters from frame right with no hand visible, presses into the front edge of the top pancake, and separates one bite-sized piece. 8-10 seconds: the fork lifts the same piece upward; one thin syrup strand stretches from the piece to the stack. 10-12 seconds: the syrup strand narrows and breaks, and the fork exits toward frame right with the piece. The remaining stack stays on the plate with one small missing bite at the front. No new pour, no pitcher, no hand, no extra fork, no extra pancakes, no changing blueberry count, no cut, no slow motion, no text, no music. Audio is quiet diner room tone with a soft fork contact and sticky syrup separation.
```

**复现与限制。** 从上例的最终帧或视觉等价的自有末帧起步；没有公开 seed，也没有对跨次生成连续性的独立量化。

## 证据与风险说明

- **模型与输出证据**：[Fal 原文](https://fal.ai/learn/devs/seedance-2-5-prompting-guide) 同时公开模型名、每条完整 prompt 与视频播放器；各 MP4 为该文内嵌资源。
- **复现层级**：`documented`，未由本仓库独立调用模型验证。
- **风险**：真实人物、品牌、产品和参考素材均可能受肖像权、商标或版权约束；请改用自有或已授权素材。
