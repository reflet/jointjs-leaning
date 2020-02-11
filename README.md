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

## 参考サイト
- [jointjs.com](https://www.jointjs.com/opensource#Download-JointJS)
- [joint api](https://resources.jointjs.com/docs/jointjs/v3.1/joint.html)
