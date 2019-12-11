# MYSQL CLIENT
MySql脚本运行环境

## 主要内容 | content
* mysql-client:latest
~~~
docker build --rm --force-rm -f ./dockerfile -t mysql-client ./
docker run \
    -it \
    -v <folder to sql>:/sqls \
    --link <mysql server container name>:mysql \
    mysql-client
~~~

### 鸣谢 | thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>
