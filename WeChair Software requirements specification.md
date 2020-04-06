
<p align=center><font size=10><strong>WeChair</strong></font></p>
<p align=center><font size=10>软件需求规格说明书</font></p><br/>
<div align=center><img width="100" height="100" src="https://github.com/irvingming11/WeChair/raw/master/WeChair.jpg?raw=true" /></div><br/><br/>
<p align=center><font size=5>所属学院：<u>福州大学至诚学院</u></font></p>
<p align=center><font size=5>团队名称：<u>WeChair</u></font></p>
<p align=center><font size=5>指导老师：<u>张栋</u></font></p>
<h2 align="center">目录</h2>
<div>
<br><a style="font-size:18px" >第一章 引言</a>
<br><a style="font-size:16px" >  1.1 编写目的</a>
<br><a style="font-size:16px" >  1.2 预期读者</a>
<br><a style="font-size:16px" >  1.3 项目背景</a>
<br><a style="font-size:16px" >  1.4 参考资料</a>
<br><a style="font-size:18px" >第二章 系统说明</a>
<br><a style="font-size:16px" >  2.1 产品描述</a>
<br><a style="font-size:16px" >  2.2 产品功能</a>
<br><a style="font-size:14px" >    2.2.1 活动图</a>
<br><a style="font-size:14px" >    2.2.2 类图 </a>
<br><a style="font-size:14px" >    2.2.3 主要功能说明 </a>  
<br><a style="font-size:16px" >  2.3 用户特点</a>
<br><a style="font-size:14px" >    2.3.1 用户群体 </a>
<br><a style="font-size:14px" >    2.3.1 典型用户场景 </a>  
<br><a style="font-size:16px" >  2.4 一般约束</a>
<br><a style="font-size:16px" >  2.5 假设和依赖</a>
<br><a style="font-size:18px" >第三章 功能性需求</a>
<br><a style="font-size:16px" >  3.1 界面原型</a>     
<br><a style="font-size:16px" >  3.2 硬件接口</a>
<br><a style="font-size:16px" >  3.3 软件接口</a>
<br><a style="font-size:16px" >  3.4 通信接口</a>
<br><a style="font-size:18px" >第四章 非功能性需求</a>    
<br><a style="font-size:16px" >  4.1 性能需求</a> 
<br><a style="font-size:14px" >    4.1.1个人信息精度(学生)</a>
<br><a style="font-size:14px" >    4.1.2个人信息精度(管理员)</a>
<br><a style="font-size:14px" >    4.1.3座位信息精度(图书馆)</a>
<br><a style="font-size:14px" >    4.1.4分享信息精度</a>
<br><a style="font-size:14px" >    4.1.5学习时长及排行榜精度</a>
<br><a style="font-size:16px" >  4.2 软件属性</a> 
<br><a style="font-size:14px" >    4.2.1 可靠性</a>
<br><a style="font-size:14px" >    4.2.2 可用性</a>
<br><a style="font-size:14px" >    4.2.3 安全保密性</a>
<br><a style="font-size:14px" >    4.2.4 可维护性</a>
<br><a style="font-size:18px" >第五章 验收验证标准</a>
<br>
</div>

<p align=center><b><font size=7>第一章&emsp;引言</font></b></p>
<p><font size=6><b>1.1编写目的</b></font></p>
<p><font size=4>&emsp;&emsp;为准确描述软件定位，明确软件需求，减少开发工作以及便于软件升级和产品转移撰写本文档。本篇软件规格说明书详细描述了“WeChair”这一小程序的用户需求、软件规格等内容。方便用户深入了解该小程序。同时也是开发者进行开发、测试以及软件验收的主要依据。</font></p>
<p><span><font size=6><b>1.2预期读者</b></font></span></p>
<ul>
  <li><p><font size=4>项目经理：项目经理可以根据本文档了解产品的实现预期以及产品的诸多细节，便于进行项目管理。</font></p></li>
  <li><p><font size=4>设计员：根据软件的需求有 针对性地设计出各种框架，其中包括数据库设计、WeUI界面设计等等</font></p></li>
  <li><p><font size=4>程序员：程序员可以根据本文档详细阐述的软件功能进行小程序开发编码。</font></p></li>
  <li><p><font size=4>测试员：测试员可以通过本文档阐述功能描述进行功能测试、接口测试以及各种细节。</font></p></li>
  <li><p><font size=4>用户：用户可以根据本文档了解产品的出发点以及小程序的功能，有助于用户确定该小程序是否满足其需求以及是否达到预期效果。协助用户与开发着更好地协商讨论，</font></p></li>
</ul>
<p><font size=4>&emsp;&emsp;本文档用于指导小程序开发者与软件工程实践课程中开发小程序项目的过程。通过规范小程序项目承担团队开发过程达到提高小程序质量、降低维护成本的目的。在阅读本文档时，首先要了解产品的功能概貌，然后可以根据自身的需要对每一功能进行适当的了解。</font></p>
<p><span><font size=6><b>1.3项目背景</b></font></span></p>
<p>&emsp;&emsp;<font size=4>小程序名称：WeChair</font></p>
<p>&emsp;&emsp;<font size=4>开发者：福州大学至诚学院2017级综合实验班软件工程实践“WeChair小组”</font></p>
<p>&emsp;&emsp;<font size=4>本项目初期通过问卷对用户需求进行调查，详细了解了潜在用户的需求，从用户需求以及当前市场上产品存在的用户痛点出发，在小组内部分析和讨论之后，确定了小程序的定位和主要功能。WeChair面对的用户是经常出入学校图书馆的学生，结合软件即服务的思维，旨在通过WeChair给经常进出图书馆的学生提供图书馆的优质服务。用户能随时随地了解图书馆座位分布情况，实时预订图书馆座位享受方便快捷的服务，座位分配问题得到合理优化。用户还可通过WeChair分享自己与图书馆之间的故事，留下自己的故事给别人带来激励和慰藉，同时在图书馆的学习时间会根据用户需要进行排名，达到利用人性心理的竞争性引导大家积极学习的效果。</font></p>
<p><span><font size=6><b>1.4参考资料</b></font></span></p>
<p>&emsp;&emsp;<font size=4>[1]《GB9385-2008 计算机软件需求规格说明规范》</font></p>
<p>&emsp;&emsp;<font size=4>[2]《GB9385-2008 计算机软件测试文档编制规范》</font></p>
<p>&emsp;&emsp;<font size=4>[3]《构建之法》第三版 作者：邹欣</font></p><br/><br/><br/><br/>


<p align=center><b><font size=7>第二章&emsp;系统说明</font></b></p>
<p><font size=6><b>2.1产品描述</b></font></p>
<p>&emsp;&emsp;<font size=4>WeChair体现软件即服务的思想，通过WeChair小程序给用户提供服务。旨在让图书馆灵活化，用户使用图书馆座位的方式人性化，行走的图书馆--无论你身处何地何时，都能利用我们的WeChair小程序，了解到图书馆内的座位使用情况，座位跟用户之间有了交互。用户能实时获取每个座位使用信息并预约座位，每个座位能记录用户的学习时长，同时用户在WeChair小程序上还能聆听或分享属于自己跟图书馆的故事，在我们WeChair提供的服务下，希望能让用户更享受图书馆、更享受学习。
</font></p>
<p><font size=6><b>2.2产品功能</b></font></p>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.2.1活动图</b></font></p>
<div align=center><img width="600" height="700" src="https://github.com/yuwenjin-king/WeChair/raw/master/%E6%B4%BB%E5%8A%A8%E5%9B%BE.png?raw=true" /></div><br/><br/>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.2.2类图</b></font></p>
<div align=center><img width="600" height="700" src="https://github.com/yuwenjin-king/WeChair/raw/master/%E7%B1%BB%E5%9B%BE.jpg?raw=true" /></div><br/><br/>


<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.2.3主要功能说明</b></font></p>

序号|功能名称|功能需求标识|优先级|简要解释
:--:|:--:|:--:|:--:|:--:|
1|预约座位|L1|高|本产品的核心之一，用户可以在手机上预约座位
2|扫码上座|L2|高|本产品的核心之一，用户可以扫码上座
3|时间沙漏|L5|中|记录用户在图书馆每周每月学习曲线
4|故事分享|L7|低|用户可以分享有趣的故事
5|自动下座|L3|高|系统会根据手机定位判定用户是否离开座位
6|学习时长排行|L3|中|对用户学习时长进行每日每周排行

<p><font size=6><b>2.3用户特点</b></font></p>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.3.1用户群体</b></font></p>

- 自主学习能力
- 组队学习人群
- 爱好阅读人群
- 其他人群

<p><font size=5><b>2.3.2典型用户场景</b></font></p>

姓名|学生甲
:--:|:--|
性别|男
职业|大三
目的、动机|喜欢在空闲时间阅读各类书籍
困难|经常去图书馆没有找到座位
典型场景	|甲想要去图书馆阅读书籍，但是又怕图书馆没有座位白跑一趟
用户定位	|本产品的核心功能为提供座位管理服务，可以让你随时随地在手机上都能看到图书馆座位的使用情况并对空座位进行预约

姓名|学生乙
:--:|:--|
性别|女
职业|大二
目的、动机|喜欢在图书馆自习
困难|有时候中途有事离开一下，回来后位置被他人使用了
典型场景|乙在图书馆写作业的时候，辅导员临时找她有事情，于是离开了图书馆，回来的时候就发现座位被别人坐了
用户定位|本产品还提供用户定位服务，根据你的定位，当你离开图书馆50米超过20分钟后系统会给您发信息提示，30分钟后如果你还未回到座位，系统会将你自动下座

姓名|老师丙
:--:|:--|
性别|男
职业|教师
目的、动机|偶尔需要去图书馆查阅教学资料
困难|有时候在图书馆查找资料时，不知道哪里有空座位可以坐下来
典型场景	|丙在找到一本教学资料后，在图书馆中到处寻找空座位，这一过程浪费了很多时间
用户定位	|本产品提供查看座位功能，用户可以通过手机清晰看到图书馆各个地方的座位分布以及状态

<p><font size=6><b>2.4一般约束</b></font></p>


* <font size=4>项目开发经验约束:组员都是大三的在校生，缺乏项目开发实战经验，所以此次是一个边学边做的过程
* 管理约束:每个人都有不同的想法，在做项目的过程中，当组长分配好任务后，组员间需要经过一定时间的磨合，对于组员和组长都是考验，同时遇到难题时，组长需要及时进行决策，调整方案，在组员的相互配合下完成好项目
* 技术约束:在一些技术方面存在着欠缺，在开发过程中需要不断地去学习和加强
* 硬件约束:这次项目涉及到关于位置的查询，这可能十分消耗cpu和io，资金受限的情况下使用低端服务器可能会造成在高并发情况下使得用户体验感不佳
* 网络传输约束:项目产品为小程序，应用于在线服务，用户的网络传输速率会对用户体验造成一定影响
* 安全和保密考虑:对于用户信息的存储保护，对于数据库结构合理性和安全性需要严谨的考虑</font>

<p><font size=6><b>2.5假设和依赖</b></font></p>

+ <font size=4>用户配合:假设小程序开发过程中，投放的问卷等调查能得到大量目标潜在用户的积极响应，并且调查结果具有真实性、普遍性和可靠性
+ 人员配合:假设在小程序开发过程中，全体组员都能够按质按量、高效地完成好自己所负责的部分，在推广过程中能够得到图书馆负责人和全体师生的支持
+ 软件开发平台支持:假设在小程序开发过程中所涉及的开发工具和平台都能很好地支持开发
+ 资金限制:假设该项目有足够的启动资金
+ 时间限制:假设该项目完成的时间不会前移
+ 可操作性:假设大多数用户对于该小程序都能灵活操作
+ 可行性:假设图书馆会给予项目鼓励并大力支持</font>
