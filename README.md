我的规则
包含的服务器地址：https://github.com/surge/surge/blob/master/S ...

包括内网穿透规则，具体方式见https://github.com/fatedier/frp

Surfboard 是一个兼容Surge配置文件的Android端网络调试代理工具，官网: https://manual.getsurfboard.com
目前[Ver. 0.8.5.0729 (26)]支持的Surge特性有：
[General]组，目前只用于定义udp-relay，dns-server和skip-proxy。
[Proxy]组，目前支持 Socks5 , HTTP , HTTPS , SS 四种代理方式,同时可以使用「direct」和「reject」作为代理方式。
[Proxy Group]组，目前只支持select类。
[Rule]组，目前只支持DOMAIN类、IP类、GEOIP类和FINAL类规则
[Host]组。具体
用法遵循如下规则。

出国规则
Surfboard规则，适用于三星国行手机
https://github.com/sumsethan/MyRules/raw/master/Rules/Sur ​​fboard.conf

Surge规则，基于Scomper http://t.cn/RQo6viU，添加一些自用规则及自己收集总结的netflix规则。
https://github.com/sumsethan/MyRules/raw/master/Rules/CrossWall.conf

SurgeRecommand规则
https://github.com/sumsethan/MyRules/raw/master/Rules/Sur ​​geRecommand.conf

macServer规则，适用Surge网关
https://github.com/sumsethan/MyRules/raw/master/Rules/macServer.conf

回国规则
适用于 Surge
方便妹子翻回国内看视频听音乐用，包括YouTube及Netflix区域选择及国内节点自动测速链接，同时短时间肉身回国可以选择位置切换默认线路
https://github.com/sumsethan/MyRules/raw/master/Rules/BacktoChina.conf
2018.7.29更新

更新Surfboard规则，添加去广告开关、直连线路选择等「适用于Surfboard 0.8.5.0729 (26)及之后版本」。
2018.5.20更新

添加macServer规则。
2018.5.6更新

©冲浪板规则。
更新其他规则，去除URL重写。
2018.1.18更新

添加Surge推荐规则，大幅精简。
增加内网穿透规则，需在内网建一个SS服务器后使用内网穿透服务暴露到外网。
增加前置代理规则，方便使用其他代理软件。
2017.12.7

初始版本，添加出国/回国规则。
2024年规则地址:https://raw.githubusercontent.com/cutethotw/ClashRule/main/GeneralClashRule.ini
