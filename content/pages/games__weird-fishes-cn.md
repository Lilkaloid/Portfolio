# 奇怪的鱼 — `/games/weird-fishes-cn`
Status: LIVE, in games grid

## Text
**H1:** 奇怪的鱼
类别：第一人称叙事步行模拟 / 实验性交互小说个人项目。**使用 UE5.6 制作。

《Weird Fishes》是一段可游玩的独白，由一系列用虚幻引擎 5 制作的实验性叙事关卡组成。它以"潜力"作为一种负担来进行心理探索，把"做游戏"——以及更广义的生活——理解为一连串不可逆的路径：我们从一个理想化、尚未成形的梦出发，最终走向一个完成了却并不完美的现实。

本项目起源于 USC 的 CTIN544 课程A project initiated in CTIN544 at USC.

Build下载 (itch.io施工中） → [link empty]

### 核心特色
1) 由旁白引导的第一人称心理探索：旁白用来建立游戏知音，表达意义与压力。是外部声音都同时也像一个焦虑的内心独白。
3) 机制克制，节奏清晰：极简玩法设计，把情绪弧线交给节奏、可读性与时机精准的旁白，从"掌控"走向"释然"。通过场景与POI设计引导、减少 UI。
2) 空间作为第二叙事者：关卡布局、视线引导、光照与声音会强化或反驳旁白，让"移动/探索"本身变成一种解读与判断。

### 设计思路
我把关卡当成叙事系统来搭：旁白是第一叙事者，空间是第二叙事者。在实现上，我重点在三件事上反复迭代：
- Level Flow & Readability：用动线、视线引导（sightlines）、构图和对比度做自然引导，让玩家在几乎不依赖 UI 的情况下知道"下一步该看哪、该往哪走"。
- Pacing & Emotional Beats：把体验拆成一段段短的叙事节拍（beats），每个区域都先抛出一个问题，再用一个小的"感知转折"（光照/尺度/声音/空间关系变化）来回应，形成清晰的 progression。
- Feedback through Iteration：通过测试去调整并设计反馈（声音确认、灯光回应、镜头/空间的微变化）回应玩家行为。

核心循环可以概括为：观察 → 靠近 → 解读 → 重新理解。

体验目标：
我从《Weird Fishes》想讲的核心出发："潜力"既是一种召唤，也是一种负担——你是谁、你可能成为谁之间的落差，会在行动里不断被放大。我希望把这个主题做成以玩家为核心的体验：让玩家通过移动、停顿、选择路线与观察方式，自己感受到"被拉向前/被拖住"的心理节奏。

解决方案
- 加"软目标"与锚点：每个区域设一个稳定的视觉母题 + 明确的交互可供性，让玩家有可追踪的目标线索。
- 更明确的起伏设计：每个 区域只强化一个变量（距离 / 可视性 / 声音清晰度 / 交互频率），避免体验强度起伏无规律。
- 更强的（小）反馈：当玩家做出"正确类型的观察/选择"时给予即的确认，增强反馈闭环。

设计风险
- 无明确目标时的可读性：玩家容易不确定目标与优先级。
- 低机制的张力维护：没有复杂系统时，方向感和紧张感更依赖节奏与空间组织。
- 象征表达的边界：太直白会失去余味，太含糊又会像"随便摆的意象"。

### CREDITS｜鸣谢
音乐：《Relíquia》（片段）— Rosalía
AI：用于 2D/3D 模型生成，以及 Blueprint 教程辅助
音效：部分音效来自 Freesound
资源：UE5 Nanite Foliage — Wheat Field
所有第三方作品的版权归原作者所有，此处仅用于非商业目的

## Flags
- [MISSING-LINK] Download link empty ("施工中").
- [TYPO?] Feature numbering out of order (1, 3, 2); "**使用" stray markdown; "建立游戏知音"; "是外部声音都同时"; "给予即的确认" — confirm intended wording.
- [INCONSISTENT] CN section order and content differ from EN (CN has 设计风险/体验目标; EN has Difficulties/Origin).
- Videos: same 4 as EN page (assumed; not separately verified).

## Visuals (1, in page order) — status: PENDING DOWNLOAD
1. `assets/games__weird-fishes/01_6725e279_微信图片_20260211001426.webp` — original name: 微信图片_20260211001426.png (same file as another page)
