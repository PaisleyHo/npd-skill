# npd-skill

A reusable skill template for simulating an NPD-flavored interpersonal style with safety boundaries, memory layers, and correction workflows.

For Chinese documentation, see [SKILL.zh-CN.md](SKILL.zh-CN.md).

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
