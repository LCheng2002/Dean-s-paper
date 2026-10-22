# mg-la-ni-ijhe-2026

This is an independent English migration for the *International Journal of Hydrogen Energy* (IJHE). The Chinese version `mg-la-ni-cjrm-2026` remains unchanged.

- Default editor entry: `main.tex` -> `project/main.tex`
- Compilation root: `project/`
- Engine: pdfLaTeX
- Bibliography: BibTeX with `elsarticle-num`
- PDF: `build/main.pdf`
- Template: `ijhe-elsarticle-year-unverified`
- Source manuscript copy: `notes/source-docx/Ni添加小论文初稿_修改1和3.docx`
- Source figure document copy: `raw_figure_ppt/source-docx/Ni添加论文插图_修改前备份.docx`
- Submission companions: `project/highlights.tex` and `project/graphical-abstract.tex`

Build from the workspace root:

```bash
./paper build mg-la-ni-ijhe-2026
./paper preview mg-la-ni-ijhe-2026 --viewer none
```

Before submission, complete the author names, affiliations, corresponding-author email, CRediT roles, competing-interest statement, data availability, funding and acknowledgements. Review the English translation against the Chinese source. Recheck the current IJHE Guide for Authors for article limits, highlights, graphical abstract, declarations, reference style, blinded-review rules and figure specifications.

The local workspace intentionally keeps figures and the bibliography in subfolders. When Editorial Manager requests LaTeX sources, create a separate flattened submission copy and compile that copy before upload, because Elsevier states that its submission system does not process subfolders reliably.
