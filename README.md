# 基于docsify的个人博客网站，具有多语言切换、分页、页脚和代码复制功能。
## 介绍
- 参考网站：[7habit.top](https://7habit.top)
- 官方文档：[https://github.com/docsifyjs/docsify-cli](https://github.com/docsifyjs/docsify-cli)

>7habit是一个基于docsify生成的个人博客网站，主要实现多语言控制。简单的侧边栏和顶部导航，markdown文字。这个主要分支是初始版本，并且是免费的。
  1. 网站的主页配置默认是英文，如果你想默认为中文可以自行切换。
  2. 根目录下的`sidebar、navbar、README`文件需与主语言对应，主语言文件夹下的README需和根目录下的README相同。
  3. 其他语言自行配置`sidebar、navbar、README`。
  4. 语言切换由`navbar`文件配置。

## Directory structure
```
.  
├── CNAME                     //github配置  
├── .nojekyll                 //github配置不忽略`_开头`的文件  
├── README.md                 //此文档仅用作github展示  
├── sw.js                     //缓存配置  
├── _coverpage.md             //封面  
├── index.html                //网站index配置  
├── style                     //本地css，js，image图片  
├── en-us                     //英文博客目录  
│       ├── 01_proactive      //英文博客下的文章目录之一  
│       └── README.md         //英文博客主页  
│       └── assets            //此目录下用到的静态资源  
│       └── _navbar.md        //顶部导航  
│       └── _sidebar.md       //侧边目录    
└── zh-cn                     //中文博客目录  
        ├── 01_proactive      //中文博客下的文章目录之一  
        └── README.md         //中文博客主页  
        └── _navbar.md        //中文顶部导航栏  
        └── _sidebar.md       //中文侧边栏  
        └── assets            //此目录下用到的静态资源  
```




## 截图：
![PC](/style/PC-index.png)

![](/style/PC-blog.png)

![mobile](/style/mobile-index-2.png)
