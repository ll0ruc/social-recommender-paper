# social-recommender-paper
This repository provides a curated list of papers about social recommender system in recent years.


# Table of Contents


<summary><b>Expand Table of Contents</b></summary><blockquote><p align="justify">

- [Graph-based](#Graph-based)
- [Neural Network](#Neural Network)
- [Collaborative Filtering](#Collaborative Filtering)
</p></blockquote>

## Graph-based
### 2021
* WWW2021: **Dual Side Deep Context-aware Modulation for Social Recommendation**
    * Author: Bairan Fu, Wenming Zhang, Guangneng Hu, Xinyu Dai, Shujian Huang and Jiajun Chen
    * url: [paper](https://arxiv.org/pdf/2103.08976.pdf) and [code](https://github.com/Drone-Banks/DICER-WWW-2021)
    * DataSet: [Ciao](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) and [Epinion](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm)
    * Metrics: *Recall@K* and *NDCG@K*

* WWW2021: **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation**
    * Author: Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung and Xiangliang Zhang
    * url: [paper](https://arxiv.org/pdf/2101.06448.pdf) and [code](https://github.com/Coder-Yu/QRec)
    * DataSet: [LastFM](http://files.grouplens.org/datasets/hetrec2011/), [Douban](https://pan.baidu.com/s/1hrJP6rq#list/path=%2F) and [Yelp](https://www.yelp.com/)
    * Metrics: *Precision@K*, *Recall@K* and *NDCG@K*

* SIGIR2021: **ConsisRec: Enhancing GNN for Social Recommendation via Consistent Neighbor Aggregation**
    * Author: Liangwei Yang, Zhiwei Liu, Yingtong Dou, Jing Ma and Philip S. Yu
    * url: [paper](https://arxiv.org/pdf/2105.02254.pdf) and [code](https://github.com/YangLiangwei/ConsisRec)
    * DataSet: [Ciao](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) and [Epinion](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm)
    * Metrics: *MAE* and *RMSE*

* SIGIR2021: **Social Recommendation with Implicit Social Influence**
    * Author: Changhao Song, Bo Wang, Qinxue Jiang, Yehua Zhang, Ruifang He and Yuexian Hou
    * url: [paper](https://sci-hub.se/https://doi.org/10.1145/3404835.3463043)
    * DataSet: [Yelp](https://www.yelp.com/)
    * Metrics: *HR@K* and *NDCG@K*

* KDD2021: **Socially-Aware Self-Supervised Tri-Training for Recommendation**
    * Author: Junliang Yu, Hongzhi Yin, Min Gao, Xin Xia, Xiangliang Zhang and Nguyen Quoc Viet Hung
    * url: [paper](https://arxiv.org/pdf/2106.03569.pdf) and [code](https://github.com/Coder-Yu/QRec)
    * DataSet: [LastFM](http://files.grouplens.org/datasets/hetrec2011/), [Douban](https://github.com/librahu/HIN-Datasets-for-Recommendation-and-Network-Embedding)        and [Yelp](https://www.yelp.com/)
    * Metrics: *Precision@K*, *Recall@K* and *NDCG@K*

* WSDM2021: **An Efficient and Effective Framework for Session-based Social Recommendation**
    * Author: Tianwen Chen and Raymond Chi-Wing Wong
    * url: [paper](https://cse.hkust.edu.hk/~raywong/paper/wsdm21-SEFrame.pdf) and [code](https://github.com/twchen/SEFrame)
    * DataSet: [Gowalla](https://snap.stanford.edu/data/loc-gowalla.html), [Delicious](https://grouplens.org/datasets/hetrec-2011/) and [Foursquare](https://sites.google.com/site/yangdingqi/home/foursquare-dataset)
    * Metrics: *HR@K* and *MRR@K*

* WSDM2021: **Heterogeneous Graph Augmented Multi-Scenario Sharing Recommendation with Tree-Guided Expert Networks**
    * Author: Xichuan Niu, Bofang Li, Chenliang Li, Jun Tan, Rong Xiao, and Hongbo Deng
    * url: [paper](https://sci-hub.se/https://doi.org/10.1145/3437963.3441729)
    * DataSet: Taobao
    * Metrics: *AUC*, *GAUC*,  *MRR* and *HR@K* 

* AAAI2021: **Who You Would Like to Share With? A Study of Share Recommendation in Social E-commerce**
    * Author: Houye Ji, Junxiong Zhu, Xiao Wang, Chuan Shi, Bai Wang, Xiaoye Tan, Yanghua Li and Shaojian He
    * url: [paper](https://www.aaai.org/AAAI21Papers/AAAI-1214.JiH.pdf)
    * DataSet: Taobao
    * Metrics: *AUC*

* WCMC2021: **Hierarchical Social Recommendation Model Based on a Graph Neural Network**
    * Author: Zhongqin Bi, Lina Jing, Meijing Shan, Shuming Dou and Shiyang Wang
    * url: [paper](https://downloads.hindawi.com/journals/wcmc/2021/9107718.pdf)
    * DataSet: [Ciao](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) and [Epinion](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm)
    * Metrics: *MAE* and *RMSE*

### 2020
* TKDE2020: **A Graph Neural Network Framework for Social Recommendations**
    * Author: Wenqi Fan, Yao Ma, Qing Li, Jianping Wang, Jiliang Tang and Dawei Yin
    * url: [paper](https://sci-hub.se/10.1109/TKDE.2020.3008732)
    * DataSet: [Ciao](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm), [Epinion](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) and Flixster
    * Metrics: *MAE* and *RMSE*
 
* TKDE2020: **Modelling High-Order Social Relations for Item Recommendation**
    * Author: Yang Liu, Liang Chen, Xiangnan He, Jiaying Peng, Zibin Zheng and Jie Tang
    * url: [paper](https://arxiv.org/pdf/2003.10149.pdf)
    * DataSet: [Douban](https://github.com/librahu/HIN-Datasets-for-Recommendation-and-Network-Embedding) and [Yelp](https://www.yelp.com/)
    * Metrics: *Recall@K* and *NDCG@K*

* TKDE2020: **Enhance social recommendation with Adversarial Graph Convolutional Networks**
    * Author: Junliang Yu, Hongzhi Yin, Jundong Li, Min Gao, Zi Huang and Lizhen Cui
    * url: [paper](https://arxiv.org/pdf/2004.02340.pdf)
    * DataSet: [LastFM](http://files.grouplens.org/datasets/hetrec2011/), [Douban](http://smiles.xjtu.edu.cn/Download/download) and [Gowalla](https://www.dropbox.com/sh/qy3s8rs66nirhl9/AAClmTnFO-rR-4ecEYO-jU4ba?dl=0)
    * Metrics: *Precision@K*, *Recall@K* and *NDCG@K*

* TKDE2020: **DiffNet++: A Neural Influence and Interest Diffusion Network for Social Recommendation**
    * Author: Le Wu, Junwei Li, Peijie Sun, Richang Hong, Yong Ge and Meng Wang
    * url: [paper](https://arxiv.org/pdf/2002.00844.pdf) and [code](https://github.com/PeiJieSun/diffnet)
    * DataSet: [Flickr](https://flickr.com/), [Yelp](https://www.yelp.com/), [Epinions](http://www.trustlet.org/downloaded) and [Dianping](https://lihui.info/data/)
    * Metrics: *HR@K* and *NDCG@K*

* CIKM2020: **Partial Relationship Aware Influence Diffusion via a Multi-channel Encoding Scheme for Social Recommendation**
    * Author: Bo Jin, Ke Cheng, Liang Zhang, Yanjie Fu, Minghao Yin and Lu Jiang
    * url: [paper](https://sci-hub.se/https://doi.org/10.1145/3340531.3412016)
    * DataSet: [Yelp](https://www.yelp.com/) and Flickr
    * Metrics: *HR@K* and *NDCG@K*

* CIKM2020: **DREAM: A Dynamic Relational-Aware Model for Social Recommendation**
    * Author: Liqiang Song, Ye Bi, Mengqiu Yao, Zhenyu Wu, Jianming Wang and Jing Xiao
    * url: [paper](https://arxiv.org/pdf/2008.04579.pdf)
    * DataSet: [Epinion](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) and [Douban-Movie](https://movie.douban.com/)
    * Metrics: *Recall@K*, *NDCG@K* and *MRR*

### 2019
* WWW2019: **Graph Neural Networks for Social Recommendation**
    * Author: Wenqi Fan, Yao Ma, Qing Li, Yuan He, Eric Zhao, Jiliang Tang and Dawei Yin
    * url: [paper](https://arxiv.org/pdf/1902.07243.pdf)
    * DataSet: [Epinion](http://www.cse.msu.edu/∼tangjili/index.html) and [Ciao](http://www.cse.msu.edu/∼tangjili/index.html)
    * Metrics: *MAE* and *RMSE*
 
* WWW2019: **Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in Recommender Systems**
    * Author: Qitian Wu, Hengrui Zhang, Xiaofeng Gao, Peng He, Paul Weng, Han Gao and Guihai Chen
    * url: [paper](https://arxiv.org/pdf/1903.10433.pdf) and [code](https://github.com/echo740/DANSER-WWW-19)
    * DataSet: [Epinions] and [WeChat]
    * Metrics: *MAE*, *RMSE*, *Precision@K* and *AUC*

* SIGIR2019: **A Neural Influence Diffusion Model for Social Recommendation**
    * Author: Le Wu, Peijie Sun, Yanjie Fu, Richang Hong, Xiting Wang and Meng Wang
    * url: [paper](https://arxiv.org/pdf/1904.10322.pdf) and [code](https://github.com/PeiJieSun/diffnet)
    * DataSet: [Yelp] and [Flickr]
    * Metrics: *HR@K* and *NDCG@K*
 
* AAAI2019: **SocialGCN: An Efficient Graph Convolutional Network based Model for Social Recommendation**
    * Author: Le Wu, Peijie Sun, Richang Hong, Yanjie Fu, Xiting Wang and Meng Wang
    * url: [paper](https://arxiv.org/pdf/1811.02815.pdf)
    * DataSet: [Yelp] and [Flickr]
    * Metrics: *HR@K* and *NDCG@K*
  
* WSDM2019: **Social Attentional Memory Network: Modeling Aspect- and Friend-level Differences in Recommendation**
    * Author: Chong Chen, Min Zhang, Yiqun Liu and Shaoping Ma
    * url: [paper](http://www.thuir.cn/group/~mzhang/publications/WSDM2019ChenChong.pdf)
    * DataSet: [Delicious](https://grouplens.org/datasets/hetrec-2011/), [Ciao](http://www.jiliang.xyz/trust.html) and [Epinions](https://alchemy.cs.washington.edu/data/epinions/)
    * Metrics: *Recall@K* and *NDCG@K*  
 

## Neural Network
### 2019
* SIGIR2019: **An Efficient Adaptive Transfer Neural Network for Social-aware Recommendation**
    * Author: Chong Chen, Min Zhang, Chenyang Wang, Weizhi Ma, Minming Li, Yiqun Liu and Shaoping Ma
    * url: [paper](http://www.thuir.cn/group/~YQLiu/publications/SIGIR2019Chen.pdf) and [code](https://github.com/chenchongthu/EATNN)
    * DataSet: [Ciao](http://www.jiliang.xyz/trust.html), [Epinion](http://alchemy.cs.washington.edu/data/epinions/) and [Flixster](https://www.cs.ubc.ca/jamalim/datasets/)
    * Metrics: *Recall@K* and *NDCG@K*

* RecSys2019: **Deep Social Collaborative Filtering**
    * Author: Wenqi Fan, Yao Ma, Dawei Yin, Jianping Wang, Jiliang Tang and Qing Li
    * url: [paper](https://arxiv.org/pdf/1907.06853.pdf)
    * DataSet: [Ciao](https://www.cse.msu.edu/∼tangjili/trust.html), [Epinion](https://www.cse.msu.edu/∼tangjili/trust.html)
    * Metrics: *MAE* and *RMSE*

* WSDM2019: **Session-based Social Recommendation via Dynamic Graph Attention Networks**
    * Author: Weiping Song, Zhiping Xiao, Yifan Wang, Laurent Charlin, Ming Zhang and Jian Tang
    * url: [paper](https://arxiv.org/pdf/1902.09362.pdf) and [code](https://github.com/DeepGraphLearning/)
    * DataSet: [Douban](https://www.douban.com/), [Delicious](https://grouplens.org/datasets/hetrec-2011/) and [Yelp](https://www.yelp.com/dataset)
    * Metrics: *Recall@K* and *NDCG@K*   

* ICDM2019: **Generating Reliable Friends via Adversarial Training to Improve Social Recommendation**
    * Author: Junliang Yu, Min Gao, Hongzhi Yin, Jundong Li, Chongming Gao and Qinyong Wang
    * url: [paper](https://arxiv.org/pdf/1902.09362.pdf)
    * DataSet: [Douban](http://smiles.xjtu.edu.cn/Download/download), [LastFM](http://files.grouplens.org/datasets/hetrec2011/) and [Epinions](http://www.trustlet.org/downloaded)
    * Metrics: *Precision@K*, *Recall@K* and *NDCG@K*   

### 2018
* WWW2018: **Network Embedding Based Recommendation Method in Social Networks**
    * Author: Yufei Wen, Zhumin Chen, Lei Guo and Jun Ma
    * url: [paper](https://dl.acm.org/doi/pdf/10.1145/3184558.3186904) and [code](https://github.com/chenchongthu/EATNN)
    * DataSet: [Ciao] and RMSE*
