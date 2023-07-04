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

## 免费使用

- **🚀[点击领取免费API Key](https://vju35dgr.top
)**
- **转发Ht1: `https://vju35dgr.top
 (国外服务器使用)**
- **转发Host2: `https://vju35dgr.top
 (国内中转，延时更低，推荐)**

***免费key请勿用于镜像站https://vju35dgr.top
会报错***

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
- 🚀[领取免费API Key](https://vju35dgr.top
***（免费key请勿用于 https://vju35dgr.top
 会报错）***
- 转发Host1: `https://vju35dgr.top
(国外服务器使用)
- 转发Host2: `https://vju35dgr.top
` (国内中转，延时更低，推荐)
- 余额和使用记录查询（通知公告也会发在这里）: [余额查询及公告](https://vju35dgr.top
)
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

![](images/sidebar.png)

### **Jetbrains插件ChatGPT**
<img src="./images/jet1.png" width='200'/>

安装好插件后在Settings > Tools > OpenAI > GPT 3.5 Turbo中如图所示配置好插件，重点要将Server Settings 修改为 `https://vju35dgr.top
` 或者 `https://api.chatanywhere.com.cn/v1/chat/completions` 。并勾选Customize Server。

![](images/jet2.png)


### **VSCode插件Code GPT**
<img src="./images/codegpt1.png" width='300'/>

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

3. 🍺 enjoy it~
![](images/raycast4.gif)

## API报错说明
- Overload错误

具体错误信息：
```
{
  "error": {
    "message": "That model is currently overloaded with other requests. You can retry your request, or contact us through our help center at help.openai.com if the error persists. (Please include the request ID xxxxxxxxxxxx in your message.)",
    "type": "server_error",
    "param": null,
    "code": null
  }
}
```
该错误由于OpenAI官方服务器负载高引起，与转发服务器负载无关。一般一段时间后恢复，可以等几秒后再试。


[![Star History Chart](https://api.star-history.com/svg?repos=chatanywhere/GPT_API_free&type=Date)](https://star-history.com/#star-history/star-history&Date)
