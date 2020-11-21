# NCF-MF-for-Recommendation
分别使用传统方法（KNN，SVD，NMF等）和深度方法（NCF）进行推荐系统的评分预测。Traditional methods (KNN, SVD, NMF, etc.) and depth method (NCF) were used to predict rating of the recommendation system.  
## 需求
- Tensorflow 
- Keras  
- surprise
## 任务
首先，下载yelp数据集（较大，未提供），进行数据分析和处理工作。提取yelp数据集中我们需要的部分，即Toronto地区的点评信息（user item rating 评论文本）。得到rating.csv和rating-text.csv（较大，未提供）。  
之后，分别使用传统方法和深度方法进行评分预测和评价指标的计算。  
## 文件结构
- yelp_data_analysis.ipynb：数据下载中、数据分析、数据处理部分。   
- rating.csv：保存好的数据。
- yelp_mf_recomendation.ipynb：利用多种传统方法进行推荐的评分预测以及模型评估。  
- yelp_nn_recomendation.ipynb：利用NCF神经协同过滤方法进行推荐的评分预测以及模型评估。  

