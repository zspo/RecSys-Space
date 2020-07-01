![from kaggle](halite-banner.gif)  
图片来自Kaggle
# **Ads-RecSys-Space**

计算广告/推荐系统领域的学习整理。  
包括点击率预估(CTR)、召回层、Embedding、序列模型、多任务等方面的**论文**、**学习笔记**及**代码实现**。
* Python3.5
* Tensorflow1.12 `TF2(Keras)、Pytorch后续更新)`
* Spark2.3.0
* Scala2.11

---
### Papers
#### *CTR*
| Model | Title | Resources | Remarks |
|:-------|:----------|:------------|:------|
|FM|Factorization Machines|[[paper]](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/Rendle2010FM.pdf) [[pdf]](./papers/Rendle2010FM.pdf)|-|
|GBDT+LR |Practical Lessons from Predicting Clicks on Ads at Facebook|[[paper]](https://research.fb.com/publications/practical-lessons-from-predicting-clicks-on-ads-at-facebook/) [[pdf]](./papers/practical-lessons-from-predicting-clicks-on-ads-at-facebook.pdf) |Facebook2014 [[code]](https://github.com/zspo/gbdt-xgboost-lr)|
|FFM|Field-aware Factorization Machines for CTR Prediction|[[paper]](https://dl.acm.org/doi/abs/10.1145/2959100.2959134) [[pdf]](./papers/ffm.pdf)|2016|
|AFM|Attentional Factorization Machines: Learning the Weight of Feature Interactions via Attention Networks|[[paper]](https://arxiv.org/abs/1708.04617) [[pdf]](./papers/afm.pdf)|-|
|FNN|Deep Learning over Multi-field Categorical Data: A Case Study on User Response Prediction|[[paper]](https://arxiv.org/abs/1601.02376) [[pdf]](./papers/fnn.pdf)|-|
|PNN|Product-based Neural Networks for User Response Prediction|[[paper]](https://arxiv.org/abs/1611.00144) [[pdf]](./papers/pnn.pdf)|-|
|Wide&Deep|Wide & Deep Learning for Recommender Systems|[[paper]](https://arxiv.org/pdf/1606.07792.pdf) [[pdf]](./papers/Wide&Deep.pdf)|Google2016|
|DeepFM|DeepFM: A Factorization-Machine based Neural Network for CTR Prediction|[[paper]](https://arxiv.org/abs/1703.04247) [[pdf]](./papers/deeofm.pdf)|Huawei2017|
|DCN|Deep & Cross Network for Ad Click Predictions|[[paper]](https://arxiv.org/abs/1708.05123) [[pdf]](./papers/dcn.pdf)|Google2017|
|xDeepFM|xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems|[[paper]](https://arxiv.org/abs/1803.05170) [[pdf]](./papers/xdeepfm.pdf)|Microsoft2018|
|DIN|Deep Interest Network for Click-Through Rate Prediction|[[paper]](https://arxiv.org/abs/1706.06978) [[pdf]](./papers/din.pdf)|Alibaba2018|
|DSIN|Deep Session Interest Network for Click-Through Rate Prediction|[[paper]](https://arxiv.org/abs/1905.06482) [[pdf]](./papers/dsin.pdf)|Alibaba2019|

#### *Embedding*
| Model | Title | Resources | Remarks |
|:-------|:----------|:------------|:------|
|Item2Vec|Item2Vec: Neural Item Embedding for Collaborative Filtering|[[paper]](https://arxiv.org/abs/1603.04259) [[pdf]](./papers/item2vec.pdf)|Microsoft2016|
|Airbnb Embedding|Real-time Personalization using Embeddings for Search Ranking at Airbnb|[[paper]](https://dl.acm.org/doi/abs/10.1145/3219819.3219885) [[pdf]](./papers/airbnb_embedding.pdf)|Airbnb2018|
|EGES|Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba|[[paper]](https://arxiv.org/abs/1803.02349) [[pdf]](./papers/EGES.pdf)|Alibaba2018

#### *Match*
| Model | Title | Resources | Remarks |
|:-------|:----------|:------------|:------|
|Youtube DNN|Deep Neural Networks for YouTube Recommendations|[[paper]](https://research.google/pubs/pub45530/) [[pdf]](./papers/youtube_dnn.pdf)|Google2016|
|DSSM|Learning Deep Structured Semantic Models for Web Search using Clickthrough Data|[[paper]](https://dl.acm.org/doi/abs/10.1145/2505515.2505665) [[pdf]](./papers/dssm.pdf)|Microsoft2013|
|MIND|Multi-Interest Network with Dynamic Routing for Recommendation at Tmall|[[paper]](https://arxiv.org/abs/1904.08030) [[pdf]](./papers/mind.pdf)|Alibaba2019|
|Youtube 双塔召回|Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations|[[paper]](https://dl.acm.org/doi/10.1145/3298689.3346996) [[pdf]](./papers/youtube2019.pdf)|Youtube2019|

---
### Learning-Notes


---
### CTR
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
