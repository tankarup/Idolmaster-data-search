# Idolmaster data search

https://assistant.google.com/services/a/uid/0000008a55b1ac73?hl=ja-JP

## 概要
* Googelアシスタント(Actions on Google)でアイドルマスターに登場するアイドルのデータを調べます。
* Googleアシスタントに「アイドルマスターデータ検索」と話しかけると起動し、例えば「天海春香の身長は？」と問いかけると「158cm」と答えを返します。
* 「身長が160cmのアイドルは？」と聞くと、該当するアイドル一覧を教えてくれます。
* 他アイドルからの呼び名にも対応しており、「はるるんの身長を教えて」「デコリーナ先輩の誕生日は？」と聞いてもOKです。

## 使い方
* Googleアシスタントから使用できます。自分でインストールする場合は以下の手順でインストールしてください。
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
* アイドルマスターはバンダイナムコエンターテインメント社が所有するコンテンツです。
