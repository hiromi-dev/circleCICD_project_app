# プロジェクト開始 command

```
1)$ docker-compose run --rm --no-deps web rails new . -fT -d postgresql

2)$ docker-compose build

3)config/database.ymlへ移動しデータベースと接続

4)$ docker-compose run --rm web rails db:create

5)$ docker-compose up -d
```

## gem 追加

```
$ docker-compose run web bundle install

sh接続で確認
$ docker-compose run web sh

```
