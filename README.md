# Github Notes

## Github 博客配置
### Github个人主页配置
配置完成之后可以使用machixian.github.com访问自己的首页

1. 注册一个Github账号
2. 建立一个Github项目，名字为machixian.github.com，这里的machixian一定要和注册的Github账号的名字一样
3. 将项目克隆到本地，执行下面的命令，注意替换当中的machixian为自己的Github用户名
```
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:machixian/machixian.github.com.git
git push -u origin master
```

4. 创建一个index.html，里面随便放置点内容即可
```
echo "This is my Github index page" > index.html
git commit -a -m "Create a index page"
git push -u origin master
```

### 参考资料
* [使用github page 建立个人主页,并绑定域名](http://www.talaland.com/liangdi-2012-04-06-dialy/)
