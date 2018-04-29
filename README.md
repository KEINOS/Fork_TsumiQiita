# TsumiQiitaとは

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE.md)
[![npm v5.8.0](https://img.shields.io/npm/v/npm.svg?style=flat)](https://nodejs.org/ja/)

MarkdownファイルをQiitaに投稿するelectron製デスクトップアプリです。\
下書きに入りきらない**積みQiita**をするためにご利用ください。

node.jsでビルドが必要です。 **インストール方法は[INSTALL.md](INSTALL.md)** を参照してください。

## 主な機能

- 選択したファイルをQiitaに限定公開として投稿
- 選択したMarkdownファイルをプレビュー
- PCのストレージから任意のMarkdownファイルを開く
- 新規Markdownファイルの作成
- Markdownで編集
- リアルタイムプレビュー
- 最後に編集してから3秒後に自動保存
- タグをつけて投稿

以上の機能により、 **限定公開の草案をローカルに際限なく貯めることを可能にします** 。

### ユースケース

1. クラウドストレージにMarkdownファイルを保存し、任意の端末から編集して置いて本アプリで投稿する。
1. リアルタイムプレビューを見ながら下書きをする。

## 注意

プレビューはQiita上での表示と異なります。あくまで参考程度とご理解ください。

### 動作検証済み環境

- Win10 Version 1709
- macOS 10.13

### TODO

- [x] ~~対象フォルダ選択~~
- [x] ~~Markdownファイル選択~~
- [x] ~~Markdownファイルプレビュー~~
- [x] ~~プレビュー中のファイルをQiitaへ限定公開として投稿する~~
- [x] ~~編集~~
- [x] ~~新ファイル作成~~
- Qiita CSS 適用
- [x] ~~最後に編集してから3秒後に自動保存する~~
- [x] ~~タグを登録できる~~
