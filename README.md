# household-account-book-swagger

「おおまか家計簿」 Swagger API リポジトリ

## docker コマンド

### docker 立ち上げ (swagger の場合、このコマンドだけで良い)

docker-compose up --build --remove-orphans

### docker リスタート

docker-compose restart

### docker イメージを削除

docker-compose down && docker system prune -a

### docker 停止

docker-compose stop

### docker のコンテナを停止

docker-compose down -v

### build して立ち上げる

docker-compose up -d --build

### app コンテナにログイン

docker-compose exec app bash

## swagger 参考記事

- REST API 設計のためのローカル環境構築(Swagger, APISprout)

  - https://qiita.com/tyoshitake/items/eef5ce0eeee8b816d9a5

- OpenAPI (Swagger) の基本的なあれこれ

  - https://girigiribauer.com/tech/20190318/

- OpenAPI (Swagger) 超入門

  - https://qiita.com/teinen_qiita/items/e440ca7b1b52ec918f1b

- Swagger と REST API の紐付けを Docker compose で実現してみた

  - https://qiita.com/shiminori0612/items/32c3c3fba30b42bc4800
