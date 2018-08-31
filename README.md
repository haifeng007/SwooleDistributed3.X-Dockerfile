# SwooleDistributed3.X-Dockerfile

####容器编排
1. 使用Dockerfile创建镜像：docker build .
2. 重命名镜像：docker tag IMAGEID(镜像id) REPOSITORY:TAG（仓库：标签）
3. 容器编排：docker-compose up 


####docker命令
1. 以交互模式启动容器：docker run -it sd:demo /bin/bash
2. 以交互模式进入已运行的容器：docker exec -it swoole /bin/bash
3. 查看所有镜像：docker images -a
4. 查看所有容器：docker ps -a
5. 命令教程：http://www.runoob.com/docker/docker-command-manual.html
