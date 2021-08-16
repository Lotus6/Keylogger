# Keylogger

* 从cs4.2中提取的web端键盘记录，记录web页面输入的所有文本内容。(如果感觉对您有帮助，感觉不错的话，请您给个大大的 ⭐️❗️)

**V1.0**
* 支持协议：HTTP/HTTPS
* 默认会在当前目录生成一个jquary.js,放在远程服务器上加载即可～（直接将生成的源码copy到页面也行，不建议js代码太多）

1. HTTP

`java -jar Keylogger-1.0-SNAPSHOT.jar -h 127.0.0.1 -p 9000 -r http`

<img width="565" alt="http" src="https://user-images.githubusercontent.com/63742814/129600533-8d31e89d-0e76-48e4-828b-05b982605dda.png">
<img width="554" alt="截屏2021-08-17 上午12 54 34" src="https://user-images.githubusercontent.com/63742814/129600641-8b77c24a-68b0-4e1f-ae45-45852a70f7bb.png">


2.HTTPS

`java -jar Keylogger-1.0-SNAPSHOT.jar -h 127.0.0.1 -p 9000 -r https -k "/Users/xxx/xxx.keystore" -s 123456`

<img width="570" alt="https" src="https://user-images.githubusercontent.com/63742814/129601182-1fa18e54-1436-4986-bc41-5280a69bd4db.png">
<img width="554" alt="截屏2021-08-17 上午12 54 34" src="https://user-images.githubusercontent.com/63742814/129601198-4e56f8ae-d08d-41b1-9292-02ee26de6bde.png">

3.Help

<img width="564" alt="截屏2021-08-17 上午1 03 26" src="https://user-images.githubusercontent.com/63742814/129601904-7783001b-aa51-46c9-b042-30fdd0363fea.png">


**免责声明**

##
本工具仅能在取得足够合法授权的企业安全建设中使用，在使用本工具过程中，您应确保自己所有行为符合当地的法律法规。


如您在使用本工具的过程中存在任何非法行为，您将自行承担所有后果，本工具所有开发者和所有贡献者不承担任何法律及连带责任。


除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要安装并使用本工具。


您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。
