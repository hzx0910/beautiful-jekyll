#Cellular-Z 网优APP详细介绍

Cellular-Z发布一年了,在这一年里也积累了很多用户,获得了不少同学们的喜爱,但是一直以来都没有一个详细的功能介绍出来,有些功能做出来了,大家却不清楚什么意思或者怎么使用,现在我在这里对APP功能一一介绍,让喜欢Cellular-Z的同学们更了解它,更好的利用它,希望这个介绍来的不是太晚。
 

##现有功能介绍

###卡槽/SIM/运营商/小区及邻区
![Alt text](./1521525811861.png)

这部分也是网优同学们最关心的功能了,对比其他APP,Cellular-Z优势主要有下面几点:

- 按照系统层级关系,将信息从底至上(卡槽/SIM/运营商/小区及邻区)分层次整理排列,结构清晰易懂。
- 安卓5.0及以上的系统支持双卡相关信息的区分及显示,这是其他大多数类似APP不具备的。
- 安卓7.0及以上的系统支持获取LTE的EARFCN及GSM的ARFCN,可据此查询到对应的BAND/频率信息。

目前APP在不同网络下可以获取的参数如下:

- **LTE** : TAC/PCI/ECI/RSRP/RSRQ/SINR/EARFCN
- **GSM** : LAC/CI/RXLEV/ARFCN/BSIC
- **WCDMA/TDSCDMA** : LAC/CI/RXLEV/UARFCN
- **CDMA/CDMA-2000** : NID/BID/SID/CDMA DBM/CDMA ECIO/EVDO DBM/EVDO ECIO/EVDO SNR

###WiFi
![Alt text](./1521525862957.png)

Cellular-Z WiFi模块可以显示附近WiFi热点的详细信息及信道图,Cellular-Z的信道图是专门开发的特殊图表,支持2.4GHz及5GHz不同WiFi热点显示到同一个信道图上,对于空白比较长的信道间隔做了省略处理.

###位置
![Alt text](./1521528337412.png)

位置模块采用高德定位,输出坐标为WGS-84全球标准
**定位类型**
 GPS | CELL | WIFI | CACHE | OFFLINE | UNKNOWN
 :-:   | :--: | :-:  | :-:  | :-:  | :-:  
  卫星 | 基站 | WIFI | 缓存 | 离线 | 未知
**卫星类型**
 |GPS | 北斗 |GLONASS | QZSS | GALILEO | SBAS|
| :---:   | :---: | :---:  | :---:   | :---:  | :---:  |
 | 美国| 中国 | 俄罗斯 | 日本 | 欧盟|`星基增强系统`|

###SpeedTest 速度测试
![Alt text](./1521525923351.png)

Cellular-Z内置**Ookla SpeedTest**速度测试,Ookla SpeedTest是世界上最权威的速度测试应用,在全球各地都有服务器,支持查看Ping值、下载、上传速度,所以我把Ookla SpeedTest集成进来,方便大家随时测试网速.

###室内室外覆盖测试
![Alt text](./1521528410863.png)

- **室外覆盖** : 目前APP可以缓存10分钟内的覆盖记录,在地图页面可以看到历史轨迹也可以导出为CSV格式的表格
![Alt text](./1521528949249.png)

- **室内覆盖** : APP支持手动/预设轨迹/传感器自动三种模式测试,自动识别记录两个卡槽和WiFI的覆盖情况,目前支持测试结果CSV文件导出,可结合室内地图源文件进行二次分析,也可在APP内部选取不同的参数进行截图记录.


##后续开发计划

- [ ] 高通ROOT方案(带信令)

- [ ] 基站工参导入

- [ ] 覆盖测试参数分段

- [ ] 桌面小工具

##下载地址及二维码
![下载地址二维码][1]


<http://a.app.qq.com/o/simple.jsp?pkgname=make.more.r2d2.cellular_z>

##联系方式
![QQ群二维码][2]


邮箱 : heiljersey@163.com

QQ群 : 686600841


  [1]: https://hzx0910.github.io/cellular-z/introduce.files/image002.jpg
  [2]: https://hzx0910.github.io/cellular-z/introduce.files/image004.jpg