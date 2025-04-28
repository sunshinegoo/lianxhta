# B771：AI能胜任匿名评审工作吗？

从下文中抽取主要观点，进而提供一些使用 AI 来评审自己论文初稿的例子 (主要是收集/自己测试一些有用的 Prompts)

作者在附录中提供了很多 Prompts，可以翻译为中文后在 ChatGPT 中测试一下。

- Liang, W., Zhang, Y., Cao, H., Wang, B., Ding, D. Y., Yang, X., Vodrahalli, K., He, S., Smith, D. S., Yin, Y., Mcfarland, D. A., & Zou, J. (2024). Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis. NEJM AI, 1(8). [Link](https://doi.org/10.1056/AIoa2400196), [PDF](https://arxiv.org/pdf/2310.01783), [Google](<https://scholar.google.com/scholar?q=Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis>).

核心观点：
- 通过回顾性和前瞻性评估，我们发现 LLM 反馈与人工反馈之间存在大量重叠，并且用户对 LLM 反馈的实用性持积极看法。尽管人工专家评审应继续成为科学过程的基础，但 LLM 反馈可能会使研究人员受益，尤其是在无法及时获得专家反馈以及稿件准备的早期阶段。
- 总结这篇论文的其他重要观点

如下内容非常实用：
- Supplementary Figure 5. Schematic of the LLM scientific feedback generation system。重点介绍这里提供的 ③ Prompt。


## Prompt 1: sample

```
Your task now is to draft a high-quality review outline for a Nature family journal for a
submission titled <Title>:
‘‘‘
<Paper_content>
‘‘‘

======
Your task:
Compose a high-quality peer review of a paper submitted to a Nature family journal.
Start by "Review outline:".
And then:
"1. Significance and novelty"
"2. Potential reasons for acceptance"
"3. Potential reasons for rejection", List multiple key reasons. For each key reason, use
**>=2 sub bullet points** to further clarify and support your arguments in painstaking
details. Be as specific and detailed as possible.
"4. Suggestions for improvement", List multiple key suggestions. Be as specific and detailed
as possible.
Be thoughtful and constructive. Write Outlines only.
```
