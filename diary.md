241001:
1. 决定Reinforcement learning paper presentation topic: An End-to-End Automatic Cloud Database Tuning System Using Deep Reinforcement Learning [SIGMOD'19].
2. 阅读文献综述：数据库参数配置智能调优研究综述


20241005：
1. 赶算法作业

20241006：
1. 提交算法作业
2. 成功把optiplex 3010主机装上系统

20241007:
1. 算法：学习网络流

20241008:
1. before 10:40: phone call to ask why SIN number letter not received. Because choosing wrong option when applying for SIN number. The letter will be received within 10 days.
2. submitted documents necessary for RA salary
3. algorithm assignment 3, finished 1,2,3,4 and 6.
4. qualcomm internship. check out open internships in Canada. https://careers.qualcomm.com/careers?location=Canada&seniority=Intern&domain=qualcomm.com&sort_by=relevance&pid=446702039826
- HW not applicable.
- require May 2025 to Aug 2026 available.
- requirements: math and statistics, CNN RNN transformer, Python / C++, practical project.
- spring semester in 2025: must complete the rest of the regular courses!

20241009:
1. RL作业。完成CEM

20241011:
1. Algorithms mid term
Time is too short.
2. Research discussion:
Reported conclusions on CoSQL paper. According to professor, drawbacks listed by myself are not disadvantages. Since currently we are using CoSQL primarily as a source to discover the existence of the problem. 5 questions is enough for discovery research. And he thinks 300 rows per table is good for experiment.

**First urgent things** is to: analyse data set, run baseline. literally run queries in CoSQL in MySQL or PostgreSQL in order to give a result on the execution statistics, for example, throughput, latency etc. This step simply requires SQL in CoSQL and doesn't involve NL.

The other thing need to consider in parallel is if CoSQL is not capable enough in terms of the size of the data, then we may need to consider using other data sets, like TPC-H, TPC-DS etc. The task is to convert SQL queries into dialogue. According to Professor MIAO, current research on SQL2NL are not that reliable.

He also raised some concerns that reviewers could criticise (Still no answers yet):
1. why not using apprimate query? For example, SELECT LIMIT
2. what is the difference betweeen human generated and LLM generated workload?

He also wants me to think the problem holistically: instead of NL input, BI scenarios can also be like gestures, mousing moving etc.

The main argument:
BI scenario, need to return result quickly. In chatting secario, users could tolerate more latency but in other scenarios like using BI tools, users may generate more dynamic changes and cannot put up with so much latency.
What we may need to do: pre-computation, predictions.

20241012:
1. RL AS2赶作业

20241013-20241015:
1. 安装docker
2. RL作业第二题一直不知道哪里出错了，模型就一直没有学习。需要office hour问助教。

20241015:
1. 安装postgre 12.5并初步测试sqlite导入postgre。
2. 整理online关于benchmark testing的资料。总体来说决定采用原生的pgbench来执行测试。

20241016:
1. sqlite导入postgres：走通了流程。但是有报错。需要整体跑一遍，统计多少成功了，多少失败了。然后分析失败日志，做相应修改。此外，对已成功的数据库进行初步统计分析

20241017：
1. 【待完成】：中文论文下载工具整理：
https://blog.csdn.net/2301_77413856/article/details/134202534
国家工程数字技术图书馆
各地方图书馆：https://post.smzdm.com/p/apvo2k49/
2. sqlite转postgres：
3. 存是写他们科研的本子。考虑有没有什么要买的，看怎么张口。

