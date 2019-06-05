# 環境について
## 技術スタック概要
- Scala
- Akka HTTP
- MySQL
- Slick
- Docker

OSなどの環境差分を吸収するために今回はDockerを使います。

## Dockerとは
コンテナ化という技術を使ってコンテナという閉じた空間の実行環境を用意してくれます。
Docker以外にもコンテナを使えるものはありますが、今回は一般的なDockerを使ってコンテナ技術の一端に触れていただきます。

## Scalaとは
Scalaは2003年にスイス連邦工科大学ローザンヌ校（EPFL）のMartin Odersky教授によって開発されたプログラミング言語です。
オブジェクト指向プログラミングと関数型プログラミングを両立することができる特徴を持ちます。
JVM上で動くこともあり、Javaとの親和性の非常に高いです。

しかしただのbetter Javaとしてではなくその言語特性を知って使いこなすことで高い生産性と堅牢なアプリケーション構築ができます。

Scalaの実行にはJava 1.8が必要です。
今回はDockreコンテナにそのあたりの実行環境を整えてあるのでそちらに頼りましょう。

## Akka HTTP
Akka HTTPはLightbend社によって開発されている、Scala/Java用のHTTP toolkitです。
ScalaでのHTTP serverを作る時にこのツールキットは非常に強力な助けをしてくれます。

## MySQL
MySQLはオープンソースで提供されているデータベース(RDBMS)の一つです。
多くのwebサイトやアプリケーションで採用されている実績をもち、安定してメンテナスがされています。
CyberBuzz社でもほとんどのアプリケーションで採用されています。

## Slick
SlickはScalaのORM(オーアールマッパー)です。
MySQLをはじめとするデータベースとのデータのやり取りをサポートします。
このORMのおかげでクエリを直接書くことや、実行時のエラーのクッションなどを柔軟に行うことが可能です。

## 各種公式ドキュメント
### Scala
https://docs.scala-lang.org/

### Akka HTTP
https://doc.akka.io/docs/akka-http/current/index.html

### MySQL
https://www.mysql.com/jp/

### Slick
http://slick.lightbend.com/doc/2.1.0/orm-to-slick.html

### Docker
http://docs.docker.jp/




