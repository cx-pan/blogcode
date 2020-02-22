# Instructions

## Sync repo

如果在一台新电脑上，要用命令行下载repo，而不是Downloaded ZIP
```
git clone https://github.com/cx-pan/blogcode.git
```

如果已经完成以上步骤，则同步GitHub的代码。如果确认已经同步，则可以跳过这一步
```
git pull origin master
```
检查theme/polarbearsimple文件夹是否有内容，如果没有，则用Downloaded ZIP方式下载theme，解压缩后，手动拷贝将全部文件拷贝到上述文件夹中。

## Writing post

注意多个tag的中间用英文的逗号，两边也是英文的括号
```
tags: [读书, 健身]
```
写好post后
```
hexo server
```
在本地检查，用浏览器打开[http://localhost:4000](http://localhost:4000)，Ctrl+C结束

## Push to Github blogcode repo

检查是否修改了正确的文件
```
git status
```

保存修改
```
git add .
git status （熟练了可以省略此步）
git commit -m "<some message>"
git push -u origin master
```

## Push to [cx-pan.github.io](https://cx-pan.github.io) and deploy
```
hexo clean && hexo deploy
```

