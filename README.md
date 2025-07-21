# Project

本仓库收录了个人的项目论文，包括空气污染时空分析、假新闻识别及互联网医疗数据挖掘等多篇研究成果。以下为主要论文简介：

---

## 1. Spatiotemporal Analysis and Prediction Modeling of Air Pollution in Dublin Based on Traffic and Meteorological Factors
基于都柏林的空气污染、交通流量和气象数据，结合时间序列分析、相关性研究和机器学习预测模型，揭示了污染物浓度的时空分布特征及其与风速和交通的关系。研究通过数据清洗与整合、特征工程和多种回归模型的比较与优化，构建了高精度的污染物浓度预测模型。利用 PCA 降维与 KMeans 聚类方法分析了不同交通流量条件下的污染分布规律。结果显示，风速与部分污染物浓度呈负相关，而高交通流量时污染浓度反而较低，历史污染数据在预测当前浓度中具有重要价值。本研究为城市空气质量管理和交通规划提供了可行的参考。

---

## 2. Urban Air Pollution Structures and Their Social-Environmental Drivers: A Multivariate Analysis Based on PCA and Machine Learning
本论文针对都柏林的多源空气污染、气象和交通行人数据，利用主成分分析提取污染结构的潜在维度。结合 KMeans 聚类识别典型污染类型，最后通过梯度提升回归模型预测污染结构并分析外部变量的解释力。研究结果显示，污染结构可分为高污染事件、典型城市背景污染和清洁期三类，不同类型在污染物组成、季节分布及外部气象与交通条件上差异显著。预测分析表明温度、风速、湿度及交通量等因素对气态污染结构的解释效果最强，粒子污染结构的预测性能次之。该研究为城市空气污染模式识别、来源解释和智能预警提供了数据支持和方法框架。

---

## 3. Dissecting Fake and Real News: A Text-Based Analysis of Linguistic and Emotional Patterns
本研究基于 ISOT Fake News Detection 数据集，通过情感分析、主题建模与文本分类方法，系统比较真假新闻在语言特征上的差异。研究发现，假新闻的整体情感表现更为极端，标题与正文之间的情感落差更大，常采用“情绪化标题 + 中性正文”的误导策略。而真新闻整体更为中立和一致。通过 LDA 主题建模，假新闻多集中于“邮件门”“移民争议”等政治敏感话题，真新闻则以政策、外交等中立主题为主。在文本建模中，利用 TF-IDF 特征和逻辑回归分类器，标题与正文结合的模型准确率可达 99%，仅用标题也能达到 95%，证明文本语言特征可高效区分真假新闻。研究进一步通过关键词权重分析揭示了假新闻常用情绪化词汇，而真新闻倾向于使用更客观和正式的表达，为自动化识别假新闻提供了有力参考。

---

## 4. 互联网医疗平台问诊数据的多维行为挖掘与预测建模
本研究基于“好大夫在线”平台的真实问诊数据，构建了一个集内容分析、用户分群与预测建模为一体的多维行为分析框架。研究首先对问诊文本进行清洗与结构化处理，并利用 LDA 主题模型抽取出涵盖诊断、用药、术后恢复等 8 个核心内容主题。结合“病情字数”“对话字数”和“总轮数”等结构化指标，采用 KMeans 聚类识别用户在活跃度维度上的分群结构，并通过 UMAP 和 PCA 实现降维可视化。结果显示，不同群体在交流频次和互动深度上存在显著差异。随后，本研究构建多种机器学习模型，仅基于上述行为特征即可高精度预测用户群体归属，其中调优后的 LightGBM 模型在测试集上达到 97.72% 的准确率，并通过 SHAP 方法实现了特征贡献的可解释化。该研究验证了互联网医疗问诊行为的结构性和可预测性，为平台用户画像、精细化管理与个性化服务提供了技术支持与实践参考。

---

## 文件列表
- `Spatiotemporal Analysis and Prediction Modeling of Air Pollution in Dublin Based on Traffic and Meteorological Factors.pdf`
- `Urban Air Pollution Structures and Their Social-Environmental Drivers A Multivariate Analysis Based on PCA and Machine Learning.pdf`
- `Dissecting Fake and Real News- A Text-Based Analysis of Linguistic and Emotional Patterns.pdf`
- `互联网医疗平台问诊数据的多维行为挖掘与预测建模.pdf`

