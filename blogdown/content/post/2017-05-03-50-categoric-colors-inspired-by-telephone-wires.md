---
title: 電話線コードを使った色分類
author: SUGIMOTO Tatsuo
date: '2017-05-03'
slug: 50-categoric-colors-inspired-by-telephone-wires
categories: ['リンク']
tags: ['d3', '色', '折れ線グラフ']
---

(via richardbrath)

表題のブログ記事をかいつまんで紹介します。

---

色でカテゴリー分類するのは、10色程度が限界です。[Colobrewer2](http://colorbrewer2.org/)で選べるのは最大12色。d3は[20色のカラースケールを3種](https://github.com/d3/d3-scale/blob/master/README.md#schemeCategory20)用意しています。

折れ線グラフでは、線のスタイルで区別をつけることができますが、破線や点線はうまく機能しません。なぜならもっとも重要な角（かど）の部分がはっきり見えないことがあるからです。

地図では、道路や線路などを、線のスタイル、グリフ（小さなシンボル）を使って区別しています。Excelでは、グリフを使った折れ線グラフを使っています。しかしグリフを多用するのも目障りで角（かど）の位置を正確に見つけられません。

さて、筆者は電話線のカラーリングをヒントに線を2色で塗り分けることを提案しています。このチャートがランダムな折れ線グラフに、25種のペアカラーを適用したものです。

[![https://gyazo.com/ad524be7c51832f3cdf692b9640697c1](https://i.gyazo.com/ad524be7c51832f3cdf692b9640697c1.png)](https://gyazo.com/ad524be7c51832f3cdf692b9640697c1)

このチャートの利点は次の通り。

1. 折れ線の角（かど）がしっかり認識できる
2. 50本の線がひしめきあっていますが、全体的な傾向を把握することができる（ここでは下落傾向）。
3. 上下にあらわれる線を簡単に識別できる。

もちろんこれが最終的な解決策ではありません。そもそも50本もの折れ線グラフをつくるべきではないかもしれません。

---

わたしは必ずしもみやすいとは思えませんでしたが、読者のみなさんはいかがでしたか。




### リンク
- [50 categoric colors, inspired by telephone wires | richardbrath](https://richardbrath.wordpress.com/2017/04/30/50-categoric-colors-inspired-by-telephone-wires/)