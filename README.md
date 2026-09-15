<p align="center">
  <img src="./assets/readme/hero.svg" width="100%" alt="Crafting Interpreters 纯中文版 PDF：从扫描、解析到字节码虚拟机的 650 页中文排版整理版">
</p>

<p align="center">
  <a href="./Crafting_Interpreters_纯中文版.pdf">下载 PDF</a>
  ·
  <a href="https://github.com/GuoYaxiang/craftinginterpreters_zh">查看原中文翻译</a>
  ·
  <a href="https://craftinginterpreters.com/">阅读英文原书</a>
</p>

# Crafting Interpreters 纯中文版 PDF

一份面向离线阅读与打印的中文 PDF 排版整理版，覆盖《Crafting Interpreters》的第 1–30 章及两个附录。

## 先看这里

- [下载最终 PDF](./Crafting_Interpreters_纯中文版.pdf) — 650 页，适合保存、检索和打印
- 从 Lox 语言出发，沿着扫描、解析、求值一路走到字节码与虚拟机
- 正文、代码块、脚注、目录和 PDF Bookmark 已做统一排版与检查

## 这份 PDF 适合谁

如果你想系统理解解释器是如何从源代码一步步变成可运行程序，这份中文排版版可以作为阅读入口。它适合编程语言、编译原理和解释器实现的自学阅读，也适合在学习原书时作为中文对照。

## 内容路线

```text
Lox 语言
   │
   ├─ jlox：扫描器 → 表达式/语句 → 语法树解释器
   │
   └─ clox：字节码 → 编译器 → 虚拟机 → 优化
```

全书结构：

- 前言与解释器基础
- Tree-Walk Interpreter：第 1–13 章
- Bytecode Virtual Machine：第 14–30 章
- 附录 I：Lox Grammar
- 附录 II：Generated Syntax Tree Classes

## 来源与致敬

本项目援引并致敬 [GuoYaxiang/craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh) 中文翻译仓库。中文翻译、章节内容及原始项目贡献属于原仓库作者与贡献者；本仓库不替代、不冒充原项目，仅提供基于其公开内容整理生成的 PDF 发行文件。

原仓库页面列出 MIT License。使用、转载或再分发本 PDF 时，请保留原仓库出处，并遵守适用的许可证与版权要求。

相关项目：

- 中文翻译仓库：[GuoYaxiang/craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh)
- 英文原书：[Crafting Interpreters](https://craftinginterpreters.com/)

## 说明

本仓库只发布 PDF 与阅读所需的说明，不包含原翻译仓库的 Markdown 源文件，也不代表原仓库的官方发布渠道。

<p align="center">
  <a href="https://github.com/openai/codex">
    <img src="./assets/readme/readme-made-with.svg" width="100%" alt="README made with Codex：项目原生的编辑式技术排版">
  </a>
</p>

