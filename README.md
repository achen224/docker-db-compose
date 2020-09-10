# Docker DB Compose

資料庫容器組合，包含 MySQL、Redis 與 phpMyAdmin，預設版本如下：

| 容器 | 版本 |
| - | :-: |
| [MySQL](https://hub.docker.com/_/mysql) | 8.x |
| [Redis](https://hub.docker.com/_/redis) | 6.x |
| [phpMyAdmin](https://hub.docker.com/_/phpmyadmin) | 5.x |

## 準備

- [Docker Desktop](https://www.docker.com/products/docker-desktop)

    Docker 與 Docker compose 應用程式

- [Visual Studio Code](https://code.visualstudio.com/)

    專案程式編輯器

- [vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

    Visual Studio Code Docker 外掛

## 使用

1. 建立 docker network
```sh
docker network create docker-db-compose-network
```
2. 啟動 docker compose

```sh
docker-compose up
```

3. 瀏覽器開啟 http://localhost:8080/ 登入 phpMyAdmin

