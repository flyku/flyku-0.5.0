## 欢迎使用 flyku.

##Flyku is an automated, modular development framework. The goal is to reduce duplication of work in the front-end development process, so that you pay more attention to the program itself.

flyku 是自动化，模块开发
目的是减少前端开发过程中的重复工作，使你更关注程序本身。

##文件后缀名必须是htm  否则打包后不可以跳转a连接

## 功能
#### 自动化生成项目结构
一条命令，完成项目的结构

#### 集成常用的 jquery underscore 库等
jquery 主要用于功能的开发，underscore 用于数据的处理等

#### 集成开发阶段使用的模块化开发库 seajs
seajs 用来完成开发阶段的模块加载和调试

#### 新型的模版组成方式，模版即模块。
每个模块都是一个文件夹，每个模块由以下文件构成:
* m.html/hogan/vm/jade 模版文件，支持4种，自动识别编译
* index.js 本模块的js业务逻辑文件
* index.json 本模块的测试数据
* data.js 模版的数据处理逻辑部分

###支持less功能
###打包后自动编译less文件

###新建存放非jq插件的插件文件夹


添加cmd文件

添加regedit  路径为：
HKEY_CURRENT_USER => Software => Classes => Local Settings => Software => Microsoft =>windows=>shell=>MuiCache


执行：flyku -g  创建项目

执行：flyku -s http  开启服务

flyku -b xxx.html 添加一个模版

