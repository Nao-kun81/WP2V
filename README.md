# WP2V概要

WordPressブログは記事別で1日あたりのPVの増減を確認することはできませんが、WP2Vを使えばどの記事が1日にどれくらい読まれているのかが分かります。記録はすべてGoogleスプレッドシートに保存されますので、毎日のPVの増加も管理しやすいです。

## main
main（wp2v_main_verX.X）はGoogleスプレッドシートに記録します

### 使い方
GCPでSheet APIのキーを取得する。記録するスプレッドシートにクライアントメールを追加して、スプレッドシートキーをソースコード内の指定された場所に貼り付ける。get_py.pyの変数にWordPressに登録しているメールアドレスまたはユーザ名とパスワード、記事一覧ページを代入する。

## cui
cui（wp2v_cui_verX.X）はCSVファイルとして記録します
