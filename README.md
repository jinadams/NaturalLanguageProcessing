# Natural Language Procesing
This repository includes basic concepts of Natural Language Processing, textbooks and blogs of good reputation, popular papers and so on.  

This is also the Natural Language Processing part of [Machine Learning Resources](https://github.com/jindongwang/MachineLearning) created by a group of people including [jindongwang](https://github.com/jindongwang).

Contributors are welcomed to work together and make it BETTER!

## Resource of Textbooks and Lectures

### Mathemetical and Statistical Foundation
* Linear Algebra
  - 18.06 MIT(Gilbert Strang)[[pdf](http://www.math.hcmus.edu.vn/~bxthang/Linear%20algebra%20and%20its%20applications.pdf)][[video](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)]

* Matrix Analysis

* Convex Optimization
  - EE364A Stanford(Stephen Boyd)[[pdf](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)][[website](http://web.stanford.edu/~boyd/cvxbook/)]
  - Introductory Lectures on Convex Programming(Yu.Nesterov)[[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.693.855&rep=rep1&type=pdf)]


### Machine Learning
* [The Elements of Statistical Learning(ESL) - HTF](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
* [CS228 Probabilistic Graphical Model - Stanford](https://cs.stanford.edu/~ermon/cs228/index.html)
* [10708 Probabilistic Graphical Model - CMU](http://www.cs.cmu.edu/~epxing/Class/10708/index.html)

### Deep Learning
* [Deep Learning - Ian Goodfellow, Yoshua Bengio, Aaron Courville](https://github.com/HFTrader/DeepLearningBook)
* [CS231n Convolutional Neural Networks for Visual Recognition - Stanford](http://cs231n.stanford.edu/)

### Natural Language Processing
* Foundations of Statistical Natural Language Processing - 
    Chris Manning
* [Speech and Language Processing - Daniel Jurafsky and James H. Martin](http://www.cs.colorado.edu/~martin/slp2.html#Chapter3)
* 统计学习方法 - 李航
* [Advanced Natural Language Processing - MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/index.htm)
* [CS 224n Natural Language Processing with Deep Learning - Stanford](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/index.htm)
* [Deep Learning for NLP at Oxford with Deepmind - Oxford](https://www.youtube.com/playlist?list=PL613dYIGMXoZBtZhbyiBqb0QtgK6oJbpm)
* [Some Knowledge about Machine Learning](https://www.youtube.com/playlist?list=PL613dYIGMXoZBtZhbyiBqb0QtgK6oJbpm)
* [A list of datasets](https://github.com/awesomedata/awesome-public-datasets#naturallanguage)

## Models and Applications
- Probalistic Graphical Model
    - Hidden Markov Model
    - Conditional Random Fields

- Topic Model
    - Latent Dirichlet Allocation[paper](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)
 
- Deep Learning Model
    - Recurrent Neuron Network
          - Seq2Seq([Tensorflow Tutorial](https://github.com/llSourcell/seq2seq_model_live/blob/master/2-seq2seq-advanced.ipynb))
          - [Machine Translation Tensorflow implement](https://github.com/tensorflow/nmt)  
          - LSTM
   - Convolutional Neuron Network
   - Attention Model
         - Overview([Chinese](https://blog.csdn.net/BVL10101111/article/details/78470716))
   - Generative Adversial Network(GAN)

## Blog and Tutorials
- [Tensorflow implement on RNN and undocumented features](http://www.wildml.com/2016/08/rnns-in-tensorflow-a-practical-guide-and-undocumented-features/)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](https://web.stanford.edu/class/cs379c/class_messages_listing/content/Artificial_Neural_Network_Technology_Tutorials/KarparthyUNREASONABLY-EFFECTIVE-RNN-15.pdf)

## Topics and Tasks
Category of areas is based on tracks in ACL 2018
### [Summerization](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Summerization)
- Model
    - Extractive
    - Generative
- Dataset
    - [CNN/DailyMail](https://github.com/JafferWilson/Process-Data-of-CNN-DailyMail)

### [Embedding](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Embedding)
- Model
    - Word2Vec
- Pre-trained embedding
    - Glove
    - word2vec

### Sentimental Analysis and Argument Mining

### Name Entity Recognition

### Tagging, Chunking, Syntax and Parsing
- Task
    - Word Segmentation
- Model
    - Hidden Markov Model(HMM)
    - Conditional Random Fields(CRFs)


### Machine Translation

### Document Analysis

### Sentence-level Semantics
 
### Word-level Semantics

### [Information Extraction and Text Mining](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Informaiton%20Extraction%20and%20Text%20Mining)
- Tasks
    - Topic Extraction
    - Sentimental Extraction
    - Aspect Extraction

### Machine Translation
- [Attention is all you need - Google and University of Toronto](https://arxiv.org/pdf/1706.03762.pdf)

### Text Generation

### Text Classification
- Task
    - Spam Classification
- Model
- Dataset
    - [Yelp Dataset](https://www.yelp.com/dataset/challenge)
    - [IMDB](https://www.imdb.com/interfaces/)

### Dialogue and Interactive Systems

### Question Answering
- Task
- Model
- Dataset
    - [CNN/DailyMail](https://cs.nyu.edu/~kcho/DMQA/)

### Resources and Evaluation

### Linguistic Theories and Cognitive Modeling

### Multilinguality
- Task
    - Code-Switching
    - Mutilingual Translation
- Model
- Dataset
    - [Linguistic Data Consortium](https://catalog.ldc.upenn.edu/) [[list](https://github.com/isi-nlp/mt_lit_lrec16/tree/master/ontology)] [[ordered by year](https://linguistics.cornell.edu/language-corpora)]
          - [CALLFRIEND Mandarin - Mainland Dialect](https://catalog.ldc.upenn.edu/LDC96S55)
          - [CALLHOME Mandarin Chinese](https://catalog.ldc.upenn.edu/LDC2008T17)
	  - [Chinese-English Name Entity List](https://catalog.ldc.upenn.edu/LDC2005T34)
    - [List of Chinese Dataset](https://github.com/Lab41/sunny-side-up/wiki/Chinese-Datasets)
    - [Cantonese Dataset](http://compling.hss.ntu.edu.sg/hkcancor/)

### [Phonology, Morphology and Word Segmentation](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Phonology%20Morphology%20and%20Word%20Segment)

### Textual Inference

### Vision, Robotics, Speech, Multimodal


## Package
- Machine Learning package
    - sci-learn
    - Tensorflow
    - Caffe2
    - Pytorch
    - MXNet
- NLTK
- gensim
- jieba
- Stanford NLP 


## 如何加入 How to contribute

如果你对本项目感兴趣，非常欢迎你加入！

- 正常参与：请直接fork、pull都可以
- 如果要上传文件：请**不要**直接上传到项目中，否则会造成git版本库过大。正确的方法是上传它的**超链接**。如果你要上传的文件本身就在网络中（如paper都会有链接），直接上传即可；如果是自己想分享的一些文件、数据等，鉴于国内网盘的情况，请按照如下方式上传：
	- (墙内)目前没有找到比较好的方式，只能通过链接，或者自己网盘的链接来做。
	- (墙外)首先在[UPLOAD](https://my.pcloud.com/#page=puplink&code=4e9Z0Vwpmfzvx0y2OqTTTMzkrRUz8q9V)直接上传（**不**需要注册账号）；上传成功后，在[DOWNLOAD](https://my.pcloud.com/publink/show?code=kZWtboZbDDVguCHGV49QkmlLliNPJRMHrFX)里找到你刚上传的文件，共享链接即可。

## 如何开始项目协同合作

[快速了解github协同工作 Learn how to collaborate through github](http://hucaihua.cn/2016/12/02/github_cooperation/)

[及时更新fork项目 Update through fork](https://jinlong.github.io/2015/10/12/syncing-a-fork/)

[如何使用git提交 How to submit in git](http://blog.csdn.net/u012150179/article/details/17172211)

[Fetch and Merge in Git](https://www.oschina.net/translate/git-fetch-and-merge?print)

#### [贡献者 Contributors](https://github.com/Nativeatom/NaturalLanguageProcessing/blob/master/Contributors.md)

