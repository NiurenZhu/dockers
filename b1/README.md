# SAP B1 DIAPI DOCKERS
B1 DIAPI的容器

### 安装包 | packages
* packages/Windows.tar.gz               操作系统缺失的链接库
* packages/SqlNativeClient.tar.gz       SqlServer数据库连接库（默认2012版）
* packages/Prerequisites.tar            基础运行环境（从安装包用7zip压缩）
* packages/DI API.tar                   DI API安装包（从安装包用7zip压缩）

### 构建镜像 | building
* tomcat:ibas-b192
~~~
docker build --rm --force-rm -f ./dockerfile-b192 -t tomcat:ibas-b192 ./
docker run -d --name ibas-b192-demo -p 8080:8080 tomcat:ibas-b192
~~~

### 鸣谢 | thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>
[Color-Coding](http://colorcoding.org/ "咔啦工作室")<br>
