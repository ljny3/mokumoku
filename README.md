# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
選択した事業側の課題

①サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

提案内容

「レディースオンリーのもくもく会」を設定できるようにする。これにより、女性利用者が安心して参加できる環境を提供します。


実装方針

もくもく会の作成時に「レディースオンリー」オプションを追加します。これはチェックボックスとして実装し、会の作成者が自由に選択できるようにします。レディースオンリーの会は、会の一覧ページと詳細ページに表示します。

もくもく会の検索機能に「レディースオンリー」のフィルターを追加します。これにより、女性ユーザーは自分たちだけの安心した環境で開催されるもくもく会を簡単に見つけることができます。
以上の提案により、女性利用者がサービスをより使いやすく感じ、活発にもくもく会に参加する機会を増やすことができると考えます。