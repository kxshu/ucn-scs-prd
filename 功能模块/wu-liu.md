# 物流

### 定义

无

### 说明（采购商角度）

物流客户不直接参加物流，客户关心`到达DC时间`，我们能拿到`到达港口时间`

### 术语

| 词汇 | 解释 | 内容 | 发起人 |
| :--- | :--- | :--- | :--- |
| Delivery forecast |  |  |  |
| Delivery plan |  |  |  |
| Loading plan |  | Product List | 采购商 |
|  |  | Container |  |
|  |  | Forwarder |  |
|  |  | Booking |  |
| Booking |  | 集装箱、仓位的协调 |  |
|  |  | 用container号追踪最好 |  |
| Loading |  |  |  |

### 流程

**文字流程**

`ETA/ATA`-&gt; `进口报关`-&gt; `国内物流` -&gt; `DC`

#### 预测流程

##### 文字流程

`Delivery forecast` -&gt; `delivery plan（客户确认运输方式，客户考虑单个SKU的发运计划）` -&gt; `loading plan（大客户可能提前2周开始订集装箱，实际应该是goods ready后才能落实）`

**类似**：

交货预测 -&gt; 发运计划 -&gt; 装柜清单

### 系统

1. Tracking system 中Exception report 时效异常报告
2. 中转港口的时效调控需要管理
3. 船公司的追踪系统对接
4. 根据`订单`、`SKU`、`物流`进行跟踪



