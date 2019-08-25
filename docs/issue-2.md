# 医疗数据周刊：第2期

记录每周值得分享的医疗数据科学资讯，周六发布。

欢迎投稿推荐，请[提交issue](https://github.com/youcc/weekly-cn/issues)。

![](https://riccomini.name/assets/images/2019-07-29-future-data-engineering/mathilda-khoo-HLA3TAFQuQs-unsplash.jpg)

题图：riccomini.name

## 软件

1、[More datasets for teaching data science](https://simplystatistics.org/2019/07/19/more-datasets-for-teaching-data-science-the-expanded-dslabs-package/) 

自学数据科学一大难关就是没有数据怎么办？本文介绍了 `dslabs: Data Science Labs` R 包，里面新增添了七个数据集，其中两个跟医学相关：  

* life expectancy 寿命预测

* breast cancer diagnosis 乳腺癌诊断

2、[Transforming Data](https://rcompanion.org/handbook/I_12.html)

数据转换是数据科学日常工作一部分，本文介绍了R中常用的数据转换方法，主要关于偏态分布数据的处理。

文中用到的 R 包：

* `car`

* `MASS`

* `rcompanion`

常用数据转换方法：

* square root

* cube root

* log transformation

3、[Data Formats in R](https://www.r-bloggers.com/date-formats-in-r/)

数据分析中各种数据格式的转换也是一大难点，尤其是日期相关的。本文介绍了 R 中常用的日期换为字符或数值，以及各种常用日期格式之间的转换。


## 文章

经济独立，早在退休（FIRE）运动风靡全球。该运动意味着减少开支，节约最大化，并创收投资，以投资支付日常生活。这里推荐几篇相关文章。

1、 [FIRE: financial independence, retire early](https://www.forbes.com/sites/ryanderousseau/2019/08/13/this-father-retired-when-his-child-was-15-months-old-and-just-two-years-after-hearing-about-fire/#7028995f3ccb) 

财富英文杂志推荐了九个出名的FIRE实践者博客。

2、 [如何在30岁时实现财务自由，早早退休？](https://cn.nytimes.com/style/20180905/fire-financial-independence-retire-early/) 

纽约时报中文版对FIRE运动的介绍。

3、 [Doctors With Disabilities Push For Culture Change In Medicine](https://www.npr.org/sections/health-shots/2018/08/06/635414552/doctors-with-disabilities-push-for-culture-change-in-medicine?utm_campaign=storyshare&utm_source=twitter.com&utm_medium=social) 

本文是 NPR 对 Dr. Lisa Iezzoni 的专访。Dr. Iezzoni 是哈佛医学院教授，主要研究医疗领域 Risk Adjustment （风险调整）。我会在书籍部分推荐她的专著。 

4、 [Rating the Raters: An Evaluation of Publicly Reported Hospital Quality Rating Systems](https://catalyst.nejm.org/evaluation-hospital-quality-rating-systems/) 

市面上有多种对医院医疗质量进行评估的系统及网站，方便患者就医选择。但这些系统良莠不齐, 新英格兰医学杂志对这些系统进行了对比打分，A 最高，F 最差。评分最高的是U.S. News & World Report (B)。Centers for Medicare and Medicaid Services' (CMS) Star Ratings 中等，得了C。最差的是Leapfrog (C-) 和 Healthgrades (D)。 Healthgrades是我平时挑选医院最常用的参考工具，看来以后要重新选择了。

5、 [The Future of Data Engineering](https://riccomini.name/future-data-engineering?utm_medium=email&utm_source=topic+optin&utm_campaign=awareness&utm_content=20190814+data+nl&mkt_tok=eyJpIjoiTVRsa1lUWmpOamd5TmpObSIsInQiOiJTY1FiYzRSWXFxcXJMWlJwZjZcL21seUVUS24wQUZ4UU53TWVVTllLTHJDVENRVWRkam1IR1ZLM0hwb2NyZGVcL0lZXC85aXRsSFVOcENOVTJoSzJaTGJMZE80QXBRbVFsdDJGb2tYRHpvVHh4UFNtclwvWExqXC83ZXdZUGVrcEd0ZTZUIn0%3D)

数据工程是数据科学中的一个重要环节。数据工程师是公司里负责迁移处理数据的专业人员，他们是数据科学家的好帮手。很多小公司里数据科学家也兼任了数据工程师的职责。本文介绍了数据工程师这一工作的前景。

## 书籍

1、 [Market Segmentation Analysis](http://www.marketsegmentationanalysis.org/) 

医疗行业里也需要用到市场细分，尤其是公司里。本书用R做数据分析，详细介绍了`MSA` R 包。

2、 [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)

机器学习在商业上的应用收到限制的一大原因就是黑箱效应，及机器学习产生的模型无法解释给非专业人员。本书旨在帮助怎样让机器学习模型可解释。

3、 [Risk Adjustment for Measuring Health Care Outcomes](https://books.google.com/books/about/Risk_Adjustment_for_Measuring_Health_Car.html?id=-UQ8oAEACAAJ)

Dr. Lisa Iezzoni 关于医疗领域风险调整的专著，已出到第四版。
