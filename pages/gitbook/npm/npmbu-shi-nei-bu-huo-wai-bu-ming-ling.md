npm默认安装路径修改后，出现“xxx”不是内部或外部命令

原因:

没有配置path

```
示例:
express -v
```

解决办法:

安装路径

```
D:\myapplication\nodejs
```

安装路径新建下面2ge文件夹

```
node\_cache
node\_global
```

查看全局的当前包的安装路径

```
npm root -g
```

重新设置环境变量

```
npm config set cache  "D:\myapplication\nodejs\node\\_cache"
npm config set prefix "D:\myapplication\nodejs\node\\_global"
```

查看全局的当前包的安装路径

```
npm root -g
```

进入环境变量

新建系统环境变量

```
 NODE\\_HOME

 D:\myapplication\nodejs  安装路径
```

下面这段话加在Path后面

```
\%NODE\_HOME%;%NODE\_HOME%/node\_global;%NODE\_HOME%/node\_modules;\
```

重启cmd,安装gulp插件

```
npm i gulp -g
检查是否安装成功
gulp -v
```

安装express检查问题是否修复

```
npm i express -g
npm i express-generator -g
express -v
```



