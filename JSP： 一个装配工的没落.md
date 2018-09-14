## JSP： 一个装配工的没落

原创： 刘欣  码农翻身

没错， 我就是大名鼎鼎的JSP,   服务器端“装配工”之王。 你要是没听说过我就实在太out了，  你要问我到底是干什么的， 其实很简单， 就是把页面模板和数据给装配起来， 变成HTML发送给浏览器， 然后你才能看到啊。

奥， 不， 我一提到装配工之王，  那个叫PHP的已经拿着板砖怒气冲冲的过来了，  好吧， PHP大哥， 你才是老大，最好的编程语言， Web编程之王， 我的意思是Java 装配之王，好吧， 消消气。

1

## 黑暗岁月

遥想当年， Web编程刚刚诞生的时候， 大家只能用Perl , C语言等以CGI的方式来输出 HTML, 那可真是一段黑暗的、可怕的岁月。

我真是难以想象CGI的小伙子是怎么装配网页的，  其实也无所谓装配， 他们就是字符串拼接而已，可怜的孩子们甚至都不知道字符串到底是什么含义。

有图有真相， 看看吧：

![2](http://mmbiz.qpic.cn/mmbiz_png/KyXfCrME6UL1r0gYVVC1QMJsnhMjIXFRl5ugg3eiaydHnmI2Rp9icXLLnB6f3oJBvmbGP03OFAU94mBsEgicuDJUA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这还不涉及到人家用户通过浏览器传递过来的参数， 那处理起来就更不容易了。

我有时候挺佩服这时候的码农的， 用这么低级原始的方式竟然还能写出复杂的Web网站， 实在是了不起啊。

2

## 服务器端动态页面

1996年， “恶名远扬”的微软推出了ASP(Active Server Page)，  这个新的页面装配工和CGI小伙子们可是大不相同， 因为他能够支持在HTML页面中嵌入代码！  这下子动态的Web页面可就轻松多了。

完全可以先用一些可视化编辑器像FrontPage, Dreamweaver 先把界面创建好， 然后码农再其中塞入代码。

![3](http://mmbiz.qpic.cn/mmbiz_png/KyXfCrME6UL1r0gYVVC1QMJsnhMjIXFR7OrTTzb3icWdpoibiaZVBcmrRzpJWt7O67vthhg8YOL84Mc49QunJkDew/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

看看这张图， 你应该能明白ASP装配工是怎么干活的，  页面看起来就像是一个html静态文本， 被<% %>包裹的就是代码了， 装配工需要运行他们， 然后把产生的数据嵌入到html当中。



由于微软的强势， ASP这厮可真是火了一把， 尤其是在中国。



我们Sun公司看到这种情况， 自然会奋起直追， 很快我这个装配工JSP  （Java Server Pages）就诞生了。



ASP主要用VBScript 这样的脚本语言 （ 唉， 我估计微软的Bill Gates实在是太喜欢VB了， 连一个脚本语言也要搞的VB很像）， 我就完全不同了， 我用的可是被无数人喜爱的Java， 跨平台啊。



每当我用这一点嘲笑ASP的时候， 他都会说：  “别整天在这里乱喷了， 说来说去， 你本质上不也是一个模板吗？   你看看你装配的那些页面， 代码和HTML混杂在一起， 搅的乱七八糟， 没有任何美感。 对了，听说你有个JSP中太长了，竟然爆出了无法编译的错误， 实在是太可笑了， 哈哈哈。”



ASP说的没错， 有个不着调的码农把绝大部分的业务逻辑都搞到了JSP 当中， 我实在是无法装配， 只好报错。



不过ASP也好不到哪里去， 也是HTML中混杂这大量代码。

3

## 标签库

















