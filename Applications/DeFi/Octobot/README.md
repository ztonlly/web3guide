# Octobot
[https://github.com/Drakkar-Software/OctoBot](https://github.com/Drakkar-Software/OctoBot)

Octobot是一个功能强大的开源加密货币交易机器人。

OctoBot 的配置和触角系统可实现高度定制。您可以使用无限的配置可能性（如 技术分析、社交媒体处理，甚至像谷歌趋势这样的外部统计管理）构建自己的机器人。

Octobot 的主要功能是进化，你可以：

+ 从头开始或使用现有的策略基础创建、回测和优化您独特的交易策略。
+ 使用技术指标 (TA)、人工智能、ChatGPT 预测、TradingView 自动化或加密篮子来自动化您的策略。
+ 在超过15 个受支持的交易所的现货和期货市场上交易任何加密货币。
+ 安装、修改甚至创建新的触手来构建您理想的加密货币交易机器人。
+ 为改进 OctoBot 核心存储库和触角做出贡献。
+ OctoBot 已为 AI 做好准备：Python 是 OctoBot 的主要语言，它可以轻松集成机器学习库（如Tensorflow或任何其他库）并利用所有可用数据并创建非常强大的交易策略。

想要了解更多信息？查看我们的 Octobot 指南：[octobot.cloud/en/guides/octobot](https://www.octobot.cloud/en/guides/octobot)

### 评估器说明
+ RSIMomentumEvaluator: 相对强弱指数 (RSI) 动量评估器，用于衡量市场的超买或超卖情况，以识别潜在的趋势反转点。
+ DoubleMovingAverageTrendEvaluator: 使用双移动平均线的趋势评估器，用于确认价格趋势的方向，典型的是短期和长期均线的交叉来识别趋势的开始和结束。
+ BBMomentumEvaluator: 布林带 (Bollinger Bands) 动量评估器，通过价格相对于上下波动带的位置来判断市场波动性和潜在趋势。
+ ACDMomentumEvaluator: 移动平均收敛/发散 (MACD) 动量评估器，用于衡量价格趋势的强度和方向。
+ CandlePatternMomentumEvaluator: 蜡烛图模式动量评估器，通常用于通过价格形态来识别短期趋势变化。
+ ADXMomentumEvaluator: 平均趋向指数 (ADX) 评估器，用于评估趋势的强度。
+ InstantFluctuationsEvaluator: 即时波动评估器，用于检测市场的快速变化，帮助识别短期交易机会。
+ RedditForumEvaluator: Reddit 论坛评估器，该评估器通常用于从社交媒体情绪中收集市场趋势数据。
+ GoogleTrendStatsEvaluator: Google 趋势统计评估器，用于跟踪关键搜索趋势，从而识别可能的市场兴趣变化。
+ TempFullMixedStrategiesEvaluator: 混合策略评估器，可能用于结合多个策略的输出来生成综合信号。
+ InstantSocialReactionMixedStrategiesEvaluator: 即时社交反应混合策略评估器，通常用于根据社交媒体的反应速度来进行市场评估。

```json
{
  "RSIMomentumEvaluator": true,
  "DoubleMovingAverageTrendEvaluator": true,
  "BBMomentumEvaluator": true,
  "MACDMomentumEvaluator": true,
  "CandlePatternMomentumEvaluator": false,
  "ADXMomentumEvaluator": true,
 
 
  "InstantFluctuationsEvaluator": true,
 
 
  "RedditForumEvaluator": false,
  "GoogleTrendStatsEvaluator": true,
 
 
  "TempFullMixedStrategiesEvaluator": true,
  "InstantSocialReactionMixedStrategiesEvaluator": false
}
```