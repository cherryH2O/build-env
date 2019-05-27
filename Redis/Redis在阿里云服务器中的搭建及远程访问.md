### 一、redis安装

1. 下载存放在/tmp `wget http://download.redis.io/releases/redis-5.0.4.tar.gz`
2. 在/usr/local创建redis目录 `mkdir redis`
3. 解压至redis目录 `tar -zxvf /tmp/redis-5.0.4.tar.gz -C /usr/local/redis`
4. 进入redis目录，发现还有一层，将redis-5.0.4中的所有文件移出来
