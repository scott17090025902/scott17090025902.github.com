---
layout: post
title: "小小md,隐含大奥秘"
category: 技术
---

git上的readme是md格式的,这里博客的博文也是md的,因此就好奇md到底跟普通的文本有什么区别.

这一来,发现md原来如此好用.其他功能就不说了,下面就记录几个使用频率极高的技巧.

----------
①可以用\#号代表标题
一个\#代表一号标题,两个代表二号标题,依次类推.效果如下
#一号标题
###三号标题

---------------
②粗体斜体
用*包裹就是粗体,两个\*包裹斜体,三个*包裹粗斜体
*粗体*
**斜体**
***粗斜体***

---------------
③分割线
输入3个以上短横线就是分割线,这个已经用到了
就是这样\-\-\-\-
-------------------
④代码
也很方便,只要按两下TAB键,就是代码格式喽

        public class Singleton1 {
            private Singleton1() {}
            private static final Singleton1 single = new Singleton1();
            public static Singleton1 getInstance() {
                return single;
            }
        }
-----------------------
⑤链接
\[Markdown语法简介\]\(http://wowubuntu.com/markdown/index.html\)
用以上语法,就得到以下效果,是不是很方便呢
[Markdown语法简介](http://wowubuntu.com/markdown/index.html)

------------------------
⑥图片
\!\[图片\]\(/path/to/img.jpg\)
图片也是一样的道理,只不过前面多个\!
效果就是下面这样
![博客园log](http://www.cnblogs.com/images/logo_small.gif)

