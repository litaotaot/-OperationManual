#### 初始化
    git init

#### 查看当前下状态
    git status

#### 创建用户名及邮箱地址
    git config --global user.name
    git config --global user.email

#### 进入.ssh
    cd ~/.ssh

#### 创建公钥和秘钥
    ssh-keygen -t rsa -C 'email@xx.com'

#### git打开id_rsa.pub
    cat id_rsa.pub

#### 关联远程仓库
    git remote add origin git@gthub.com:xxxxxxx.git

#### 关联后推送远程仓库
    git push -u origin master