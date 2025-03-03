1
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
4. 写RL project proposal. 

20241018：
1. 写RL project proposal
2. 收到新主机
3. RL作业管欣怡要了代码。发现是没有加一个上下文管理器。

20241019:
1. 资源：OEIS latex notation。包含各类数学符号的latex语法。
2. 写算法作业。

20241020:
1. 写并提交算法作业
2. 完善并提交RL proposal
3. RL AS2放到了天文台组的集群。模型改成了1024。待观察效果。

20241021:
1. pgloader导数据，python脚本顺序执行SQL查询。总体看来延迟非常小。数据size也非常小。
2. 开会笔记：sql->
pair to generate dialogue.
pipeline

human generated dialogue
compare any difference

enlarge data size can have same values.

whether materialisation will work.

literature:
existing works
starightforward way to reuse.

if no improvements, then just show discovery.

implementations:
LLM需要知道并重写
feedback LLM需要能够感知，并且rewrite。

3. 申请jetbrains的license
4. 回复奖学金签名
5. 做rl presentation的beamer。

20241022:
1. 每日科研：别忘了pre computation。
2. 每日学习：熵、散度解决的问题
3. RL paper presentation：读paper，模型基本搞懂，尤其是reward function的设计。ppt模型部分的框架已经基本搭建出来。
   
20241023：
1. RL AS3作业：代码编写完毕，又是在查为什么没有learning的问题。

20241024：
算法作业

20241025:
算法作业

20241026：
1. IDEBench paper中，normalized的含义并不是正规化，而是标准化。建立事实表，维度表这样的标准模型！

20241027：
查询计划

20241028：
算法作业
讨论

20241029：
算法作业

20241030：
准备RL paper presentation

20241031:
基本啥事都没干。给zhengjie过生日

20241101:
rl present。基本啥事都没干

20241102:
观察rl 第三次作业训练情况。能确定代码没有问题，训练正常了。
pytorch过了前三章
video database的paper：读了dove db

20241103：
有了video database的思绪
pytorch 图像chapter 4

20241104：
部署rust book
完结pytorch图像chapter 4

20241105:
pytorch图像chapter 5一半
扩增数据offset方法基本完成

20241106:
给出了pets_1，materialized view处理后的基本结果
pytorch RNN开头

20241107：
复习算法
决定AS5抄答案

20241108&09&10:
算法作业

20241111：
research: 给出voter_2的结果。update通知教授

20241112:
捣鼓了一天的pycharm。测通了github上一个开源的RL project源码库。

20241113:
找到了有用的资料。新想法：multi-agent+query rewrite w/ 物化视图

20241114:
pytorch convolution部分 完结
sfu的远程desktop配置rust go
开组会
metagpt+llama部署

20241115:
反馈dialogue, turn的统计问题：证实自己统计的没有错误。原因已经写在notes上
统计了一些杂项指标：例如turn>=4的dialogue的个数，按照db_name汇总。结果比较客观。
进一步明确研究思路。

20241116：
又是没有效率的一天。不过把deepseek的key刷了一遍。

20241117：
又是他妈屁事没敢的一天。ray框架初步学习

20241118：
大概摸清项目结构

20241119：
实际SQL根本执行不了。
已经跑好了箱形图。
目前准备把前后SQL的PG cost跑一遍

20241120：
终于跑上了latency。希望明天是最后一天。

20241121：
project算是潦潦草草地做完了吧

20241122：
龟速做了一道题
看了下rl其他组做的project. 倒是都挺像模像样。

20241123：
做了三道题。。。抄答案。。。其中有一道随机算法题真是费了牛劲。
朋友圈丹华分享去朋友实验室，意识到社交圈的重要性
母通话。天真让我找实习，还去问顾江。

20241124:
终于有一天干科研的事情。
又调查了一下idebench。

20241125:
讨论。笔记put down到了goolge notes上。
今天终于接了一次电话。终于搞清楚了为什么接到了很多电话。之前的机主也是个程序员，在今年3月份在vansky上post了一个求职信息。很巧，这个人也是个程序员，还有8年华为中央研究院的工作经历。不过想了一下，现在根本就不是找实习的时候。专注于科研！！！！！

20241126：
RL ppt

20241127：
RL pre
算法作业

20241128:
提交算法作业
RL project report，考虑能否ai代笔。
初步学习hydra，回顾prompt engineering。从李瑀旸的分享中得知了internet of agents。这个可以自己组队什么的。考虑尝试。
关于研究：测试让agent自动生成prompt。
发现了一本不错的书，概率图。有向图模型（贝叶斯网），无向图模型（马尔科夫网）

20241129：
初步应用autogen和prompt。RL project

20241130:
RL project report
谷歌开发者burnaby会议

20241201:
找到了免费电子书阅读资源：https://online.anyflip.com/tsehh/icxx/mobile/index.html和https://zh.z-lib.gs/
RL project终于做完了。

20241202：
数据合成I

20241203：
数据合成II

241204：
数据合成III

241205-07：
更新内容放到personal_notes了

241208：
学习calcite

241209：
开会

241210：
数据合成SDV

241212-13:
已经更新到了笔记中

20241214:
屁事没干

20241215：
解决了字符串偏移的问题。

20241216：
准备考试

20241217：
考试

20241218：
开会

20241219:
学习calcite。效率很低。

20241220:
学习calcite，算是有了一些些心得。准备开始实践。

20241221:
在chatgpt和单测的帮助下，算是从0-1突破了calcite的schema，并且打印每张表，每行的记录。

20241222:
掌握通过calciteConnection查询jdbc数据。
掌握通过planner把sql转换成relnode。
判断是否可以物化的框架搭起来了，但是估计还需要调整细节。目前没有办法正确返回结果。

20241223:
擦屁股。36机器的磁盘满了。先把自己的东西腾出去。pg_dump -h localhost -p 5432 -U pod -n public -F c -b -f /tmp/department_store_syn.dump assets_maintenance_syn
终于测通重写流程。剩下的就是集成+规模运行了！开干！

20241224:
完成批量运行重写的准备工作（python部分）

20241225：
学习go rust

241226-27：
搭calcite rewrite骨架

241228-29：
先统计数据：关键指标&完整的csv文件；修复能够通过硬编码规则程序明显能解决的缺陷；走通测试框架，统计数据

241230:
流程走通并开会。todo: 
1. 用gpt生成mv，目前deepseek推理时间太长（avg 10s/turn）。推测可能和网络延迟有关。
- 看到所有 or turn by turn。如果turn by turn效果非常差，则需要考虑train（holistically review） + test（turn by turn）。
3. calcite自动生成mv作为baseline。有余力的话做uniview。
4. 修复各种bug: 无法rewrite（修改rule set）, rewrite报错，ex低（有些列没有被裁减）
5. 读paper，确认mv creation time是否有被计入cost function or not。

241231:
calcite作为baseline的解决方案基本梳理完成：autolattice已经实现。TODO: 注册lattice到schemaplus，把evolve, statisticprovider, rules全都注册到configbuilder上。

250101-0103：
把lattice注册到schema上。自动生成tile。

250104：
总算把rewrite给搞定了。解决方案：calcite根本不存在显式的接口来用物化视图重写。而是必须走explain query->生成执行计划->生成relnode->生成sql的方式。

250105：
重构lattice部分代码。进度：50%完成。

250106-07：
屁事没干。不过读了一下C-Store。

250108：
关键词：裸金属、无栈协程
项目又迁移回36。

250109-0110:
又是赶工的两天。短期目标：尽全力在两周以内完结cosql数据！绝对不能再做无谓的纠缠了！！！

250111-12:
读c-store，写ppt...

250113:
学习2PL--主要是为了调度的冲突可串行化.
2PC--为了确定分布式事务的提交
写ppt
制定本周research规划：大体上要完成cosql baseline 动态（独立+依赖）
弄好数据合成任务（1h）
修改单表不能重写bug（2h）
把目前独立的代码改为依赖的代码（3h）


250114：
写paper review，讲c-store。完成.
基本搞定数据合成和单表重写bug代码开发。

250115：
了解基本压缩技术。目前锚定snappy。
成功修复calcite bug
规划对话依赖修改：文件夹随机排序函数；删除物化视图函数挪位置。

250117：
开会汇报

250118-19：
读paper，考察gpu rmm的可能性。

250120:
把cpp, cuda的基本环境配置了一下。算是完成了。

250121:
决定将重心转移至TPC和JOB。因为cosql数据集质量比较差。到时候写文章做argue。为此我们才不得不根据已有数据集新建dialogue对话。
发现另外一个问题：如何selection。可能需要比较postgres cost function和一些learned cardinalities模型。需要看literature review（比如国梁的文献综述，找几个具有代表性的cardinality optimizer用上）。以及uniview。
明日：
集中calcite-baseline。todo: 1. 测试数据落地函数，2. 编写记录size函数，3. 编写integer programming函数，4. 编写execution time benefit计算的函数（一定是来自postgres的optimizer，即一定是estimated），4. 在job, cosql上测试不同size threshold的效果。
limit的问题：后续可以慢慢解决。不过现在是完全有理由先手动改成正确的SQL。

250122：
calcite基本调试完毕。待测

250123：
200k cosql运行完毕
今日目标：JOB运行完毕。JOB发现了问题：1. 多表连接瞎几把join; 2. 多表引发的on字段排布不等价。初步方案：只要表的数目一样，直接把mv的from表部分 和 where on部分直接照搬到原sql。这样应该就能重写了。路线：把where涉及on的部分全部删除。然后整体把新的from替换到旧的from。

250124：开会

250125: 看论文。效率很低

250126: 
计划明日：线性规划做了结。JOB数据集 calcite重写做了结

250127:
基本把JOB数据集的替换工作做完了。逼的没办法，一个一个试。

250128：
屁事没干

250129-30:
纯calcite基本应该能算完结了。发现了dremio的reflection。可能可以作为一个benchmark

250131：
开会汇报

250201：
学习arrow想idea

250202：
写一篇review

250203：
写另一篇review。基本完成project idea构思

250204：
写proposal

250205:
研究uniview

250206：
先给出一版数据。静态，对话依赖。用整数线性规划给出各个space capacity情况下的推荐物化视图，加速比。一定要注意考虑ex！！！！！至于动态，后续可能需要用到rl框架来预测cost。
会后，思考了很多。当务之急是自己要闯出一些名堂来。就拿gpu这个project作为抓手。memory, persistent-memory。

250207：
写一个review

250208:
基本确定了JOB生成NL question的思路。明天开干！！！

250209：
prompt基本写好

250210：
基本确定了project要做啥。group by和连接 

250211：
学多线程

250212:
改prompt

250213:
真正开始实测prompt。

250214:
写代码，提取NL信息。肉眼过NL信息。开会。
千万不要再纠缠细节了！！！！！

250215：
配置cuda环境

250216：
过数据集，初步学习cmake

250217:
决定自己实现一版拼接的NL。修改mv推荐workflow(1/2)。

250218（周二）:
修改mv推荐workflow（2/2）。主要任务：修改prompt（添加schema, 输出rewrite sql）。

250219（周三）：测试并把ex计算融入评价模型中。
后续：可能涉及到calcite融入重写，不加nl情况，uniview数据剔除ex错误的情况，实现自己那一版的NL比较结果。

250220：得到baseline result

250221：开会

250222：
写paper review

250223：
读论文

250224：
搞了下gpu，又读了篇paper

250225-26：
搭建静态workflow, 写prompt

250227：
必须正式测流程！！！！！

250228:
开会。效果不太好。要继续静态
读b link tree的paper

250301：
做ppt，完成另一篇paper的review
收拾心情。
设置了auto deposit, health care的auto pay

250302：
总算做完了ppt。决定参加ED I J项目。读paper

250303:
跑通了truthscope。计划：改前端为gradio。写proposal。

1. 把JOB数据集拆成多个对话
2. 并行运行JOB数据集calcite benchmark
3. 线性规划


后日：IP。

queryexecutor，todos，正式全量

别忘记发关于connect google的邮件！
和差旅报销！

必须完结。
