# Drama Skills · short-drama-review

> **[short-drama-review](https://github.com/simlpandordinary/short-drama-review)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/zenstory-ai/drama-skills> |
| 上游路径 | `skills/short-drama-review` |
| 上游协议 | MIT |
| 上游 Star | 3.7k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

审查短剧项目中的原著分析、故事、剧本、视觉设定、图片提示词、分镜、冻结关键帧、视频提示词和已有媒体。用户提出“审稿/检查剧本”“检查资产或连续性”“检查图片/视频提示词”“检查原著分析”“审查模板感”“根据生产观察做项目校准”时使用；只写审查问题、结论和修订要求，不代替负责人修改来源文件。

## 目录结构

```
['SKILL.md', 'agents/openai.yaml', 'references/anti-template-repair.md', 'references/generated-media.md', 'references/production-quality-gates.md', 'references/project-calibration.md', 'references/review-method.md', 'references/rubric-assets-prompts.md', 'references/rubric-source-analysis.md', 'references/rubric-story-script.md', 'references/rubric-visual-motion.md', 'references/stage-contract.md', 'LICENSE', 'README.upstream.md']
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原文。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/short-drama-review/`：

```bash
git clone https://github.com/simlpandordinary/short-drama-review.git ~/.workbuddy/skills/short-drama-review
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/short-drama-review> 装成 Skill」。

安装后用自然语言触发，例如「Drama Skills · short-drama-review」「用 short-drama-review 帮我处理这个任务」。

本仓库仅含 Drama Skills 技能包中的 `short-drama` 家族技能之一，其余 10 个技能各自独立成仓。

## 版权

原始作者与版权归上游仓库 `zenstory-ai/drama-skills` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
