# README
## このリポジトリについて
- rails tutorialアウトプット用のリポジトリです。

## 使い方
### 環境構築
```
docker-compose run app rails new . --force --no-deps --database=postgresql
docker-compose build
docker-compose up
docker-compose run app rails db:create
```

### コンテナの立ち上げ・コンテナに入る場合
```
docker-compose up
docker exec -it rails_tutorial_app_1 /bin/bash