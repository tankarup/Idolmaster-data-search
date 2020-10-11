# Idolmaster data search
## 概要
* Googelアシスタント(Actions on Google)でアイドルマスターに登場するアイドルのデータを調べます。
* 現在アプリは未公開です。下記の方法で自分のPCにインストールすればGoogleアシスタントで使えるようになります。「アイドルマスターデータ検索」と話しかけると起動し、例えば「天海春香の身長は？」と問いかけると「158cm」と答えを返します。
* 他アイドルからの呼び名にも対応しており、「はるるんの身長を教えて」と聞いてもOKです。

## 使い方
* 今のところはまだGoogleアシスタントには登録されていません。自分でインストールする必要があります。
1. Actions on Googleの開発環境を整える。
1. Actions on Google Console でプロジェクトを作成する。
1. このリポジトリからsdkフォルダをダウンロード
1. "sdk\settings\settings.yaml"を開き、projectIdを作成した自分のプロジェクトのIDに書き換える。
1. コマンドプロンプトでダウンロードしたsdkフォルダに移動
1. `gaction push`でActions on Google Consoleにアップロード
1. webhookでfirebaseを有効化
1. Testで動く、はず。

## 謝辞
* アイドルのデータは im@sparql のデータを使用させていただきました。
* アイドルの呼び名はニコニコ大百科の呼称表ページから使用させていただきました。
