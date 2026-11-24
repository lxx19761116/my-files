# 紫微斗数·命盘解读 Skill

**目录**：`ziwei-doushu-skill/skills/ziwei-doushu/SKILL.md`

把紫微斗数的排盘与解读整理成一套可复用的分析流程：先确认生辰与命盘，再逐宫解读，专业层与白话层双轨输出，全程不硬算、不预言、不制造恐惧。

覆盖：
- 生辰信息收集、时辰不确定时的定盘校准
- 十二宫、三方四正、十四主星、四化飞星的解读框架
- 命宫底色 / 事业 / 财运 / 感情 / 大限 / 流年 六段输出
- 术语白话翻译、质量门与明确边界

## 直接使用

将 `skills/ziwei-doushu/` 整个目录（含 `SKILL.md` 与 `references/`）放入兼容 Skills 的智能体环境，或把 `SKILL.md` 内容作为行为指令加载。**此仓库保存文件不等于自动在 ChatGPT / Codex / WorkBuddy 中启用**，需在使用环境中安装或加载；安装后建议用 `examples.md` 的样例做一次调用验证。

## 调用例子

- 帮我排一张紫微斗数命盘，1990 年农历八月初三午时，女。
- 我只记得是下午出生，时辰不准，还能看吗？
- 我这张盘事业和财运该怎么看？
- 夫妻宫有化忌，是不是感情一定不顺？

## 文件

| 文件 | 用途 |
|------|------|
| `skills/ziwei-doushu/SKILL.md` | 核心指令与输出协议 |
| `skills/ziwei-doushu/references/chart-basics.md` | 排盘要素、时辰索引、真太阳时、流派差异、常见错误 |
| `skills/ziwei-doushu/references/stars-reference.md` | 十四主星与常用辅煞星速查 |
| `skills/ziwei-doushu/references/palaces-guide.md` | 十二宫含义、三方四正、问事选宫 |
| `skills/ziwei-doushu/references/four-hua-guide.md` | 生年四化表、四化含义与解读误区 |
| `examples.md` | 示例对话 |
| `NOTICE.md` | 用途与身份声明 |
| `plugin.json` | 插件展示信息 |

## 排盘说明

本 Skill **不内置排盘算法**，不凭空推算星曜宫位。排盘应来自用户提供的命盘、或可靠的开源排盘工具（如 `SylarLong/iztro` 等）。缺失命盘时只给方法论框架，并明确说明局限。

## 边界

紫微斗数属传统术数，无科学实证支持。本 Skill 输出仅供文化了解与娱乐参考，不构成医疗、法律、投资、婚姻等任何决策依据。不预言死亡疾病，不制造恐惧，不引导付费改运、消灾或购买相关服务。

本项目与任何命理流派、机构或商业服务没有关联，不属于官方授权产品。
