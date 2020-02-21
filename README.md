# Instructions

## Push to blogcode repository

只用设置一次remote
```
git remote add origin https://github.com/cx-pan/blogcode.git
```

写完日志，检查是否修改了正确的文件
```
git status
```

保存修改
```
git add .
git status
git commit -m "<some message>"
git push -u origin master
```

## Deploy to github.io

```
hexo clean && hexo deploy
```

Go to [GitHub Pages](cx-pan.github.io)
