# Awesome Seedance 2.5 — 官方案例首批素材

> 收录原则：只收录可回溯到发布者的**效果视频直链**和**公开原始提示词**。本批全部来自字节 Seed 于 2026-07-31 发布的官方案例页；提示词保持原文，不将第三方“示例 prompt”误标为实测复现配方。

## 使用与转载说明

- 视频文件版权归原发布方所有。本仓库建议保存外链与来源页，不把 MP4 二次上传到 GitHub。
- `@图片`、`@视频`、`@白模`是官方案例中使用的参考输入占位符；要复现，需要用等价的自有素材替换。
- `T2V` 为文生视频，`R2V` 为参考驱动/编辑视频。点击“效果视频”可直接播放官方 CDN 文件。

## 索引

| ID | 案例 | 模式 | 验证点 | 效果视频 |
|---|---|---|---|---|
| SD25-001 | 歌手后台至体育馆演出 | T2V | 30 秒长叙事、一镜到底、音画同步 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms8eg74b.mp4) |
| SD25-002 | 地铁追逐续写 | R2V | 多轮延长、人物/声音连续性 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89gioe.mp4) |
| SD25-003 | 京剧三人舞台调度 | R2V | 多主体、遮挡转场、时间段镜头 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89gnha.mp4) |
| SD25-004 | 古典音乐会群像 | R2V | 18 张参考、多人同框 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89h7hu.mp4) |
| SD25-005 | 白模驱动童话动画 | R2V | 白模、轨迹、运镜与风格分离 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89imyw.mp4) |
| SD25-006 | 足球绿幕重渲染 | R2V | 绿幕编辑、分段换景 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89jtbf.mp4) |
| SD25-007 | 早餐片段改运镜 | R2V | 保持内容、仅编辑摄影机 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89jxvz.mp4) |
| SD25-008 | 南宋词意教学短片 | R2V | 教育场景、风格化叙事 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89k0ne.mp4) |
| SD25-009 | 汽车装配白模渲染 | R2V | 工业仿真、空间/零件约束 | [播放](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89k8sg.mp4) |

## 案例与提示词

### SD25-001｜歌手后台至体育馆演出

- 模式：T2V
- 关注：用单一连续摄影机完成“准备—穿行—登台—高潮”的叙事弧。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms8eg74b.mp4)

```text
一镜到底手持稳定器跟拍，镜头从红色厚重幕布缝隙缓缓推进，进入暖色后台化妆间。年轻女歌手背对镜头整理耳机，工作人员提醒她准备登台。她回头看向镜头，开始唱起 City Pop。镜头后退跟拍，歌手穿过幕布进后台通道，与舞伴自然互动，一位工作人员把麦克风递给她。随后歌手与舞伴登上舞台，镜头绕至背面，红黑舞美、LED 屏、追光、烟雾与反光地板逐渐展开。镜头最终拉远至体育馆全景，呈现满场观众、灯牌、荧光棒与欢呼声，营造年轻自由的演唱会高潮氛围。
```

### SD25-002｜地铁追逐续写

- 模式：R2V（延长）
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89gioe.mp4)

```text
延长视频，衔接 @视频 1 画面内容和主体继续生成一个 30 秒的视频，保持人物主体、场景、画面风格、声音音效一致。小男孩抱着足球沿车厢跑，地铁停稳后侧边门打开，他立刻冲出，男主紧追。两人一路穿过站台跑到街上，惊动街边路人，男主最终追上并抓住他，小男孩委屈抬头，男主慢慢消气，摸摸他的头，露出无奈笑容。
```

### SD25-003｜京剧三人舞台调度

- 模式：R2V；输入：4 张场景/角色参考。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89gnha.mp4)

```text
16:9 宽幅电影级质感，一镜到底，丝滑运镜，无剪辑。场景参考 @图片 4。0-5 秒：@图片 2 霸王近景开场，镜头缓慢环绕上半身并过渡至中景；霸王旋身翻转，随后身体与靠旗从镜头前快速掠过，形成自然遮挡，镜头顺势绕至 @图片 1 虞姬身侧。6-10 秒：镜头稳定环绕 @图片 1 虞姬中景，跟随水袖动作完成环绕运镜：虞姬抬臂、挑腕、展袖、半转身。最后收袖定格，侧身看向霸王。11-20 秒：@图片 3 武生出场完成后空翻腾动作，随后霸王居中，武生在对侧进退攻防。虞姬位于霸王侧后方以水袖配合，形成刚柔对比。镜头从武生中近景缓慢后拉至舞台大景，结尾三人面向观众同步京剧落幕亮相。
```

### SD25-004｜古典音乐会群像

- 模式：R2V；输入：场景、乐手、合唱团、观众等 18 张图。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89h7hu.mp4)

```text
30 秒音乐会片段，16:9 横屏，电影感写实，真实音乐厅光影，暖金色舞台灯，正式古典音乐会氛围。场景@图一，钢琴家参考@图二，大提琴参考@图三，小提琴参考@图四，主唱参考@图五，管弦等其他乐队参考@图六到图十，合唱团参考图十一到图十四，观众席参考@图十五到图十八。主唱舞台中央走向前沿，钢琴家在钢琴旁，乐队分布两侧与后方，合唱团在舞台后方。开场高位俯拍音乐厅全景，钢琴家落键，主唱进入追光演唱，镜头自然带过小提琴、大提琴与管弦乐队，小提琴明亮，大提琴温暖。后段合唱团加入，主唱与第一排观众短暂眼神交流，观众微笑点头。结尾镜头后移，演唱结束，观众跟随鼓掌。
```

### SD25-005｜白模驱动童话动画

- 模式：R2V；输入：白模 1 + 风格图 2。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89imyw.mp4)

```text
参考 @白模 1 的运镜、镜头节奏、景别变化、主体轨迹和镜头调度。参考 @图片 2 的角色外形、场景、材质、光照、色彩和童话氛围，将白模渲染为梦幻温暖、儿童幻想感、3D 动画短片。剧情依次为：幻想天空飞行→云海神兽伴飞→俯冲入海→鳐鱼海底穿梭→镜面时空裂缝→宇宙摘星→幻化回房间→爸爸盖被→合上绘本定格。
```

### SD25-006｜足球绿幕重渲染

- 模式：R2V（绿幕编辑）。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89jtbf.mp4)

```text
把 @视频 1 绿幕背景渲染场景、障碍、服装和配角：0-4 秒：户外训练，障碍换石头、砖块、轮胎、木箱；4-10 秒：休息室，朋友鼓励；10-15 秒：国际赛场，训练杆换原创防守球员和门将，主角进球。整体写实电影级。
```

### SD25-007｜早餐片段改运镜

- 模式：R2V（只编辑运镜）。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89jxvz.mp4)

```text
编辑 @视频 1，保持人物、动作及画风不变，仅调整运镜。15 秒分段运镜设计：0–4 秒，微型 FPV 贴锅穿行，跟随弹起的吐司后横甩至咖啡；4–7 秒，推近并沿锅边横移，跟随煎蛋翻起落回；7–11 秒，急速升至顶视角，匀速下压扫过餐盘和钥匙；11–15 秒，手持近镜跟随双手快速横甩，最后推近早餐，再拉回双人中景。全程连贯稳定。
```

### SD25-008｜南宋词意教学短片

- 模式：R2V；输入：辛弃疾人物参考图。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89k0ne.mp4)

```text
东方写意风格。南宋临安街景，热闹的街上几个孩子边跑边闹，孩子们嘴里张嘴念着“蓦然回首，那人却在，灯火阑珊处”。镜头始终跟随孩子们奔跑，带过热闹的街景。镜头上摇，此人正是 @图片 1 辛弃疾。辛弃疾回头，远处是在灯火阑珊中的男子，镜头连贯。
```

### SD25-009｜汽车装配白模渲染

- 模式：R2V；输入：白模 1 + 材质/氛围图 1。
- [效果视频](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/user-upload/4xfa4ms89k8sg.mp4)

```text
参考 @白模 1 的运镜、构图、景别、空间关系、零件位置、模型结构、装配顺序和运动轨迹。参考 @图片 1 的材质、光照、色彩、反射和氛围，将白模渲染为高端真实汽车拼装片段。
```

## 来源与贡献规范

- 官方发布页：[《一镜成片，随心参考｜Seedance 2.5 正式发布》](https://seed.bytedance.com/zh/blog/%E4%B8%80%E9%95%9C%E6%88%90%E7%89%87-%E9%9A%8F%E5%BF%83%E5%8F%82%E8%80%83-seedance-2-5-%E6%AD%A3%E5%BC%8F%E5%8F%91%E5%B8%83)（2026-07-31）。
- 更多非官方、但带输入与输出的案例见 [社区案例补充](./community-reported.md)。请保留其 `creator-reported` 证据等级。
- 新增案例应提供：效果视频可访问链接、完整 prompt、模式、参考素材用途、原始出处、确认日期。
- 标注 `official`、`creator-reported`、`reproduction` 三种证据等级；本文件均为 `official`。
