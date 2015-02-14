---
layout: post
title: UTF-8エンコーディングされたCSVファイルをExcelで開く
---

UTF-8エンコーディングされたCSVファイルをExcelで開くと文字化けします。
そこで文字化けせずに開くことのできるマクロを作成したので公開します。
[tools repository](https://github.com/fightpm/tools) からreadUTF8CSV.xlsm をダウンロードしてください。

本マクロはWindows版のExcelおよびExcel for MAC2011のどちらでも使えます。


<strong>操作方法</strong>

1.CSVファイルの読み込み先の先頭セルを選択します。

2.マクロを実行し[ファイルを開く]ダイアログボックスでファイル名を指定して[開く]ボタンを押します。
