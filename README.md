# .net-core-nginx-ssl-docker-compose-config
.net core+ nginx ssl+docker compose config

- 在发布项目的当前目录下创建一个目录：
```bash
  mkdir nginx
```
- 创建一个新的 Dockerfile 并添加这些行：
```bash
  FROM nginx
  COPY nginx.conf /etc/nginx/nginx.conf
```
- 接下来，创建一个 nginx.conf 文件
- 回到程序的根目录，创建 docker-compose.yml
- 运行以下指令来启动这个多容器程序：
```bash
  docker-compose up
```
  **or**
```bash
  docker-compose up -d
```
