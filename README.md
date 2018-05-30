# Frequent-Association-Rule-Mining
软统课作业之频繁关联规则挖掘
现在有一份数据集A.csv，数据来自https://archive.ics.uci.edu/ml/datasets/Congressional+Voting+Records ，每一行的第i项数据代表议员对第i个政策的投票结果记为ni或yi或？i，
请根据数据集的描述（https://archive.ics.uci.edu/ml/machine-learning-databases/voting-records/house-votes-84.names） ，
读取数据集提取出minimum_support为150时的频繁项集，然后求出此时支持度大于等于0.45，置信度大于等于0.9的，以包含republican0或democrat0为左边的关联规则。
如：['y3', 'democrat0'] => ['n4']
结果返回格式为：
[[['democrat0'], ['n4']], [['y3', 'democrat0'], ['n4']], …… ]
