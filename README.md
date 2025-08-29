# E-Commerce-Data-Analysis
# 电商销售与用户行为分析项目

## 🎯 项目概述
本项目基于[Online Retail数据集](https://archive.ics.uci.edu/ml/datasets/Online+Retail)，完整复现了数据分析的全流程，旨在挖掘用户购买行为模式与销售关键指标，为业务决策提供数据支持。

## 📊 业务目标
1.  **趋势分析**: 分析销售额趋势与增长动力。
2.  **产品分析**: 识别核心创收产品类别（帕累托分析）。
3.  **用户行为**: 发现用户购买时间规律，优化运营策略。

## 🛠️ 技术栈
-   **语言**: Python
-   **库**: Pandas, NumPy, Matplotlib
-   **工具**: Google Colab (Jupyter Notebook)
-   **技能**: 数据清洗、数据处理、可视化、业务解读

## 🗂️ 项目文件结构
```
E-Commerce-Analysis/
├── README.md               # 项目说明（本文档）
├── e-commerce_analysis.ipynb  # 完整的Jupyter Notebook源码
├── e-commerce_analysis.html  # 可交互的HTML报告
└── data/                   # 数据目录
    └── Online Retail.xlsx  # 原始数据集
```

## 🚀 快速开始
1.  **克隆本项目**:
    ```bash
    git clone https://github.com/SeleneZhong/E-Commerce-Data-Analysis.git
    ```
2.  **在Google Colab中打开**:
    -   上传 `E-Commerce-Data-Analysis.ipynb` 文件至 [Google Colab](https://colab.research.google.com/)。
    -   按顺序运行所有单元格即可重现全部分析过程。

## 📈 核心发现与结论
### 1. 销售趋势
-   通过月度销售额趋势图，发现Q4季度销售额相较于Q3有显著增长（约30%），推测与节假日促销活动有关。

### 2. 核心产品分析
-   应用帕累托法则分析，发现约**2%**的头部商品贡献了超过**40%**的营收，建议进行重点库存管理和精准营销。

### 3. 用户行为分析
-   **订单时间分布**: 用户的购买行为存在明显的时间规律，订单高峰集中在北京时间**晚上8点-10点**。
    -   **业务建议**: 在此黄金时段集中投放广告、开展直播带货等活动，并确保服务器稳定，以最大化转化率。
