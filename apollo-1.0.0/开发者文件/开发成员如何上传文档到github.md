###在上传之前首先要在开发成员电脑端配置ssh秘钥，并在开发成员的github账号中设置ssh，上传流程如下：
1.到 https://github.com/SQJP/Apollo 去下载 Apollo1.0,放到本地git工作区。  
2.将readme.md进行翻译，完成后命名为README_cn.md.  
3.应用“git add apollo-1.0.0/文件路径/文件名” 添加文件到虚拟空间。  
4.应用git commit -m "添加XXXXREADME_cn.md" 命令添加到本地仓库 。  
5.关联远程库 git remote add origin git@github.com:SQJP/Apollo.git 。  
6.使用命令git push origin master推送最新修改。  

