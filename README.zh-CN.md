# book-context-map

[English README](./README.md)

`book-context-map` 是一个可复用的 skill，用来把一则信息较薄的书籍笔记，扩展成更有进入感和连接感的“上下文地图”。

它不以逐章摘要为目标，而是帮助你把一本书放回更大的知识网络里：作者是谁、它在回答什么问题、依赖什么框架、读之前最好知道什么、读完之后还能往哪里走，以及它和现有 Obsidian 库之间可以建立哪些连接。

## 这个 Skill 解决什么问题

把一本书加入个人知识库时，最常缺的往往不是“这本书讲了什么”，而是：

- 为什么这本书值得现在进入
- 它属于哪个问题域或主题网络
- 进入它之前需要哪些背景
- 读完之后应该接到哪里去

这个 skill 就是为这层“书籍上下文”而设计的。

它希望补出来的是一种：

- 比长摘要更快扫描的入口层
- 比一次性读书笔记更可复用的背景层
- 比孤立书卡更容易连接进知识网络的中间层

## 快速开始

1. 下载或复制 [SKILL.md](./SKILL.md)。
2. 在你的本地 skills 目录下新建一个 `book-context-map` 文件夹。
3. 把 `SKILL.md` 放进这个文件夹里。
4. 如有需要，重启你的助手客户端。
5. 在处理书籍笔记时显式调用这个 skill。

示例目录结构：

```text
.claude/
  skills/
    book-context-map/
      SKILL.md
```

## 怎么使用

当你想把一本书加入 vault，或者想补强一条已有的 book note 时，就可以调用这个 skill。

示例提示词：

```text
Use book-context-map to add this book to my vault: The Structure of Scientific Revolutions by Thomas Kuhn.
```

```text
Use book-context-map to enrich my existing note on Seeing Like a State.
Focus on author background, core question, framework, and further reading.
```

```text
Use book-context-map to create a lightweight reading context note for Debt: The First 5000 Years.
```

## 使用前后对比

没有这个 skill 时，一条书籍笔记很容易变成：

- 一段简短摘要
- 几条摘录
- 一些松散标签
- 没有明确阅读路径

有了这个 skill 之后，同一条笔记更可能补出：

- 为什么这本书值得进入
- 它在回答什么问题
- 进入之前需要哪些背景
- 读完之后接什么
- 它应该挂进哪个更大的主题网络

## 它会产出什么

这个 skill 默认会帮助生成一个结构化的“书籍上下文”区块，通常包括：

- 作者背景
- 写作背景与时代语境
- 这本书的核心问题
- 理论框架、方法框架或叙事框架
- 核心概念
- 适合的读者与使用场景
- 前置阅读
- 延伸阅读
- 对照阅读或批评视角
- 与 vault 内现有笔记的连接

## 最适合什么场景

这个 skill 特别适合：

- 非虚构类书籍
- 理论与思想类阅读
- 商业与方法类书籍
- 心理学、社会学
- 历史、传记、思想史
- 希望在 Obsidian 中建立长期知识网络的读者

它也可以用于小说或诗歌，但会把“框架”部分改写为更适合文学作品的维度，比如主题母题、叙事结构、文学传统、人物关系和时代语境。

## 它刻意避免什么

这个 skill 不希望把结果做成：

- 营销式夸赞
- 百科词条式作者介绍
- 只是重写目录的空泛摘要
- 在资料不足时假装确定的判断

## 输出风格

默认输出风格是：

- 清楚
- 克制
- 结构化
- 面向后续检索与复用

理想结果是让用户能快速知道：

- 这本书是谁写给谁的
- 它在回答什么问题
- 进入它之前需要哪些背景
- 读完以后适合往哪里延伸
- 它该如何挂进现有笔记网络

## 仓库结构

- [SKILL.md](./SKILL.md)：核心 skill 定义
- [README.md](./README.md)：英文说明
- [README.zh-CN.md](./README.zh-CN.md)：中文说明

## 适用用例

- 把新发现的一本书加入 Obsidian 库
- 给已有但过薄的书籍笔记补上下文
- 在正式开始阅读前先建导读层
- 把一本书挂进既有主题网络
- 生成前置阅读和延伸阅读路径

## 支持一下

如果这个 skill 对你的工作流有帮助，欢迎给这个仓库点一个 star。

也欢迎反馈、示例和改进建议。

## 许可证

MIT
