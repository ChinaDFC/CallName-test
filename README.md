<!-- 
    git status     查看状态
    git add .      添加所有有改变的文件或文件夹
    git commit -m '注释'    提交到本地仓库
远程仓库管理(增删查)
    git remote  查看远程仓库别名
    git remote -v 查看别名和地址
    git remote add 别名 地址
        地址：
            1. ssh协议
            2. https协议
    git remote rm 别名    删除
推送到远程仓库中
    git push -u origin master
    
密钥管理
    1. 生成rsa非对称密钥
        ssh-keygen -t rsa   //再敲3次回车
    2. 查看并复制公钥内容
    3. 将公钥内容放到GitHub服务器上
        右上角头像 -> settings -> SSH and GPG keys -> new SSH key -> title随便写，Key粘贴公钥内容 -> Add SSH key
 -->