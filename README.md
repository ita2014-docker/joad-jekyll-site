# Joad

Joadのポータルサイトを作成するリポジトリです。GitHub PagesのJekyllを利用しています。

## ローカル環境

ローカルで確認するためにはJekyllが必要になります。Rubyのツールでgemを使ってインストールすることができます。

```
gem install jekyll
```

## ページの編集

`_posts`以下にMarkdown形式のファイルを置くと自動的にindex.htmlに読み込まれます。ファイルの読み込み順は日付の昇順となっています。（ファイル名に付いている日付はダミーです）

## ページの確認

リポジトリのrootで以下のコマンドを実行するとWebサーバーが起動して、ブラウザから確認することができます。

```
jekyll serve
```
