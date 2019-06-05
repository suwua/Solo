# Solo
The Java development language used by the Solo blog system is developed. The technical framework uses Spring, SpringMVC, MyBatis, and project construction using Maven. The database uses MySQL


SoloBlog , 该作者是在 [Forest](https://github.com/saysky/ForestBlog)博客系统基础上进行修改的。

SoloBlog 使用的是 Spring+SpringMvc + Mybatis + Layui 打造的一个个人博客模板。

花了十天的时间把整个项目的代码都敲了一遍，熟悉了整个项目，修改了原来的一些 bug，增加了个人信息管理，前台写文章等模块。

喜欢该项目的话，可以给项目点个 star，如果你想在这基础上修改，那么建议你 fork 该项目，然后再修改哦。





项目安装步骤：

##### 1、克隆项目 

克隆或者下载项目到本地，解压，使用IDEA导入该项目



##### 2、修改项目配置

将数据库文件solo.sql导入到你的你的数据库,并修改源代码的数据库配置文件db.properties为你的账户名密码。

由于文件上传是传到本地，且和项目文件夹不在一起，就是说是源码和上传目录是分离的。 
由于我们把 uploads 目录默认放到 E盘根目录(见源代码UploadFileController)，因此需要在Idea中进行静态资源映射相关配置。
![](C:\Users\Zhaogw_Lss\Desktop\QQ截图20190605133643.png)

项目启动前首先启动redis，否则会显示404页面

访问地址：http://localhost/login
