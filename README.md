# MRC_Leadboard
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

## 中文
数据集 | 排行榜链接|数据集描述
---|---|---
**DuReader 2.0** | http://lic2019.ccf.org.cn/read|本届竞赛的机器阅读理解任务是“2018机器阅读理解技术竞赛”的延伸。任务数据集包含约28万来自百度搜索的真实问题，每个问题对应5个候选文档文本及人工整理的优质答案。数据集划分为包含27万个问题的训练集、约3000个问题的开发集和约7000个问题的测试集。
**CAIL 2019** | http://cail.cipsc.org.cn/ranking.html|本任务所使用的数据集是来自“中国裁判文书网”公开的法律文书，主要涉及民事和刑事的一审判决书，总共约1万份数据，并按比例划分训练、开发和测试。每份数据包括若干个问题，对于训练集，每个问题只包含一个标准回答，对于开发和测试集，每个问题包含3个标准回答。回答内容可以是案情片段，可以是YES或NO，也可以拒答即回答内容为空。数据格式参考SquAD2.0的数据格式，整体为json格式的数据。并增设案由"casename"字段和领域"domain"字段，"domain"字段只有"civil"和"criminal"两种类型。"context"抽取自裁判文书的案情描述或原告诉称部分。

## To be continue...
