# 稀有金属模板

本目录保存用户提供的《稀有金属》Word 模板原件，并提供本地 LaTeX 迁移入口。

- `original/`：未经修改的期刊 Word 原件，唯一权威源
- `SOURCE.md`：来源、年份核验状态和文件指纹
- `artifact.md`：从完整模板提炼的版式与字段契约
- `latex-migration/project/`：非官方 LaTeX 适配层，可复制到新的投稿版本

模板标识：`cjrm-word-year-unverified`。年份未核实是有意保留的状态；文件内部示例为 2019 年，最后保存于 2021 年，不能据此标注为 2026 年模板。

官网依据为[《稀有金属》投稿指南](https://zxjs.cbpt.cnki.net/portal/journal/portal/client/news/zxjs_0a96be87-490b-49ff-90aa-bee7b5d1b2cc)，2026-09-07 已核对栏目顺序、摘要长度、关键词、标题层级、图表和参考文献要求。官网链接的模板下载会进入验证码页，因此原件是否与官网当前下载文件逐字节一致仍待人工核验。

从工作区建立独立投稿版本：

```bash
./paper templates
./paper new mg-la-ni mg-la-ni-cjrm-2026 --template cjrm-word-year-unverified
./paper build mg-la-ni-cjrm-2026
```

新版本会复制 LaTeX 迁移工程，不会链接回模板或覆盖其他投稿版本。建立后先把 `papers/papers.yaml` 中题目、年份和状态改为实际信息，再迁移正文。
