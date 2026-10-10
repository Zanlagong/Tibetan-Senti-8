# Tibetan‑Senti‑8: A multi‑category annotated dataset for Tibetan sentence‑level sentiment analysis
## Project Information
- Manuscript: Tibetan‑Senti‑8:一个面向藏文句子级情感分析的八类别标注数据集
- Dataset DOI: https://osf.io/yj9p/contibutors
- License: CC‑BY‑4.0 International
- GitHub (source code): https://github.com/Zanlagong/Tibetan-Senti-8
- Contact: Nuo Qun (email:  zlg@stu.xzu.edu.cn).

## Project content
This repository contains:
1. `/dataset`: Full Tibetan‑Senti‑8 dataset, including original full dataset and split train / val / test sets (json & txt format).
2. `/annotation_materials`: Annotation guideline document, typical confusing‑case samples appendix.
3. `/metadata`: Machine‑readable metadata json file and codebook csv.

### File list
#### dataset folder
- Tibetan‑Senti‑8.json / Tibetan‑Senti‑8.txt：Full 50000‑sentence dataset
- train.json / train.txt：training set (40000 samples)
- val.json / val.txt：validation set (5000 samples)
- test.json / test.txt：test set (5000 samples)
- Tibetan‑Senti‑8_model_test.json / Tibetan‑Senti‑8_model_test.txt：5000 samples for large‑model zero‑shot evaluation

#### annotation_materials folder
- Annotation_Guide.pdf：Complete annotation operation manual
- confusion_case_samples.pdf：Typical ambiguous & confusing annotation samples (especially for Sadness category)

#### metadata folder
- dataset_metadata.json：Machine‑readable metadata
- codebook.csv：Field‑definition codebook

## Label mapping
|label_code|label_name(chinese)|label_name(english)|
|----|----|----|
|0|乐|joy|
|1|好|good|
|2|怒|anger|
|3|哀|sadness|
|4|惧|fear|
|5|恶|disgust|
|6|惊|surprise|
|7|讽刺|irony|

## Citation
If you use this dataset, please cite:
[1]Maas, Andrew L.Daly, Raymond E.Pham, Peter T. , et al.Learning word vectors for sentiment analysis[C].//49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies, ACL-HLT 2011.2011:142-150.
[2]Pontiki, Maria,Galanis, Dimitrios,Pavlopoulos, John , et al.SemEval-2014 Task 4: Aspect Based Sentiment Analysis[C].//8th International Workshop on Semantic Evaluation, SemEval 2014 - co-located with the 25th International Conference on Computational Linguistics, COLING 2014.2014:27-35.
[3]Demszky, Dorottya,Movshovitz-Attias, Dana,Ko, Jeongwoo , et al.GoEmotions: A Dataset of Fine-Grained Emotions[C].//58th Annual Meeting of the Association-for-Computational-Linguistics (ACL).2020:4040-4054.
[4]Demszky, Dorottya,Movshovitz-Attias, Dana,Ko, Jeongwoo , et al.GoEmotions: A Dataset of Fine-Grained Emotions[C].//58th Annual Meeting of the Association-for-Computational-Linguistics (ACL).2020:4040-4054.
[5]Jiang, Qingnan,Chen, Lei,Xu, Ruifeng , et al.A Challenge Dataset and Effective Models for Aspect-Based Sentiment Analysis[C].//Conference on Empirical Methods in Natural Language Processing / 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP).2019:6280-6285.
[6]姚源林,王树伟,徐睿峰,等.面向微博文本的情绪标注语料库构建[J].中文信息学报,2014,28(5):83-91.
[7]王雨函,廖丹,梁国栋.网络社会事件评论的高频词情感语料库构建研究[J].华南理工大学学报(社会科学版),2025,27(4):143-156.DOI:10.19366/j.cnki.1009-055X.2025.04.012.
[8]魏晓聪,于澜.中文慕课评论情感识别语料库的构建与应用[J].重庆理工大学学报(自然科学),2023,37(4):174-181.
[9]赵金鑫,郭荣新,施一帆.多粒度特征融合的分层式机器学习情感分析[J].华侨大学学报(自然科学版),2026,47(2):164-174.
[10]杨洵.多任务BERT模型在校园舆情监测中的应用[J].信息记录材料,2026,27(1):108-110+126.DOI:10.16009/j.issn.1009-5624.2026.01.035.
[11]张逸民,李野.基于BERT模型的微博文本细粒度情感分析[J].现代信息科技,2026,10(4):112-115+121.DOI:10.19850/j.cnki.2096-4706.2026.04.019.
[12]张洋,胡慧君,刘茂福.基于全景语义和多层次特征融合的方面级多模态情感分析[J].计算机工程与科学,2026,48(2):341-352.
[13]曾桢,廖茂熙,杨楠,等.基于提示学习和注意力机制的多模态方面级情感分析[J].科学技术与工程,2026,26(2):708-716.
[14]冯广,刘馨婷,林忆宝,等.基于统一对齐与多阶段融合机制的多模态情感分析模型[J].计算机应用研究,2026,43(2):342-352.DOI:10.19734/j.issn.1001-3695.2025.06.0214.
[15]朱宇雷,德吉卡卓,群诺,等.基于图神经网络结合预训练模型的藏文短文本情感分析研究[J].中文信息学报,2023,37(2):71-79.
[16]才让东知,杨杰,尼玛扎西.藏文情感词典构建的现状分析[J].计算机技术与发展,2024,34(3):9-14.
[17]公确多杰,索南才让,才藏太.融合词典的BERT-BiGRU的藏语句子情感分类方法[J].计算机工程与设计,2025,46(3):918-926.DOI:10.16208/j.issn1000-7024.2025.03.037.
[18]黄晨晨,索朗拉姆,拉姆卓嘎,等.基于SVM的藏文微博文本情感分析研究与实现[J].高原科学研究,2020,4(1):92-96.DOI:10.16249/j.cnki.2096-4617.2020.01.013.
[19]周明军,李秉林,群诺,等.基于双向软模板方式提示学习的藏文文本分类[J].中文信息学报,2025,39(1):16-27.
[20]朱宇雷.基于深度学习的藏文情感分析方法研究[D].西藏大学,2023.DOI:10.27735/d.cnki.gxzdx.2023.000154.
[21]田金超,闫晓东,常浩远,等.Ti-ABSA：藏文方面级情感分析数据集[J].中国科学数据(中英文网络版),2025,10(3):523-531.

## Usage Notes
1. The texts in this dataset have been manually rewritten, rephrased and de‑identified for copyright and privacy protection.
2. Surprise and Irony have context‑dependent valence (positive / negative / neutral).
3. The sadness category has relatively lower inter‑annotator consistency; please be aware of potential annotation noise.
4. This dataset supports **sentence‑level** fine‑grained emotion classification only, not document‑level tasks.
