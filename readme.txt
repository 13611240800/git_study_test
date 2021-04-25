Git常用命令
Git历史：
管理开源linux代码，分布式管理系统比集中式好在哪里。
   
为什么用版本控制管理系统？记录修改日期、修改内容等等
Git安装：
Linux：sudo apt-get install git
Mac: brew install git
Windows: git-scm.com/downloads

配置用户名和邮箱，用于通信标识
git config --global user.name ‘’
Git config --global user.email ‘’
创建仓库
Git add ...
Git commit -m ...
Git status 
Git diff
 
Git restore ...
Git reset --hard HEAD^  直接还原到上一次提交commit的版本
Github
将本地仓库推送到远程仓库Git push
github配置
Cd ~/  -->   Cd .ssh  -->   生成密钥文件id_rsa.pub
（命令：ssh-kengen -t rsa -C “40665316@qq.com”）
