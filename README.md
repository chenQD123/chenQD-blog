# chenQD123.github.io
这是一个hexo搭建的私人博客
# 部署新的域名
去阿里云查找，想要的域名是否被占，没有则买，买了去云解析DNS管理页面添加cname，给chenqd.wiki和www.chenqd.wiki，
对应的记录值就是github上的仓库名chenQD123.github.io·然后到github的pages管理页面更新阿里云的域名地址
# 新增博客
在source/_post文件夹新增markdown文件即可，但是要做好分类，如以下：
```javaScript
---
categories: 
    - 杂记
    - 
tag: 
    - 考研经验
    - 成都信息工程考研

quicklink: true
---
还有使用<!--more-->只展示部分文章
```
# 部署编辑后的博客
hexo clean
hexo -g -d
