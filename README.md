# ChaoXingDownload
### ~~2022.7.11 更新了下载方式，整节课资源批量下载和mp3下载懒得修了（开摆~~
### 2025.3.14 在家赋闲想把以前手动抓包的过程写成插件，感谢AI赋能。
### 已知恶性bug：存在于原作者的逻辑，从课程第一次点进章节会死循环，pdf和word的阅读器一直刷不出来。
### 解决方法：点一下油猴图标就好了。
#### 已知问题：可能视频用浏览器没法下，但IDM插件捕获可以下。
#### 不影响使用的问题：为了修IDM下载空格变成+号的URL解析问题改了文件名，要让视频文件名正常还要再改代码 ~~（大部分人应该不需要吧，改了以后其他文件可能还会有麻烦的尾缀）~~。

给网页版超星学习通添加课件的下载功能的油猴脚本，支持ppt,doc,pdf,mp4(x),flv(x),mp3(x),avi(x)资源的下载，支持整节课资源批量下载（需要浏览器允许，在chrome的默认下载中似乎有最多同时下载数限制，可能需要等待前面的文件下载完成后后面的文件才会开始下载，不是bug！！）。      

点击[这里](https://www.tampermonkey.net/script_installation.php#url=https://raw.githubusercontent.com/gandizm/ChaoXingDownload/master/cxdownload.user.js)（github源，需要科学上网）

或者[这里](https://greasyfork.org/zh-CN/scripts/529786-%E8%B6%85%E6%98%9F%E5%AD%A6%E4%B9%A0%E9%80%9A%E7%AB%A0%E8%8A%82%E7%9B%B4%E9%93%BE%E4%B8%8B%E8%BD%BD)（Greasy Fork）来安装

因为修改了页面，安装后在课程页面可下载的资源下会出现下载链接和复制按钮；课程（小节）标题会被改成一键下载的按钮。

**不完全确保和网课脚本的兼容性**   
#### 如果觉得这个脚本对你有帮助，请给个star，谢谢

