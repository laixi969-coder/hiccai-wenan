# hiccai-wenan (v5.1.0)

商业文案与社交货币品牌创意 Agent Skill（v5.1.0）。适用于 Antigravity / Gemini Skills、Claude Code、Codex 等可读取 `SKILL.md` 的助手。

v5.1.0 深度融合 [hiccai-baokuan](https://github.com/laixi969-coder/hiccai-baokuan) 的 **「渐进式披露模块化架构 + 五阶段工作流 + 五维 10 分制红队重写」** 与原版 `hiccai-wenan` 的 **「事实与行动收口硬边界 + 社交货币引擎」**，并确立 **「默认静默五阶段、直接交付 2.0 终稿、零废话」** 的实战体验。

## 核心亮点

- **默认直接给结果，零废话**：只要需求里已明确品牌/品类/对象，策略拆解、三方向优选、社交货币试飞与五维红队重写全部在**内部静默完成**，直接输出可直接上版/发布的 2.0 成稿（未知硬事实标 `[待补]`，不擅自编造）；仅在完全不知卖什么或用户明确要“选方向/看全案扩散包”时才展开过程。
- **第一优先级「社交货币引擎」**：内置五大制造公式（关系嘴替 / 互损接话暗号 / 态度名片 / 实用人情 / 同行暗语）与「双人对话试飞测试」（谁拍给谁、对方回哪句、拿掉产品特点是否立刻失效、删掉转发指令是否仍值得发）。
- **1 主控 + 5 按需加载载体规范**：创作前只读对应 1 个规范，杜绝多载体文风串味。

## 模块架构

| 文件 | 定位 | 核心内容 |
| :--- | :--- | :--- |
| `SKILL.md` | 主控路由与核心引擎 | 默认直出结果机制、社交货币引擎（五大公式 + 双人试飞）、内部静默五阶段、硬约束 + 五维 10 分制红队重写、全局反 AI 味与合规红线 |
| `references/01-brand-poster-outdoor.md` | 品牌 / 海报 / 户外 / 高端 | 广告语与系列平面、按投放位置分行上版、图文分工、社交货币落地、高端/奢侈品/地产边界、Few-Shot 与红队清单 |
| `references/02-social-and-content.md` | 小红书 / 公众号 / 朋友圈 | 停留/转发/收藏/关注动作拆解、小红书首图与图文节奏、公众号社交体面爆文、双人试飞与热点核查 |
| `references/03-sales-and-conversion.md` | 卖货 / 详情页 / 招商 / 收口 | 购买阶段与 6 大障碍、五段转化骨架、主图详情逐屏、跨位置行动收口、招商同行暗语与合伙人转发理由、咨询留资与客户案例 |
| `references/04-video-tvc-campaign.md` | TVC / 品牌大片 / 短视频 / 声音 | 文化张力、去 Logo 不可替代铁律、视听双锤、黄金 3 秒与 5 秒节奏、时长可执行与纯听觉声音广告 |
| `references/05-creative-review.md` | 高创意标准 / 冲奖与反事实审查 | Cannes Lions & D&AD 维度参考、一句话命题检验、换品牌/去解释/换媒介三项反事实测试、原创与实效分离 |

## 安装

```bash
# Antigravity / Gemini Skills
git clone https://github.com/laixi969-coder/hiccai-wenan ~/.gemini/config/skills/hiccai-wenan

# Claude Code
git clone https://github.com/laixi969-coder/hiccai-wenan ~/.claude/skills/hiccai-wenan

# Codex
git clone https://github.com/laixi969-coder/hiccai-wenan ~/.codex/skills/hiccai-wenan
```

已有版本执行 `git pull` 即可更新。

## 验证

[40 个行为评估场景](test-prompts.json) 完整保留原有 35 题并覆盖 v5.1 专项验证：
- 1–35 题：覆盖品牌、豪宅边界、促销、高端卖货、B2B、短视频、信息不足、局部改写、原创腕表、奖项概念、跨位置上版、图文分工、详情分屏、嘴替原话、社媒传播、咨询边界、热点核查、社交货币与商业行动收口。
- 36–40 题：覆盖 v5.1 默认直出结果零废话（有品牌直接交付、不卡 Stage 0）、C 端与 B 端招商社交货币（双人对话试飞 + 产品绑定）、显式要求时才展开多方向/全案扩散包，以及真·信息真空才简短追问。

## License

Private use.
