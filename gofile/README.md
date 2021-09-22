# GO FILE
文件服务器filebrowser及http代理gost

## 使用说明 | instruction
* gofile:amd64
~~~
docker build --rm --force-rm -f ./dockerfile -t niurenzhu/gofile:amd64 ./
# 路径：
#  存储：/home/files/
~~~
* gofile:arm32v7 (适用树莓派3B)
~~~
docker build --rm --force-rm -f ./dockerfile-arm32v7 -t niurenzhu/gofile:arm32v7 ./
# 路径：
#  存储：/home/files/
~~~

### 鸣谢 | thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>