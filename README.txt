Hacker information collection, used to collect information about the target.
Direct operation of specific usage.
Example:
python3 Hacker Tool set.py
python3 Hacker information collection.py
python3 translate.py
python3 arp.py
Please modify the SMTP. Login and SMTP. Sendmail () parameters before calling the mailbox forge script.
Ddos.py is the user I wrote with python2.7 please
Self modify the attack target inside
Defense ddos
Defense ddos: please first execute install. Py =>fyddos.

Then the defense ddos script starts. If you are attacked by ddos, execute.

Netstat -ntu | awk '{print $5}' | cut -d: -f1 | sort | uniq-c | sort -n.

Command to view your IP. Detailed article: http://www.cnblogs.com/haq5201314/p/8351960.html

python shell.py -h
-a  asp Trojan horse 
-j  jsap Trojan horse 
-p php Trojan horse 
-v Edition

python3 Sqllinject.py

python3 WebmasterTools.py
Usage: [-z Subdomain mining][-p Side of the station inquiries][-x http status query]

Options:
  -h, --help    show this help message and exit
  -z SUBDOMAIN  Subdomain mining
  -p SIDE       Side of the station inquiries
  -x HTTP       http status query

I didn't have time to go to school before I uploaded the scripts I finished.

My blog: http://www.cnblogs.com/haq5201314/




Distinguish.py用于批量安装工具包，方便大家安装工具


These scripts and methods of use are all in my blog. Please dig or use this script.

The updated scripts are as follows:
cms.py #For mining target CMS targets His accessories are data.json
csrfjiance.py #Used to detect CSRF vulnerabilities
sqlzhuruapi.py #This is a script for mass mining site SQL injection
urltiaozhuan.py #This is a script for mining URL jump holes
Distinguish.py #This is the two generation of an information collection script
dianjijieci.py #This is a script that excavated clicking hijacking



python3 exploitsearch.py
Usage: exploitsearch.py [options]

Options:
  -h, --help  show this help message and exit
  -m          Save the home directory in the local area
  -w          Save all the attack loads of Web
  -s SEARCH   search exploit
  -y          Save the Long-range all exploit
  -b          Save the local all exploit


CVE-2018-2894任意文件上传漏洞检测POC：在Weblogic任意上传文件里面


2018年7月31号新增加的
dedecms远程文件写入exp 15年的
phpcms中转注入漏洞批量验证

Linux信息收集脚本
直接在目标机运行就行，信息保存在save.txt

收集的信息有：
首先要获取系统信息：
系统名称
本地ip
主机名
本地dns
环境变量
shell程序
hosts文件
路由信息
arp缓存
计划任务
挂载磁盘
mail目录
history文件
home/root/bin/sbin目录

获取用户信息
当前权限
用户信息
本地用户
在线用户
hash加密规则
hash信息
用户组信息
最后登录信息
最后登录用户信息
所有用户的计划任务

安全扫描
是否能无密码sudo
conf配置文件
ssh的密钥文件
是否能root登录
敏感配置文件扫描
关键字含有config、web.xml、database、pass的文件
uid为0用户
敏感服务匿名
空密码用户
zip/tar.gz/sh/pl/py/rb/txt/bak后缀文件

cms_debug是一个集合多种CMS插件的项目 目前版本1.0，已集合Asp_CMS的插件
Cms_debug is a collection of multiple CMS plug-ins. Now version 1, the plugin that has already assembled Asp_CMS.


WDCP爆破是专门针对wdcp后台进行爆破的

云悉指纹用于识别web指纹

MS17010是自己闲着无聊写的检测脚本

ECShop-exploit ECSHOP RCE 漏洞复现教程：VULNSPY实验-ECShop <= 2.7.x 全系列版本远程代码执行高危漏洞利用

SPLOITUS抓取了一个不错的exploits搜索引擎

xss_payload
是用于进行xss检测的

LEFI
是用于进行文件包含漏洞扫描的

这段时间比较忙没有及时更新写的脚本，在此说声抱歉。很多写过的脚本，具体作用我也忘的差不多了
请各位自行使用和了解,Thanks

By 九世 time 2018.11.16 0:11

base64 _injection.py 是用于进行base64注入的脚本，他要求你先填写你的url，在填写里面的id
例如：http://xxx.com/ss.php?id=MTM
先填：http://xxx.com/ss.php?id=
在填ID=13
此脚本针对无防御的站点

测试站点：http://yyyhhg.com

搜索更多类似的站点:google语法：inurl:.php?id=MTM

Base64_injection.py is a script for base64 injection. It asks you to fill in your URL first and fill in the ID in it.
For example: http://xxx.com/ss.php?Id=MTM
First fill in: http://xxx.com/ss.php?Id=
Filling in ID=13
This script is for defenseless sites
Test site: http://yyyhhg.com
Search for more similar sites: Google grammar: inurl:. php? Id = MTM

By 九世 time:2018/12/2

c2项目是我第一个接触c2通信所写出来的脚本
具体使用方法：
server:demo.py IP port or demo.exe IP port
client:修改gc.html里的连接配置http://127.0.0.1/gc.html，连接服务器并执行命令（可过360）
视频:[c2通信实现—其他—视频高清在线观看-优酷](https://v.youku.com/v_show/id_XMzk2NDI2MjI0MA==.html?spm=a2hzp.8253869.0.0)


C2 project is my first script to contact C2 communication
Specific methods of use:
Server: demo.py IP port or demo.exe IP port
Client: Modify the connection configuration in gc.html http://127.0.0.1/gc.html, connect to the server and execute commands (up to 360)

BY 九世 2018/12/14

新c2是我重新写的一个，他支持端口扫描，交互式的shell，文件上传，Linux后渗透信息收集。不足：有一定的BUG，但是服务端不会断开连接。

The new c2, which I rewrote, supports port scanning, interactive shell, file upload, and post-Linux infiltration for information collection. Insufficiency: There are some BUGs, but the server will not disconnect.

By 九世 2018/12/30

更新了一个wifi_dos攻击脚本
功能有：
一键开启网卡监听模式
MAC洪水攻击
Deauch攻击
SSID扫描

Update a wifi_dos attack script
The functions are:
One-click Open Network Card Monitoring Mode
MAC flood attack
Deauch attack
SSID scan

祝各位新的一年新年快乐
Happy New Year to you all

By 九世 2019/1/4

2019/1/11添加了新的thinkphp_5.* 远程代码执行利用脚本
支持单个利用，与批量

New thinkphp_5. * Remote Code Execution Utilization Script was added to 2019/1/11
Support single use, batch

By 九世 2019/1/11

更新了之前写的网易云音乐搜索，其实这个就是抓网易云对应的音乐ID，然后去指定的地方下载
补天爬虫，为了方便各位挖洞者收集URL，做了个对应的爬虫。具体看里面的使用说明，可爬公益SRC和专属SRC子域名批量查询和单个查询

Update the previous written music search of Netease Cloud, in fact, this is the corresponding music ID of Netease Cloud, and then go to the designated place to download.
Butian crawler, in order to facilitate the excavators to collect URLs, made a corresponding crawler. See the instructions in detail, you can climb public SRC and exclusive SRC subdomain name batch query and single query.

By 九世 2019/1/19

UAC旁路是为了以后后渗透好做事所写
参考文章来源于：http://www.ggsec.cn

UAC Bypass is written to infiltrate good work in the future.
Reference article from: http://www.ggsec.cn
By 九世 2019/1/24

windows文件查询用于查询页面指定的路径，用于后渗透方便探索目标windows有没有敏感路径或者日志等等。由于方便携带我将其用url来解析获取路径在进行查询。windows-file.txt就是，扔到web容器下用windows-file.py输入url路径即可

Windows file query is used to query the path specified by the page, and it can be used to penetrate into the target windows to find out whether there are sensitive paths or logs, etc. Because it is easy to carry, I use URL to parse the access path and query it. Windows-file.txt is to throw it under the web container and enter the URL path with windows-file.py.

By 九世 2019/1/25

这是我研究了chm钓鱼所写出的，为了方便快速生成。将在file文件里面生成的start.html放入Easy CHM中生成对应的chm，将fanvicon.ico,放入
你的apache目录，Linux的话他会自动帮你移动，windows下的话不会。
chm钓鱼：https://422926799.github.io/2019/01/27/Chm-fishing/

By 九世 2019/1/27


This is what I wrote about chm fishing, in order to facilitate the rapid generation. Put the start.html generated in the file file into Easy CHM to generate the corresponding chm, put fanvicon.ico,
Your apache directory, Linux, he will automatically help you move, windows will not.
Chm fishing: https://422926799.github.io/2019/01/27/Chm-fishing/

By IX 2019/1/27

CVE-2018-18852是cerio路由器的CVE，github上有py2的，我这里写了个py3的

CVE-2018-18852 is the CVE of the cerio router, py2 on the github, I wrote a py3 here.

By 九世 2019/1/30

新增了一个子域名爆破，具体请看：https://422926799.github.io/2019/02/03/Subdomain-blasting/

Added a sub-domain blast, see: https://422926799.github.io/2019/02/03/Subdomain-blasting/

By 九世 2019/2/2

子域名爆破改进版，子域名爆破.rar那个

By 九世 2019/2/3

子域名爆破新增加了端口扫描和网页截图，不是rar的那个，适用于windows。如果Linux用户请自行下载Chrome的驱动和浏览器
扔到脚本目录，驱动下载地址：https://sites.google.com/a/chromium.org/chromedriver/downloads，指定端口扫描，不要把80和443去掉。

By 九世 2019/2/9

网易云下载那个是网易云音乐下载的进化版，可以搜索，下载，在线播放等应该说是打开浏览器自动播放

By 九世 2018/2/12
