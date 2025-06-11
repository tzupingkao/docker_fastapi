## Referenc
- [Docker五部曲之一：容器术语介绍](https://blog.csdn.net/qq_45295475/article/details/135426978)
- [Docker五部曲之二：Docker引擎](https://blog.csdn.net/qq_45295475/article/details/135434809)
- [Docker五部曲之三：镜像构建](https://blog.csdn.net/qq_45295475/article/details/135434814)
- [Docker五部曲之四：Docker Compose](https://blog.csdn.net/qq_45295475/article/details/135434820)
- [Docker五部曲之五：通过Docker和GitHub Action搭建个人CICD项目](https://blog.csdn.net/qq_45295475/article/details/135611462)
- [Docker 教程](https://www.runoob.com/docker/docker-tutorial.html)

## 指令參考
- 打包docker image
  - docker build -t fastapi:v1 -f ./Dockerfile .
- 啟動 docker container
  - docker run -itd -p 8000:8000 --name fastapi fastapi:v1 
- 查看 docker image 列表
  - docker image ls
- 查看 docker container啟動狀況
  - docker ps -a
- 查看 docker container log資訊
  - docker logs container_name

- docker compose打包image
  - docker compose build
- docker compose啟動全部service
  - docker compose up -d
- docker compose關閉全部service
  - docker compose down
- docker compose 查看service執行狀況
  - docker compose ps -a
- docker compose 查看log資訊
  - docker compose logs service_name

- volume查看
  - docker volume ls
- volume刪除
  - docker volume rm vol_name