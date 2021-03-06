# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです
[*Ruby on Rail チュートリアル*](https://railstutorial.jp/)
[Michael Hartl](https://www.michaelhartl.com)著

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にある
ソースコードはMITライセンスとBeewareライセンスのもとで公開されています。
詳細は [LICENCE.md](LICENSE.md) をご覧ください。

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドで必要になる RubyGems をインストールします。

`
$ bundle install --without production
`

その後、データベースのマイグレーションを実行します

`
$ rails db:migrate


最後に、テストを実行してうまく動いてイルカどうか確認してください

`
$ rails test
`

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

`
$ rails server
`

詳しくは [*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
を参考にしてください。

## 12月18日　変更点

layoutフォルダにあったapplication.html.erbをプロジェクトファイル直下に移動した

## 12月23日　メモ

railsの仕組みがだいたいわかったので9章から14章は後でやることに
