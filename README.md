<div align="center">
<h1 align="center">ChatGPT3.5/4.0GPT-APIKEY-free</h1>

支持 **GPT-4** / GPT-3.5

国内动态加速 直连无需代理

[镜像站](https://www.w421.com/) / [快速开始](#如何使用) / [领取免费Key](https://vju35dgr.top/) / [支持付费Key](https://vju35dgr.top/)

[QQ群: 796802719](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=SG5GfBPiUOh3LO2Tl5XvOuFoRwvlUEzY&authKey=Dz8p7V46sUWO6nKUCL5TV9ejN4SSIWCq0JJ1JuMbJGzX%2BHkXCceIkDO2SYm54IJf&noverify=0&group_code=796802719)

</div>

## 隐私声明

该项目高度重视隐私，致力于保护其用户的隐私。该项目不会以任何方式收集、记录或存储用户输入的任何文本或由 OpenAI 服务器返回的任何文本。该项目不会向 OpenAI 或任何第三方提供有关 API 调用者的身份的任何信息，包括但不限于 IP 地址和用户代理字符串。

但OpenAI官方会根据其[数据使用政策](https://platform.openai.com/docs/data-usage-policies)保留 30 天的数据。

## 👏广告
ChatGPT3.5/5刀120刀, ChatGPT4.0 30刀/500刀/100刀 Openai, Midjourney等。站内充值，邀请功能一应俱全，详情查看 https://vju35dgr.top

## 更新日志
- **2023年6月14日** 适配GPT-3.5-Turbo-16K，免费key也支持16k模型；付费key跟随官方价格降低收费。

- **2023年6月15日** 适配0613版本新增的functions。

- **2023年6月18日** 新增对语言转文字模型Whisper支持。

## 特点
1. 支持Models, Embedding, text-davinci, GPT-3.5-Turbo, GPT-3.5-Turbo-16K, ***GPT-4***(免费版不支持), ***DALLE***(免费版不支持), ***Whisper***(免费版不支持)。（免费版就可以支持AutoGPT以及gpt_academic）
2. 与官方完全一致的接口标准，兼容各种软件/插件。
3. 支持流式响应。
4. 国内线路使用动态加速，体验远优于使用代理连接官方。
5. 无需科学上网，国内环境直接可用。
6. 个人完全免费使用。

## 🚩注意事项

❗️**免费API Key仅可用于个人非商业用途，教育，非营利性科研工作中。严禁商用，严禁大规模训练商用模型！训练科研用模型请提前加群联系我们。**

❗️我们将不定期对被滥用的Key进行封禁，如发现自己的key被误封请通过QQ群联系我们。

为了该项目长久发展，免费API Key限制**120请求/小时/IP&Key**调用频率，也就是说你如果在一个IP下使用多个Key，所有Key的每小时请求数总和不能超过120；同理，你如果将一个Key用于多个IP，这个Key的每小时请求数也不能超过120。(**付费版API没有这个限制**)


我们会定期根据使用量进行相应的扩容，只要不被官方制裁我们会一直提供免费API，如果该项目对你有帮助，还请为我们点一个***Star***。如果遇到问题可以在[Issues](QQ联系我们)中反馈，有空会解答。



## 付费版API
- 纯公益提供免费Key显然不是能持久运营下去的方案，所以我们引入付费API Key维持项目的日常开销，以促进项目的良性循环，还望大家理解。
- [购买低价付费Key](https://vju35dgr.top
)

1. **支持GPT3.5/4 API**，价格仅官方价格八折。
1. 性价比高，除了GPT4的其他模型价格相当于官网价格七分之一。
2. 同官网计费策略，流式问答使用tiktoken库准确计算Tokens，非流式问答直接使用官方返回Tokens用量计费。
3. 余额不会过期，永久有效。根据用户反馈30块钱个人中度使用GPT3.5估计能用一年。

## 如何使用
- 由于频繁的恶意请求，我们不再直接提供公共的免费Key，现在需要你使用你的Github账号绑定来领取你自己的免费Key。
- 转发API无法直接向官方接口api.openai.com发起请求，需要将请求地址改才可以使用，大部分插件和软件都可以修改。

## 常见软件/插件使用方法

### 最方便的使用方法

***由于对IP的访问速率限制，免费Key请勿在这两个上使用，会报错too many requests***

### **python openai官方库（使用AutoGPT等）**
示例代码请参考[demo.py](./demo.py)

***方法一***

```python
import openai
openai.api_base = "https://vju35dgr.top
"
# openai.api_base = "https://vju35dgr.top
"
```

***方法二***

修改环境变量OPENAI_API_BASE，各个系统怎么改环境变量请自行搜索，修改环境变量后不起作用请重启系统。
```bash
OPENAI_API_BASE=https://vju35dgr.top

或 OPENAI_API_BASE=https://vju35dgr.top

```
### **开源gpt_academic**
找到`config.py`文件中的`API_URL_REDIRECT`配置并修改为以下内容：
```python
API_URL_REDIRECT = {"https://vju35dgr.top
"}
# API_URL_REDIRECT = {"https://vju35dgr.top
"}
```

### **ChatBox(推荐使用)**

ChatGPT开源桌面应用，支持全部桌面平台。

下载链接：https://github.com/Bin-Huang/chatbox/releases

使用方法：如图在设置中填入购买的密钥，并将代理设置为`https://vju35dgr.top
` 或者 `https://vju35dgr.top
` 即可

![](images/chatbox.png)


### **浏览器插件ChatGPT Sidebar**

官网链接：https://chatgpt-sidebar.com/

安装好插件后进入设置页面，如图所示修改设置，将url修改为 `https://vju35dgr.top
` 或者 `https://vju35dgr.top
` 。

### **Jetbrains插件ChatGPT**

安装好插件后在Settings > Tools > OpenAI > GPT 3.5 Turbo中如图所示配置好插件，重点要将Server Settings 修改为 `https://vju35dgr.top
` 或者 `https://api.chatanywhere.com.cn/v1/chat/completions` 。并勾选Customize Server。

![](images/jet2.png)


### **VSCode插件Code GPT**

这个插件修改Host相对麻烦一些，需要修改源码才可以使用。

1. 安装插件。安装好后按Ctrl+Shift+P，弹出框中输入Open Extensions Floder
![](images/codegpt2.png)

2. 点击Extensions: Open Extensions Floder，这将打开插件目录，找到Code GPT的文件夹。
![](images/codegpt3.png)

3. 打开后进入打开文件./src/clients/openai_client.js，搜索文件中的api.openai.com，并替换为 `https://vju35dgr.top
` 或者 `https://vju35dgr.top
`。保存文件。
![](images/codegpt4.png)

4. 再次回到vscode，按Ctrl+Shift+P，弹出框中输入CodeGPT: Set API KEY，点击CodeGPT: Set API KEY。然后将购买的Key输入进去即可。
![](images/codegpt5.png)

5. 以上步骤完成后，重启VSCode

- 其他VSCode插件类似。

### **Raycast 插件 ChatGPT（推荐使用）**

1. 在 Raycast Store 中找到 ChatGPT 插件，并按照提示安装：
![](images/raycast1.png)

2. 安装完成后在该插件配置中的 `API Key` 中填入我们的API Key，以及选中 `Change API Endpoint`，并在 `API Endpoint` 中填入 `https://vju35dgr.top
`
![](images/raycast2.png)
![](images/raycast3.png)

ChatGPT下载
ChatGPT官网地址
chatgpt国内能用吗？
ChatGPT在内容运营的应用初探
chatgpt是什么意思?
chatgpt中国能用吗？
chatgpt怎么读？
探秘ChatGPT提示词的三个小技巧
ChatGPT提示词大全
ChatGPT提示词大全，12个可以使用ChatGPT的场景
教师该如何使用ChatGPT？
ChatGPT教育变革的下一个浪潮
ChatGPT与未来
ChatGPT 在石油行业十大专业领域的应用
与ChatGPT聊创业
ChatGPT目前能达到的智能水平有多高？
基层治理，或成ChatGPT时代首个赢家
ChatGPT中文版免账号注册在线使用入口
最全ChatGPT中文提示词指南（3）
ChatGPT中文调教指南，教你如何撰写中文提示词
ChatGPT使用指南——快速帮你写论文~
ChatGPT+剪映—10分钟生成短视频
ChatGPT为什么是一个字一个词输出？ChatGPT温度说明
科普文：ChatGPT国内怎么用？
离谱！新西兰律师被ChatGPT虚构的案件所蒙蔽，“它不会的时候会乱编”...
ChatGPT也能“读书”了，人类怎么自我启蒙？
ChatGPT做推荐怎么样？阿里巴巴最新《ChatGPT作为通用推荐模型性能》评估，表现良好，有其局限，大有潜力
ChatGPT 能为计算材料科学做些什么？未来会取代计算材料科学家吗？
Chatgpt中文版手册及购买方法
将 ChatGPT装进了口袋，这款穿戴产品有摄像头、能投影到掌心、交互用对话
ChatGPT对学术图书馆的影响
律师不会被ChatGPT取代，但一定会被使用ChatGPT的律师所取代
结合ChatGPT和Obsidian，生成带图片和表格的ppt
ChatGPT推出企业版订阅服务，允许用户关闭聊天记录
理财经理会被ChatGPT取代吗？
逆转生命时钟，ChatGPT 之父也在投的永生科技有多牛？
ChatGPT监管：生成式人工智能对信息传播的影响
​ChatGPT能帮忙写论文吗？写综述行不行？查重率怎么样？
ChatGPT注册教程，轻松快速入门
外国小哥同时打4份工,用ChatGPT完成80%工作
ChatGPT类应用服务，数据合规的看法


ChatGPT获政策支持！ChatGPT概念股大幅走强
ChatGPT的“狂风”正吹向电商
AutoGPT是什么？使ChatGPT的使用变得轻而易举
微软计划推出私人ChatGPT服务，防止数据泄露给ChatGPT
ChatGPT如何帮助儿童学习
​ChatGPT在药物发现方面的前景 

ChatGPT教你如何准备与申请海外留学

通过ChatGPT赚钱的技巧！
ChatGPT的公司OpenAI的创始人的故事
通过使用ChatGPT分析畅销书，我赚了 3,043 美元
ChatGPT为代表的大模型如何在各行业落地？
用ChatGPT写文书材料


chatgpt中医体验，医生说gpt4的答案跟他的诊断和用药思路有八九成相似
最先受到ChatGPT影响的职业
传音控股：全球首家介入ChatGPT融合手机端上市
用ChatGPT 爬虫搞钱，赚了！
OpenAI 将推出 ChatGPT 企业版；微软开放 BingChat；阿里云大规模降价｜To B 周周侃
ChatGPT重构教育，一场供给侧的军备竞赛！
chatgpt告白书
chatGPT镜像网站国内使用，实测免费稳定！
我问了ChatGPT几个关于培训课程设计的问题
ChatGPT为教师专业发展提供新机遇
ChatGPT在各行业应用场景
隐私计算九问！涉及断直连、ChatGPT、数据开放
科大讯飞超越ChatGPT？吸引人的不一定是技术
17 天狂赚 270 万，ChatGPT是新型印钞机？
如何用ChatGPT加Midjourney画图？（实操教程）
ChatGpt的高效提问框架：CRISPE
chatGPT为啥火了

ChatGPT 之父推出加密货币钱包 World APP与世界币项目（WorldCoin）
亚马逊的神秘新型家用机器人具有ChatGPT-AI功能
被ChatGPT“抢饭碗”的人
ChatGPT能胜过临床医生吗？JAMA子刊：回答患者问题或更专业、更人性化！
用 ChatGPT 发的第一篇顶会....
原创 | 工作的未来：在工作场所集成ChatGPT
一份出自CHATGPT的法律检索报告，震撼到我了.....
讯飞版ChatGPT上线！诚意满满，用完想骂百度~
ChatGPT大模型对经济学研究的影响
前端同学都是如何玩转 ChatGPT 的？？？
如何利用ChatGPT生成报告？
ChatGPT给程序员带来了哪些就业机会？
敢于对标ChatGPT，国产大模型迎来高光时刻
专访奈特瑞董事长曲毅：要实现ChatGPT的应用，还需全力投入数字医疗新基建建设
【ChatGPT】如何使用 OpenAI 的 ChatGPT
浅析ChatGPT局限性与展望
ChatGPT聊天： 知识图谱和LLM的融合之道和未来发展
新大模型能超GPT-4，Bard全面升级，谷歌反击ChatGPT
国内怎么玩chatgpt?
问ChatGPT：如何把写作和AI进行结合？
【ChatGPT实战】做一款模拟面试官小程序
微软官方亲自出教程，拿捏「Prompt提示词」高级玩法
ChatGPT颠覆教育的可能与不可能
ChatGPT vs. Bing AI选哪个？小孩子才做选择题，成年人当然是全都要
ChatGPT赚钱变现的5种方法
ChatGPT怎么用？90%的人都用错了
ChatGPT能通过大学考试吗？
ChatGPT如何帮助科研人员写作？
ChatGPT运营秘诀与变现攻略：3天1w ，GPT全面实用教程
ChatGPT功能简介，GPT最新模型免费体验
ChatGPT爆火后，我快被它卷失业了
ChatGPT影响国际数据生态安全治理
中国版ChatGPT点击即可使用
金蝶将推出苍穹GPT，将ChatGPT嵌入金蝶云·苍穹平台
竟然开源了！基于ChatGPT的视频生成工具，是真牛逼...
黄仁勋，ChatGPT时代的第一位赢家
深度丨ChatGPT后，百度匆匆交卷，科大讯飞将“星火”燎原？
12位专家解读ChatGPT与教育
专业性与实用性兼备，ChatGPT类聊天AI在医疗端的使用报告
不被ChatGPT淘汰的体验设计师，都具备这4点能力 | 极客时间
为什么 ChatGPT 的流量增长放缓了？
ChatGPT爆火后，智能音箱们，抢先要步入“GPT+”时代了。
最好的 AI 聊天机器人：ChatGPT 和其他值得注意的替代品
问ChatGPT：作为新人如何写好公众号？
超实用！50 个ChatGPT提示词
Pandas与ChatGPT在一起了
​CHATGPT逆天了，新功能将把年薪第一的工作拉下岗
用ChatGPT做PPT是真香！提要求、复制粘贴就搞定，我还学PPT干啥！
ChatGPT来了！校外培训出现新机会
ChatGPT如何帮助打造无货源的小红书电商？
ChatGPT 发布重磅更新，插件系统即将上线！
一分钟带你了解ChatGPT
选择什么专业才可能不被ChatGPT取代？
ChatGPT大爆炸！最新更新让你欲罢不能！
如何使用chatgpt写出高质量视频文案？
ChatGPT插件全宇宙爆炸级开放！无需排队，下周可用，GPT-4突然「紫」了
羊驼系列大模型和ChatGPT差多少？详细测评后，我沉默了
​AI人工智能-11：ChatGPT的10种核心用法（重磅干货！）上
新时代下的国土空间规划编制，ChatGPT 规划师互联赋能
苹果的人工智能应用，跟 ChatGPT 不太一样
使用ChatGPT开发股票量化策略
ChatGPT 大战 Bard
ChatGPT爆火，会给老师带来哪些影响？如何应对？（保姆级教程来了）
ChatGPT应用：手把手教你如何用ChatGPT和AI快速制作PPT
研究13个ChatGPT插件发现新的商业模式，感到以后也许就没传统大厂什么事了
gpt4申请介绍怎写?当然是用chatGPT写啊
GPT-4 API 申请图文教程
GPT-4：OpenAI 的研究，是怎么让 AI 更像我们大脑的？
GPT重塑商业模式：他们已经把大模型引入业务流 | ToB产业观察
ChatGPT中文版来了！只需简单注册ChatGPT，即刻使用最先进的AI工具~
让ChatGPT调用10万 开源AI模型！HuggingFace新功能爆火
ChatGPT 系列教程 - 浏览器插件篇：LINER 为答案附上参考链接
chatGPT会“改写”教育吗？
白会计与ChatGPT的对话，笑翻了
ChatGPT两个月引爆万亿新赛道，国内外有哪些AI玩家能够突出重围？
布鲁金斯学会：人工智能的政治化--ChatGPT和政治偏见
惠灵顿（中国）首席总校长：与其担心ChatGPT让孩子没有未来，不如先担忧学校的滞后
如何使用第三方ChatGPT？【纯干货！建议收藏！速删！】
ChatGPT，正在加速淘汰“巨婴员工”
ChatGPT时代：提对问题，比给出答案更重要
浅谈ChatGPT与学校教育
十倍之路：今天问了ChatGPT几个股票投资问题，回答如下，果然有惊喜
ChatGPT 发布重磅更新，Plus会员支持实时联网和插件系统！
ChatGPT到来后，新的职业与赚钱机会来了
谷歌向180国家开放ChatGPT竞争对手巴德，对互联网搜索进行AI升级
我问ChatGPT被领导发现是水货应该怎么办?
ChatGPT：孩子未来的朋友还是敌人？
突发！ChatGPT爆炸级更新~
ChatGPT成了机器人大脑？机器人的下一个大风口是...
值得收藏的几个实用 ChatGPT Prompt （提示词）
再迎重大升级！ChatGPT上线联网功能
观点 | ChatGPT类人工智能会进入电视台吗?
用ChatGPT制作ppt
前沿 | 周维栋：如何利用ChatGPT辅助司法裁判
ChatGPT重大升级 上线联网功能解除最后一道封印
ChatGPT:学术工匠之歌
ChatGPT提示工程学入门：用AI提升工作、学习效率 | AIGC应用实操系列第三期
懒人福音！用 ChatGPT 轻松完成交互服务作品集中的前期调研！
ChatGPT 中文调教指南，各种场景使用教学，学习怎么让它听你的话
如何用 ChatGPT 帮你自动分析数据？
ChatGPT发布半年，美国课堂最大的变化竟然是这个
ChatGPT打工系列
【ChatGPT】如何利用ChatGPT加持Chrome浏览器
AI界杀疯了--ChatGPT联网、Claude提升10万文本阅读、NewBing全面开放、谷歌AI大模型、！！！
钥坤Zeuspace论坛：《ChatGPT在金融领域的应用场景和未来展望》
中小学教师使用ChatGPT教学的几个场景 | 火遍全球的ChatGPT加速教育转型进程
ChatGPT 发布重磅更新，插件系统即将上线！
提示工程师：如何高效的向ChatGPT提问对话
ChatGPT、Midjourney不香了吗，New Bing 已向全球个人开放
ChatGPT 系列教程 - 浏览器插件篇：Glarity 网页内容摘要
ChatGPT抢工作|浙江结构化面试热点预测
3分钟，ChatGPT＋剪映即可一键成片！
最全ChatGPT中文提示词(prompt)
ChatGPT如何影响未来教育
ChatGPT的100个常见应用(1)：零基础扫盲，速度上车起飞！
ChatGPT 可能影响药物发现进程，又有哪些局限性？
借助ChatGPT，打造你的私人学习助理
如何用 ChatGPT 帮你自动分析数据？
激战千亿大模型，“国产ChatGPT”背水一战
OpenAI又放大招，ChatGPT插件将全面开放，这是首个官方认证的“投资Plugin”
如何部署ChatGPT来为短视频创作服务
如何利用ChatGPT提升10倍Python效率
您也可以体验chatgpt（限时免费）
ChatGPT如何快速写作，文章批量化生产，工厂化运营，或成为主流。
用ChatGPT搞懂GPT技术原理
换个角度，谈谈 ChatGPT 与 AI 硬件
超八成美国学生用ChatGPT作弊，我们的教育再不改也真的没戏了
ChatGPT——人工智能领域的知识产权策略
ChatGPT上线联网和插件功能，Plus 用户可使用
​ChatGPT插件将全面开放，可以帮助选股？
利用ChatGPT是如何实现升职加薪的？
chatGPT-4论文导读
OpenAI创始人：押注游戏，是ChatGPT成功的两大要素之一
超越ChatGPT的原来是TA
让金牌销售ChatGPT告诉你，Astell&amp;Kern CA1000T相较初代机，究竟值不值得买
重磅！新增ChatGPT功能：智能邮件回复和语法纠错
什么？ChatGPT竟然能通过注册可靠性工程师考试？
ChatGPT开放联网和插件；三星发力AIGC平台；中文在线启用AI主播丨AIGC大事日报
OpenAI &amp;吴恩达权威打造！《ChatGPT 提示工程课程》中文版来了！
【华西金工】基于chatgpt的国债期货择时策略
利用 ChatGPT 掌握数据科学 | Harness ChatGPT for data science mastery
ChatGPT，从入门到精通 3：免费ChatGPT资源
为什么强人工智能率先以ChatGPT方式出现？
干货满满 | 学术版Chat GPT ! 几秒钟完成一篇学术论文!
AI智能GPT 将如何影响我们的工作？
效果超越LLaVA&amp;MiniGPT-4，阿里开源多模态版ChatGPT「mPLUG-Owl」
一次10万token！GPT4最强对手Claude！
ChatGPT联动脑机接口，用脑电波回邮件！科幻成真了
北京智造论坛第一期： ChatGPT助力智能制造
高考押题24：从ChatGPT看高技术产业
AI助手必不可少：这8款基于ChatGPT的工具，将成为你的得力助手
学会ChatGPT，普通人的超强逆袭工具
ChatGPT火爆全球：有人靠它年入百万，有人账号都没注册
ChatGPT下周扩大插件测试范围，AI应用有望进一步加速！
超越ChatGPT的原来是TA
靠谱：chatGPT 写毕业论文，一键生成论文范文！
不可量化系列｜ChatGPT的未来影响v0.1
全世界都在封杀chatgpt？马斯克首当其冲，25％的岗位将被AI取代
ChatGPT可以作为副业发展吗？
【送书福利】终于有本书讲清了ChatGPT和AIGC
ChatGPT开放联网和插件；三星发力AIGC平台；中文在线启用AI主播丨AIGC大事日报
500%回报率？史上最强基金经理ChatGPT造！
国产开源版「ChatGPT插件系统」来了！豆瓣、搜索一应俱全，清华、面壁智能等联合发布
ChatGPT联动脑机接口，用脑电波回邮件！科幻成真了
ChatGPT的朋友们：大语言模型经典论文一次读到吐
相比ChatGPT，人的优势是什么？
ChatGPT可以作为副业发展吗？
北京智造论坛第一期： ChatGPT助力智能制造
高考押题24：从ChatGPT看高技术产业
AI助手必不可少：这8款基于ChatGPT的工具，将成为你的得力助手
学会ChatGPT，普通人的超强逆袭工具
ChatGPT火爆全球：有人靠它年入百万，有人账号都没注册
ChatGPT下周扩大插件测试范围，AI应用有望进一步加速！
超越ChatGPT的原来是TA
什么是Chat GPT4？它是干什么的？
ChatGPT插件全宇宙爆炸级开放！无需排队，GPT-4突然「紫」了
ChatGPT爆火！数据分析师会被取代吗？
王迁：ChatGPT生成物与“猕猴自拍”无异，不应受著作权法保护
最强反击！Chatgpt联网 插件！谷歌Bard还顶得住吗？
ChatGPT插件全宇宙爆炸级开放！无需排队，GPT-4突然「紫」了
ChatGPT爆火背后，AI算力成全新角逐风口
ChatGPT外贸文案新攻略
交通界的chatGPT，没有最智能 只有更专业
中科院发布多模态ChatGPT，图片、语言、视频都可以Chat？中文多模态大模型力作
Google 疯狂的一周才刚结束，ChatGPT 又要大更新｜Hunt Good 周报
ChatGPT横扫英国大学考试周！老师逐句批改找到AI破绽！UCL公开人工智能使用规范！
使用 ChatGPT 辅助学习——为自己找一个老师
激战千亿大模型，“国产ChatGPT”背水一战
ChatGPT联动脑机接口，用脑电波回邮件！科幻成真了
如何将chatgpt培养成全能助理？
研究生如何利用 ChatGPT 帮助开展日常科研工作？
ChatGPT|用简单提示词，快速入门，轻松掌握AI绘画的技能！
ChatGPT当教练！美国男子运动3个月成功减重近12公斤
借助ChatGPT了解食品安全世界
ChatGPT的原理和《成为故事大王》
【生巧】用这个插件，进入ChatGPT更方便了！
ChatGPT 的 18 种玩法，惊到我了！！
【科技前沿】ChatGPT能取代人类吗？｜ 人类的终极问题
ChatGPT插件全宇宙爆炸级开放！无需排队，GPT-4突然「紫」了
ChatGPT4.0来了！ 你离失业还远吗？
堪比ChatGPT，Claude注册和使用教程
数智加油站||ChatGPT介绍
学院速递||ChatGPT的简单介绍
chatgpt简介
基于ChatGPT的Burp Suite自动化打点插件
ChatGPT的朋友们：大语言模型经典论文一次读到吐
ChatGPT3.5 和GPT-4 的区别
ChatGPT联动脑机接口，用脑电波回邮件！科幻成真了
ChatGPT赋能，批量写音频、“图文成片”日赚100 人人可做，关键看赛道！
CHATGPT的出现对中国教育产生了哪些影响？要如何应对？
【协会动态】人工智能特辑——ChatGPT专场活动顺利召开
chatGPT 17：如何实现从一个想法到一个完整的文学剧本
王迁：ChatGPT生成的内容受著作权法保护吗？
如何向ChatGPT提问并获得高质量的答案——提示技术的完整指南.
大模型及ChatGPT核心技术论文
ChatGPT 从入门到精通4：办公室AI“摸鱼”
chatgpt 旅行智能规划助手能成为决策入口吗？
《中国金融》｜ChatGPT在商业银行的应用
ChatGPT来了，会计人员怎么办？
ChatGPT创始人将出席国会听证会
ChatGPT引发恐慌？类似的事不止一桩！
ChatGPT每日问答：哪些习惯能促进个人成长和持续学习？
王一洋：持续火爆半年的ChatGPT
亚马逊准备为电商增加类ChatGPT搜索 已在招聘研发人员
ChatGPT-4出现后还有必要学计算机吗？
让chatgpt4证明2^n=7x^2 y^2
企业家谈在日常工作中动用ChatGPT的四种方式
学术攻防|ChatGPT-4对于美术教育是机遇VS挑战
一文了解ChatGPT4（plus会员）开放的71个插件：即将开启人工智能新体验。
ChatGPT-4 通过图灵测试
ChatGPT 是在线教育的开始，而不是结束
ChatGpt4有多厉害？
ChatGPT绝对是属于年轻人的一个大机会
有了ChatGPT，微软依然没当上“搜索一哥”
活在ChatGPT们阴影里的Stack Overflow：流量萎缩、裁员10%，CEO坦言公司正处于困难时期
如何申请OpenAI GPT-4 API：简单步骤与成功技巧
chatGPT4 不完全注册指南
赶快申请加入 GPT-4 API  waitlist
申请普通ChatGPT账号等待GPT-4 API开放的过程
免费使用GPT-4创建AI模板，只需输入变量内容，就能获得高质量模式化结果
OpenAI已在中国申请注册“GPT-4”商标
Chatgpt4 注册、使用教程合集
GPT4账号怎么注册：详细步骤指南，让你轻松get新账号！
可免费使用GPT-4 的网站
GPT-4详细注册流程：科技赋能，进化迭代自我，正在扑面向我们走来
我的 GPT4 API 申请通过啦
GPT4申请指南
Chatgpt怎么获得GPT-4账号?(注册 使用完整教程)
GPT-4详细注册流程：科技赋能，进化迭代自我，正在扑面向我们走来
GPT4申请指南
GPT-4 API 参考指南
终极GPT-4指南
想用GPT-4，手把手保姆级教程教你国内开通chatGPT Plus
ChatGPT4.0接入详细教程-GPT4特点介绍
GPT-4 教程：如何使用 OpenAI 的 GPT-4 语言模型
OpenAI 的 GPT-4 模型初学者指南
GPT4免费版使用教程
chatgpt4开通教程
Chatgpt4 注册、使用教程合集
如何申请OpenAI GPT-4 API：简单步骤与成功技巧
美国版“作业帮”接入GPT-4，教育垂直化应用取得重大突破？
免费终极GPT-4 指南 The Ultimate GPT-4 有100多个资源60章节，ChatGPT的从零基础入门到精通！
终极 GPT-4 指南 The Ultimate GPT-4 Guide
Chatgpt怎么获得GPT-4账号?(注册 使用完整教程)
下周起ChatGPT联网，同时支持70 第三方插件
像用iPhone一样用ChatGPT？就从今天开始咯
抢先体验联网版 ChatGPT：优点和缺点同样明显，还藏着无限可能
学术诚信在ChatGPT面前岌岌可危？高校与出版商出台应对措施｜查尔斯沃思学术服务
印度人眼中的ChatGPT
AI前哨｜对话中科院王飞跃：过度炒作ChatGPT干扰大众认知，只是少数人获利
ChatGPT帮助如何使用Excel
我用ChatGPT做了一个“老友记随机选集器”，说说制作过程和体会
ChatGPT开放插件，我联网试了一下
用ChatGPT帮你写产品文档
我问了问ChatGPT市场营销人的职业规划 | 大咖说
「ChatGPT-Plugins &amp; Chat-GPT4.0在线免费体验」
ChatGPT对于科研和学业能带来哪些帮助—来自大学生视角
颠覆BI的，不是增强分析，而是ChatGPT!
徐飞：今年高考作文会考ChatGPT吗？
ChatGPT还没搞懂，新的法律AI又出道了！
chatGPT眼中的三维重建
ChatGPT颠覆就业，这些职业最危险
Chatgpt杀疯了，建筑师可以不用转行了
ChatGPT，未来最容易取代的10大工作
微软官方亲自出教程，拿捏GPT 「Prompt工程」高级玩法
国内开通Chat GPT Plus保姆级教程【GPT4.0典藏版】
Chat-GPT入门指南
终极GPT-4指南
Chat GPT教你轻松写文章：逆向工程大法（附详细教程）
《小白玩转GPT指南》
《解锁GPT-4插件 联网功能保姆级教程》 7款超好用精选插件详细介绍！
GPT4free安装部署教程 - 白嫖GPT
注册/升级Chat GPT账号保姆级教程来了
2023年5月最新ChapGPT最新注册教程
全网最详细的AutoGPT保姆级教程，小白也可轻松上车（合集）
GPT-4 教程：如何使用 OpenAI 的 GPT-4 语言模型
GPT4免费版使用教程
Auto-GPT-使用教程
【探险手册】—几个Gpt工具上手详细教程
GPT使用教程：推荐5款GPT实用工具与GPT使用技巧攻略
ChatGPT Plus付款失败？详细说说几种常见原因及解决方法！
ChatGPT Plus订阅过程详细解析—让你轻松掌握订阅流程
如何开通ChatGPT Plus？完整步骤分享！
chatgpt plus paypal可以升级吗：购买更方便！
chatgpt plus paypal能搞定吗：chatgpt plus升级详解
chatgpt plus插件在哪下载：让你聊天更加自如
chatgpt plus开通的方法有什么：一步一步教你如何操作
ChatGPT Plus暂停升级，背后的原因是什么？
chatgpt plus续费时要注意什么？
chatgpt plus合租可靠吗？
chatgpt plus 如何付费才能顺利使用？
ChatGPT Plus账号服务哪里有？完美解决你的疑惑！
chatgpt plus如何付费？
chatgpt plus订阅国内使用需要什么？
chatgpt plus租号可以吗？
chatgpt plus 如何付费才能顺利使用？
chatgpt plus 支付用什么才能升级成功？
chatgpt plus购买流程是？
chatgpt plus账号在哪里有？
chatgpt plus共享靠谱吗？有什么注意事项？
chatgpt plus代付代给可以吗？安全吗？
chatgpt plus合租靠谱吗？
ChatGPT Plus共享账号在哪里？详细介绍常用聊天机器人共享方式
ChatGPT Plus是什么的12个问题？
ChatGPT Plus使用体验
ChatGPT无法撼动HR地位的4个理由
ChatGPT等生成式人工智能引发的版权问题 | 每日IP英文第473期
ChatGPT讲解中国-中国绘画
AI入侵，职场人能否与“ChatGPT们”共存？
ChatGPT保姆级教学｜帮你轻松搞定大数据
ChatGPT联动脑机接口，用脑电波回邮件！科幻成真了
我让 ChatGPT 反过来问我问题，40 个问题把我给“训练”了
简析chatGPT超能力的来源
人工智能 复发大学类 chatgpt 人工智能模型 moss 来了
Stack Overflow 遭到 ChatGPT 的 “暴击”，被迫裁员
chatGPT，能让PPT逻辑更清晰吗？
ChatGPT赋能教师专业发展的路径
美国举行首次AI重大听证会！“ChatGPT之父”：要把AI管起来！
张新宝：对ChatGPT们的五点思考｜前沿
看这里！ChatGPT生成的套磁邮件居然这么靠谱！
无药可救！莫兰特的道歉声明，居然还是用ChatGPT生成的？
70多种插件加持，联网版ChatGPT评测来了
ChatGPT之父舌战国会山！OpenAI欲与政府联手，权力通天
问ChatGPT：情商低不会说话怎么办？
当我还在担心被chatGPT取代的时候，一不小心被这个学生取代了
对话ChatGPT，聊聊养老那些事儿
终于有本书讲清了ChatGPT和AIGC的前世今生！
今晚八点半，人类和chatgpt的辩论赛视频全球首发：你不敢相信的故事结局！
看这里！ChatGPT生成的套磁邮件居然这么靠谱！
深入ChatGPT与AI营销前沿，助力提升成都产区酒企竞争力和创新力
小语种语库资料不足？ChatGPT认错日本首相
如何用ChatGPT辅助做小红书无货源电商？
AI写作 | 对Chatgpt用哪些提示方式才能让它写一篇优秀的小红书笔记?
研究观点33-制药公司如何适应ChatGPT
国外大神制作的宝藏PDF工具，用ChatGPT读取PDF
对话中科院王飞跃：过度炒作ChatGPT干扰大众认知
东南亚也有山寨版“ChatGPT”？AI热潮来袭
張朋朋丨從文字的產生到ChatGPT的出現
全网最全chatgpt应用
如何用 ChatGPT 流水线生产自媒体短视频？
十问AI研究：解构ChatGPT背后的力量和边界
五问「ChatGPT 医学影像」：新一代的AI能否成为放射科医生的一把利器？
当狂飙的“ChatGPT”遇上法律缰绳——速览ChatGPT六大法律问题
ChatGPT 之父回应一切
ChatGPT将消灭保险公司的“理”和“赔”。
ChatGPT plugins使用体验
羊驼开源大模型把ChatGPT逼上梁山？推演大模型的竞争终局！
教你如何用ChatGPT写一篇论文
三步开启 chatgpt4.0联网功能教程
ChatGPT聊志愿｜浙江大学介绍、王牌专业、填报条件
初次尝试使用chatGPT
为什么ChatGPT用Python实现？
七大语言模型PK，ChatGPT内容基线评测稳居第一
警惕ChatGPT应用热潮中的欺诈骗局
ChatGPT AI实用工具=Office职场利器！
ChatGPT背后的智能数字发展浪潮——访清华大学新闻学院元宇宙文化实验室主任沈阳
ChatGPT支持的5个插件，实用性超强！让人工智能为你解忧！
chatgpt获取与心得
​ChatGPT plus充值可以用国内信用卡吗？
chatgpt会员多少钱一个月？
13种ChatGPT类似实用工具
类chatGPT应用，AI换装也来了，电商服装模特们都要失业啦！
Chatgpt账号密码忘记了怎么办?
chatgpt4怎么充值?
ChatGPT Plus 版申请付费流程-步骤、支付方式、注意事项 支持微信支付宝付款
《Nature》正刊，教你用ChatGPT搞科研。
什么是ChatGPT Plus?有关GPT Plus付费订阅计划的12个官方介绍
ChatGPT Plus值得买吗?Open AI的服务物有所值吗?
怎么利用ChatGPT写论文，分六步走。
ChatGPT是一款基于人工智能的聊天机器人
开发ChatGPT插件
Chat GPT 4价值与收费介绍
OpenAI 公司对 GPT-4的介绍
给ChatGPT做角色定位
明确ChatGPT对词汇的定义
如何用ChatGPT生成小红书爆文
ChatGPT+小红书爆文，1天量产100篇笔记
ChatGPT注册指南
ChatGPT 85个插件介绍，让你的学习、工作、生活效率翻倍！
如何使用ChatGPT插件
ChatGPT开始入侵，一大批主播要失业了？
孩子与ChatGPT的对话，尤其最后面的问题，让我哭笑不得
招聘广告要求ChatGPT技能 AI将给工作场所带来什么变化？
关于ChatGPT封号原因和解决办法
ChatGPT 还可以帮读文献？妈妈再也不用担心我的学习
ChatGPT 简史：我们如何走到今天
免费试用ChatGPT
作为普通人，能用ChatGPT做的10件事，很实用！
ChatGPT：互联网营销的必要性
全网首个，自带Chatgpt的pdf工具箱
蓝凌MK接入ChatGPT，看“蓝博士”5大智能场景
ChatGPT人工智能写文章的优缺点
问ChatGPT：自控力极差的人如何自救？
ChatGPT全面进攻，马化腾如何看待AI的竞争？
基于AIGC的ChatGPT创业风口：大模型、小场景
怎么借助ChatGPT快速肝一篇学术论文？
用上ChatGPT后，我停掉了孩子的英文私教
ChatGPT 的议论文究竟写的怎么样？111 位高中教师告诉你答案
ChatGPT MidJourney 高效创作插画
ChatGPT大火，我们普通人能抓住的下一个风口在哪？
ChatGPT提问词大全（建议收藏）
微软CEO：只有微软愿意和 OpenAI 合作
ChatGPT辅助编排调研计划
用ChatGPT做翻译真的太香了！这4个用爱发电的免费神器，好用到飞起
从哪里获取ChatGPT4账号？
ChatGpt4有多厉害？
ChatGPT4 plus插件详细介绍
ChatGPT使用指南与ChatGPT使用技巧
对话ChatGPT,如今爆火的人工智能如何回答环保问题？
AI聊天机器人ChatGPT与3DFrame集成以革新虚拟产品演示
王一洋：我用ChatGPT重新梳理了一下用户需求……
ChatGPT帮大学生写论文创作，提升写作质量与效率！
会计如何应对ChatGPT的冲击？
ChatGpt论文指令，很全！
ChatGPT底层原理及高质量提问
元启数藏将升级chatGPT AI项目
ChatGpt等生成式人工智能对法律职业的价值、挑战与应对
你以为ChatGPT只会聊天？NO！人工智能已经通过了注会考试！
工业设计版 ChatGPT--PAM™！正式面向全球邀请内测体验师！
手把手教你如何用Chatgpt提问（上）
ChatGPT引领的变革时代
ChatGPT：教育行业新宠，开启智能学习无限可能！
ChatGPT已被超越？多模态AI：AI技术的下一个风口！
chatgpt4.0是否会取代你？深度合成技术快速发展
用ChatGPT写书，是一种怎样的体验？
警惕ChatGPT热潮下的陷阱：相关诈骗攻击与日俱增
ChatGPT：一文搞懂数据埋点的认知、方案、代码实现
ChatGPT中文网页版地址，最新可用！
ChatGPT风口下的灰色“生意经”
ChatGPT可以被用于哪些应用场景
在百度问一问用chatgpt答题赚钱
介绍3款好用的IntelliJ IDEA ChatGPT插件
教师对ChatGPT的26种用法
教师指南：如何使用ChatGPT开展教学与评估
ChatGPT论文指令大全！大纲、选题、文献等
ChatGPT家教：如何提高孩子学习成绩？
你真的了解ChatGpt嘛
ChatGPT如此火爆，而大模型才是背后Boss...
ChatGPT 在软件功能测试中的应用探索
CHATGPT4.0 plus功能再升级！联网功能终于不再鸡肋~
ChatGPT-挑战中考能拿多少分？速看…
当ChatGPT在考场遇到神经外科医生/医学生...
ChatGPT美国用户画像：年轻、富裕、受过良好教育
内置ChatGPT的PDF编辑器“PDFgear”发布
ChatGPT爆火，网络安全再次被摆上台面
ChatGPT里体验大佬智囊团出谋划策！
ChatGPT官方推出分享链接功能 您可以让别人查看您的聊天内容并继续
必应的chatgpt聊天入口在哪?
chatgpt网页版提问入口
chatgpt镜像入口
ChatGPT背后的创新支撑机制及的启示
第一批用ChatGPT工作的HR，已经吊打同事了
用好ChatGPT的咒语心法
ChatGPT | 探索中国美食
ChatGPT 造富“神话”：大四学生放弃大厂去创业，半年后月收入45万
ChatGPT的过去，现在和未来——这才是今年Build上最重要的对话｜大模型新鲜事
ChatGPT的升级：从3.5到4.0 版本区别对比
ChatGPT会取代HR吗？
ChatGPT Prompt提示词学习手册
单GPU实现99%ChatGPT性能，「原驼」火了：手机也能微调大模型
最晚明年，特斯拉将迎来一个ChatGPT时刻！马斯克最新对话，回答了一个叩问所有人内心的问题……
ChatGPT带来新挑战，金融科技创新有望解决哪些实体经济难题？
如何编写有效的ChatGPT提示 |女仕界科普专栏：ChatGPT使用技巧
ChatGPT 说论文是 AI 代笔，学生悲剧了
ChatGPT当“法律顾问”！Spellbook帮600个法律团队起草、审核法律合同
用ChatGPT帮用户选股票，摩根大通将发布IndexGPT
人工智能ChatGPT视域下的未来创新人才培养
ChatGPT探秘之旅：探究世界之谜，拓展视野
OpenAI 宣布 ChatGPT 移动应用扩大覆盖范围，在更多国家上线
AI荐股要来了？摩根大通正在研发“类ChatGPT”业务
ChatGPT充值,银行卡被拒绝了还能再次充值吗？
详细的ChatGpt变现实战攻略，可让你轻松月入1-3K
借助ChatGPT等AI工具，用AIDA模型优化你的文案
ChatGPT全球大宕机；9秒被骗走245万元！“打了视频电话确认是熟人”；
詹姆斯·卡梅隆自曝：新终结者电影剧本由ChatGPT写！天网大结局，AI自己定
Sam Altman：ChatGPT的发布堪比登月壮举｜中企荐读
ChatGPT 登录报错 Sorry, you have been blocked（抱歉，您已被屏蔽）解决办法
我如何使用ChatGPT和Copilot
ChatGPT 共享链接让精彩与互动继续！
ChatGPT：重塑企业内容营销，运营狗可以下岗了？
ChatGPT是什么？大语言模型（LLM）的本质（万字干货）
chatGPT论图文广告行业面临的艰难困境
最新ChatGPT手把手注册教程
湖南永雄的崩溃：我们如何借助ChatGPT探寻其所处的催收行业
ChatGPT起名技巧，算命大师要下岗了？
利用ChatGPT成就超级个体，实践派的AI时代红利
刘兆基 | 借助Chatgpt虚拟AI，美国网红诠释“万法分身”（中）——产业革命来了吗?​
ChatGPT前世今生，及其数字化转型启示
【AI提示】ChatGPT提示工程课程（吴恩达&amp;OpenAI）转换文本（中文chatgpt版）
刘慈欣谈 ChatGPT：我们的未来，仍是星辰大海！
chatGPT秘钥—回答式Prompt
ChatGPT秘钥:Prompt基本原理
ChatGPT背景下，英语老师更需要什么思维？英语学习活动观！
【问ChatGPT】：应该拥抱焦虑而不是拒绝焦虑，你觉得这个观点如何?
chatGPT全能应用
ChatGPT如何颠覆法律行业?
灾难日！ChatGPT大面积封号了...
SmartGPT 横空出世，大大提升 ChatGPT 回答准确率！
chatgpt评中国最好就业的十个专业
怎么通过ChatGPT完成一副灯光画
ChatGPT Plus插件和联网功能开启、安装和组合使用教程
跨境电商如何利用ChatGPT做谷歌SEO优化
ChatGPT、GPT4、AutoGPT 和 MemoryGPT：初学者指南
ChatGPT到底有多厉害？0编码0调试搞定网站系统开发
“千模大战”100天：六路玩家围攻ChatGPT
这是我们第一篇由ChatGPT写作的稿件
chatGPT在教育中的应用场景
新增ChatGPT功能：智能邮件回复和语法纠错
​ChatGPT如何应用于人力资源领域？
掌握实用的Prompt技巧可以更好地利用ChatGPT
ChatGPT在汽车客户服务中的应用及意义
ChatGPT对可持续发展会计问题带来的变革与挑战
ChatGPT对我们意味着什么
ChatGPT也能画图？教你一键提效小技巧
终于用上GPT4的插件功能了！
GPT-4 Plugins使用说明
ChatGPT插件介绍与插件安装方法【最全Plus插件列表介绍】
ChatGPT封号！卖家文案全清零
ChatGPT协助策展是怎样的体验？首届元宇宙设计大赛作品展开展
ChatGPT火爆全网：科技化时代下该如何培养孩子？
力压ChatGPT？！阿联酋推出“最强”开源大模型FalconLM
ChatGPT会对临床工作有帮助吗？存在哪些优缺点？
ChatGPT对书法理论研究的影响
ChatGPT爆紅觸發研發AI熱,GPU供應不足成掣肘
ChatGPT是什么意思？ChatGPT介绍
ChatGPT的启示：师德是教师最硬核的专业底气
数字经济大裁员，ChatGPT就业新方向
GPT-4进行数据分析的成本不到人类分析师的1%
教你辨别ChatGPT网站究竟是基于 GPT-3.5 还是 GPT-4
chatgpt+midjourney绘画
鼓励教师把握机会：使用ChatGPT作为教学辅助工具
chatGPT炒股
GPT-4能否取代数据分析师？达摩院的初步实验为你解答~
AI孙燕姿，ChatGPT，AI绘图...这节课通过探究“人工智能”学习“概念的概述”
超越ChatGPT — 机器学习如何提高增材制造的生产力
ChatGPT调教指南-咒语指南-提示词工程
基于ChatGPT的视频智能摘要实战
使用ChatGPT教学的七个案例
华佗GPT来了，真人医生，盲测效果优于ChatGPT
ChatGPT的万能提问词，学会提问确实是一种很高级的能力。
ChatGPT可以为汽车提供AI驾驶助手
ChatGPT回答：孩子不爱学习怎么办？
ChatGPT唤醒AI游戏,七天制作一款新游戏？
如何对抗ChatGPT、算法、生物识别监控等科技力量？AI Now2023年度报告解读
AIGC时代如何安全使用ChatGPT
chatGPT运用分享(教学篇)
用好ChatGPT的咒语-提示词工程
实战怎么用ChatGPT编程
不要拿 ChatGPT 干这 6 件事
ChatGPT/GPT-4做知识图谱构建推理
一招让ChatGPT不再胡说八道！
在ChatGPT风口上，起飞的只有英伟达
程序员小哥用ChatGPT做了一个AI女友，还得到了真女友的赞赏！
【教程】Chat GPT注册和充值Chatgpt Plus具体步骤
优化ChatGPT指令，保姆级教程
ChatGPT成企业应用最多生成式AI工具，至少提升50%生产力
深圳：推进“千行百业＋AI” 孵化高度智能化的生产机器人
ChatGPT帮你快速掌握新行业的秘籍！
快讯，ChatGPT Plus插件商店已支持搜索插件功能
ChatGPT + Midjourney 绘画教程
从ChatGPT到WorldCoin， Sam会给Web3带来惊喜吗？
ChatGPT提示词秘诀,一个技巧让ChatGPT做你的Prompt Engineering教练
ChatGPT中文版入口，持续更新！
李政涛：ChatGPT时代，什么样的知识最有价值？教师最需要哪些本领？
ChatGPT：打破推荐算法的“牢笼”
ChatGPT 80个插件帮你搞定行业和生活难题
安妮·埃尔诺获诺奖后无法写作，ChatGPT是一个科幻迷书呆子
ChatGPT支持分享对话啦!
我和chatGPT聊了聊校园霸凌
安克全力布局ChatGPT，多个岗位将被取代？
Midjourney注册与使用超详细教程
描述一幅令人惊艳的画midjourney关键词
ChatGPT之父的母校约翰•巴勒斯中学：让学生在无限探索中找到终身热爱
ChatGPT 不会倒写单词？
ChatGPT悄悄上线新功能，与他人共享对话
3个chatgpt的最强辅助工具
科大推出自己的ChatGPT，全校免费用！
ChatGPT与软件架构(2) - 基于Obsidian和GPT实现解决方案架构自动化
用 ChatGPT 打造你的一人公司，让它扮演各个员工角色，榨取它的剩余价值
【ChatGPT】Mr. Ranedeer：可定制个性化学习体验的 GPT-4 AI 导师提示
​人工智能聊天机器人程序 - ChatGPT
AI工具 ChatGPT-4 VS GoogleBard，SQL开发者会Pick 谁？
用 ChatGPT 写论文、演讲、求职、创作歌曲或做员工评估
对话周枫 | ChatGPT下的颠覆、革命与场景
ChatGPT是什么？如何帮我写科研论文？
开发了一个gpt指令大全
GPT大模型掀起AI浪潮！一文看懂毫末自动驾驶生成式大模型DriveGPT
如何用ChatGPT「6分钟」写一篇论文
ChatGPT当中的“GPT”是什么意思？
用 ChatGPT 做书单号，小白也能搞定！
如果你还不知道ChatGPT，就OUT了？
如何让ChatGPT帮我做小红书美食账号？
最新，chatGPT插件介绍，共270个
ChatGPT玩法（二）：AI玩转Excel表格处理
用好ChatGPT，让你的创作一日千里
靠ChatGPT在问答平台答题，简单复制粘贴，日赚500多
ChatGPT Prompt中文教学！使用技巧＋使用方法攻略
ChatGPT 使用指南（如何使用GPT）
3分钟让ChatGPT生成小红书爆款文案，节约99%时间成本！
使用chatgpt4提高工作效率及生活质量
GPT-4 AI绘图之戴眼镜的美女，高清美图欣赏
GPT生成技术的背景和潜力
GPT4化身为一位资深的临床医生，与我们一起探讨如何看待疾病：“疾病的隐喻：探索身心之旅”
GPT真的能写好高考作文吗？
GPT-4知道它是不是“胡说八道”吗？一篇关于大模型“自知之明”的研究
GPT 是如何诞生的
最强人工智能ChatGPT-4，就是冲着赚钱来的
Your credit card was declined.Try paying with a debit card instead.怎么办？
ChatGPT Plus支持中国信用卡吗？在国内如何代充ChatGPT Plus？
笑死！网友意外升级 ChatGPT Plus，被迫体验 GPT-4 插件
GPT能做Excel了！
OpenAI CEO重申：未训练GPT-5，短期内也不会开始
用ChatGPT plus插件，一句话就可以生成网站！
概述GPT生成技术的背景和潜力
阅读清单丨《超越想象的GPT医疗》（1）
chat GPT对于人类未来的工作会有哪些影响？
用chatGPT 帮你写 PPT
人工智能、大模型和Chat - GPT的关系
GPT-4：我的的工作助手
GPT翻译利器：如何提高翻译质量和效率，让你的翻译更加准确和流畅
选择最适合自己需求的GPT-4插件
用 chatGPT4打游戏是个什么体验
基于GPT设计数据产品的一些思考
GPT教你如何拆解OKR，增强制定目标的手感
理想自研Mind GPT上车，让老人小孩也能轻松使用AI
开启 AI 新篇章：GPT-4 引入新的函数调用能力
GPT4预测：未来10年中国排名前十城市生活质量与成本
