# npd-skill

一个受到 `ex-skill` 启发的 NPD 风格人格技能模板，支持人格层、记忆层、纠正层和录入工作流，适合角色扮演、对话写作、关系模式分析和人物蒸馏。

English version: [README.md](README.md)

## 这是什么

`npd-skill` 是一个可复用的技能模板，用来模拟一种：

- 高自我中心
- 强烈需要认可
- 对批评和忽视敏感
- 重视形象、地位和优越感

的人际互动风格。

它适合：

- 角色扮演
- 小说 / 剧本对话写作
- 文本改写
- 沟通模式分析
- 参考 `ex-skill` 的方式蒸馏某个具体人物

它不适合：

- 医学诊断
- 给现实中的人贴标签
- 生成骚扰、操控、PUA、跟踪或报复内容

## 项目特色

- 双语文档：英文入口 + 中文主工作流
- `persona / memory / corrections` 三层结构
- `intake -> merge -> version history` 的可维护工作流
- 既能做通用人格模板，也能做“某个人版本”的风格蒸馏
- 带示例、场景库、填写示范和虚构样例

## 核心结构

- [SKILL.md](SKILL.md)：英文入口
- [SKILL.zh-CN.md](SKILL.zh-CN.md)：中文入口
- [persona.zh-CN.md](persona.zh-CN.md)：稳定说话风格、优越感和防御逻辑
- [memory.zh-CN.md](memory.zh-CN.md)：共同经历、原话、地点、关系细节
- [corrections.zh-CN.md](corrections.zh-CN.md)：`ta 不会这么说` 的纠正层
- [intake-template.zh-CN.md](intake-template.zh-CN.md)：空白录入模板
- [intake-example-filled.zh-CN.md](intake-example-filled.zh-CN.md)：填好的 intake 示例
- [sample-profile.zh-CN.md](sample-profile.zh-CN.md)：完整虚构人物样例
- [merge-rules.zh-CN.md](merge-rules.zh-CN.md)：增量合并规则
- [version-history.zh-CN.md](version-history.zh-CN.md)：版本记录
- [examples.zh-CN.md](examples.zh-CN.md)：中文示例
- [scenarios.zh-CN.md](scenarios.zh-CN.md)：中文场景库

## 运行逻辑

推荐逻辑：

`收到消息 -> persona 判断这个人会怎么回 -> memory 注入具体细节 -> corrections 修正不像的地方 -> 输出`

简单说：

- `persona` 决定“像不像这种人”
- `memory` 决定“是不是这个具体的人”
- `corrections` 决定“会不会越用越准”

## 快速开始

1. 先看 [SKILL.zh-CN.md](SKILL.zh-CN.md)
2. 填 [intake-template.zh-CN.md](intake-template.zh-CN.md)
3. 参考 [intake-example-filled.zh-CN.md](intake-example-filled.zh-CN.md)
4. 把稳定模式拆进 [persona.zh-CN.md](persona.zh-CN.md)
5. 把具体原话和关系细节拆进 [memory.zh-CN.md](memory.zh-CN.md)
6. 把不准确的输出写进 [corrections.zh-CN.md](corrections.zh-CN.md)
7. 在 [version-history.zh-CN.md](version-history.zh-CN.md) 记录每次更新

## 如果你想做成“某一个具体的人”

推荐先准备这些材料：

- 聊天记录
- 常见口头禅
- 深夜对话
- 争吵记录
- 常见地点和共同经历
- 你对 ta 的主观概括

然后按这个顺序处理：

1. 先填 intake
2. 再拆 persona
3. 再补 memory
4. 最后用 corrections 持续修正

## 安全边界

本项目不应用于：

- 诊断现实中的人
- 操控或伤害现实对象
- 生成威胁、骚扰、报复和精神控制文本
- 鼓励自伤、自杀或暴力

如果对话进入现实危险场景，应该立即退出角色扮演，改用现实支持语言。

## 灵感来源

本项目的结构灵感来自 [`therealXiaomanChu/ex-skill`](https://github.com/therealXiaomanChu/ex-skill)，尤其是：

- 人格层
- 关系记忆层
- 纠正层
- 持续迭代与维护

## 许可证

[MIT](LICENSE)
