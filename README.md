# Configs

[⚡ jsDeliver 加速](https://cdn.jsdelivr.net/gh/forliuyifei/Configs@master/)

## 这是一个公开仓库，用于备份各类非隐私的配置文件
*若发现任何不合适的内容请帮忙提醒 😶* 

### [Share](https://www.coolapk.com/apk/com.hengye.share) 微博屏蔽词
屏蔽理由包括但不限于：
- 舔美、精日、哈韩、吹印……恨不得东食西宿的精神肉体双分裂患者。
- 低俗烂俗无限反刍无营养恶意钓鱼引战拱火引流哗众取宠双标阴阳人谣棍歪屁股降智可选全母营销号。
- 低龄幼稚疯狂无脑的流量明星粉丝群体。
- 疯狂刷屏的广告、头条怪。
- 不感兴趣的话题：减肥、健身、美妆、低俗搞笑、乱搞男女关系极其衍生话题……
- 卖减肥长斑假药、劣质产品推销、连胃口都吊不起的小h漫。
- 极端狗奴、精致圣母。

*关于部分用户或关键词的屏蔽，不针对其本身，只是为了避免遭受相关群体/话题的精神污染。*

**导入方法：**
需要第三方微博客户端 Share 并购买高级版。（建议找人合租，不贵，闲鱼偶尔也有人出激活码。修改版很容易失效，各种问题）

设置 -> 隐私设置 -> 关键词屏蔽 -> 右上角导入屏蔽词 （文件名为 `Black_List.share_backup` ）

**👉 [下载屏蔽词](https://cdn.jsdelivr.net/gh/forliuyifei/Configs@master/Share%20%E5%BE%AE%E5%8D%9A%E5%B1%8F%E8%94%BD%E8%AF%8D/Black_List.share_backup)**（感谢 jsd 提供的加速服务）

### [药方YAWF](https://tiansh.github.io/yawf/) 配置文件

还网页版微博一个清爽界面   
屏蔽词理由同上
支持正则表达式，例如屏蔽所有涉及张三的微博：/(?=.*张)(?=.*三)^.*$/mu

### banAD.ACL

粉灰机可用的ACL文件
 
屏蔽常用网站、视频、手机rom广告&运营商劫持广告&数据跟踪&开屏广告

### 其它应用配置备份

![IMG_20201228_171702](https://cdn.jsdelivr.net/gh/forliuyifei/img@mater/img/2020/12/1609147035897.webp)

TBD...

## 添加至本地
**使用 Termux**
```
termux-setup-storage
cd ~/storage/downloads
git clone https://github.com/forliuyifei/Configs.git
cd
ln -s /storage/emulated/0/Download/Configs/ Configs
```
*或者 `git clone git@github.com:forliuyifei/Configs.git`*


