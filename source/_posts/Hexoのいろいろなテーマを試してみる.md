---
title: Hexoのいろいろなテーマを試してみる
date: 2020-08-03 23:40:36
tags:
---
静的サイトジェネレータHexoには様々なテーマがあります。
備忘録を兼ねて、以下に簡単な手順をまとめておきます。

## Hexoテーマ変更手順

1. https://hexo.io/themes/ にアクセスし、お好みのテーマを選ぶ
2. テーマ名をクリックしてGitHubのリポジトリに遷移し、テーマをzipでダウンロード&解凍する
3. ブログのディレクトリ/themesに解凍したフォルダを置く
4. ブログのディレクトリ/_config.ymlの theme: に解凍したフォルダ名を指定する
5. ブログをデプロイする

## デプロイ後テーマが反映されないとき
ブラウザのキャッシュを削除すると表示されることがあります。
一旦コマンドで hexo server と打ってローカルで表示を確認すると、キャッシュなしの表示を確認できます。

## 画像（順次追加）

- corporate
![corporate](https://f.easyuploader.app/eu-prd/upload/20210402004100_6964306f.jpg)

- indigo
![indigo](https://f.easyuploader.app/eu-prd/upload/20210402004115_6739586a.jpg)

- material
![material](https://f.easyuploader.app/eu-prd/upload/20210402004059_516c6e52.jpg)