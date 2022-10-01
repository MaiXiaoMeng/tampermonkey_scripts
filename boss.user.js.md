## **写在前面**

> **前言**
>
> 关于昨天发了个贴吐槽找工作难,好多人问是怎么在 BOSS直聘 上标注若比邻黑名单的, 所以我来教你们了
>
> 按照目前我去面试的情况来看, 现在这个境况下空出来的岗位大概率也是别人忍受不下去的坑, 所以尽量避免无效面试,避坑就尤其重要了, 毕竟面试白跑三小时不如打三小时游戏
>
> 这个脚本是我自己写的,暂时只有支持BOSS直聘,不能保证永久更新(已经支持 BOSS 直聘、智联招聘、前程无忧), 也不提供任何的技术支持, 如果你更好的建议可以私信我, 但我不一定会听....
>
> 本脚本以纯学术交流使用,无针对任何公司,组织,或者个人,如果哪位高人利用此脚本侵犯公司,组织,或者个人的利益,请不要来找我！一切和本人没有半毛钱关系！
>
> 创建这个章节的目的在于为我节省时间，而不是反复地解释一些琐碎的安装使用问题，如果您已经认真检索过本章节的内容，确认没有符合的 FAQ 能帮到您，
>
> 请通过 [Facebook](https://www.facebook.com/MaiXiaoMeng)  or  [Telegram](https://t.me/MaiXiaoMeng) 联系我，这是能和我直接对话的最有效方法
>
> 最后，祝大家早日找到好工作！！！就酱紫

## 安装教程

### 1. 安装脚本管理器 **`必须`**

比较知名的脚本管理器有：Tampermonkey，Violentmonkey，Greasemonkey，脚本猫。

这里以功能最强的 Tampermonkey 为例：

> Tampermonkey，俗称“油猴”，是一款免费的浏览器扩展和最为流行的用户脚本管理器。
>
> 所谓脚本就是一段代码，它们能够优化您的网页浏览体验。安装之后，有些脚本能为网站添加新的功能，有些能使网站的界面更加易用，有些则能隐藏网站上烦人的广告。

**根据您的浏览器前往对应扩展商店安装  Tampermonkey 扩展：**

| 浏览器       | Tampermonkey 下载地址                                                                                                                                                                                                         | 安装方法                                                                                                          |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Chrome浏览器 | [Crx搜搜扩展商店](https://www.crxsoso.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo)（推荐）或  ~~[Chrome 网上应用店](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)~~（被墙）  | [点击查看](https://www.baiduyun.wiki/zh-cn/crx.html?spm=1664612349106#chrome%E6%B5%8F%E8%A7%88%E5%99%A8)             |
| Edge浏览器   | [Crx搜搜扩展商店](https://www.crxsoso.com/addon/detail/iikmkjmpaadaobahmlepeloendndfphd)（推荐）或  ~~[Edge 外接程序](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)~~（很慢） | [点击查看](https://www.baiduyun.wiki/zh-cn/crx.html?spm=1664612349106#edge%E6%B5%8F%E8%A7%88%E5%99%A8)               |
| 火狐浏览器   | [Crx搜搜扩展商店](https://www.crxsoso.com/firefox/detail/tampermonkey)（推荐）                                                                                                                                                   | [点击查看](https://www.baiduyun.wiki/zh-cn/crx.html?spm=1664612349106#%E7%81%AB%E7%8B%90%E6%B5%8F%E8%A7%88%E5%99%A8) |

安装成功后浏览器扩展栏将出现如下图标就是安装成功了：

![Tampermonkey](https://vkceyugu.cdn.bspapp.com/VKCEYUGU-0d8c17ea-3b18-45d5-bf2f-64e5c812dfc9/16b28aa3-ac95-4085-a563-8447399b566c.png)

### 2. 安装脚本【BOSS 直聘 跨境黑名单】**`必须`**

> 请确保第 1 步的脚本管理器 Tampermonkey 已安装成功。然后点击下列地址安装网盘助手脚本

👉 **[BOSS 直聘 跨境黑名单](https://greasyfork.org/zh-CN/scripts/448162)**

打开安装页面，点击下图中绿色按钮

![微信截图_20221001164406.png](https://tva1.sinaimg.cn/large/006UJlBGgy1h6pvu3kf6qj30r50ditf4.jpg)

在弹出的窗口中继续点击安装，成功后窗口自动关闭，**（注意：安装完成后没有任何提示信息）**

![微信截图_20221001165417.png](https://tva1.sinaimg.cn/large/006UJlBGgy1h6pw1t9vj6j30q90d97ah.jpg)

### 3. 打开 BOSS直聘职位搜索页面 查看是否正常显示黑名单就可以了

👉 **[BOSS直聘职位搜索页面](https://www.zhipin.com/web/geek/job?query=%E8%B7%A8%E5%A2%83%E7%94%B5%E5%95%86%E8%BF%90%E8%90%A5)**

### 4. 附言&联系方式

> 下面的图是会显示黑名单标注的地方, 黑名单标注右键键新窗口打开此链接可以直接跳到这家公司在若比邻的黑名单贴子, 投简历前可以先去看看
>
> 彩蛋： Facebook 聊天框也会显示 AMZ123 的测评黑名单（~~虽然没什么卵用~~）：

![](https://s3.bmp.ovh/imgs/2022/07/20/1aa262064ede048a.png)
![](https://s3.bmp.ovh/imgs/2022/07/20/a8685344af0d6be8.png)
![](https://s3.bmp.ovh/imgs/2022/07/20/b9bf85a3c82dd131.png)
![](https://s3.bmp.ovh/imgs/2022/07/25/b3fa9970fe35767b.png)
![](https://s3.bmp.ovh/imgs/2022/07/23/692476068165aaa4.png)
![](https://s3.bmp.ovh/imgs/2022/07/23/16f06b56747322ed.png)
![](https://s3.bmp.ovh/imgs/2022/07/23/921139007d518388.png)
![](https://s3.bmp.ovh/imgs/2022/07/23/b0edf6a02d5ac7e7.png)
