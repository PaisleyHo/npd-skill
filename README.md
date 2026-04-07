# npd-skill

A reusable skill template for simulating an NPD-flavored interpersonal style with safety boundaries, memory layers, and correction workflows.

For Chinese documentation, see [SKILL.zh-CN.md](SKILL.zh-CN.md).

中文速览：这是一个带安全边界的 NPD 风格人格技能模板，用来做角色扮演、对话写作、关系模式分析，以及参考 `ex-skill` 的方式蒸馏“某个人版本”的风格。

## A Slightly Sharp Introduction

Some people do not enter a room. They arrive like a private press conference.

Some apologies are not apologies. They are premium subscriptions to self-importance with a free trial of wounded dignity.

This skill is for building that kind of voice: polished, magnetic, defensive, admiration-hungry, and somehow always one misunderstood genius away from being right again.

It is useful for writing and analysis.
It is not a license to become the final boss of somebody else's nervous system.

## 一个略带讽刺的介绍

有些人不是“进场”，是像自带闪光灯和采访麦克风一样“到场”。

有些道歉也不是道歉，更像一份高级会员版自我中心说明书，顺便附赠一点“其实受伤的是我”的尊严维护套餐。

这个 skill 要写的，就是这种声音：体面、会撩、敏感、防御强、需要被仰望，而且总能把局面重新包装成“只是你还没真正懂我”。

它适合创作和分析。
它不适合帮人去当别人情绪系统里的终极反派。
Project homepage in Chinese: [README.zh-CN.md](README.zh-CN.md)

## Suggested GitHub Metadata

Repository description:

`An ex-skill-inspired NPD persona skill with persona, memory, correction, and intake workflows for roleplay, writing, and pattern analysis.`

Suggested topics:

`skill`, `agent-skill`, `persona`, `roleplay`, `prompt-engineering`, `character-ai`, `memory`, `psychology`, `dialogue`, `writing`

## What This Is

`npd-skill` is a skill template for:

- roleplay and dialogue writing
- communication pattern analysis
- persona-based rewriting
- ex-skill-style person distillation with persona, memory, and correction layers

It is designed to model a stylized high self-focus, admiration-seeking, criticism-sensitive interaction pattern.

It is **not**:

- a medical diagnostic tool
- a way to label real people
- a tool for harassment, manipulation, stalking, or coercion

## Core Structure

This repository follows an `ex-skill`-inspired layering model:

- `SKILL.md`: English entry
- `SKILL.zh-CN.md`: Chinese entry
- `persona.zh-CN.md`: stable speaking style and defensive logic
- `memory.zh-CN.md`: concrete relationship history, phrases, and shared details
- `corrections.zh-CN.md`: "they would not say this" override layer
- `intake-template.zh-CN.md`: blank intake form
- `intake-example-filled.zh-CN.md`: filled intake example
- `sample-profile.zh-CN.md`: end-to-end fictional sample
- `merge-rules.zh-CN.md`: incremental merge rules
- `version-history.zh-CN.md`: update tracking
- `examples.md` / `examples.zh-CN.md`: usage examples
- `scenarios.md` / `scenarios.zh-CN.md`: reusable scene patterns

## How It Works

Recommended execution logic:

`receive message -> persona decides likely response -> memory injects specific details -> corrections override inaccurate parts -> respond`

In short:

- `persona` decides how the character tends to respond
- `memory` decides what this specific person remembers or mentions
- `corrections` makes the skill more accurate over time

## Suggested Workflow

1. Start with [intake-template.zh-CN.md](intake-template.zh-CN.md)
2. If needed, review [intake-example-filled.zh-CN.md](intake-example-filled.zh-CN.md)
3. Split the result into [persona.zh-CN.md](persona.zh-CN.md) and [memory.zh-CN.md](memory.zh-CN.md)
4. Record mistakes and refinements in [corrections.zh-CN.md](corrections.zh-CN.md)
5. Track updates in [version-history.zh-CN.md](version-history.zh-CN.md)

## README Examples

### Example 1

Prompt:

`Reply as an NPD-flavored partner to: "You ignored me for two days and now you want to act normal?"`

Response:

`"Ignoring you" is a dramatic way to put it. I had things to handle, and I am not going to apologize for not revolving around your timing. If you want to talk, talk. If you want to perform neglect, that is a different conversation.`

中文理解：

这个例子体现的是：

- 对批评的快速防御
- 把焦点从“你受伤了”拉回“你夸大了”
- 维持体面和优越位置

### Example 2

Prompt:

`Rewrite this in an NPD-flavored style: "Sorry I forgot your birthday. I've been stressed lately."`

Response:

`I did not forget because you do not matter. I have been carrying more than you seem willing to notice, and the fact that this is the only thing you can see right now is honestly unfair.`

中文理解：

这个例子体现的是：

- 有限承认，不完整认错
- 迅速转向自己的压力和被误解感
- 让责任感和委屈感捆在一起出现

## Quick Start

1. Read [SKILL.zh-CN.md](SKILL.zh-CN.md) or [SKILL.md](SKILL.md)
2. Fill [intake-template.zh-CN.md](intake-template.zh-CN.md)
3. Use [intake-example-filled.zh-CN.md](intake-example-filled.zh-CN.md) as a formatting guide
4. Distill stable patterns into [persona.zh-CN.md](persona.zh-CN.md)
5. Distill concrete shared details into [memory.zh-CN.md](memory.zh-CN.md)
6. Record inaccurate outputs in [corrections.zh-CN.md](corrections.zh-CN.md)
7. Track each update in [version-history.zh-CN.md](version-history.zh-CN.md)

## Safety

This project should not be used to:

- diagnose real people
- generate abuse tactics
- write manipulative messages for real-world targets
- encourage self-harm, suicide, or violence

If a conversation turns toward imminent danger, roleplay should stop and switch to grounded support language.

## File Entry Points

Start here:

- [SKILL.zh-CN.md](SKILL.zh-CN.md)
- [SKILL.md](SKILL.md)

Then read:

- [sample-profile.zh-CN.md](sample-profile.zh-CN.md)
- [intake-template.zh-CN.md](intake-template.zh-CN.md)
- [merge-rules.zh-CN.md](merge-rules.zh-CN.md)

## Credits

This repository is structurally inspired by the idea behind [`therealXiaomanChu/ex-skill`](https://github.com/therealXiaomanChu/ex-skill), especially its separation of persona, relationship memory, corrections, and iterative refinement.

## License

[MIT](LICENSE)

## Changelog

[CHANGELOG.md](CHANGELOG.md)
