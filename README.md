# html5-css3
zencoding emmet 安装使用技巧：

Eclipse中安装zen coding(emmet)的方法：http://jingyan.baidu.com/article/d713063507e72313fdf475ff.html 

Sublime中如何安装emmet ：http://blog.csdn.net/gebitan505/article/details/29565249

notepad++中安装zen coding(emmet)：http://my.oschina.net/yangphere/blog/70981

Win7下快捷键Ctrl+Alt+Enter调出zencoding的心印(koan)，koan一词源于佛语。

生成html5整体结构zencoding写法：html:5

一个比较好的学习zencoding的网页：http://blog.chinaunix.net/uid-22414998-id-3184766.html

生成一个比较综合的框架网页：

html>(head>(title+style+script[src=abc$.js]&#42;3))+body>((.content>.nav>ul>li*5>a>span)+(.sidebar>.top+.middle+.bottom)+.main>.acticle&#42;3>h1{文章标题$}+p)+.footer{版权信息}

一个生成bootstrap结构的zencoding写法：

html>(head>meta+script+link+title)+body>.panel.panel-primary>(.panel-heading>.panel-title{My Html})>.panel-body>.row>.col-md-12>(nav.menu>h2[style=border-bottom:1px solid gray;]>a&#42;3)+br+form.form-horizontal[role=form]>(.form-group>label.col-md-2.control-label+.col-md-2>input.form-control)&#42;3

bootstrap中文官网
http://www.bootcss.com/

        <!-- 新 Bootstrap 核心 CSS 文件 -->
        <link rel="stylesheet" href="http://cdn.bootcss.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <link rel="stylesheet" href="http://libs.baidu.com/bootstrap/3.0.3/css/bootstrap.min.css">
        <script src="http://libs.baidu.com/jquery/2.0.0/jquery.min.js"></script>
        <script src="http://libs.baidu.com/bootstrap/3.0.3/js/bootstrap.min.js"></script>
        
        <!-- 可选的Bootstrap主题文件（一般不用引入） -->
        <link rel="stylesheet" href="//cdn.bootcss.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">
        
        <!-- jQuery文件。务必在bootstrap.min.js 之前引入 -->
        <script src="//cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>
        
        <!-- 最新的 Bootstrap 核心 JavaScript 文件 -->
        <script src="//cdn.bootcss.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
        <script src="http://code.angularjs.org/angular-1.0.1.min.js"></script>

