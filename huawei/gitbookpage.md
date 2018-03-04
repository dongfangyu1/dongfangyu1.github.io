GITBOOK环境搭建指导

参考文档:

```
http://3ms.huawei.com/km/groups/2954837/blogs/details/5202965
http://pages.huawei.com/codeclub/guides/tools\_gitbook  工具和服务章节
https://yuzeshan.gitbooks.io/gitbook-studying/publish/gitpages.html
```

cmd窗口配置npm代理:

```
npm config rm proxy
npm config rm http-proxy
npm config rm https-proxy
npm config set no-proxy.huawei.com
npm config set registry http://w3cloudnkg-sit1.huawei.com/ccloud/nexus/content/groups/npm-all/
```

创建git page

```
 http://pages.huawei.com/codeclub/guides/tools\_code\_pages
 浏览器访问
     http://pages.huawei.com/serviceom/gitbook/
 自定义域名访问
     http://serviceom.page.huawei.com/
     dongfangyu.page.huawei.com
```

本地git仓库目录

```
D:\workspace\gitbook\gitbook
```

 本地编辑目录

```
D:\workspace\mybook\Import\serviceombook
```



