# 【BBT】ビジネスデータ処理入門【難問チャレンジ課題】

<br/>

Pythonを使用し、東京都文京区の保育園情報を検索・PDF出力するプログラムを作成しました。

読み込みデータは下記、東京都オープンデータカタログサイトの資料を使用しています。

https://www.city.bunkyo.lg.jp/library/opendata-bunkyo/02kosodate-kyouiku/02hoikuen/hoikuen.csv

検索キーは「施設名」とし、データ接続用のExcelファイル「保育園情報【文京区】.xlsx」を作成して動作を確認しました。

***

【課題内容】

- Step1

Pythonを用いてネットワーク上のファイル（主にCSV）を取得し、エクセルファイルとしてローカルに保存します。

例：（東京都オープンデータカタログサイトより）

https://www.opendata.metro.tokyo.lg.jp/fukushihoken/130001_shinryoukensa20220105.csv

<br/>

- Step2

その際、検索キーが1列目になるようにPythonで加工します。

例：1列目を削除するなど

<br/>
 
- Step3

保存したエクセルにデータ接続するエクセルを作成します。

「データ」タブの「データの取得」より接続します。

（保存したエクセルで操作してもOKとします）

<br/>
 
- Step4

別シートに単票を作成し、検索キーをVLOOKUPなどを利用し検索キーを入れると単票が出来上がるように作成します。

例：名前と住所を表示するなど

<br/>
 
- Step5

Pythonを用いて指定した検索キーの単票をPDFで保存します。
