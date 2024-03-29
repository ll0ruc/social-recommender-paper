# social-recommender-paper
This repository provides a curated list of papers about social recommender system in recent years.

A website link for accepted paper in recent years.

<br>KDD-2023 [https://kdd.org/kdd2023/research-track-papers-list/]
<br>KDD-2022 [https://kdd.org/kdd2022/paperRT.html]
<br>KDD-2021 [https://kdd.org/kdd2021/accepted-papers/index]
<br>KDD-2020 [https://www.kdd.org/kdd2020/accepted-papers]
<br>KDD-2018 [https://www.kdd.org/kdd2018/accepted-papers]
<br>SIGIR-2023 [https://sigir.org/sigir2023/program/accepted-papers/full-papers/]
<br>SIGIR-2022 [https://sigir.org/sigir2022/program/accepted/]
<br>SIGIR-2021 [https://sigir.org/sigir2021/accepted-papers/]
<br>SIGIR-2020 [https://sigir.org/sigir2020/accepted-papers/]
<br>SIGIR-2019 [https://sigir.org/sigir2019/program/accepted/]
<br>SIGIR-2018 [https://sigir.org/sigir2018/accepted-papers/]
<br>WWW-2023 [https://archives.iw3c2.org/www2023/program/accepted-papers/]
<br>WWW-2022 [https://archives.iw3c2.org/www2022/accepted-papers/]
<br>WWW-2021 [https://www2021.thewebconf.org/program/papers/index.html]
<br>WWW-2019 [https://thewebconf.org/www2019/accepted-papers/]
<br>WWW-2018 [https://www2018.thewebconf.org/proceedings/]
<br>CIKM-2023 [https://sigir.org/sigir2023/program/accepted-papers/full-papers/]
<br>CIKM-2022 [https://archives.iw3c2.org/www2022/accepted-papers/]
<br>CIKM-2021 [https://www.cikm2021.org/accepted-papers]
<br>CIKM-2020 [https://www.cikm2020.org/accepted-papers/]
<br>WSDM-2024 [https://www.wsdm-conference.org/2024/accepted-papers/]
<br>WSDM-2023 [https://www.wsdm-conference.org/2023/program/accepted-papers]
<br>WSDM-2022 [https://www.wsdm-conference.org/2022/accepted-papers/]
<br>WSDM-2021 [https://www.wsdm-conference.org/2021/accepted-papers.php]
<br>WSDM-2020 [https://www.wsdm-conference.org/2020/accepted-papers.php]
<br>WSDM-2019 [https://www.wsdm-conference.org/2019/accepted-papers.php]
<br>WSDM-2018 [https://www.wsdm-conference.org/2018/accepted-papers.html]
<br>RecSys-2023 [https://recsys.acm.org/recsys23/accepted-contributions/]

# Table of Contents


<summary><b>Expand Table of Contents</b></summary><blockquote><p align="justify">

- [Graph-based](#Graph-based)
- [Neural Network](#Neural-Network)
- [Collaborative Filtering](#Collaborative-Filtering)
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
 

## Neural-Network

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

* TKDE2019: **A Hierarchical Attention Model for Social Contextual Image Recommendation**
    * Author: Le Wu, Lei Chen, Richang Hong, Yanjie Fu, Xing Xie and Meng Wang
    * url: [paper](https://arxiv.org/pdf/1806.00723.pdf)
    * DataSet: [F_S] and [F_L](a large dataset form Flickr)
    * Metrics: *HR@K* and *NDCG@K*

### 2018
* WWW2018: **Network Embedding Based Recommendation Method in Social Networks**
    * Author: Yufei Wen, Zhumin Chen, Lei Guo and Jun Ma
    * url: [paper](https://dl.acm.org/doi/pdf/10.1145/3184558.3186904)
    * DataSet: [Ciao] and [Epinions]*
    * Metrics: *MAE* and *RMSE* 

* SIGIR2018: **Attentive Recurrent Social Recommendation**
    * Author: Peijie Sun, Le Wu and Meng Wang
    * url: [paper](http://www.le-wu.com/files/Publications/CONFERENCES/SIGIR%202018%20Attentive%20Recurrent%20Social%20Recommendation.pdf)
    * DataSet: [Epinions] and [Gowalla]*
    * Metrics: *HR@K* and *NDCG@K* 

* AAAI2018: **Deep Modeling of Social Relations for Recommendation**
    * Author: Wenqi Fan, Qing Li and Min Cheng
    * url: [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/16075)
    * DataSet: [Ciao](http://www.cse.msu.edu/∼tangjili/index.html) and [Epinions](http://www.cse.msu.edu/∼tangjili/index.html)*
    * Metrics: *MAE* and *RMSE* 

* IEEE TRANSACTIONS ON SYSTEMS2018: **Collaborative Neural Social Recommendation**
    * Author: Le Wu, Peijie Sun, Richang Hong, Yong Ge and Meng Wang
    * url: [paper](http://www.le-wu.com/files/Publications/JOURNAL/TSMC-2021-CollaborativeNeuralSocialRecommendation.pdf)
    * DataSet: [Flixster] and [Douban]*
    * Metrics: *HR@K* and *NDCG@K* 

* SIGIR2017: **Item Silk Road: Recommending Items from Information Domains to Social Users**
    * Author: Xiang Wang, Xiangnan He, Liqiang Nie and Tat-Seng Chua
    * url: [paper](https://arxiv.org/pdf/1706.03205.pdf)
    * DataSet: [Trip.com], [Facebook] and [Twitter]*
    * Metrics: *AUC* and *Recall@K* 

## Collaborative-Filtering

### 2019
* IJCAI2019: **Feature Evolution Based Multi-Task Learning for Collaborative Filtering with Social Trust**
    * Author: Qitian Wu, Lei Jiang, Xiaofeng Gao, Xiaochun Yang and Guihai Chen
    * url: [paper](https://www.ijcai.org/proceedings/2019/0538.pdf)
    * DataSet: [Epinions], [Ciao] and [FilmTrust]
    * Metrics: *MAE* and *RMSE* 

* IEEE TRANSACTIONS ON CYBERNETICS2019: **Exploiting Implicit Influence from Information Propagation for Social Recommendation**
    * Author: Fei Xiong, Weihan Shen, Hongshu Chen, Shirui Pan, Ximeng Wang and Zheng Yan
    * url: [paper](https://shiruipan.github.io/publication/tcyb-2019-xiong/tcyb-2019-xiong.pdf)
    * DataSet: [Epinions] and [Ciao]
    * Metrics: *MAE* and *RMSE* 
