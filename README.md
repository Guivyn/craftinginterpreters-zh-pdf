<p align="center">
  <img src="./assets/readme/hero.svg" width="100%" alt="Crafting Interpreters 中文版 PDF：从扫描、解析到字节码虚拟机的 693 页中文排版整理版">
</p>

<p align="center">
  <a href="./Crafting_Interpreters_中文版.pdf">下载 PDF</a>
  ·
  <a href="https://readonly.link/books/https://raw.githubusercontent.com/GuoYaxiang/craftinginterpreters_zh/main/book.json">在线阅读中文翻译</a>
  ·
  <a href="https://github.com/GuoYaxiang/craftinginterpreters_zh">查看原翻译仓库</a>
  ·
  <a href="https://craftinginterpreters.com/">阅读英文原书</a>
</p>

# 手撸解释器教程（Crafting Interpreters 中文版 PDF）

> 一个基于 [GuoYaxiang/craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh) 中文翻译内容，由自动化排版流程生成的 PDF 阅读版。

## 📖 项目简介

本项目将原翻译仓库公开的 Markdown 内容重新整理，构建为一份适合长期阅读的中文 PDF 电子书。原仓库以 Markdown 源文件和在线阅读为主；本仓库提供独立的 PDF 发行文件，方便下载、保存、检索和打印。

我们的目标很简单：把分散的章节整理成一本完整、可搜索、可跳转的中文技术书，让读者把更多注意力放在代码和概念本身，而不是排版和跳转上。

## 📚 关于本书

《Crafting Interpreters》由 Bob Nystrom 编写，是一本从零实现解释器的技术书。全书从一门小型语言 Lox 开始，带着读者逐步实现两种不同路线的解释器：

1. 树遍历解释器 `jlox`
2. 字节码虚拟机解释器 `clox`

书中循序讲解：

- 词法分析与扫描器
- 语法分析、递归下降解析与 AST
- 表达式求值、运行时环境与状态
- 函数、闭包、类与继承
- 字节码、编译器与虚拟机
- 垃圾回收与性能优化

它不是只讲概念，也不是只堆代码。每一章都在前一章的基础上向前走，让抽象的语言机制逐渐变成可以运行的程序。

## ✨ PDF 版本特点

### 中文纯净阅读

- 以中文正文为主，不插入英文原文对照段落
- 保留代码、技术名称和必要的英文标识
- 不为了中文化而改动代码语义

例如，下面这些内容会原样保留：

```java
class Interpreter {
}
```

以及：

```text
AST
JVM
GC
Lox
Parser
Scanner
```

### 📑 完整章节结构

完整覆盖：

- 第一部分：欢迎与解释器基础
- 第二部分：树遍历解释器
- 第三部分：字节码虚拟机
- 第 1 章至第 30 章
- 后记
- 附录 I：Lox Grammar
- 附录 II：Generated Syntax Tree Classes

### 🔗 PDF 导航优化

PDF 内包含：

- 可点击目录
- PDF 书签
- 章节跳转
- 内部引用跳转
- 脚注跳转

适合电脑、平板以及其他支持 PDF 的阅读设备。

### 🎨 排版整理

针对技术书阅读场景进行了统一处理：

- A4 页面与中文正文排版
- 代码块与图片布局优化
- 章节分页与 Part 独立页面
- 目录、脚注和页面结构整理
- 生成 693 页完整 PDF，并完成基础结构检查

## 📥 下载

当前正式版本可以直接下载仓库根目录中的：

**[Crafting_Interpreters_中文版.pdf](./Crafting_Interpreters_中文版.pdf)**

文件大小约 21.55 MB，共 693 页。对应的 GitHub Release：[v1.0.1](https://github.com/Guivyn/craftinginterpreters-zh-pdf/releases/tag/v1.0.1)。

## 📊 文件信息

| 项目信息 | 内容 |
| --- | --- |
| 格式 | PDF |
| 语言 | 中文 |
| 页数 | 693 页 |
| 内容来源 | [craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh) |
| 构建方式 | Markdown → HTML/CSS → Chromium PDF → 目录与书签后处理 |
| 阅读方向 | 中文技术阅读 |

## 🛠️ 构建流程摘要

```text
公开中文 Markdown
        ↓
章节解析与内容整理
        ↓
HTML / CSS 排版
        ↓
Chromium 生成 PDF
        ↓
目录、书签与内部链接后处理
        ↓
最终 PDF
```

当前仓库以发布阅读版为主，提供最终 PDF 和阅读说明，不包含原翻译仓库的 Markdown 源文件与完整构建脚本。因此，上面是构建过程的摘要，方便读者理解产物如何生成；仅克隆本仓库并不能直接一键复现 PDF。

## ⚠️ 声明

本项目：

- 不是 Bob Nystrom 的官方 PDF
- 不是原作者的官方发布版本
- 不是原中文翻译项目的官方发布渠道

本项目仅基于公开中文内容进行自动化整理、排版和 PDF 构建，方便学习者阅读，不替代原书或原翻译项目。

## 📜 版权与许可

原书内容版权归 Bob Nystrom 及相关权利人所有，中文翻译内容及原始项目贡献归原翻译仓库作者与贡献者所有。本仓库不主张拥有原书或原翻译内容的版权。

本整合版 PDF 的自动化构建脚本、样式与整合发布部分基于 GPL-3 许可。原翻译仓库附有 [MIT License](https://github.com/GuoYaxiang/craftinginterpreters_zh/blob/main/LICENSE)。转载或再分发本 PDF 时，请保留原仓库出处，并同时遵守原书版权要求及适用的许可证条款。

原项目：[GuoYaxiang/craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh) · 原书：[Crafting Interpreters](https://craftinginterpreters.com/)

## 🙏 致谢

感谢：

- Bob Nystrom 编写《Crafting Interpreters》
- GuoYaxiang 及所有贡献者完成中文翻译与维护
- [xieyuheng](https://github.com/xieyuheng) 提供在线阅读支持
- 所有愿意分享知识、维护开源项目的人

## ⭐ 如果这份 PDF 对你的学习有帮助

欢迎：

- 给项目点一个 Star
- 提交排版问题
- 提交构建改进建议

如果是翻译内容问题，建议直接回到[原翻译仓库](https://github.com/GuoYaxiang/craftinginterpreters_zh)反馈；如果是 PDF 排版或导航问题，欢迎在本仓库提出 Issue。

希望这份整理版，能让更多中文读者更轻松地走进解释器的世界：

> 从一枚 token 开始，亲手走到一台真正会运行的虚拟机。

<p align="center">
  <a href="https://github.com/openai/codex">
    <img src="./assets/readme/readme-made-with.svg" width="100%" alt="README made with Codex：项目原生的编辑式技术排版">
  </a>
</p>
