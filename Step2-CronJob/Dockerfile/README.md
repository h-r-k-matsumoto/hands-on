# hands-on-images-for-cronjob

[Kubernetes Sapporo for Beginners](https://sapporo-beginner-kubernetes.connpass.com/)で利用するcronjobハンズオン用のimageです。

ハンズオンに関しては、
https://kubernetes-sapporo-for-beginners.github.io/hands-on/
を確認して下さい。

# 概要
alpine 3.8をベースにcurlとjqコマンドを追加しています。  
上記ハンズオンのStep1で構築するAPIを呼び出しているため、前提としてStep1のコンテナを作成する必要があります。
