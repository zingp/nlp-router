# NLP资料
## 入门篇
- [Yoav Goldberg's Primer](http://u.cs.biu.ac.il/~yogo/nnlp.pdf) 
    - 适合NLP新入门同学阅读，建议一周内读完。备份地址：链接:https://pan.baidu.com/s/1RxYMyaVNtypuR0v9UabB7A  密码:5byy
- [Kyunghyun Cho's Notes](https://arxiv.org/abs/1511.07916)
    - NLP+Deep Learning的入门资料，建议两周内读完。
- [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/)
    - 很全面也很长的教材，建议同学选读。[豆瓣地址](https://book.douban.com/subject/2403834/)
- [复旦邱锡鹏教授的深度学习课程](https://nndl.github.io)
    - 如果希望学习/复习深度学习相关知识，建议看这门课的slides(PPT)。邱教授做NLP方向的研究，他的课会更偏向于Deep Learning在NLP中的应用。
- [Deep Learning中文版](https://github.com/exacity/deeplearningbook-chinese)
- [斯坦福 cs224n Home](http://web.stanford.edu/class/cs224n/)
- [斯坦福 cs224n B站视频](https://www.bilibili.com/video/av46216519)


## 数据集
- [最全中文数据集检索地址](https://www.cluebenchmarks.com/dataSet_search.html)
- [英中翻译IWLST数据集](https://wit3.fbk.eu/mt.php?release=2015-01)  :内含21W个句子对，是TED演讲的中英字幕。
- **IELST中英数据集百度网盘:** 链接:https://pan.baidu.com/s/1jYT8hMG3uN4gtdDKekpygQ  密码:gcm6
- [中文数据基准评测](https://github.com/CLUEbenchmark/CLUE)
- [Chinese Bert-wwm](https://github.com/ymcui/Chinese-BERT-wwm)

### 情感分类数据集
- [Yelp](https://www.kaggle.com/yelp-dataset/yelp-dataset)
    - 这个数据集有两个，一个是有5个评级标签的（Yelp-5），一个是正负情感标签的（Yelp-2）。
    - Yelp-5 每一类有 650000 条训练样本和 50000 条测试样本。
    - Yelp-2 每一类有 560000 条训练样本和 38000 条测试样本。
- [IMDb](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
    - 电影评论情感二分类。包含同等数量的正负情感样本，各自有 25000 条样本。

- `[Movie Review（MR]`电影文本正负情感二分类，总共包含 10662 条样本。经常使用 随机切割的10折交叉验证 来测试这个数据集。

- `The Stanford Sentiment Treebank（SST）`上一个数据集 MR 的扩展版本。有两个版本可以用。一个是包含五个标签的 SST-1，一个是二分类的 SST-2.

- `SST-1` 一共有 11855 条样本，其中 8544 条训练样本，1101 条验证样本，2210 条测试样本。
- `SST-2` 6920 条训练样本，872 条验证样本，1821 条测试样本。
- `MPQA`多视角问答数据集，是一个意见语料库，有两个标签。一共有 10606 条样本。这是一个 不均衡数据集，3311 条正样本和 7293 条负样本。

- [Amazon](https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products)
    - 来自亚马逊购物网站的商品评论，也有两个版本：二分类和多分类。
    - 二分类版本 有 3600000 条训练样本和 400000 条测试数据。
    - 五分类版本 有 3000000 条训练样本和 650000 条测试样本。

- `SemEval-2014 Task 4``Semeval-2016 task 5`
- `SentiHood`: Targeted aspect based sentiment analysis dataset for urban neighbourhoods



## 工具篇
### pytorch
- [动手学深度学习Pytorch版](http://tangshusen.me/Dive-into-DL-PyTorch/#/)

### TensorFlow2.0
- [动手学深度学习TensorFlow2.0版](https://trickygo.github.io/Dive-into-DL-TensorFlow2.0/#/)

## 论文篇
### Machine Translation

## 实战篇
### 数据清洗与预处理
### 模型训练与评测
### 模型部署与上线
### 模型推理性能优化
