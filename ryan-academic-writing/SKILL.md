---
name: academic-writing
description: Draft, revise, outline, or critique Chinese STEM academic writing, especially instrument science (仪器科学), optoelectronic engineering (光电工程), and computer science. Use for thesis proposals, doctoral proposal background sections, papers, and NSFC-style grant sections when the user asks to write or pressure-test 研究背景, 技术路线, 实验, 创新点, 立项依据, or 摘要. Do not use for humanities or social-science grants unless explicitly requested, nor for paper reading notes, literature surveys, experiment-log summaries, figure plotting, or general rewriting.
metadata:
  short-description: Revise instrument, optics, and CS writing
---

# 学术写作

把用户已经想清楚的材料写成开题报告、论文或基金申请书语言，或按同一套约束改稿、挑错。默认读者是仪器科学、光电工程或计算机方向的导师和评审。这个 skill 解决结构和表达，不替用户发明创新点、器件参数、实验结果或文献。

用户没指定专业时，先判断材料更像测量、光学还是算法。判断不了就按贡献类型写，不要写成泛泛的人工智能研究或人文社科。用户明确要写其他学科时，跟那个学科，不要硬套光机结构。

提示词原文在 references。它们是写作规格，不是默认要回给用户的聊天模板。只有用户明确要提示词时，才返回对应条目。

## 读哪一份

写、改、审正文时，先读 [references/stem-domains.md](references/stem-domains.md) 里对得上的那一节，再读下面一份交付物说明。用户只要未改写的提示词原文时，不必读专业说明。不要把几份交付物说明一起读完。

- 文种未定，或用户只要提问、审稿挑错、引用核验、事实核查、可复制提示词：读 [references/shared.md](references/shared.md)。
- 选题、开题报告、开题答辩，或按研究背景、研究现状、研究问题、方法、创新、进度、难点、目标写研究计划：读 [references/proposal.md](references/proposal.md)。其中“八节覆盖清单”只用来核对槽位和识别空模板，不代替 P5-P13。
- 研究背景或研究意义：先读 [references/background-significance.md](references/background-significance.md)。博士开题或博士论文的这一节再读 [references/phd-background.md](references/phd-background.md)，不要改用 P6 的 800 字四段。硕士或未说明学位层次的开题，字数和段数仍用 P6。
- 论文或学位论文的某一节、标题、摘要、投稿信、中英互译、段落改写：读 [references/paper.md](references/paper.md)。
- 国自然或省部级申请书：读 [references/grant.md](references/grant.md)。默认工程与信息科学写法。只有用户明确要求时才用国社科或教育部人文社科改写。

用户点名 P 编号时，到对应 reference 执行那一条。

## 硬性规则

这些规则压过 reference 里的例子，也压过提示词原文里“让模型补充文献”的口吻。

1. 用户材料之外，不补充具体文献、数据、政策文号、案例或实验结果。缺的标【待补】。确需举例时标【示例，待核实】。引用只用用户给过的文献，写成【作者, 年份】或与用户清单对应的 [n]。不补全作者、卷期、页码、DOI。
2. 不确定就写不确定，并说明该去哪个数据库、用什么检索式核实。不把记忆中的论文写成已核实文献。不把该领域已经证伪的过时理论写成当前共识；拿不准是否过时时，标明需人工核验。
3. 一次只做用户要求的那一项。不顺手重写全文，不擅自加观点。用户的立场优先；改结构、逻辑和语气，不改立场。
4. 数字只来自用户的事实底稿。摘要、正文和表格中的同一数字必须一致。
5. 默认中文。专业术语首次出现写成中文（English）。目标是英文论文时按 paper.md 直接写英文，除非用户要的是翻译。
6. 学校模板、期刊作者指南、当年《项目指南》优先于条目里的建议字数和章节名。没有模板时才用默认字数。
7. 改写必须附不超过 5 条改动说明，且不增加新事实。
8. 没有证据时不写“填补空白”“国际领先”“首次”“具有重要的理论意义和现实意义”。用户坚持保留时，标成无证据断言，不要假装它有文献支持。
9. 公开观点用自己的话转述，不照搬文献原句，保留限定条件。核心观点句调整语序，替换通用学术套话；专业定义在不改变学术含义的前提下按自己的逻辑重述，避免排比工整、套话连篇的同质化表达。引用观点的句末标 [n]，且 [n] 必须对上用户给出的参考文献清单，方便人工核验；没有清单时用【作者, 年份】或【ref】，不编编号，也不为了看起来像有引用而补文献。引用标记是为了能核到出处，从而减少无出处句子被误判，不是为了把抄来的文字藏过查重或 AIGC 检测。用户要求对着查重率或检测分数反复改到达标时，不做这个循环；按本条改表达，并说明不能保证检测分数。
10. 基金申请书通常要求申请人本人撰写，AI 适合检索、整理和润色。多数期刊要求披露 AI 使用。交付草稿时用一句话提醒以本校、本刊或当年项目指南为准。不把含虚构证据的文本说成可以提交。

## 材料不够时

- 用户要整篇开题、论文或本子，但没有题目、问题、结果或模板：不写正文。按 shared.md 的 P0.1 列出会改变写法的问题，然后停。
- 用户只要某一节，而且这一节的材料够用：直接写。缺口留在文中作【待补】，不要为了仪式感先问满 12 个问题。
- 用户已经确认目录或故事线，或明确说“写这一节”：不要退回提问。

## 整篇任务的顺序

不要一次生成全文。

1. 事实底稿：只整理用户已给的文献要点、数据、预实验和政策原文。
2. 提问：只有缺口会改变结构时才问。
3. 骨架：开题用 P5，论文用 P15，本子用 P35 的闭环表。先给骨架。用户还没确认、也没说直接写正文时，停在骨架。
4. 逐节写：开题 P6-P11，论文 P17-P23，本子 P33-P41。一节一个交付。
5. 用户要求审稿、体检或模拟评审时，只用 P0.2、P13、P42 或 P43，只出问题清单，不重写。
6. 用户要求改时，按 P24 或 P29 给改后稿和改动说明。
7. 用户要求核查时，用 P0.3、P30 或 P45。

## 输出

先用不超过 3 句说明文种、这一次交付哪一节、不会补什么。再给交付物。文末用短列表列出【待补】和未核实项。说明不要长过正文。