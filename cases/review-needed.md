# 待复核候选（不计入主案例）

> 本页记录已定位到的公开创作者视频，但它们还缺少“完整公开 prompt + 可对应的具体输出”的证据组合。它们不是已验证案例，不能直接作为可复现配方使用。

| 候选 | 来源与日期 | 已确认 | 缺口 | 后续复核方式 |
|---|---|---|---|---|
| RN-01｜全流程电影工作流 | [Rourke Heath](https://www.youtube.com/watch?v=MY6f9xnYOwU)，2026-08-08 | 作者称使用 Higgsfield Seedance 2.5、50 张图片参考，并展示作品与流程。 | Prompt 仅在视频画面中展示，描述栏未公开全文；输出与各 prompt 的逐条对应未结构化公开。 | 若作者将 prompt 文本或项目文件公开，可逐条建立案例。 |
| RN-02｜人物与环境一致性 | [Marin Method](https://www.youtube.com/watch?v=MckeX0s_PWI)，2026-08-05 | 作者称在 Dreamina 使用 Seedance 2.5，并给出 Notion 模板链接和完整流程视频。 | 模板不是已验证的具体生成 prompt；没有把某个完整 prompt 与某个公开输出一一对应。 | 打开作者公开的项目/Notion，确认是否有具体 prompt、输入与输出对应。 |
| RN-03｜电影时装广告 | [Raph Guilhem](https://www.youtube.com/watch?v=LgE0fVBCHig)，2026-07-23 | 作者说明使用 Gemini、Claude 与 Seedance 2.5，从时装参考视频生成新广告。 | 原视频描述未提供具体生成 prompt、输出链接或参考素材。 | 仅在工作流页公开逐案素材和完整 prompt 后入库。 |
| RN-04｜一张图与声音克隆 | [Zubair Trabzada](https://www.youtube.com/watch?v=Ii5vlQMsgl8)，2026-08-08 | 作者称视频含“exact prompts”，并在视频中演示参考图、声音和 UGC 工作流。 | 描述栏只给出 prompt pack 入口，未公开单条 prompt 与对应视频；涉及人脸与声音，风险更高。 | 取得明确公开、可访问且有授权说明的单例资料后再评估。 |
| RN-05｜单 prompt 多风格测试 | [Yaroflasher](https://www.youtube.com/watch?v=7pQ9SJUzA4w)，2026-08-03 | 作者明确称片头由 Seedance 2.5 和单个 prompt 生成，视频公开。 | 原帖未公开该 prompt 的全文或具体生成设置。 | 作者补充 prompt、模型入口与设置后可升级。 |
| RN-06｜Figma Weave 商品广告 | [Artturi Jalli](https://www.youtube.com/watch?v=IqosffVLFEA)，2026-08-09 | 作者提供工作流/提示词链接，并公开商品广告视频。 | 外部 Weavy 工作流页受 Cloudflare 访问保护，当前无法核验单个完整 prompt、输入素材和模型调用记录。 | 在公开可访问时验证模型版本、输入与输出一一对应。 |
| RN-07｜兔爪触脸的接触动作测试 | [u/Guilty-Cap2069](https://www.reddit.com/r/Seedance_AI/comments/1vi9d4f/seedance_25_kept_the_character_consistent_but/)，2026-08-10 验证 | 作者称以 ZenMux 的 `bytedance/doubao-seedance-2.5` 生成 720p、8 秒成片；原帖嵌入效果视频，并具体说明预期接触动作未执行。 | 作者称完整 prompt 在首条评论，但该评论未出现在当前可访问的公开页面，故无法核对完整文本与成片。 | 若作者在正文、可公开读取的评论或项目页贴出 prompt 全文，可作为“失败也可复现”的动作接触案例复核。 |
| RN-08｜单提示词电影片段 | [u/huzi001](https://www.reddit.com/user/huzi001/comments/1vg7n0s/seedance_25_output/)，2026-08-10 验证 | 作者称该嵌入成片由 Seedance 2.5 的单条文生视频 prompt 生成，并明确提及动作、运镜、物理、对白与连续性。 | 正文没有公开 prompt 原文、模型入口、时长、分辨率或参考素材；无法据此区分实际参数与事后描述。 | 若作者补充完整 prompt 和使用平台/设置，可将成片与文本建立一对一案例。 |
| RN-09｜单图 Vlog 广告 | [r/Seedance_AI 帖子](https://www.reddit.com/r/Seedance_AI/comments/1vbse9l/seedance_25_is_insane_for_vlog_style_ads/)，2026-08-10 验证 | 帖子嵌入一支 30 秒广告视频，并声称由“一张产品图 + 一条 prompt”一镜生成；评论中也向作者索要 prompt。 | 公开页面没有作者实际使用的 prompt、输入产品图、具体平台或设置；“prompt”仅是未证实的说法。 | 作者在正文/评论公开 prompt 与可使用的参考素材后，再核验是否为 Seedance 2.5 成片。 |

## 处理规则

- 待复核条目不计入 README 的案例总数，也不得标为 `official`、`creator-reported` 或可复现配方。
- 升级到主库前，至少需要原始来源、精确的 Seedance 2.5 主张、公开输出、完整/明确标注状态的 prompt，以及案例级限制说明。
- 对含真人脸、声音克隆、品牌/影视 IP 的条目，额外确认授权范围与合成媒体风险。

## 本轮补证记录（2026-08-10）

- Chris Jarou 的 [公开提示词文档](https://docs.google.com/document/d/1p2zqv0vt3fYZd73qKuFz1Nx2ClDjYihOK3Fgw1sy-0w/edit) 可访问，包含通用参考图 prompt；但没有把其中任一 prompt 与视频中的具体输出建立公开的一一对应，因此不升级为案例。
- Raph Guilhem 的 Pletor 工作流跳转页可访问，但仅公开页面标题，未见可供核验的 prompt 或输出资产。
- Artturi Jalli 的 Weavy 工作流页返回 Cloudflare 验证页；未绕过访问保护。
