# XieBroRAT



## 简介

XieBroRAT的前身为DcRat，在DcRat的基础之上，进行流量特征的修改，并且添加了一些有意思的功能，对此我还参考了Quasar、Async、NanaCorer、NJrat、CobaltStrike的工作原理，开放出来的release客户端为DcRat的原版客户端，在此我非常感谢@qwqdanchun 提供的代码以及对我的帮助。 （目前不打算开放二开的XiebroRAT客户端，因此请不要滥用并上传dcrat的客户端）

## 视频链接：

无文件抓取密码凭证：https://www.bilibili.com/video/BV12e4y1C7SG/?spm_id_from=333.999.0.0

## 新增功能

1.隐藏桌面控制（HVNC）

2.隐藏Powershell

3.抓取浏览器密码

4.抓取wifi密码

5.获取用户登入密码(logonpassword)

6.反向代理

7.Getsystem

8.客户端上线自动进程迁移

9.获取域内信息

10.去除用户态钩子

11.自动安装任务计划

12.生成Powershell、JavaScript、VBScript、Mshta、VBA（宏）脚本。

13.开启Http服务

14.图片隐写功能

15.Dll劫持自动化添加

16.注册表自动添加





[+]后续会考虑添加更多渗透测试的插件，包括类似CobaltStrike的TeamServer的团队作战工具

##  图形化界面 

##  ![image](https://user-images.githubusercontent.com/89376703/192097075-070bddf4-b489-4844-8a27-026aece493c3.png)                       

## ![image](https://user-images.githubusercontent.com/89376703/192097086-acb1861c-8728-4a27-852e-def19b17c4f4.png)




## 注意

1.渗透插件的信息收集模块需要打开Http服务，在此之前需要下载Python3.8的环境，注意http服务端口不要与客户端监听端口重复。

2.该工具的应用场景为前期的钓鱼打点，作为一个冲锋马的作用，不要指望它能在内网渗透中发挥多大的作用，在获取到内网的入口点以后可以将会话迁移至Metasploit，在msfvenom中生成bin文件，然后在XiebroRAT中进程迁移注入Bin文件，即可完成迁移。

3.XieBroRAT是否存在后门？不存在的。作为一个B站UP主，做这样的事情，显然对我没有任何好处，如果发现了后门你们可以检举我。

4.点不开的功能都是经过删减和阉割，我会在知识星球陆续开放未删减版的XiebroRAT，主程序经过复杂的混淆,软件未开放源代码，但是你可以尝试去破解，如果破解成功，+我VX请你吃肯德基。

5.接受BUG反馈，不接受恶意评论，否则我会清空该仓库。

6.该工具仅用于网络安全教育和研究，禁止用于非法途径，我对您由使用或传播等由此软件引起的任何行为和/或损害不承担任何责任。您对使用此软件的任何行为承担全部责任，并承认此软件仅用于教育和研究目的。下载本软件或软件的源代码，您自动同意上述内容。



![image](https://user-images.githubusercontent.com/89376703/192097112-2e559dd3-1f93-4896-973f-aa6908266be7.png)



![image](https://user-images.githubusercontent.com/89376703/192097104-a610eae8-30df-49b2-8ccc-f9d2e0af4c65.png)







## 参考链接：

https://github.com/qwqdanchun/DcRat

https://github.com/NYAN-x-CAT/AsyncRAT-C-Sharp

https://github.com/quasar/Quasar

https://github.com/sysrom/DcRatCHS

https://github.com/Meltedd/HVNC

https://github.com/qwqdanchun/HVNC
