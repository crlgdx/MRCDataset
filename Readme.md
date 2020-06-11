# **基于预训练模型的机器阅读理解研究综述**

综述中提到的数据集及获取方式

| 数据集                                                       | 语言 | 问题数量 | 文章数量 | 问题来源 | 文章来源      | 答案类型  |
| ------------------------------------------------------------ | ---- | -------- | -------- | -------- | ------------- | --------- |
| [CNN/DM](https://cs.nyu.edu/~kcho/DMQA )                     | 英   | 1.4M     | 300K     | 人工合成 | 新闻          | 填空      |
| [CBT](http://www.thespermwhale.com/jaseweston/babi/CBTest.tgz) | 英   | 688K     | 108      | 人工合成 | 儿童读物      | 多项选择  |
| [RACE](https://www.cs.cmu.edu/~glai1/data/race/)             | 英   | 870K     | 50K      | 英语考试 | 英语考试      | 多项选择  |
| [MCTest](https://github.com/mcobzarenco/mctest)              | 英   | 2K       | 500      | 众包     | 虚假故事      | 多项选择  |
| [NewsQA](https://www.microsoft.com/en-us/research/project/newsqa-dataset/#!download) | 英   | 100K     | 10K      | 众包     | 新闻          | 抽取型    |
| [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)         | 英   | 100K     | 536      | 众包     | 百科          | 抽取型    |
| [SearchQA](https://github.com/nyu-dl/dl4ir-searchqA)         | 英   | 140K     | 6.9M     | 搜索日志 | 网络文本      | 抽取型    |
| [TrivaQA](http://nlp.cs.washington.edu/triviaqa/)            | 英   | 40K      | 660K     | 搜索日志 | 百科/网络文本 | 抽取型    |
| [NarrativeQA](https://github.com/deepmind/narrativeqa)       | 英   | 46K      | 1.5K     | 众包     | 书籍/电影     | 描述型    |
| [MS-MARCO](https://microsoft.github.io/msmarco/)             | 英   | 100K     | 200K     | 搜索日志 | 网络文本      | 描述型    |
| [DuReader](https://ai.baidu.com/broad/subordinate?dataset=dureader) | 中   | 200K     | 1M       | 搜索日志 | 网络文本      | 描述型    |
| [HLF-RC](https://github.com/ymcui/cmrc2017)                  | 中   | 100K     | 28K      | 人工合成 | 新闻/儿童故事 | 填空      |
| [CMRC 2018](https://github.com/ymcui/cmrc2018)               | 中   | 20K      | -        | 众包     | 百科          | 抽取型    |
| [DRCD](https://github.com/DRCKnowledgeTeam/DRCD)             | 中   | 30K      | 10K      | 众包     | 百科          | 抽取型    |
| [CJRC](http://cail.cipsc.org.cn/)                            | 中   | 50K      | 10K      | 人工合成 | 裁判文书      | 抽取/判断 |



注：

CJRC <http://cail.cipsc.org.cn/>  截至目前，官网可正常打开，注册已关闭，如需要数据集可尝试在官网联系工作人员

这里有 CAIL2018获取方式： <https://github.com/thunlp/CAIL>





cite at: http://cea.ceaj.org/CN/10.3778/j.issn.1002-8331.2001-0285

```
@article{MRCDataset,
  title={基于预训练模型的机器阅读理解研究综述},
  author={张超然;裘杭萍;孙毅;王中伟},
  journal={计算机工程与应用},
  year={2020}.
  {Volume}=56,
  {Pages}=17-25
}
```

