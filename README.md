# MRC_Leaderboard
Machine Reading Comprehension Leaderboard Summary
## English
Dataset | Leaderboard Link|Description
---|---|---
**SQuAD 1.0 & 2.0** | https://rajpurkar.github.io/SQuAD-explorer/|Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.
**Who-Did-What** | https://tticnlp.github.io/who_did_what/leaderBoard.html|We have constructed a new "Who-did-What" dataset of over 200,000 fill-in-the-gap (cloze) multiple choice reading comprehension problems constructed from the LDC English Gigaword newswire corpus.
**MS MARCO** | http://www.msmarco.org/|Microsoft MAchine Reading COmprehension Dataset
**RACE** | http://www.qizhexie.com/data/RACE_leaderboard|The RACE dataset is a large-scale ReAding Comprehension dataset collected from English Examinations that are created for middle school and high school students.
**Movie QA**|http://movieqa.cs.toronto.edu/leaderboard/|We introduce the MovieQA dataset which aims to evaluate automatic story comprehension from both video and text.Each question comes with a set of five highly plausible answers; only one of which is correct. The questions can be answered using multiple sources of information: movie clips, plots, subtitles, and for a subset scripts and DVS.
**Hotpot QA** | https://hotpotqa.github.io/|A Dataset for Diverse, Explainable Multi-hop Question Answering.HotpotQA is a question answering dataset featuring natural, multi-hop questions, with strong supervision for supporting facts to enable more explainable question answering systems. 
**CoQA**|https://stanfordnlp.github.io/coqa/|A Conversational Question Answering Challenge.HotpotQA is a question answering dataset featuring natural, multi-hop questions, with strong supervision for supporting facts to enable more explainable question answering systems. 
**DREAM**|https://dataset.org/dream/|A Challenge Dataset and Models for Dialogue-Based Reading Comprehension.DREAM is a multiple-choice Dialogue-based REAding comprehension exaMination dataset. In contrast to existing reading comprehension datasets, DREAM is the first to focus on in-depth multi-turn multi-party dialogue understanding.
**QuAC**|http://quac.ai/|Question Answering in Context is a dataset for modeling, understanding, and participating in information seeking dialog. Data instances consist of an interactive dialog between two crowd workers: (1) a student who poses a sequence of freeform questions to learn as much as possible about a hidden Wikipedia text, and (2) a teacher who answers the questions by providing short excerpts (spans) from the text. QuAC introduces challenges not found in existing machine comprehension datasets: its questions are often more open-ended, unanswerable, or only meaningful within the dialog context.
**ReCoRD**|https://sheng-z.github.io/ReCoRD-explorer/|Reading Comprehension with Commonsense Reasoning Dataset (ReCoRD) is a large-scale reading comprehension dataset which requires commonsense reasoning. ReCoRD consists of queries automatically generated from CNN/Daily Mail news articles; the answer to each query is a text span from a summarizing passage of the corresponding news. The goal of ReCoRD is to evaluate a machine's ability of commonsense reasoning in reading comprehension. ReCoRD is pronounced as [ˈrɛkərd].
**Cosmos QA**|https://wilburone.github.io/cosmos/|Cosmos QA is a large-scale dataset of 35.6K problems that require commonsense-based reading comprehension, formulated as multiple-choice questions. It focuses on reading between the lines over a diverse collection of people's everyday narratives, asking questions concerning on the likely causes or effects of events that require reasoning beyond the exact text spans in the context.

## 中文
数据集 | 排行榜链接|数据集描述
---|---|---
**DuReader 2.0** | http://lic2019.ccf.org.cn/read|本届竞赛的机器阅读理解任务是“2018机器阅读理解技术竞赛”的延伸。任务数据集包含约28万来自百度搜索的真实问题，每个问题对应5个候选文档文本及人工整理的优质答案。数据集划分为包含27万个问题的训练集、约3000个问题的开发集和约7000个问题的测试集。
**CAIL 2019** | http://cail.cipsc.org.cn/ranking.html|本任务所使用的数据集是来自“中国裁判文书网”公开的法律文书，主要涉及民事和刑事的一审判决书，总共约1万份数据，并按比例划分训练、开发和测试。每份数据包括若干个问题，对于训练集，每个问题只包含一个标准回答，对于开发和测试集，每个问题包含3个标准回答。回答内容可以是案情片段，可以是YES或NO，也可以拒答即回答内容为空。数据格式参考SquAD2.0的数据格式，整体为json格式的数据。并增设案由"casename"字段和领域"domain"字段，"domain"字段只有"civil"和"criminal"两种类型。"context"抽取自裁判文书的案情描述或原告诉称部分。
**成语阅读理解大赛** | https://www.biendata.com/competition/idiom/ | 比赛数据中，每条数据由若干段文本和一组固定长度的候选项构成，每段文本被挖去了若干个空格（每个空格都有唯一的编号），选手需要从候选项中选出每个空的答案。注意同一条数据的文本的填空答案在词义或语境上可能是相近的。保证每一条数据中，各个空的答案互不相同。
**莱斯杯：全国第二届“军事智能机器阅读”挑战赛** | https://www.kesci.com/home/competition/5d142d8cbb14e6002c04e14a/content/0 | 本次竞赛提供的大规模中文阅读理解数据集，共包含约7万个军事类复杂问题，每个问题对应五篇文章，含推理类问题。
**CMRC2019** | https://hfl-rc.github.io/cmrc2019/task/ | 根据给定的一个叙事篇章以及若干个从篇章中抽取出的句子，参赛者需要建立模型将候选句子精准的填回原篇章中，使之成为完整的一篇文章。 与第一届中文机器阅读理解（CMRC 2017）的填空型阅读理解不同的是：空缺部分不再只是一个词，而是一个句子。每个篇章不只是一个空缺，会包含多个空缺位置，机器可利用的信息大大减少。候选选项中包含假选项，即该选项不属于篇章中任何一个空缺位置，显著增加了解答难度。


## To be continue...
