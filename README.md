## server
* 创建数据库
* 执行init.sql
* 修改start.bat里数据库相关信息
* 双击start.bat运行


## agent
agent目前打包后运行，动态编译时存在找不到类的问题，以后有空修复，目前只能在idea下运行

* uiServerHost修改为server的ip（core/src/main/java/resources/application-dev.properties）
* 运行core模块下的Application的main方法即可
