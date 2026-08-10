# Awesome Seedance 2.5

> A curated, source-attributed collection of Seedance 2.5 video examples, prompts, and playable output links.

中文说明：这是一个可追溯的 Seedance 2.5 案例库。每个案例收录效果视频、完整提示词、生成模式、来源与证据等级；不把营销示例或未证实的转述伪装成实测结果。

## Contents

- [Official cases — 9 examples](./cases/official.md): ByteDance Seed 发布页公开的 prompt 与视频。
- [Community-reported cases — 12 examples](./cases/community-reported.md): 公开 Showcase 中的输入、prompt 与视频，均明确标记为 `creator-reported`。
- [New creator case — CR-13](./cases/creator-reported-2026-08-07-fal-bodega.md): Fal.ai 作者公开的 30 秒一镜到底实测（`creator-reported`）。
- [Fal creator cases — CR-14 ～ CR-22](./cases/creator-reported-2026-08-07-fal-more.md): 公开的因果物理、遮挡、参考分工、对话、流体和续写实测。
- [Krea creator cases — CR-23 ～ CR-30](./cases/creator-reported-krea-prompt-gallery.md): 公开 Prompt Gallery 的 8 个可播放案例，涵盖食物、时装、城市生活、动物、运动和艺术。
- [Independent creator case — CR-31](./cases/creator-reported-2026-08-08-teachers-tech-fisherman.md): Teacher's Tech 公开完整 prompt 的 30 秒叙事与同步音频案例。
- [Review needed](./cases/review-needed.md): 已发现但尚缺完整 prompt 或输入/输出对应证据的创作者候选，不计入案例总数。
- [Showcase expanded cases — CR-32 ～ CR-48](./cases/community-reported-more.md): 17 个经视频链接核验的参考生成、视频编辑与续写案例。
- [Showcase serialized cases — CR-49 ～ CR-55](./cases/community-reported-serialized.md): 7 个从页面原始序列化数据还原的完整 prompt，涵盖多参考广告与长提示词续写。
- [Reddit creator cases — CR-56 ～ CR-63](./cases/creator-reported-reddit-2026-08-10.md): 八个独立创作者公开的成片帖与完整 prompt，覆盖第一人称动作、30 秒手持单镜头、双参考对话、旅行 Vlog、多房间转场、咖啡制作、日常纪实和对象持续性测试。
- [Early-access creator case — CR-64](./cases/creator-reported-2026-07-11-testingcatalog.md): TestingCatalog 公开的 30 秒 Seedance 2.5 样片；原帖后续更正为非 Pro，仅公开题材级 prompt 文本，明确标记为 `partial`。
- [X creator cases — CR-65 ～ CR-70](./cases/creator-reported-x-2026-08.md): 六条原作者公开的 Seedance 2.5 成片与 prompt 文本，涵盖复古奇幻、机甲追逐、产品广告、旅行 Vlog、工程拆解与粤语对白；CR-68 明确标为 `partial`。
- [Cloudstitcher creator case — CR-71](./cases/creator-reported-x-2026-08-03-cloudstitcher.md): STΛRJUPI 公开的双参考图云城动作 RPG 成片与完整 30 秒时间轴 prompt（`creator-reported`）。
- [Summer-rain creator case — CR-72](./cases/creator-reported-x-2026-08-05-summer-rain-memory.md): CREATOR'ZZ 公开的雨后夏日 POV 成片与完整日文 prompt，prompt 中直接标明 Seedance 2.5（`creator-reported`）。

目前共 **81 个**带可播放视频链接的案例；其中 **79 个**公开完整 prompt，**2 个**仅公开部分 prompt（CR-64、CR-68），覆盖：

- 30 秒叙事、一镜到底与多轮延长
- 多图/视频/音频参考与多人群像
- 白模预演、绿幕重渲染、时间段运镜编辑
- 电商产品替换、广告、第一人称 Vlog、教育与工业仿真

## Evidence levels

| Level | Meaning |
|---|---|
| `official` | Prompt 与效果视频均来自模型发布者的公开页面。 |
| `creator-reported` | 发布者声称为实测配方并公开了结果，但尚无独立验证。 |
| `reproduction` | 社区成员依据公开参考自行复现；必须标明运行日期、平台与设置。 |

## How to use a case

1. 在案例表点击“播放”观看结果。
2. 复制 prompt；将 `@图片`、`@视频`、`@白模` 占位符替换为你自有且有权使用的参考素材。
3. 记录模型入口、时长、比例、参考素材角色和生成日期。不要将一次输出当作稳定保证。

## Curation rules

- 仅收录有公开来源、完整 prompt 和可访问效果视频的条目。
- 只保存链接与文本说明，不上传或镜像第三方视频文件。
- 视频、人物、商标及参考资产的权利归各自权利人；使用前请确认授权。
- 链接失效时标记 `link-rot`，保留出处，避免悄然删除或改写来源。

## Contributing

欢迎提交案例。请先阅读 [贡献规范](./CONTRIBUTING.md)，并确保你的 PR 包含原始出处、视频链接、完整 prompt、证据等级与最少必要的参考素材说明。

## Sources

- [ByteDance Seed: Seedance 2.5 official release](https://seed.bytedance.com/zh/blog/%E4%B8%80%E9%95%9C%E6%88%90%E7%89%87-%E9%9A%8F%E5%BF%83%E5%8F%82%E8%80%83-seedance-2-5-%E6%AD%A3%E5%BC%8F%E5%8F%91%E5%B8%83)
- [AI Seedance 2.5 Showcase](https://aiseedance25.ai/showcase)

This repository is an independent community collection and is not affiliated with ByteDance.
