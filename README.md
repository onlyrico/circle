# 让网页赏心悦目，让阅读回归初心 - Circle 提供更舒适的阅读体验

由染河**全职**开发的产品，每两个月发布一次更新。v2.2.0 即将发布 - 快捷键模块的增强，真正的效率提升。认可我的工作，请我杯[咖啡](https://ranhe.xyz/donate)☕️

为了不饿死自己，v2.0.0 版开始加入高级功能。由于集成了用户体系，决定 v2.0 之后的版本闭源更新。如果有同学对识别算法感兴趣，可以[看这里](https://ranhe.xyz/wang-ye-zheng-wen-ti-qu-suan-fa-yan-jiu-xue-xi/)

------  以下才是正文 ------

简约、优雅、轻量，Circle v2.1.0 版本发布啦！v2.1.0 版本的 Circle 可以是一个简单的阅读辅助工具，可以是一个小说阅读神器、可以是一个故事机，也可以是一个资料整理助手。

比 Safari 阅读模式更强大的阅读助手浏览器扩展 Circle ，是浏览器自带阅读模式的扩充和完善；是电脑阅读网页、看小说、看新闻的不二神器；具有快捷键支持、自定义样式、自定义字体、自定义主题、自动滚动、自动加载下一页、大声朗读、文章大纲（outline）、返回顶部、分栏目阅读、打印阅读模式格式化之后的网页、支持浏览器自带的翻译等阅读辅助类功能。

自研的解析引擎，解析更快速、解析能力更智能。自研的排版引擎，自动屏蔽 html 上的广告和噪音，和格式跑掉说拜拜。纯 js 开发的 Circle 阅读助手浏览器扩展，已经上线 Google Chrome 浏览器、火狐浏览器、Edge 浏览器、360 浏览器、Opera 浏览器。[免费下载安装 Circle](https://ranhe.xyz/circle-install/)

## 关于 Circle

广告太多分散注意力、配色太丑不忍直视、字体太小看不清、排版太乱找不到正文，阅读真的需要这么困难吗？

有没有产品可以把网页中的内容提取出来重新整理，渲染成更方便阅读的排版界面呢？

能够做到这些的产品很多，这类产品最大的问题就是识别正文效果太差，识别失败、识别成非正文、漏掉正文、漏掉主图、图片裂开等都是常事。在我看来目前做的比较好的是苹果系统的 Safari 浏览器。即使是 Safari 浏览器也或多或少的存在此类问题，除此之外 Safari 的设置界面太简单，定制型不够灵活 

为了解决上面普遍存在的问题，Circle 诞生了。Circle 是一款不太一样的浏览器扩展程序，我们采用自研的正文解析引擎，识别成功率大大提高，甚至于比 Safari 还要智能。只需要单击一下（或许不需要），Circle 还你最纯粹的阅读体验，为你更好的阅读保驾护航。如果你正在寻找一款极度轻量化的阅读辅助产品，Circle 也许可以打动你

![Circle 识别效果](https://ranhe.xyz/post-images/parser.png)

上图就是 Cirlce 的默认界面。舒适美观的界面、极易上手的操作、灵活丰富的配置、强大智能的识别算法共同成就了 Circle

## 舒适美观的界面

为了打造更舒适的阅读体验， Circle 内置了 5 款绚丽主题。如图所示：

![Circle 舒适美观的界面](https://ranhe.xyz/post-images/color-theme.png)

### 自定义主题

正如莎士比亚所说 “ 一千个观众眼中有一千个哈姆雷特 ” 不同的人有不同的阅读喜好，内置的主题做不到让所有人都喜欢，所以我们支持灵活的自定义配置。如下图所示：

![Circle 灵活的自定义配置](https://ranhe.xyz/post-images/theme.png)

不仅仅是文字颜色、背景颜色。Circle 还支持自定义滚动条、自定义背景渐变和图片（图片暂未上线）等等

### 跟随系统

针对白天和夜晚的光线不同，阅读的时候为了更舒服，Circle 提供跟随系统自动切换主题功能。且支持自定义不同时间的主题

![Circle 跟随系统](https://ranhe.xyz/post-images/1628575159368.png)

## 独创的网页多栏阅读

大屏幕用户的福利。两栏、三栏、四栏？你说了算！不浪费屏幕上的每一寸空间。

![Circle 独创的网页多栏阅读](https://ranhe.xyz/post-images/column.png)

## 用了会上瘾的多页解析

当前页浏览其他页面内容，小说党的最爱。滚动到页面底部，秒开其他页面的内容

![Circle 用了会上瘾的多页解析](https://ranhe.xyz/post-images/nextpage.png)

大声朗读、自动滚动、跟随系统切换主题、查找关键字、删除内容块、现场编辑等等，只为你更好的阅读

## 极易上手的操作

为了让用户快速上手，Circle 整个操作流程都是经过设计的。如下列举部分逻辑：

  “选项页面” 默认是浏览器单独的页面，考虑到用户在浏览文章的时候想修改配置又不想离开当前页面，为此 Circle 支持当前页面直接访问选项配置页面

![Circle 支持直接打开选项页面](https://ranhe.xyz/post-images/1625040265590.jpg)

为了方便用户沉浸式阅读，Circle 支持多页加载（需要满足存在下页链接的条件）

为了让用户零等待，程序会后台解析页面。正常浏览多页文章时，完全感觉不到加载的动作

为了方便用户多页浏览退出时找不到最后在什么页面，退出 Circle 会自动跳转到最后一页

为了急速展示页面，Circle 取消了 loading 页面，先展示正文，后格式化。实现秒开格式化页面

为了方便用户退出当前页面还需要关闭网页，Circle 提供 “退出关闭” 选项，开启之后退出 Circle 当前页面也会同时关闭

更多细节欢迎自己体验

## 灵活丰富的配置

借助于 Circle ，你可以调整字体，字体大小，字体间距、字体行高，字体粗细、段落间距，页面宽度等等。如下图所示：

![Circle 灵活丰富的配置](https://ranhe.xyz/post-images/style.png)

## 强大智能的识别算法

借助于自研解析引擎的能力，Circle 更智能更强大

### 正文识别效果对比

你可以分别使用 Circle 和其他相关产品访问如下网址对比识别效果

http://www.shb.cas.cn/kjjz2016/201607/t20160712_4639424.html

原始网页效果

![Circle 阅读模式三方原始网页](https://ranhe.xyz/post-images/1615281013027.jpg)

识别效果对比

![Circle 阅读模式效果对比图](https://ranhe.xyz/post-images/1615281038997.jpg)

上面的网址内容结构不够规范，对于大部分产品都是从中间部分开始展示，漏掉了大段的前半部分正文（  Safari 也不例外），除此之外，请大家注意识别之后的**文章标题**！！！！

### 主图识别效果对比

不仅可以完美识别标题和正文，Circle 还可以智能识别主图。业界大部分产品仅仅识别正文，正文主图对于理解正文有时候也是至关重要的。 如下图对比：

infoQ 一篇文章： https://www.infoq.cn/article/m30vgkxw9alvzo9czoay

![Circle 对比 infoQ](https://ranhe.xyz/post-images/1625041363522.jpg)

Circle 识别的效果

![Circle 识别 infoQ](https://ranhe.xyz/post-images/1625041376759.jpg)

Safari 正文都识别不出来，其他产品大多**识别失败**

### 多页解析识别

对于当前文章页面含有下一页链接时，Circle 可以自动加载其他页面追加到当前页面

![Circle 阅读模式多页加载](https://ranhe.xyz/post-images/1617696858472.gif)

## 其他功能介绍

### 打印文章

借助于 Circle 阅读模式你可以打印任何文章。以 “如何看待市场监管总局对阿里巴巴垄断行为作出 182.28 亿行政处罚？会带来哪些影响？”为例展示如何使用 Circle 阅读模式打印知乎文章

原网页如下：

![Circle 阅读模式如何打印知乎文章](https://ranhe.xyz/post-images/1618068826994.png)

直接右键打印效果如下：

![Circle 阅读模式如何打印知乎文章](https://ranhe.xyz/post-images/1618068835801.png)

安装启用 Circle 之后如下：

![Circle 阅读模式解析知乎文章](https://ranhe.xyz/post-images/1618068847977.png)

右键打印如下：

![Circle 阅读模式打印知乎文章](https://ranhe.xyz/post-images/1618068855510.png)

### 直接选择文章（聚焦模式已下线）

Circle 不存在任何预先写好的模版，全部使用算法识别正文。所以对于 Circle 而言，不存在所谓的小众网站，只要是正文，就可以识别并展示。所以 Circle 做到了秒开，只要页面加载完成，立即就可以展示格式化之后的效果

但是算法无法做到 100% 完美效果，为此对于无法识别的正文，你可以使用直接选取正文，噪音信息就可以消失

使用入口（快捷键 f 和右键菜单）

### 大纲展示

当文章中含有子级目录时会统一展示在页面左侧，不含子目录的文章页面不会显示。默认是折叠的，你可以固定和隐藏

![Circle 大纲展示](https://ranhe.xyz/post-images/1628562719721.png)

### 返回顶部

通过“返回顶部”可以快速返回页面最顶部，滚动鼠标离开顶部才会显示滚动到顶部按钮

### 白/黑名单

当前文章网址加入白/黑名单后，访问相关页面匹配到会自动开启。需要匹配整站可以修改网址只保留域名提交即可

同时你可以搜索和翻页查看已存在的白/黑名单

![Circle 白/黑名单](https://ranhe.xyz/post-images/1628575560619.png)

### 快捷键

通过快捷键模块，你可以自定义快捷键，且支持开关快捷键和全局开关快捷键系统

![Circle 快捷键系统](https://ranhe.xyz/post-images/1628562873553.png)

### 右键菜单

通过右键菜单模块，你可以开关右键菜单和全局开关右键菜单系统

![Circle 右键菜单系统](https://ranhe.xyz/post-images/1628575703231.png)

### 配置中心

通过配置中心，你可以导入导出你的设置信息。借助于高级帐户体系，你可以开启自动同步配置，方便不同设备的同步

![Circle 配置中心](https://ranhe.xyz/post-images/1625043160924.jpg)

### 自定义样式

尽管我们的设置页面已经足够灵活，但是仍然存在无法实现的效果，对于专业人员，你可以通过自定义样式实现你自己的任何想法💡

### 本地文件支持

你可以在浏览器使用本地文件，如markdown 文件和纯文本文件，Circle 也可以识别。

## 真实用户评价

文海*：非常棒！简洁，功能也简单，**解析特别快**，用起来舒适！千万不要做复杂化了！！找了N久，是真的，几年了，每隔段时间就找阅读插件，只有这款最符合我的需求~

Andong Wang： Awesome！Apple上习惯了Safari的阅读模式，这个插件一使用我就知道是我想要的感觉了，**简洁**、**美观**。

Yanyan su： 值得五星推荐，比简悦简约不要太多！希望作者做一下导出功能。

chuanliang zang：Reader View、简悦... 还有好几款阅读模式都在用，现在只保留了前面两个，简悦因为交了钱也退不了，功能繁杂不太想用。平常Reader View用的多一些，刚才试用了一下 Circle，一下子就喜欢上了。最喜欢的就是能方便的调节页面宽度、行距、段距(!!)，非常的推荐。

aione：之前用过一个差不多的插件，外国的，十分顺心。这个和我之前用的那个差不多。
我不是来推荐之前那个插件的，我的意思是，可以遇见这么好同类的插件，也是十分不易的

Aeon Khronos：小众软件推荐过来的，确实好用！**赞**！！！

LI Yi：很快很简洁，感谢开发者！非常期待黑白名单~

曾小*：小巧，漂亮，高效！

## 问题反馈

意见建议、产品缺陷和其他任何问题都可以在 https://support.qq.com/products/317910 反馈

## 支持我

如果觉得 Circle 还不错，欢迎升级为高级帐户支持 Circle 更好的发展。你也可以在[这个页面](https://ranhe.xyz/donate)捐赠支持我