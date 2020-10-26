# paperlink

Nuxt.js プロジェクトを、レンタルサーバ ＆ AWS環境で運用する練習をします。

## Build Setup

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

```console
(初動時は biuld オプションで実行)
docker-compose up --build

(立ち上がったら web ブラウザで localhost:3000 確認)

(2回目以降はこちらのコマンド)
docker-compose up
```

- 参考コマンド
  - (docker-compose コマンドを実行するときは docker-compose.yml が存在するディレクトリで実行)

```console
(起動中のコンテナの中に入る場合)
docker-compose exec web /bin/bash

(コンテナの中でライブラリ追加 Commander の場合)
# yarn add commander

(コンテナ終了)
# exit

(コンテナの外からモジュールを追加したいとき vuex-persistedstate の場合)
docker-compose exec web yarn add vuex-persistedstate
```
