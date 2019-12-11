# jekyll

## 主要内容 | content
* dockerfile                 创建docker镜像

## 使用说明 | instruction
* 本地编译镜像
~~~
docker build --force-rm --no-cache -f ./dockerfile -t jekyll ./
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll bundle install && bundle exec jekyll build
~~~
* 直接使用镜像
~~~
docker run --rm --volume="$PWD:/srv/jekyll" -it niurenzhu/jekyll bundle install && bundle exec jekyll build
~~~

### 鸣谢 | thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>
