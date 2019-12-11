# JEKYLL
jekyll编译环境

## 使用说明 | instruction
* jekyll:latest
~~~
docker build --rm --force-rm -f ./dockerfile -t jekyll ./
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll bundle install && bundle exec jekyll build
~~~

### 鸣谢 | thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>
