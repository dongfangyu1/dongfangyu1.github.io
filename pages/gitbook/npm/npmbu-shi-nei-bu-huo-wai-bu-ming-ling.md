

现象

    npm默认安装路径修改后，出现“xxx”不是内部或外部命令

原因:

    没有配置path

	示例:

	express -v

解决办法:

    安装路径

	     D:\myapplication\nodejs

		 

	安装路径新建文件夹

       	 node\_cache

		 node\_global

		 

	查看全局的当前包的安装路径

	npm root -g

	

	重新设置环境变量

		npm config set cache  "D:\myapplication\nodejs\node\_cache"

		npm config set prefix "D:\myapplication\nodejs\node\_global"

	

	查看全局的当前包的安装路径

	npm root -g

	

    进入环境变量

    新建系统环境变量	

         NODE\_HOME

         D:\myapplication\nodejs  安装路径

		 

	下面这段话加在Path后面

	\*%NODE\_HOME%;%NODE\_HOME%/node\_global;%NODE\_HOME%/node\_modules;\* 



     重启cmd,安装gulp插件

     npm i gulp -g

	 

	 检查是否安装成功

	 gulp -v



     安装express

	 npm i express -g

	 npm i express-generator -g

   

npm镜像

 淘宝 npm 地址：

 http://npm.taobao.org/

 

设置镜像

npm config set registry https://registry.npm.taobao.org



检查是否设置成功

npm config get registry

npm info express





nodejs 升级流程

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

n latest





















