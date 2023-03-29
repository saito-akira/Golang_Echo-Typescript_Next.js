仮想インターフェイスへのエイリアス追加

```
sudo ifconfig lo0 alias 127.8.8.8 netmask 0xff000000
```

バックエンドコンテナへのexec bash と バックエンドサーバー起動
```
dokcer-compose exec echo bash
air
```

フロントエンドコンテナへのexec bash と フロントエンドサーバー起動
```
dokcer-compose exec next bash
yarn dev
```