# ui

# 環境構築手順

Android と iOS でカウンターアプリを表示できるまでの手順です

https://kurosame-th.hatenadiary.com/entry/2020/03/18/203259

※手順の中の`flutter create [Project Name]`は実行せず、このリポジトリを`clone`してください  
※手順の中ではシェルは`fish`を使っているので、他のシェルの場合は置き換えて実行してください

# サードパーティパッケージのインストール方法

1. [こちら](https://pub.dev/flutter/packages)で探す
1. `pubspec.yaml`を手動で更新する
1. `pubspec.yaml`を更新すると、自動で`flutter packages get`コマンドが走る

# Flutter コードメモ

Flutter/Dart のコードメモを雑多にまとめてます  
https://gist.github.com/kurosame/857f01201ef6934348000bde926a4692

# エラーメモ

## `flutter run`がうまくいかないときがある

`flutter run -v`を実行し、止まった箇所のログでググる

ググっても分からなかった場合は、違うデバイスに変更して`flutter run`
