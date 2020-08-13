## 字幕组机翻小助手 - [视频演示](https://www.bilibili.com/video/av82675511) - [教程](https://doc.tern.1c7.me/zh/)
桌面软件，支持 Windows + macOS

## 下载地址
* [下载 Windows 版本 (.zip)](https://tern-release.oss-cn-shenzhen.aliyuncs.com/Tern_Windows_2.9.0.zip)    
* [下载 macOS 版本 (.dmg)](https://tern-release.oss-cn-shenzhen.aliyuncs.com/Tern_macOS_2.9.0.dmg)

## 媒体评价
* [少数派: App+1 | 让「熟肉」来得更快一点，省时省力制作双语字幕：Tern](https://sspai.com/post/59168)
* [小众软件：Tern – 字幕组机翻小助手：自动翻译英文字幕为中英双语字幕[Win/macOS]](https://www.appinn.com/tern-subtitle-file-translator/)

## 软件外观
<img src="./image/main.png" width='800px'>

## 解决的问题：1. 翻译字幕文件
比如拖入英语字幕，翻译成中英双语字幕   

<img src="./image/subtitle_0.png" width='800px'>   
<img src="./image/subtitle_1.png" width='800px'>   
<img src="./image/subtitle_2.png" width='800px'>   


### 说明
1. 支持三种字幕格式：.srt，.ass，.vtt      
2. 支持多种语言如德语，法语，日语，韩语，俄语，西班牙语，意大利语（只要翻译服务商支持，软件就支持）    
3. 如果不想要中英双语，也可以只要中文，不要英文（具体设置方法见下方截图）

### 设置输出格式
设置为"译文"即可（下图中的红框里，从上往下数起，第二个选项）   
<img src="./image/format0.png" width='800px'>   

如果想要中英双语，那么需要设置成"原文+译文"，点击右侧白色按钮可"设置格式"   
<img src="./image/format.png" width='800px'>

## 解决的问题：2. 可以语音转文字          
拖入音频或视频，识别出文字，然后输出为"纯文本"或"字幕"  
<img src="./image/speech.png" width='800px'>
<img src="./image/speech1.png" width='800px'>

说明：
1. 如果选择"输出为字幕"，还可以进行后续翻译，可以做到拖入视频，得到中英双语字幕  

## 支持双平台 Windows + macOS
## Windows 截图
<img src="./image/win10.jpg">

## macOS 截图
<img src="./image/macos.jpg">

## 适合谁用?
1. 个人
1. 字幕组（翻译视频的人）


## 使用场景
1. 个人：看视频教程或其他没字幕的视频，机翻一下字幕，对质量要求不高，大概看懂 80% 内容就行   
1. 字幕组：先用机器翻译对字幕进行粗加工，然后再手动改进，这样效率更高

（备注：如果你对字幕质量要求很高，想要信达雅，最好还是雇人翻译。机器翻译的准确度区间 50%~85%）   

## 价格 (Pricing)
软件分为两个版本:
1. 免费版（适合95%的人）
2. 专业版

## 免费版的特点
* 字幕翻译：每月最多翻译100万字符 （每月1号重置）   
* 语音转文字：最多10小时 （每月1号重置）            

## 专业版的特点
* 字幕翻译：翻译字符无上限
* 语音转文字：无时间上限
* 字幕翻译：支持字符数统计功能，  
可以看到用腾讯云翻译了 25 万个字符，用百度翻译了 7 万个字符，用谷歌翻译了 10 万个字符。可单独为服务商设置字符数上限，避免超出额度
* 语音转文字：支持时长统计
       
## 支持的服务商列表

### 字幕翻译支持如下服务商(共13家):
* 彩云
* 腾讯云
* 百度
* 阿里云
* 有道
* 搜狗
* 小牛
* 译云
* 亚马逊
* 谷歌
* Azure
* Yandex
* IBM
* DeepL  

[查看表格: 免费额度和价格](https://doc.tern.1c7.me/zh/folder/pricing/)

### 语音转文字支持如下服务商(共6家):
* IBM
* Azure
* Amazon
* 讯飞
* 阿里云
* 腾讯云  

[查看表格: 免费额度和价格](https://doc.tern.1c7.me/zh/folder/pricing_sound/)

说明：所有语音转文字服务商都支持"任务历史"功能，    
意思是只要文件成功传给服务商，服务商开始处理了，那么就可以关掉软件，不需要一直开着。      
过一阵子再回来看任务做完没    

## [使用教程看这里](https://doc.tern.1c7.me/zh/)
基本概念：
1. 先设置一家服务商，如果要用字幕翻译，就设置一家翻译服务商，如果要用语音转文字，就设置一家语音服务商
2. 拖入文件，字幕的话后缀是 .ass .vtt .srt，音视频的话是 .mp4 .mkv .mp3 .flac .wav
3. 从下拉菜单中选择刚设置好的服务商，然后点击右侧的大按钮"开始"，就会开始处理你文件了

## 推荐哪家服务商？
### 如果是字幕翻译
* 推荐先申请百度，因为免费额度无限，而且整个注册流程较快，没有人工审核的部分，照着"使用教程"里一步步做大概5-10分钟就行
* 备注：不推荐使用腾讯云，因为速度慢（速度慢是因为 API 不支持分行，因此只能一行字幕发一个请求，虽然 QPS 最高是5，但实际使用中一秒大概能处理1-2行，总之就是慢）
* 彩云每个月免费额度100万，不过申请流程是人工审核，因此需要1-3天，可以先申请了然后过阵子看成功没，如果很急用的话不要用彩云，来不及。
* 其他服务商可以自己试试，很难对比质量然后打个分，只能自己试

### 如果是语音转文字
* 推荐先用阿里云，因为每天2个小时的免费额度
* 讯飞的免费额度是5小时（一次性）
* 腾讯云的字幕断句很有问题（一句一大段文字）如果只是想输出纯文字，那问题不大，但如果需要字幕，那不太舒服，一句话很多字，在屏幕上可能会显示4-5行
* 如果要识别中文，推荐阿里云，讯飞，腾讯云
* 如果要识别英文，推荐 IBM Azure Amazon (国内服务商当然也能用，但是准确度平均来说低那么一丢丢）
* 如果要识别其他语言，日语泰语德语法语等等，自己先在下拉列表里找一找，看看哪家服务商支持，然后再去申请

## 替代品 
* [字幕酱](https://www.zimujiang.com/): 使用简单。如果嫌弃机翻助手配置很麻烦，希望不要配置直接用，那么用字幕酱
* [VideoSRT](https://github.com/wxbool/video-srt-windows): (Windows 独占，不支持 macOS)
* [网易见外](https://sight.netease.com/)：贵（人工所以贵）
* [讯飞听见](https://www.iflyrec.com/)：贵（相对于本软件可以利用服务商的免费额度而言）
* [Arctime Pro](http://arctime.cn/service.html)：贵，文档原话：（Arctime平台采用“积分”作为统一的虚拟货币，1元=100积分）全自动语音转写每分钟价格：普通话/粤语/英语30积分，其他语种45积分。机器翻译每100字符扣除1积分。

推荐试用字幕酱和 VideoSRT

## 用户 QQ 群
982808006    

不管是免费或付费用户都欢迎加入 QQ 群           
（截止至2020-8-13，Q 群共有 301 人）