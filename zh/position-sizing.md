仓位管理

逻辑
DocuRefinery 的仓位管理策略将定量风险管理与现代投资组合理论 (MPT) 相结合，以优化资本配置。通过采用凯利公式 (Kelly Criterion)，模型旨在最大化投资组合的长期增长率，同时降低破产风险。该方法承认，虽然有效市场假说 (EMH) 认为价格反映了所有可用信息，但行为偏差和流动性约束造成了暂时的市场低效。我们的逻辑利用波动率调整模型来考虑资产的 Beta 和历史 Alpha，确保仓位大小与其风险贡献成反比。我们分析 Free Cash Flow (FCF) yield 与 Weighted Average Cost of Capital (WACC) 之间的关系，以确定信念的基本面强度。通过考虑止损距离和与现有持仓的相关性，该策略防止了在高 beta 行业的过度集中。这种系统性框架利用了在非管理投资组合中经常侵蚀收益的波动率拖累。通过将每笔交易视为概率结果而非确定性事件，我们弥合了基本面分析（如 P/E ratio 扩张）与严格数学风险控制之间的差距，为抵御信息不对称和尾部风险事件提供了对冲。

AI 模型任务
由 Claude 和 Gemini 驱动的 DocuRefinery AI 模型在严格的确定性框架内运行，以确保机构级的可靠性。每次分析均受不可变的提示词模板管理，这些模板强制要求使用凯利公式和固定分数模型。为了消除幻觉，AI 被禁止生成推测性数字；它必须交叉核对实时市场数据，并为每个指标（如当前的 P/E 或债务权益比）提供强制性引用。输出以结构化格式交付，包括波动率调整后的表格和相关矩阵。如果存在数据缺口，AI 被编程为报告遗漏而非捏造数值，确保决策过程的完全透明。

This documentation is a public mirror of DocuRefinery. For real-time analysis and updated logic, visit: https://docurefinery.com/stock/AIG/hub/position-sizing?lang=zh
