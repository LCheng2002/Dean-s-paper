
## [2026-09-20 12:26 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: failed
- note: [local source path omitted]

## [2026-09-20 12:26 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-09-20 12:28 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: failed
- note: [local source path omitted]

## [2026-09-20 12:28 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-09-20 12:29 +0800] create-version
- object: mg-la-ni-ca-ijhe-zh-2026
- action: 新建独立 IJHE 中文 LaTeX 版本、注册元信息和相对软链接；从两份 Word 迁移正文、图表及文献。
- status: success
- note: 原 Word 未修改；图号按正文顺序归一为 1–8。

## [2026-09-20 12:29 +0800] build
- object: project/main.tex
- action: 使用 XeLaTeX 编译并检查 PDF 文本与页面预览。
- status: success
- note: build/main.pdf，20 页；图 1–8、表 1–9、参考文献齐全，无未解析引用、缺字或 overfull 警告。作者与投稿声明待补充。

## [2026-09-26 17:38 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-09-26 17:40 +0800] figure-and-text-update
- object: mg-la-ni-ca-ijhe-zh-2026 / 图1与显微组织分析
- action: 使用新四成分BSE拼图替换图1；新增α-Mg、Mg17La2、Mg2Ni及Ca细化组织分析；同步更新摘要、讨论和结论中的旧SEM范围表述。
- status: success
- note: 原始TIF保存在project/figures/figure-01-source.tif，XeLaTeX实际引用figure-01.png；引用沿用现有ref4、ref6、ref7、ref12、ref15。

## [2026-09-26 18:47 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-09-26 18:53 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-09-26 18:51 +0800] figure-and-text-update
- object: mg-la-ni-ca-ijhe-zh-2026 / XRD图1与物相组成分析
- action: 将用户提供的四成分XRD图及其PDF标准卡片峰位标注插入铸态组织分析之前，新增Mg、Mg$_{17}$La$_2$、Mg$_2$Ni及Mg$_2$Ca候选峰位的证据边界说明；原显微组织图顺延为图2，后续图号由LaTeX自动更新。
- status: success
- note: 原始TIF保存在project/figures/figure-01-xrd-source.tif，XeLaTeX实际引用figure-01-xrd.png；编译生成build/main.pdf（22页），图1页面渲染检查通过，未发现未解析引用或Overfull警告。

## [2026-09-26 18:55 +0800] consistency-update
- object: mg-la-ni-ca-ijhe-zh-2026 / 研究局限性与最终编译
- action: 将研究局限性中插入XRD前的旧表述更新为当前XRD峰位匹配、Mg$_2$Ca候选峰不确定及四组成分SEM覆盖范围；重新编译并复核图号与图1页面。
- status: success
- note: build/main.pdf，22页；图1为XRD，图2为BSE显微组织，未发现未解析引用或Overfull警告。

## [2026-10-14 19:24 +0800] kinetics-data-consistency-update
- object: Mg-8La-4Ni基体脱氢JMAK/Arrhenius参数
- action: 按已确认的96.8 kJ·mol⁻¹基准，统一0Ca样品的四温度JMAK参数为η=1.100、1.110、1.090、0.910及ln k=-4.185、-4.661、-5.355、-6.234；更新摘要、结果、表格、讨论、结论及动力学图源figure-05.png，并补充拟合区间、反应分数和时间单位。
- status: success
- note: 由四温度Arrhenius回归得Ea=96.778 kJ·mol⁻¹、R²=0.98995，分别四舍五入为96.8 kJ·mol⁻¹和0.98995；其他Ca含量样品参数及原始Word文档未改。

## [2026-10-14 19:24 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-10-14 19:25 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-10-14 19:28 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-10-14 19:28 +0800] restore-original-kinetics-figure
- object: Ca系列脱氢动力学图源figure-05.png
- action: 按用户要求，从原始插图Word文档恢复图源文件；保留96.8 kJ·mol⁻¹及对应文字、表格和JMAK参数修改，并重新编译。
- status: success
- note: 恢复图与Word内原图SHA-256一致；build/main.pdf编译成功。

## [2026-10-14 19:45 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: [local source path omitted]

## [2026-10-14 19:45 +0800] remove-first-principles-content
- object: mg-la-ni-ca-ijhe-zh-2026 / Ca微合金化稿件
- action: 删除第一性原理计算方法、结果、相关讨论与结论，清理摘要、关键词、引言、研究局限性中的计算表述，移除计算专属参考文献和图6–8素材；保留实验数据、JMAK参数及原始动力学图figure-05.png。
- status: success
- note: 当前登记稿LaTeX源码及编译PDF中未检出第一性原理计算术语或结果；未修改原始动力学图，旧的未登记Word源稿仍作为归档副本保留。

## [2026-10-14 19:45 +0800] build
- object: mg-la-ni-ca-ijhe-zh-2026
- action: [local source path omitted]
- status: success
- note: build/main.pdf，15页；引用和标签检查无未定义项。日志含已有字体、xeCJK、书签Unicode及Underfull hbox警告。
