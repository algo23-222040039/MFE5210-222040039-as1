# MFE5210-222040039-as1
【项目参考文献】《20190606-光大证券-光大证券市场情绪体系系列报告之二：重构情绪体系，探知市场温度》
【标的资产选择】沪深300股票指数（000300.SH）
【策略实现】
1.构造A股自由流通换手率指标
2.计算当日换手率历史分位数，当历史分位数进入拥挤区间：卖出；当历史分位数进入非拥挤区间：买入；
3.交易费用以单边3.5%%计算
4.未考虑现金隔夜利息

【回测区间】2009/7/17-2023/5/4
【策略表现】
1.累计收益（净值）：354.4%（3.544）
2.最大回撤率：22.2373%
