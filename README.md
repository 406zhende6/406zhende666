# 406zhende666

## 问题解析：
### 分类：识别泄露
* 有标签：有监督方法学习
* 无标签（难度更大）：水利学模型构建新数据集（带标签）（pattern无法确定），再训练预测分类模型
* 以朋博士论文，无监督，可以识别大的泄露
### 定位
* 暴力搜索
* 建立映射法：模拟各类工况，建立工况到监测点数据映射值

### 我们已知的条件：
漏量为日均inflow的10%
最多有两个漏点
用WINTR软件模拟的scenario（即epanet的边界条件）

## Method 1 violent search
···


## Method 2 creat simulated data and train deep neural network
...
