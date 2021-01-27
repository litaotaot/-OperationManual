#### 查看开放端口
    firewall-cmd --list-all
#### 设置开放端口
    <!-- firewall-cmd --add-service=http-permanent -->
    sudo firewall-cmd --add-port=80/tcp --permanent (添加80端口)
#### 重启防火墙
    firewall-cmd --reload
#### 查看nginx状态
    ps -ef | grep nginx
#### 关闭nginx
    nginx -s stop
#### 启动nginx
    nginx 
#### 重加载nginx
    nginx -s reload