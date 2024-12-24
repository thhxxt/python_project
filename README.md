# python_project
## 学生成绩影响因素分析与预测
高中生的学习成绩，是对其学习评价的直观体现。为进一步研究、探讨学生成绩的影响因素，同时根据这些因素，能较好地预测出学生的学习成绩，从而为制定更加科学、合理的教学策略和家庭指导方案提供有力支持，最终促进学生的全面发展与健康成长，本文分析了年龄分布在15岁到18岁的美国高中生数据集，针对所给出的11种特征，首先对2392名高中生学习成绩构建线性回归模型，分析对学生成绩影响具有统计学意义的关键特征。随后，为了根据所给特征，从而预测出学生的最终GPA成绩，选择了线性回归模型、神经网络模型和CatBoost回归模型三个模型进行对比，得到预测效果较好的模型，实现对学生成绩较高精准度预测。
### 代码
#### 主代码.ipynb文件包含为文章而建立的三个类，以及模型评估对比的函数；
#### 数据描述.ipynb文件包含数据的基本描述和数据的基础可视化代码。
### 运行环境：
python3.8
### 需安装的包：
#### pandas == 2.2.2
#### numpy == 1.26.4
#### sklearn == 1.4.2
#### catboost == 1.2.7
#### scipy == 1.13.1
#### statsmodels == 0.14.4
#### matplotlib ==3.8.4
#### tensorflow == 2.18.0
#### seaborn == 0.13.2
