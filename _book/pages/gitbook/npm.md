npm镜像

```
淘宝 npm 地址：
http://npm.taobao.org/

设置镜像
npm config set registry 
https://registry.npm.taobao.org

检查是否设置成功
npm config get registry
npm info express
```

nodejs 升级

```
查看帮助
node -h

查看当前版本
node -v

清除npm cache
npm cache clean --force

升级之前还需要安装n模块，n模块是专门用来管理nodejs的版本
npm install -g n
npm install -g n --force  上面命令报错执行这个

升级到指定版本
n 6.11.2
升级到nodejs最新稳定的版本
n stable
```







