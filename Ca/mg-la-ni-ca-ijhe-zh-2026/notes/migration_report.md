# Word → IJHE 中文 LaTeX 迁移记录

- 来源正文：`[local source path omitted]`，106 段、9 个表格。
- 来源插图：`[local source path omitted]`，8 个嵌入图像。
- 目标：本地 Elsevier `elsarticle` IJHE 迁移框架；XeLaTeX 编译，保持中文。
- 已转换：标题、中文摘要和关键词、章节正文、4 个独立公式、9 个可编辑表格、8 幅图和 19 条原有参考文献。
- 图号处理：插图文档标签为图 1、2、4–9，正文引用图 1–8。LaTeX 按正文顺序设置为图 1–8，源图像顺序不变。
- 原 Word 文件没有修改。图 1 由原 TIFF 无损转为 PNG 供 XeLaTeX 使用，其余图像按原格式导出。
- 作者、单位、通信邮箱、CRediT、利益冲突、数据可用性、基金与致谢保持待补充。
- 模板状态：本地 `elsarticle` 迁移框架并非 IJHE 专属官方类；正式投稿前须核对当期要求，且需要英文稿。
- 验证：`./paper build mg-la-ni-ca-ijhe-zh-2026` 成功；20 页 PDF；图 1–8、表 1–9、参考文献均在 PDF 中；无未解析引用、缺字或 overfull 警告。

- 2026-09-26 更新：图 1 替换为 `Ca_SEM_collage_square_no_namebar.tif` 的无损 PNG 导出版，保留原始 TIF 为 `project/figures/figure-01-source.tif`；新增四成分 BSE 组织分析，并在第二相判定和 Ca 细化机制处引用 ref4、ref6、ref7、ref12、ref15。
