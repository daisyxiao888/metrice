# metrice
sklearn包中metrics包的详细用途
sklearn.metrics 不仅包括了评估功能，还有性能度量，距离度量等 。
分类矩阵：

metrics.accuracy_score(y_true, y_pred[, …])  精确度
metrics.auc(x, y[, reorder])                AUC面积
metrics.average_precision_score(y_true, y_score)   根据预测得分计算平均精度
metrics.balanced_accuracy_score(y_true, y_pred)    计算平衡精度
metrics.brier_score_loss(y_true, y_prob[, …])  计算布里尔分数	
metrics.classification_report(y_true, y_pred) 	构建显示主要分类指标的文本报告
metrics.cohen_kappa_score(y1, y2[, labels, …])  kappa系数用于一致性检验
metrics.confusion_matrix(y_true, y_pred[, …]) 	计算混淆矩阵
metrics.f1_score(y_true, y_pred[, labels, …])	计算F1-score ，也被叫做 平衡 F-score 或者F-measure
metrics.fbeta_score(y_true, y_pred, beta[, …]) 计算 F-beta 
metrics.hamming_loss(y_true, y_pred[, …]) 	计算两个样本集合之间的平均汉明距离
metrics.hinge_loss(y_true, pred_decision[, …])	平均hinge loss (non-regularized)
metrics.jaccard_similarity_score(y_true, y_pred) 杰卡德相似系数：衡量2个集合的相似度
metrics.log_loss(y_true, y_pred[, eps, …])	对数损耗，又称为逻辑损耗或者交叉熵损耗
metrics.matthews_corrcoef(y_true, y_pred[, …])	计算马修斯相关系数（MCC）
metrics.precision_recall_curve(y_true, …)	计算不同概率阈值的精确度、召回度
metrics.precision_recall_fscore_support(…)	计算不同支持度下每一个类的精确度，召回度
metrics.precision_score(y_true, y_pred[, …])	计算精确度
metrics.recall_score(y_true, y_pred[, …]) 	计算召回度
metrics.roc_auc_score(y_true, y_score[, …]) 	计算AUC
metrics.roc_curve(y_true, y_score[, …])	计算ROC曲线
metrics.zero_one_loss(y_true, y_pred[, …])	0-1分类损失

回归矩阵：

metrics.explained_variance_score(y_true, y_pred)	解释方差回归评分函数
metrics.mean_absolute_error(y_true, y_pred)	平均绝对误差
metrics.mean_squared_error(y_true, y_pred[, …])	均方误差
metrics.mean_squared_log_error(y_true, y_pred)	平均平方对数误差
metrics.median_absolute_error(y_true, y_pred)		中位数绝对误差
metrics.r2_score(y_true, y_pred[, …]) 	R ^ 2(确定系数)

聚类矩阵：

metrics.adjusted_mutual_info_score(…[, …])	互信息 用来衡量两个数据分布的吻合程度
metrics.adjusted_rand_score(labels_true, …)	兰德指数 
metrics.calinski_harabaz_score(X, labels)	计算Calinski-Harabasz分数值
metrics.davies_bouldin_score(X, labels)	计算Davies-Bouldin score.
metrics.completeness_score(labels_true, …)	一个簇 的计算分数
metrics.cluster.contingency_matrix(…[, …])		建立描述标签之间关系的列联矩阵
metrics.fowlkes_mallows_score(labels_true, …)	衡量两个簇直接的相似性
metrics.homogeneity_completeness_v_measure(…)	同时计算同质性、完整性和V测度得分.
metrics.homogeneity_score(labels_true, …)	同质性得分
metrics.mutual_info_score(labels_true, …)	互信息得分
metrics.normalized_mutual_info_score(…[, …])	标准互信息得分
metrics.silhouette_score(X, labels[, …])	轮廓系数
metrics.silhouette_samples(X, labels[, metric]) 计算每个样本的轮廓系数
metrics.v_measure_score(labels_true, labels_pred)	V测度得分
