# mg-la-ni-cjrm-2026

默认编辑入口：`main.tex`（指向 `project/main.tex`）。编译根目录：`project/`。
引擎：xelatex；参考文献：bibtex。
PDF：`build/main.pdf`；输出及同步文件集中在 `build/`。

从工作区执行 `./paper build mg-la-ni-cjrm-2026`；备选入口相对 `project/` 传入。
主文件位于 project 顶层时也可直接编辑；嵌套工程请从稳定 main.tex 入口打开。
元信息以根目录 papers/papers.yaml 为准。新版本来源：template cjrm-word-year-unverified。

## 本次迁移

- 正文来源：`notes/source-docx/Ni添加小论文初稿_修改1和3.docx`
- 插图来源：`raw_figure_ppt/source-docx/Ni添加论文插图_修改前备份.docx`
- LaTeX 正文：`project/main.tex`
- 参考文献：`project/bib/references.bib`
- 投稿图片：`project/figures/figure-01.png` 至 `figure-09.png`
- 迁移检查：`notes/migration_report.md`

Word 原件副本设为只读；正文和插图源文件的内容权威性仍由其各自原始文件承担。LaTeX 迁移保留原稿研究内容，只增加排版、公式、引用和图表交叉引用结构。

当前需补充作者、单位、中图分类号、英文题目、800--1000 词英文长摘要、中英文作者信息、基金和作者简介。9 幅图和4张表的英文题名已于2026-09-10补齐。完成其余信息后运行：

```bash
./paper build mg-la-ni-cjrm-2026
./paper preview mg-la-ni-cjrm-2026
```
