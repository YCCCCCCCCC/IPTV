# **使用说明：**
## **为了保护仓库PHP源码，已经对源码进行加密处理，使用方法如下：**
1.首先将phpso文件夹中的扩展下载至你本地指定目录，比如`/home/php-so/tonyenc.so`  
2.然后在PHP主配置文件添加`extension = /home/php-so/tonyenc.so`如果你不懂，可以用宝塔面板部署，如下图所示：
![](https://raw.githubusercontent.com/youshandefeiyang/IPTV/main/logo/jiami.jpg)
3.添加完成后记得保存并重启服务器，然后访问PHP或使用PHP-CLI即可生效！  
4.`gudou.php`使用方法：
需要在ROOT的安卓手机安装抓包工具（抓包精灵/小黄鸟），并安装9004版谷豆（腾讯应用宝下载），然后登录自己的手机号码，开启抓包后筛选关键词aut002，然后puser是你的手机号，你需要记录`ptoken`和`pserialnumber`以及`cid`，本源码只适合安卓版本！！  
最后你访问`http://xxx.xxx.xxx:xxx/gudou.php?phone=你的手机号&ptoken=你的ptoken&pserialnumber=你的pserialnumber&cid=你的cid&id=谷豆频道对应id`即可观看谷豆！！