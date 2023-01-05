# らぼちっくげーとmlflowとPyTorch Lightningを利用したらくらく実験管理のリポジトリ
学習コードはこちらになります。
dockerの学習環境を立ち上げて実行する流れです。

docker-composeのバージョンはdocker-compose<=1.29.1

使い方
```
$docker-compose up
or
$docker-compose up -d
```

dockerコンテナが立ち上がると[jupyter server](http://localhost:8888)が立ち上がります。
パスワードはrun.shに記載してあります。

kaggle petfinder2の学習データはkaggleからダウンロードし、/workdir/work/inputディレクトリに配置してください。
学習コードは
/workdir/work/notebook/laboticgate_mlflow_logger_kaggle_petfinder2.ipynb
となります。
