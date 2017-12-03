# Experiments
Experiment data

| 方向           | 目标              | 建议                              | 成员      |
| ------------ | --------------- | ------------------------------- | ------- |
| backbone网络压缩 | 精度下降不多前提下尽量提高速度 | 换MobileNet，网络压缩、量化              | 梁丰、胡旭孟  |
| 特征提取         | 提高检测小物体能力       | 加FPN，STN等                       | 管悦、王骞   |
| 分类&后处理       | 降低复杂度，提高训练效率    | focal loss, light-head, non-NMS | 徐吉睿、周相鑫 |

TODO: 

1. 数据集：FDDB（由胡旭孟负责准备）
2. baseline: py-R-FCN，由backbone网络组负责baseline实验


## Backbone by [Jeff-LiangF, aozhan]
| backbone     |modification     | learning-rate schedule|epoch(iteration)|dataset|
| ------------ | --------------- | ----------------------| ------- |----|

## Localization by [SophieGuan, knwng]
| backbone     |modification     | learning-rate schedule|epoch(iteration)|dataset|
| ------------ | --------------- | ----------------------| ------- |----|

## Classification & post-process by [abnerdesigner1992, Nick-Zhou]
| backbone     |modification     | learning-rate schedule|epoch(iteration)|dataset|
| ------------ | --------------- | ----------------------| ------- |----|
