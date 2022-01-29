![from kaggle](halite-banner.gif)  

# **RecSys-Space**

搜广推领域的学习整理。  
包括`点击率预估(CTR)`、`召回`、`Graph`、`Embedding`、`序列推荐`、`多任务`、`推荐系统工程`等方面的**论文**、**学习笔记**及**代码实现**。
* Python3.6
* TensorFlow1.14.0
* Pytorch1.8.0
* Spark2.3.0
* Scala2.11

---
### Papers
#### *CTR*
| Model | Title | Resources | Remarks |
|:-------|:----------|:------------|:------|
|FM|Factorization Machines|[[paper]](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/Rendle2010FM.pdf)|-|
|GBDT+LR |Practical Lessons from Predicting Clicks on Ads at Facebook|[[paper]](https://research.fb.com/publications/practical-lessons-from-predicting-clicks-on-ads-at-facebook/)|Facebook2014 [[code]](https://github.com/zspo/gbdt-xgboost-lr)|
|FFM|Field-aware Factorization Machines for CTR Prediction|[[paper]](https://dl.acm.org/doi/abs/10.1145/2959100.2959134)|2016|
|AFM|Attentional Factorization Machines: Learning the Weight of Feature Interactions via Attention Networks|[[paper]](https://arxiv.org/abs/1708.04617)|-|
|FNN|Deep Learning over Multi-field Categorical Data: A Case Study on User Response Prediction|[[paper]](https://arxiv.org/abs/1601.02376)|-|
|PNN|Product-based Neural Networks for User Response Prediction|[[paper]](https://arxiv.org/abs/1611.00144)|-|
|Wide&Deep|Wide & Deep Learning for Recommender Systems|[[paper]](https://arxiv.org/pdf/1606.07792.pdf)|Google2016|
|DeepFM|DeepFM: A Factorization-Machine based Neural Network for CTR Prediction|[[paper]](https://arxiv.org/abs/1703.04247)|Huawei2017|
|DCN|Deep & Cross Network for Ad Click Predictions|[[paper]](https://arxiv.org/abs/1708.05123)|Google2017|
|xDeepFM|xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems|[[paper]](https://arxiv.org/abs/1803.05170)|Microsoft2018|
|DIN|Deep Interest Network for Click-Through Rate Prediction|[[paper]](https://arxiv.org/abs/1706.06978)|Alibaba2018|
|DSIN|Deep Session Interest Network for Click-Through Rate Prediction|[[paper]](https://arxiv.org/abs/1905.06482)|Alibaba2019|

#### *Embedding*
| Model | Title | Resources | Remarks |
|:-------|:----------|:------------|:------|
|Item2Vec|Item2Vec: Neural Item Embedding for Collaborative Filtering|[[paper]](https://arxiv.org/abs/1603.04259)|Microsoft2016|
|Airbnb Embedding|Real-time Personalization using Embeddings for Search Ranking at Airbnb|[[paper]](https://dl.acm.org/doi/abs/10.1145/3219819.3219885)|Airbnb2018|
|EGES|Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba|[[paper]](https://arxiv.org/abs/1803.02349)|Alibaba2018

#### *Match*
| Model | Title | Resources | Remarks |
|:-------|:----------|:------------|:------|
|Youtube DNN|Deep Neural Networks for YouTube Recommendations|[[paper]](https://research.google/pubs/pub45530/)|Google2016|
|DSSM|Learning Deep Structured Semantic Models for Web Search using Clickthrough Data|[[paper]](https://dl.acm.org/doi/abs/10.1145/2505515.2505665)|Microsoft2013|
|MIND|Multi-Interest Network with Dynamic Routing for Recommendation at Tmall|[[paper]](https://arxiv.org/abs/1904.08030)|Alibaba2019|
|Youtube 双塔召回|Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations|[[paper]](https://dl.acm.org/doi/10.1145/3298689.3346996)|Youtube2019|

---
### Learning-Notes


---
### CTR
* [x] BaseModel 未完待续
* [ ] LR  
* [x] GBDT+LR  
* [ ] FM  
* [ ] FFM  
* [ ] DeepFM  
* [ ] Wide&Deep  
* [ ] ...

---
### TF_Basic
* [ ] NN
    * [x] basic tensorflow
    * [x] linear regression
    * [x] logitstic regression
    * [x] simple neural network
    * [x] cnn model
    * [x] rnn lstm model 
    * [ ] ...

* [ ] TF
    * [ ] csv2tfrecord
    * [ ] save model
