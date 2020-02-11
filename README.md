# joint.jsを使ってみる

## dockerの準備
dockerイメージを作成します。

```:bash
$ docker-compose build
```

## パッケージをインストールする
npmコマンドでインストールします。

```:bash
$ docker-compose run --rm node npm install
```

