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

### 文本分类数据集GLUE
- `CoLA(The Corpus of Linguistic Acceptability)`:纽约大学发布的有关语法的数据集，该任务主要是对一个给定句子，判定其是否语法正确，因此CoLA属于单个句子的文本二分类任务；
- `SST(The Stanford Sentiment Treebank)`: 是斯坦福大学发布的一个情感分析数据集，主要针对电影评论来做情感分类，因此SST属于单个句子的文本分类任务（其中SST-2是二分类，SST-5是五分类，SST-5的情感极性区分的更细致）；
- `MRPC(Microsoft Research Paraphrase Corpus)`:由微软发布，判断两个给定句子，是否具有相同的语义，属于句子对的文本二分类任务；
- `STS-B(Semantic Textual Similarity Benchmark)`:主要是来自于历年SemEval中的一个任务（同时该数据集也包含在了SentEval），具体来说是用1到5的分数来表征两个句子的语义相似性，本质上是一个回归问题，但依然可以用分类的方法做，因此可以归类为句子对的文本五分类任务；
- `QQP(Quora Question Pairs)`，是由Quora发布的两个句子是否语义一致的数据集，属于句子对的文本二分类任务；
- `MNLI(Multi-Genre Natural Language Inference)`:同样由纽约大学发布，是一个文本蕴含的任务，在给定前提（Premise）下，需要判断假设（Hypothesis）是否成立，其中因为MNLI主打卖点是集合了许多不同领域风格的文本，因此又分为matched和mismatched两个版本的MNLI数据集，前者指训练集和测试集的数据来源一致，而后者指来源不一致。该任务属于句子对的文本三分类问题。
- `QNLI（Question Natural Language Inference)`，其前身是SQuAD 1.0数据集，给定一个问句，需要判断给定文本中是否包含该问句的正确答案。属于句子对的文本二分类任务；
- `RTE(Recognizing Textual Entailment)`:和MNLI类似，也是一个文本蕴含任务，不同的是MNLI是三分类，RTE只需要判断两个句子是否能够推断或对齐，属于句子对的文本二分类任务；
- `WNLI(Winograd Natural Language Inference)`:也是一个文本蕴含任务，不过似乎GLUE上这个数据集还有些问题；

### SquAD2.0
- `SQuAD 2.0 `由斯坦福大学计算机系 Pranav Rajpurkar, Robin Jia, Percy Liang 三人在获得 ACL 2018 最佳论文奖的论文《Know What You Don't Know: Unanswerable Questions for SQuAD》（https://arxiv.org/abs/1806.03822）中提出。SQuAD 页面的主题色也从玫红色更换为了蓝紫色。
- `指标`：精确匹配EM（Exact Match）和模糊匹配F1（F1-score）

### 情感分类数据集-英文
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

### 自然语言推理数据集
- [SNLI]

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
