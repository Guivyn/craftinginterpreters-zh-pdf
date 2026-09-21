# Crafting Interpreters 中文版 PDF 构建报告

- Status: **PASS**
- Critical issues: **0**
- Source repository commit: `0ed158ed4307f28a8e2feceee05e27cb1713969c`
- Generated at (UTC): `2026-09-21T07:12:04.650611+00:00`
- Chapter entries: `36` (book.json order)
- Final PDF pages: `693`
- Final PDF size: `21.55 MB`

## Pipeline

- Markdown renderer: Mistune 3 per chapter with raw HTML, tables, footnotes, strikethrough, superscript/subscript
- PDF renderer: Playwright CDP with system Chrome/Edge, A4, print backgrounds
- PDF postprocessor: PyMuPDF for Chinese header/footer, metadata, internal Outline/bookmarks

## Publication processing

- Deleted English natural-language nodes: `4082`
- Retained Chinese/body nodes: `6930`
- Local image assets copied and rewritten: `164`
- External image assets downloaded: `1`
- Chapter-local footnote containers: `30`
- Internal links rewritten: `3`; unresolved: `0`
- Heading Registry entries: `468`
- TOC entries: `190`; bookmark registry entries: `190`
- Source Markdown modifications: `content/*.md was not modified`

## QA

- Chapter completeness: `PASS`
- Chinese text and landmarks: `PASS`
- Chinese font/rendering: `PASS`
- Local images: `PASS`
- Java/C/Lox code: `PASS`
- Internal HTML links: `PASS`
- PDF annotations: `PASS`
- Table of contents: `PASS`
- PDF Bookmark: `PASS`
- Abnormal blank pages: `PASS`

## Required landmarks

- Part I: `8`
- Chapter 1: `10`
- Part II: `44`
- Chapter 4: `46`
- Part III: `262`
- Chapter 14: `264`
- Chapter 30: `656`
- Afterword: `680`
- Appendix I: `681`
- Appendix II: `684`

## Metrics

```json
{
  "entries": 36,
  "registry_entries": 468,
  "toc_entries": 190,
  "bookmark_registry_entries": 190,
  "local_images": 164,
  "external_images": 1,
  "html_code_blocks": 1516,
  "footnote_chapters": 30,
  "deleted_english_nodes": 4082,
  "retained_chinese_nodes": 6930,
  "internal_links": 3,
  "unresolved_links": 0,
  "pages": 693,
  "bytes": 22594980,
  "mb": 21.55,
  "Part I": 8,
  "Chapter 1": 10,
  "Part II": 44,
  "Chapter 4": 46,
  "Part III": 262,
  "Chapter 14": 264,
  "Chapter 30": 656,
  "Afterword": 680,
  "Appendix I": 681,
  "Appendix II": 684,
  "blank_pages": [],
  "body_only_pages": [],
  "pdf_footnote_syntax_pages": [],
  "pdf_structural_syntax_pages": [],
  "pdf_links": 1166,
  "internal_pdf_links": 1009,
  "external_pdf_links": 157,
  "local_pdf_links": 0,
  "launch_actions": 0,
  "outline_entries": 190
}
```

## Remaining issues

- None
