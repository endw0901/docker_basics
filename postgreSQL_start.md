# postgreSQL開始


## 

```
// インストール(version, useridは別途確認)
docker run --name my-db -p 5432:5432 -e POSTGRES_USER=dev -e POSTGRES_PASSWORD=secret -d postgres:9.6

// コンテナ確認
docker container ls -a

// 方法① run : 新規コンテナ開始

// 方法② exec：起動中のコンテナでbash起動
docker container exec -it xxxxxx(container id) bash

// 方法③ start：停止済みのコンテナを再起動
docker container start -ai xxxx(container id) 

```


|コマンド|内容|
|:------------|:-----------|
|||
|||
