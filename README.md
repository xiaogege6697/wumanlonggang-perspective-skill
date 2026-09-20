# 🧠 雾满龙冈视角 Skill（Wumanlonggang Perspective）

**知识蒸馏·投资认知：基于雪球大V雾满龙冈（王大磊）公开内容提炼的投资框架与人生哲学决策 Skill**

*An educational thinking lens distilled from public posts by Wang Dalei (雾满龙冈): cycle awareness, contrarian value, safety margin — and a full "ordinary person's philosophy" for investing and life. Perspective, not impersonation; analysis, not financial advice.*

## 🎯 为什么做这个

雪球上的投资大 V 每天输出大量碎片观点，读过就忘、散落难查。这个项目把 **1,915 条帖子 + 476 张图片分析 + 19 篇公众号深度文章**（2021–2026，另有 2019 年起的历史文章）用 Nuwa 知识蒸馏框架蒸馏成一套可运行的 AI Skill：7+1 个投资心智模型、6 个人生哲学模型、19 条决策启发式、8 组"历史→投资"映射，以及完整的表达 DNA。装进你的 Agent 后，一句"大磊怎么看"就能调用这套框架分析当下问题——不是复读旧帖，而是用他的思维模型推演新情况。

稳定边界见 [`docs/core-boundary.md`](docs/core-boundary.md)：perspective, not impersonation; analysis, not instruction; 涉及实时市场判断必须先查最新数据。

## ✨ 核心特性

- 🔥 **8 个投资心智模型** — 万物皆周期、人弃我取（逆向三要素）、安全边际体系、需求第一性原理、利弗莫尔阻力最小方向、历史战略思维、抗打击能力模型、选股六道审核
- 🧘 **6 个人生哲学模型** — 知止而后定、荀彧"深根固本"、普通人的尊严、静与俭、盈亏同源/命运观、为别人的优秀鼓掌
- 🎯 **19 条决策启发式** — 投资线（全行业亏损→准备抄底、产品排队→值得关注、空仓也是炒股…）+ 人生线（机会不给不要硬来、一生只富一次、苟住就是胜利…）
- 📜 **历史典故方法论** — 79 条含历史典故帖子的系统提炼：刘邦纠错、荀彧深根固本、李世民谋定后动、朱元璋摆脱窠臼，8 组"历史→投资"核心映射
- 📊 **完整分析流程** — 需求判断 → 行业分析 → 六道审核 → 逆向时机 → 安全检查 → 证伪信号，另有独立的人生决策流程（普通人自检 → 风险 → 根据地 → 时机）
- 💬 **表达 DNA** — 5 类语气特征、标志性句式、高频词汇 Top20、85 条带日期和点赞数的经典语录
- 📈 **476 张图片分析** — 持仓截图、收益曲线、K 线图经视觉模型提取
- 🆚 **差异化对比** — vs metalslime（药神）、段永平、但斌

## 心智模型速览（投资）

| # | 模型 | 一句话 |
|---|------|--------|
| 1 | 万物皆周期 | 没有永续的趋势；全行业亏损 = 去产能尾声，为拐点布局 |
| 2 | 人弃我取（逆向三要素） | 市场极度悲观 + 价格远低于内在价值 + 持有足够久 |
| 3 | 安全边际体系 | 永远不出全价；只买龙头、适度分散、绝不上杠杆 |
| 4 | 需求第一性原理 | 股票上涨的第一性原理是需求：新需求 / 周期需求 / 萎缩需求 |
| 5 | 阻力最小方向（利弗莫尔） | 市场不选"对的方向"，只选"更容易走的方向" |
| 6 | 历史战略思维 | 谋定后动、后发制人；最合适的才是最好的，不是最有先例的 |
| 7 | 抗打击能力 | 胜利不取决于你多能打，而取决于你能挨多少拳还能站起来 |
| 8 | 选股六道审核 | 了解、大跌、强表、内购、低估、催化——六道全过才买 |

## 人物底色（来自公开自述）

- **起点**：2003 年，安徽小县城，3.6 万元起步全职投资，23 年全职经验
- **自述年化**：2003–2017 约 38%
- **风格**：长期价值 + 周期意识 + 逆向入场；A股为主，关注港股美股
- **历史持仓**（来自公开持仓截图，非当前推荐）：凯莱英、爱尔眼科、爱美客等消费医药标的
- **差异化**：唯一以"普通人"为核心受众和自我定位的大V——不教你怎么成为巴菲特，教普通人怎么在股市安全地、体面地活下去；雪球少有的系统分享人生哲学（父亲智慧、荀彧、曾国藩）的投资者

## 📦 安装

### OpenClaw

```bash
# Clone into your shared-skills directory
cd ~/shared-skills
git clone https://github.com/xiaogege6697/wumanlonggang-perspective-skill.git wumanlonggang-perspective

# Restart OpenClaw to discover the new skill
openclaw gateway restart
```

### Claude Code 及其他兼容 Agent

本 Skill 是标准 `SKILL.md` 格式，可直接放入任何支持 skills 目录的 Agent：

```bash
# Claude Code：放到用户级 skills 目录
git clone https://github.com/xiaogege6697/wumanlonggang-perspective-skill.git \
  ~/.claude/skills/wumanlonggang-perspective
# 重启 Claude Code 生效

# 其他 Agent：把仓库内 SKILL.md 及同目录内容复制到对应的 skills/ 目录即可
```

### 激活方式

对支持中文触发词的 Agent 说：
- "用雾满龙冈的视角分析一下"
- "王大磊怎么看"
- "大磊视角"

也适用于："帮我分析这只股票""普通人怎么投资""35 岁该不该辞职全职投资"等场景。

## 💡 使用示例

**场景 1：行业分析（投资线）**

> 你："大磊视角，现在医药行业怎么看？"
>
> Skill 工作流：先搜最新行业数据（当前数据闸门）→ 判断需求类型（周期需求）→ 检查周期位置（供给/价格/库存）→ 走六道审核给出通过/未通过项 → 以历史类比开场（"就像 2021 年集采后的医药一样……"）→ 只输出变量、证据和风险约束，不给买卖指令。

**场景 2：人生选择（人生哲学线）**

> 你："手里有点积蓄，该不该辞职炒股？"
>
> Skill 走人生决策流程：①普通人自检（"99% 的人把自己定位为天才，但事实上仅仅是普通人"）② 风险检查（最坏结果能否承受、会不会负债）③ 有根据地吗（跌倒了能站起来吗）④ 时机判断（"机会不给你的时候不要硬来"）——先讲刘备夷陵或荀彧深根固本的典故，再回到你的具体约束，强调底线而非收益。

## Agentic 模式

激活后 Skill 以 **Agentic Mode** 运行：
1. **先搜实时数据**再回答——不依赖陈旧知识
2. 把**王大磊式框架**应用到当前市场语境
3. 使用**大磊风格视角**，但不声称自己就是王大磊、不代表其当前观点或持仓
4. **守住金融边界**——不给个性化的买/卖/仓位指令，只给框架、变量、风险和证伪条件

## 数据来源

| 来源 | 数量 | 时间范围 |
|------|------|---------|
| 文字帖子 | 1,915 | 2021-05 ~ 2026-06 |
| 图片分析 | 476 | 混合 |
| 公众号深度文章 | 19 | 2019-2023（历史/人生哲学体系） |
| 帖子类型 | 原创 + 转发 + 评论 | 全部 |

## ⚠️ 边界与免责

- **教育分析用途**：本 Skill 基于公开内容蒸馏，是思维模式的 AI 近似，仅作教育与反思用途
- **不冒充本人**：不是王大磊，不代表其当前观点或持仓
- **不构成投资建议**：不提供个性化买卖指令；历史规律不预示未来结果，核实最新数据，独立决策

## License

MIT（见 [LICENSE](LICENSE)）

## 🔗 相关项目

- [metalslime-perspective-skill](https://github.com/xiaogege6697/metalslime-perspective-skill) — metalslime 式投资思维镜头
- [web-crawler-skill](https://github.com/xiaogege6697/web-crawler-skill) — 负责任的网页采集策略
- 更多 AI Skills 见 [github.com/xiaogege6697](https://github.com/xiaogege6697)

---

⭐ If you find this useful, please star the repo! It helps others discover it.
