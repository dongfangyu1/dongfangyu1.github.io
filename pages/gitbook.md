gitbook官网

```
https://www.gitbook.com
项目访问路径
https://dongfangyu1.gitbooks.io/mybook
```

gitbook仓库克隆地址

```
https://git.gitbook.com/dongfangyu1/mybook.git
```

gitbook安装流程

* 下载nodejs

  ```
   https://nodejs.org/zh-cn/download/current/
  ```

* 检查安装是否成功

  ```
  node -v
  ```

* 安装gitbook

  ```
  npm install gitbook-cli -g

  检测gitbook安装成功
  gitbook -V
  gitbook -h
  ```

* 初始化 GitBook

```
创建 mygitbook 文件夹，并切换到这个文件夹下面
mkdir mygitbook &&cd mygitbook

初始化gitbook工作目录,创建必要的文件
gitbook init

开启本地服务器,自动构建工程
gitbook serve

浏览器访问 
http://localhost:4000/ 
http://127.0.0.1:4000/
```

* 转换为PDF格式

```
 检查pdf转换是否正常 
 gitbook pdf
  
下载pdf转换包
https://calibre-ebook.com/download\\_windows

转换命令
gitbook pdf mygitbook mygitbook/mygitbook.pdf
```

构建工程命令

```
 gitbook build
```

升级gitbook

```
gitbook update
```

下载gitbook桌面编辑器

```
https://www.gitbook.com/editor/
```



