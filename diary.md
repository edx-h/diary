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
This can be a link to a video describing your project, your code base, your project documentation or presentation, etc.

250304-5：
984gpu project

250306-07：
把mv generation和query rewrite分开。calcite rewrite转api。后续可能还是需要研究字符串层级的sql修改以适配calcit（可以制定几个典型的fewshot让gpt写），可”操作”空间也比较大。不过还是先把llm给做好。

250308:
丢手机，提交optiql。

250309
EDIJ可以做的改造：前端，gemini改deepseek，记日志，配置搞成hydra。搞1-2个小时，主攻mv

250310-11：
10日登记手机，
11日手机找到了！
发现了新大陆！CSIL！几乎没有人使用！
llm baseline框架搭建。后续优化：无脑全怼，随机，各cluster数量，不给schema，给schema不给注解，修正语法错误mv SQL/重写（给提示/给提示+推理），各种refine的策略（比如训个learned cost estimator，那3篇论文等等）。

250312-14: 用qwen 32b跑推理模型尝试。跑静态场景下的baseline结果。

250315-16: 写scheduling paper review 

250317：部署EDIJ的RAG模型。全面end-to-end计时。

250318-19：主要是在搞RAG项目。

250320：Redshift，用UniView改写LLM MV

250321: 开会，看起来他还比较满意。

250322: 两篇paper必须完结！！！！！

250323: 搞完两篇paper。

SSH：
# Read more about SSH config files: https://linux.die.net/man/5/ssh_config
Host 10.3.10.166_dell
    HostName 10.3.10.166
    User dell

Host 10.3.10.166_starglm
    HostName 10.3.10.166
    User starglm

Host 36.103.203.203
    HostName 36.103.203.203
    User pod
    Port 34241
    ForwardAgent yes

Host 142.58.22.188
    HostName 142.58.22.188
    User xha102

Host 119.255.238.25
    HostName 119.255.238.25
    Port 61222
    User wangcunshi

Host 192.75.242.213
    HostName 192.75.242.213
    Port 222
    User dolly

Host secb1010-a12.csil.sfu.ca
    HostName secb1010-a12.csil.sfu.ca
    Port 24
    User xha102

Host secb1010-b12.csil.sfu.ca
    HostName secb1010-b12.csil.sfu.ca
    Port 24
    User xha102

Host secb1010-c12.csil.sfu.ca
    HostName secb1010-c12.csil.sfu.ca
    Port 24
    User xha102

Host 98.82.34.109
    HostName 98.82.34.109
    Port 22
    User ubuntu
    
250324:
研究导入redshift流程。刷cs 144

250325:
成功导入redshift。刷cs 144。

250326:
1. 已经确定automv生效。跑出了延迟加速。
2. UniView debug，确认就是一些表出现多次的原因。这就是UniView本身的缺陷。

250327：
1. UniView验证EX，计算acceleration ratio。2h。已完成。UniView重写的全是错的。
3. Redshift执行MV和MV sql，end-to-end 统计。2h。完成90%。等待明天统计数据。

250328：
1. 统计AutoMV加速比率（没有办法统计size大小）。1h
2. end-to-end统计。2h。重跑一遍应该不是难事。难点在于埋点。
3. 认认真真地整理笔记（几大块：1. 运行UniView的重写结果，2. 运行automv的重写结果&和redshift上运行LLM重写结果的加速比较，3. 端到端的对比结果）。
4. 开会

250329-31：
准备aurora的ppt。
0331: 证实了即使join order对齐，只要差异表格>=2，calcite就根本没有办法重写。我决定了，calcite就这样盖棺定论了！！！！！

250401:
1. 推理需要改的prompt点：
以general purpose为例：
   1. 查询22d，ON里面出现了非法子查询。导致在Redshift上卡住了。
   2. 查询12c，重写后的查询根本没有follow as后的新列名。
   3. 27a, 27b，重写后的查询on字段不匹配。
2. 基本redshift完成了任务（90/100）。
3. present aurora

250402：
1. 彻底完成redshift。要求：组合新的自动化灌入数据的脚本。
2. 一些发现：
   2.1 有几个(如27a, 27b)查询在pg因为类型转换而无法被执行，放到redshift就可以被执行。可能做了自动的类型转换。
   2.2 相当一部分（五六十个查询，原始SQL本身在PG/rs的执行结果就不一样！）这是在使用pg查出来的结果作为标答，计算EX的时候发现的问题。因此必须要规范好流程：先在云上跑一份标准答案数据然后做持久化存储。
3. 大致整理好了框架。

250403：
塞肉！

250404：
开会

250405：
整天购物

250406-07：
project收尾

250409-11:
写project报告

250412：
算是有重大进展吧。翻到了presto的源代码。至此，最好的情况下，除去LLM有6个rewrite的benchmark。本周的任务：完成query rewrite和execution! 

250413:
完成了presto的部署和功能测试。
部署方式：抄单测。纯java交互。后续会封装成api。
功能测试：
证实：功能非常弱。支持查询被多个MV重写，但是一个mv必须只能包含一个relation。即不支持具有多表join的mv的重写！而且，必须要显式的，以子查询的方式“提示”presto，presto才知道可以重写。
formatsql函数好像也有问题。不会自动生成alias。

250414:
又有重大发现：doris, **hive**也支持query rewrite。今天完成了doris和starrocks的初步测试。doris还提供无法重写的原因具体分析。
maxcompute: https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/download%2Fpdf%2F27990%2FDevelopment_intl_en-US.pdf#page=180.13
celerdb好像甚至支持recommendation。
argument：要经过溯源、套壳分析（例如celerdb就是基于starrocks的）

250415:
数据导入工作流基本完成。但是发现starrocks导入特别的慢。后续解决方案：抛弃insert into, 调参，切到云机器再试。

250416:
doris, starrocks数据确认成功导入库中。
重写, execution流程融入到doris（1/2）

250417：
代码正式支持了doris上auto rewrite。不过看又是一个重写的都没有。而且延迟居然还上升了。

250418：
写代码，判断被重写的个数。
调节这些rewrite开关再试一波。https://doris.apache.org/zh-CN/docs/dev/query-acceleration/materialized-view/async-materialized-view/functions-and-demands#%E7%9B%B8%E5%85%B3%E9%85%8D%E7%BD%AE
调整sql格式，探索没有被重写的原因。
现有逻辑把starrocks集成
开会

250419：
没干活

250420：
完成了hive的”数据导入“和建表

250421:
规划模块化方案。

250422:
实现了部分basic data structure

250423-25：陷入迷茫中。推进的不顺利。主要是未来的活太多了。要硬碰硬了。
开会过后确定：必须坚持现在的路线。充分解耦candidate generation和recommendation。再加上rewrite功能。
光环云配置好了postgres。测通了解决readline的一个路线（参考deepseek的回答）：conda安装conda install -c conda-forge readline，然后执行python脚本python -c "import readline; print(readline.__file__)"查看文件路径。把路径添加到./config中。./configure \
  --prefix=$(pwd) \
  --enable-cassert \
  --enable-debug \
  --with-includes=$CONDA_PREFIX/include \
  --with-libraries=$CONDA_PREFIX/lib

这样成功把pg安装到了sfu和cas的机器上！

250426-27：
gpt pro用着就是顺手。基本已经快把bigsubs和yang 1997的mv enumerator搞完了。

250428：
大选，vancouver island。

250429：
uniview在enumerator方面的改造。引入更多candidates。part I。增加了selectivity。重点：是否允许谓词膨胀。发现uniview确实还是有规则上的缺陷，比如谓词矛盾等。

250430：
必须完成uniview的扩展。包含：max join, 收益测算的（高频低收益，低频高收益）和剩余的selectivity问题。
实际上：累了，该做了了解了。selectivity和benefit应该改都开发完了。

250501 （周四）：
回忆，应该是在继续写代码吧

250502：
开会。认识了andy。启动了gpu项目。

250503：去NNM

250504：专注于gpu项目。确定了挑选任务的维度框架（包含调用频率、任务目的、修改代码的程度）；找了一批AI4DB的literature review；找了一波相关的工作组。

250505：
选workload

250506:
精读了一半llumnix。cosql迁移zhisuan平台

250507：
开GPU的会。

250508：
听waterloo大牛的讲座。把mlflow引入mv项目。

250509:
把mlflow引入mv项目，实践成功。

250510：
wrap up enumerator。具体任务：把uniview对齐到canonical plan。先得出一些描述性指标。同时总结cost model。
宝藏网站：lens, openalex, 国外硕博论文：proquest, ndltd

250511:
改bigsubs代码

250512:
厘清uniview的适配逻辑

250513：
改造uniview

250515-18:
时间全都浪费在TA上了

250519:
uniview get candidate正式完结
分析静态场景可能的组合以及难度评估
本周里程碑：静态场景，不交叉情况下information collection模块 和 recommendation模块代码要写完
交叉
动态交叉不交叉*2周。即6月20号代码开发应该全部完成。
策略必须是先把非交叉情况下搞定。要有保底。

250520-21：实现bigsubs。
冒出了一个新的，严重问题：候选集出现了很多笛卡尔积。要把这个问题给解决。

250522:
看起来无论secb还是tianzheng的机器，装docker就不要想了。不过也可以有workaround: 非rewrite的阶段，全都不涉及docker。只有rewrite的时候再搬回142机器执行。总之问题不大，绝不是耽误科研进程的借口。
决定了，下个月从gpt pro改为以下组合：gpt pro -> gpt plus, 新增claude 5* max. 原本含税价格从CAD 313降至CAD 188。节省40%费用。 

250523:
花了好几个小时，发现引导chatgpt改代码的方法不太好。

背景：
需要对candidate enumerator做全面检修。问题有很多：隐式join写法（需要改为显式join），笛卡尔积（需要将其转为带谓词的join）。优化canonicalplan，来做合并去重。

现状：
1. yang1997: 
- 输出字段：只有min。可能之后要去除掉min
- phiJ：全部为空。需要从phiS中提取涉及id相关的放到J
- 笛卡尔积问题（最重要的问题）：存在
- 隐式join：存在
- 语法错误：存在（大概占到20%左右）
    - 输出字段涉及到的表在R中根本不存在（1265-86）
- 可被重写潜力判断错误（重要的问题）：存在
    - 1265-86（33c）。物化视图多引入了不在原始Sql中的表
- 枚举充分性：

2. bigsubs
- 输出字段：*最多，也有min
- phiJ：提取正确。
- 笛卡尔积问题：应该不存在
- 隐式join：不存在
- 语法错误：
    - *肯定不存在。但是需要自己去显式列出字段名。对于min，也不存在yang1997一样的问题
- 可被重写潜力判断错误：不存在
- 枚举多样性：有带有过滤谓词的

3. uniview
- 输出字段：显示列出了每一个字段。一个min也没有
- phiJ: 和yang 1997一样。
- 笛卡尔积问题：应该不存在
- 隐式join：存在
- 语法错误：之前测试过。uniview会存在
- 可被重写潜力判断错误：存在。比如372-86。不知道为什么和uniview一样，都是有cast_info。
- 枚举多样性：有带有过滤谓词的。

总体评价：
bigsubs简直要比yang 1997实现好的太多太多，目前看是最好的。
uniview至少不存在笛卡尔积问题，倒是可以继续跑。

下一步的策略：
1. 针对yang 1997，以下解决方案：
    - 用例子喂给chatgpt让他修改。
    - or 根据bigsubs退化。同时著名要求
    - 比较之前实现两版本的提示词。高度怀疑yang 1997用的是逗号连接的数据
2. 24号：搭建好bigsubs的推荐层。注意要评估并且支持把*转为表名+列名的格式。25号：联通各阶段。

250524:
在real_size, real_latency都是false的情况下，把bigsubs的information collection给跑通了。重要的进展：过滤了>4张表的查询；测度cost_to_sec的时候，采用了更快捷的分层抽样+并行的方式。

250525：
实现bigsubs的recommendation。已经完成了。ilp vs bigsubs，实际上ilp是精确但是慢的，适合小规模。bigsubs适合大规模速度快但是只是近似。我们的场景只用bigsubs即可。所以相当于bigsubs全链路都已经弄完了！

250526：
成功安装了starrocks, doris。尝试了hive，但是装不上。之后再试试吧。先放了。
确定了本学期的组会时间：周三组会，周五两个小会。
本周预期目标：mv串通出结果；gpu有基本的benchmark结果。都不是很艰巨的任务。

联通rewrite

250527:
用原始查询压测了一下starrocks。除了三个小问题要修改（priority port导致backend重启失败，replication num, 关键字加引号），没有其他的问题（比如运行时的崩溃）。

250528:
1. mv：就差临门一脚recommend了
2. gpu: 算是磕磕绊绊把环境装完了。明天还需要重新过一遍。
3. 决定了：申请下一周专门搞定rewrite。明天好好整理已经做完的东西，设计好指标。

250529：
迈开了艰难地走通athena环境的第一步。

250530：
开会

250531：
基本上算是玩了一天吧。

250601:
expectation:
读athena的paper
做ppt √

250602:
浏览本周ppt √
mv: rewriter开了个头。我决定本周就一心一意搞rewriting。每日安排：截止二：完成migrator和rewriter。截止三：完成evaluator.周四还得干gpu的活呢。

250603：
进行rewriting

250604：
开组会。必须把rewriting完成！！！！！

250605-06：
rewriting已经取得了重大进展。

250607：
买鞋，costco，取jellycat玩具

250608:
学了一些杂七杂八的东西

250609：
本周规划：
mv：静态结束。测通doris, presto, hive。evaluator。
gpu: 跑通athena仓库。

250610：
决定对rewrite重构一下。主要是并行物化和多种计算benefit和排序的方式。

250611：
专门干gpu的事情。

250612-17：
效率极低。不知道在干什么。判作业、学binary analsis，做sync meeting

250618：
决定新抽象出一个pruner类，负责后续可能引入的排序。以及，决定把物化测size的流程直接提前到mv candidate enumerator。超时了的直接drop。但是最后一定要删除！
还要排查一个问题，为什么7张表的join还会被推荐为true

250619：
GPU临时抱佛脚

250620：
开会

250621-22：
庆生、判作业

250623-25:
cosql优化：MV测度提前到stage_summary执行，hive物化视图功能测通。
gpu安装nsys

250626:
基本测通了hive。

250627：
开会。

250628：
整整一天判作业。基本判完了。

250629：
一次排查问题的典范。解决了hive max counter的问题。先自己试了一堆调优语句（通过cursor execute执行），发现好像不行。换成pyhive connection建立时configuration配置，还是没有生效。另一方面问chatgpt找到了日志路径：/tmp/hive/hive.log。进而确定根源就是counter的问题。最终问chatgpt确定了应当在xml配置文件就配置好max counter。
增加完counter数目后，错误query数从75降到了55个。剩下的大头问题：broken pipe。unexpected exception。

250630:
进一步调优。初步测试，回归到只增加memory size。但是还是效果不太好。有的SQL就被卡住了。
最终解决方案：
要么提取SQL直接在PG上执行（preferred），要么搞2个容器。分别执行各自能执行的SQL。

250701:
颇有收获。解决了之前发现的bigsubs已经被drop掉的仍然被推荐的问题（索引问题），并且把hvie rewritten sql集成到postgres执行（只是开发完了代码）。
目前仍然未准备好的：
rewriter: presto, doris, automv, calcite
枚举器：测通autoview
信息收集和推荐：autoview, yang 1997
本周计划：给出一个全链路结果模板（要设计好指标）。整理出所有能做的实验。写好自动化运行的脚本。且不急于拓展大规模运行。

250702:
初步走通了用nsys benchmark程序。还需要进一步学习如何看图。
mv: 整理好了metric框架。todo: 重要紧急那几个predicate统计；并行化改造，以支持后续快速massively running experiment

250703：
benchmark hive

250704:
开会*2。装mongo docker env

250705:
干一天的家务（洗衣服、退货）。给大andy跑mv

250706：
初步分析a3 autograding；找到了一篇关于gpu profiling的宝藏研究论文。确定使用nvml和dcgm。

