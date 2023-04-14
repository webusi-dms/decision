<p align="center">
	<img alt="logo" src="http://www.webusi.net/favicon.png">
</p>
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">decision v1.1.1</h1>
<h4 align="center">基于SpringBoot+Vue前后端分离的智能决策平台</h4>
<p align="center">
	<a href="https://gitee.com/webusi/decision/stargazers"><img src="https://gitee.com/webusi/decision/badge/star.svg?theme=dark"></a>
	<a href="https://gitee.com/webusi/decision/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg"></a>
</p>

## 平台简介

智能决策平台是一套全部开源的快速开展决策业务的平台，毫无保留给个人及企业免费使用。

* 前端采用Vue、Element UI。
* 后端采用Spring Boot、Spring Security、Redis & Jwt。
* 权限认证使用Jwt，支持多终端认证系统。
* 支持加载动态权限菜单，多方式轻松权限控制。
* 高效率开发，使用代码生成器可以一键生成前后端代码。
* 提供了技术栈（[Vue3](https://v3.cn.vuejs.org) [Element Plus](https://element-plus.org/zh-CN) [Vite](https://cn.vitejs.dev)）版本。
* 特别鸣谢：[element](https://github.com/ElemeFE/element)，[vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)，[eladmin-web](https://github.com/elunez/eladmin-web)。

## 团队产品
https://www.webusi.net

## 更新日志
### 1.1.1 2023-04-14
1.  功能：规则配置页面，逻辑运算符增加：包含、不包含、不等于
2.  功能：规则配置页面，右表达式支持选择数据集字段枚举值，支持单选和多选
3.  功能：决策计算，支持逻辑运算符：包含、不包含、不等于
4.  优化：数据集字段配置页面，数据集字段关联枚举值问题修复

### 1.1.0 2023-03-30
1.  功能：通过antv-x6实现流程拖拉拽
2.  功能：支持决策流
3.  优化：规则引用数据集改用数据集id存储

### 1.0.0 2023-03-21
1.  功能：支持专家模型
2.  功能：支持mysql数据源
3.  优化：解决尖括号解析错误问题
4.  优化：mybatis转至mybatis-plus
5.  优化：调整自动生成代码
6.  优化：调整自动分页

## 核心功能
1.  数据源管理：配置多个业务数据库，当值只支持MySQL。
2.  主属性管理：配置用于唯一标识实体的字段名。如：身份证号码=id_card。
3.  数据集管理：配置可用于决策的数据。
4.  数据字段管理：配置数据集存在哪些可用字段。
5.  规则管理：配置决策规则，支持：max、min、sum、avg、count等常用算法。
6.  策略管理：配置策略，指出何种情况命中策略。
7.  决策引擎：根据调用入参，执行规则和决策计算，输出决策结果。

## 基础功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
16. 缓存监控：对系统的缓存信息查询，命令统计等。
17. 在线构建器：拖动表单元素生成相应的HTML代码。
18. 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。

## 演示图
<table>
    <tr>
        <td><img src="http://www.webusi.net/login-1.png"/></td>
        <td><img src="http://www.webusi.net/policy-2.png"/></td>
    </tr>
    <tr>
        <td><img src="http://www.webusi.net/rule-3.png"/></td>
        <td><img src="http://www.webusi.net/master-4.png"/></td>
    </tr>
    <tr>
        <td><img src="http://www.webusi.net/dataset-5.png"/></td>
        <td><img src="http://www.webusi.net/flow-6.png"/></td>
    </tr>
</table>


## 智能决策平台交流

QQ： 43530640