+++
title = "あばうと"
date = 2022-01-01T00:00:00+09:00
template = "static.html"
+++

あばうとのページ。

<img src="../images/1920x1080.jpg" alt="サンプル画像" width="50%">

これは<span style="color: red; ">赤文字</span>です。


![サンプル画像](../images/1920x1080.jpg)

画像は「static/images」へ入れて管理していく方針。

固定ページと記事投稿は、相対リンクの階層が異なるので、記述に注意する。

記事投稿
- ../../images/xxx.jpg
- `![テキスト](../../images/xxx.jpg)`

固定ページ
- ../images/xxx.jpg
- `![テキスト](../images/xxx.jpg)`


## 環境

- パソコン: X230（Lenovo ThinkPad）
- OS: Linux Mint 20.3（Xfce）
- Zola v0.17.2


## 補足

サクッと使う個人的な用途で小規模を想定。

blogフォルダへ投稿を詰め込んで、タグで仕分けるイメージ。

Zolaで個人的に使うシンプルなテーマ。

短時間で作ったので、大雑把にやっつけです。

マイナーチェンジ版

