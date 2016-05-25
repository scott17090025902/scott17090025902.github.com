---
layout: post
title: "小小md,隐含大奥秘"
category: 技术
---

git上的readme是md格式的,这里博客的博文也是md的,因此就好奇md到底跟普通的文本有什么区别.

这一来,发现md原来如此好用.其他功能就不说了,下面就记录几个使用频率极高的技巧.

----------
①可以用\#号代表标题<br />
一个\#代表一号标题,两个代表二号标题,依次类推.效果如下<br />

# 一号标题

### 三号标题


---------------
②粗体斜体<br />
用\*包裹就是粗体,两个\*包裹斜体,三个\*包裹粗斜体<br />
*斜体*<br />
**粗体**<br />
***粗斜体***<br />

---------------
③分割线<br />
输入3个以上短横线就是分割线,这个已经用到了<br />
就是这样\-\-\-\-<br />

-------------------
④代码<br />
也很方便,只要按两下TAB键,就是代码格式喽<br />

        public class Singleton1 {
            private Singleton1() {}
            private static final Singleton1 single = new Singleton1();
            public static Singleton1 getInstance() {
                return single;
            }
        }

-----------------------
⑤链接<br />
\[Markdown语法简介\]\(http://wowubuntu.com/markdown/index.html\)<br />
用以上语法,就得到以下效果,是不是很方便呢<br />
[Markdown语法简介](http://wowubuntu.com/markdown/index.html)<br />

------------------------
⑥图片<br />
\!\[图片\]\(/path/to/img.jpg\)<br />
图片也是一样的道理,只不过前面多个\!<br />
效果就是下面这样<br />
![博客园log](http://www.cnblogs.com/images/logo_small.gif)<br />

---------------------
⑦其他<br />
换行需要按两个回车,当然html的原生标签也是完全支持的,剩下的再去慢慢探索吧

