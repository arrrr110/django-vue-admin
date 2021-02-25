# Django-Vue-Admin

使用django+vue进行极速开发的全栈管理系统。

[![img](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/newpanjing/simpleui/blob/master/LICENSE) [![img](https://img.shields.io/pypi/v/django-simpleui.svg)](https://pypi.org/project/django-simpleui/#history) [![img](https://img.shields.io/badge/python-%3E=3.6.x-green.svg)](https://python.org/)  ![PyPI - Django Version badge](https://img.shields.io/badge/django%20versions-2.2-blue)[![img](https://img.shields.io/pypi/dm/django-simpleui.svg)](https://pypi.org/project/django-simpleui/)



## QQ群

- QQ群号：812482043

- 由于项目正在启步阶段，第一版预计3月底发，后序会慢慢维护其他版本，有什么不到位的请大家担待~

  <img src='http://pic.pgroom.cn/72851614273011_.pic.jpg' width='200'>

## 源码地址

github地址：[https://gitee.com/liqianglog/django-vue-admin](https://gitee.com/liqianglog/django-vue-admin)

gitee地址：[https://github.com/liqianglog/django-vue-admin](https://github.com/liqianglog/django-vue-admin)

## 平台简介

* 前端采用ruoyi-ui 、Vue、Element UI。
* 后端采用Python语言Django框架。
* 权限认证使用Jwt，支持多终端认证系统。
* 支持加载动态权限菜单，多方式轻松权限控制。
* ~~高效率开发，使用代码生成器可以一键生成前后端代码。~~
* 特别鸣谢：[RuoYi](https://gitee.com/y_project/RuoYi-Vue) ，[Vue-Element-Admin](https://github.com/PanJiaChen/vue-element-admin)，[eladmin-web](https://gitee.com/elunez/eladmin-web?_from=gitee_search)，[Gin-Vue-Admin](https://www.gin-vue-admin.com/)。

## 内置功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
9.  登录日志：系统登录日志记录查询包含登录异常。
10.  在线用户：当前系统中活跃用户状态监控。
11.  定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
12.  ~~代码生成：前后端代码的生成。~~
13.  ~~服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。~~
14.  ~~在线构建器：拖动表单元素生成相应的HTML代码。~~

## 在线体验

演示地址：[https://demo.django-vue-admin.com/](https://demo.django-vue-admin.com/) 账号：demo 密码：123456

文档地址：[https://django-vue-admin.com/](https://django-vue-admin.com/)

## 前端

### 	开发

```bash
# 克隆项目
git clone https://gitee.com/liqianglog/django-vue-admin.git

# 进入项目目录
cd dvadmin-ui

# 安装依赖
npm install

# 建议不要直接使用cnpm安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题。
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev

# 浏览器访问 http://localhost:8080
```

### 	发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 后端





## 演示图

<table>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/cd1f90be5f2684f4560c9519c0f2a232ee8.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/1cbcf0e6f257c7d3a063c0e3f2ff989e4b3.jpg"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/707825ad3f29de74a8d6d02fbd73ad631ea.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/46be40cc6f01aa300eed53a19b5012bf484.jpg"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/4284796d4cea240d181b8f2201813dda710.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/3ecfac87a049f7fe36abbcaafb2c40d36cf.jpg"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/71c2d48905221a09a728df4aff4160b8607.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/c14c1ee9a64a6a9c2c22f67d43198767dbe.jpg"/></td>
    </tr>	 
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/5e8c387724954459291aafd5eb52b456f53.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/644e78da53c2e92a95dfda4f76e6d117c4b.jpg"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/fdea1d8bb8625c27bf964176a2c8ebc6945.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/509d2708cfd762b6e6339364cac1cc1970c.jpg"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-f1fd681cc9d295db74e85ad6d2fe4389454.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-c195234bbcd30be6927f037a6755e6ab69c.png"/></td>
    </tr>
</table>
