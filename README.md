# Personalized-Federated-Recommedantion
| Paper | Venue | Code | Summary | Challenge |
|-------|-------|------|---------|-----------|
| Personalized Federated Recommendation via Joint Representation Learning, User Clustering, and Model Adaptation | CIKM | [PDF](https://dl.acm.org/doi/abs/10.1145/3511808.3557668), [Code](https://github.com/sichunluo/PerFedRec)| 融合全局模型、簇模型、本地模型来解决客户端数据异构问题。|
| FedCDR: Federated Cross-Domain Recommendation for Privacy-Preserving Rating Prediction | CIKM | [PDF](https://dl.acm.org/doi/10.1145/3511808.3557320)| 1. 利用联邦跨域推荐来解决推荐系统中的用户冷启动问题。2.设计了个性化模块来解决客户端异构数据分布问题| 1. 利用矩阵分解来获取user embedding，只利用了用户评分信息，没有使用评分以及属性信息，推荐性能较差。 2. 只考虑了域共有客户端的个性化迁移模型，对于冷启动用户客户端，依旧使用统一的全局迁移模型。 3.没有考虑不同领域之间的隐私泄露问题。
| Fast-adapting and privacy-preserving federated recommender system | VLDB | [PDF](https://link.springer.com/article/10.1007/s00778-021-00700-6) | 利用一阶元学习Repitle来代替二阶元学习MAML来减少客户端计算代价以及通信代价 |
