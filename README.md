# E-Commerce-Data-Analysis
# 电商销售与用户行为分析项目

## 项目概述
本项目基于[Online Retail数据集](https://archive.ics.uci.edu/ml/datasets/Online+Retail)，通过对在线零售数据的深度挖掘与分析，构建了一套完整的分析流程：从使用Python进行数据获取与清洗，到利用Tableau创建交互式可视化仪表板。最终揭示了潜在的销售趋势、核心产品特征以及用户行为模式，为业务决策提供了数据驱动的支持。  

## 业务目标
1.  **趋势分析**: 分析销售额趋势与增长动力。
2.  **产品分析**: 识别核心创收产品类别（帕累托分析）。
3.  **用户行为**: 发现用户购买时间规律，优化运营策略。

## 🛠️ 技术栈
-   **语言**: Python(Pandas/Numpy/Matplotlib)
-   **工具**: Google Colab(Jupyter Notebook)、Tableau
-   **版本控制**: Git、GitHub
-   **技能**: 数据清洗、数据处理、可视化、业务解读

## 项目文件结构
```
E-Commerce-Analysis/
├── README.md               # 项目说明（本文档）
├── e-commerce_analysis_Selene.ipynb  # 完整的Jupyter Notebook源码(代码+可视化图表+文字分析)
├── e-commerce_analysis_selene.py  # 完整的Python源码
└── data/                   # 数据目录
    └── Online Retail.xlsx  # 原始数据集
```

## 可视化展示
### 交互式仪表板截图
![Tableau Dashboard](./Dashboard.jpeg)

*如果您想体验交互式仪表板，可以访问此地址进入我的可视化仪表盘[Dashboard](https://prod-apnortheast-a.online.tableau.com/)。*

## 快速开始
1.  **克隆本项目**:
    `
    git clone https://github.com/SeleneZhong/E-Commerce-Data-Analysis.git
    `
2.  **在Google Colab中打开**:(若电脑中本地环境配置满足要求，也可在本地中直接运行)
    -   上传 `E-Commerce-Data-Analysis.ipynb` 文件至[Google Colab](https://colab.research.google.com/)。
    -   按顺序运行所有单元格即可逐步重现全部分析过程。(也可以点击全部运行按钮一键生成。)

## 核心发现与结论
### 1. 销售趋势
-   通过月度销售额趋势图，发现Q4季度销售额显著增长，经过计算得出Q4季度销售额相较于Q3增长（约30%），推测与节假日促销活动（圣诞节）有关。

### 2. 核心产品分析
-   使用帕累托法则分析，发现约**3.79%** 的头部商品贡献了超过 **40%** 的营收，建议进行重点库存管理和精准营销。

### 3. 用户行为分析
-   **订单时间分布**: 用户的购买行为存在明显的时间规律，订单高峰集中在北京时间**晚上8点-10点**。

## 业务建议
-   **库存管理**：对贡献40%营收的核心产品实施重点监控，优先保障其库存。
-   **营销策略**：将广告预算和促销活动集中在Q4季度以及黄金时段（12:00-14:00），以最大化投资回报率(ROI)。
-   **技术运维**：建议在用户访问高峰时段增强服务器运维保障，确保网站稳定。
