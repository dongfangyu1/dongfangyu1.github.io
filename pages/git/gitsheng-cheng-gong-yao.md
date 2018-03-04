sshkey:

ssh-keygen -t rsa -C "dong328662958@qq.com"

三次回车即可生成 ssh key

key 生成目录为 用户名

dfy/.ssh

查看生成的公钥key

cat ~/.ssh/id\_rsa.pub



添加公钥到仓库: 



在本地测试是否联通制定仓库

ssh -T git@git.oschina.net

ssh -T git@github.com

