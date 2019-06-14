# Dockerの基本と環境セットアップ
## Docker
Dockerは使用しているOSにDockerエンジンというコンテナ環境を使うための
プログラムを動かしてその中で独立した環境を用意し、OSやプログラム言語のバージョンコントロールを行います。

## 今回の環境
今回はDockerが公式で提供しているDocker環境のhubから環境をインストールします。
Dockerhub(https://hub.docker.com/)

# インストール手順
```
$ cd /path/to/local_work_dir
$ docker run -it --rm -v `pwd`:/root hseeberger/scala-sbt
・・・省略・・・
root@2ea77ee39bc0:~# pwd
/root
```
## 確認
