# README

※参照
https://qiita.com/azul915/items/5b7063cbc80192343fc0#dockerfile%E3%82%84docker-composeyml%E3%81%AE%E5%A4%89%E6%9B%B4%E3%82%92%E5%8F%8D%E6%98%A0rails%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E3%82%92%E5%86%8D%E8%B5%B7%E5%8B%95

##初回のみ

1,$ docker-compose build

2,$ docker-compose up -d

3,$ docker-compose run web rails db:create
※sampleAppで実行

## コンテナ起動（rails s）

1,$ docker-compose up -d

2,$ docker-compose run web rails db:create \
※sampleAppで実行

## コンテナ終了(サーバーexit)

$ docker-compose down

## bundle installコマンド

$ docker-compose run web bundle install


