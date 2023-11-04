# Moderate-risk-model

![clsl](readme/clsl.png)

本因子来源于[【方正金工】成交量激增时刻蕴含的alpha信息——多因子选股系列研究之一|成交量_新浪财经_新浪网 (sina.com.cn)](https://finance.sina.com.cn/stock/stockzmt/2022-04-21/doc-imcwiwst3090589.shtml)。

复现方正金工的”适度冒险“因子，并进行测试

由于数据量较大，只对299只随机股票的1年数据进行回测，后续会逐步尝试更大的股票池与回测时间。

在本次测试中，我首先计算出因子数值，然后使用Fama-MacBeth回归、分组收益率以及单因子策略评价每个因子的效果。

