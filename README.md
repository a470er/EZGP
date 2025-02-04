# EZGP
Image J macro program for measuring Goldmann-Perimetry

# Usage Guide in Japanese

視覚障害認定用ゴールドマン視野検査結果計測プログラム [EZGP_ver0.7]
     2019/10/31 Yuto Iida
1.	概要
ゴールドマン視野計の結果をコンピュータ上で解析することを目的としたプログラムです。

2.	環境
OS： ImageJ(またはFiji)が動作するmacOS, Windows, Linux

3.	セットアップ
1.	ImageJ(またはFiji)のインストール
ImageJ https://imagej.net/index.html
Fiji https://fiji.sc

2.	プラグイン　ActionBarのインストール
ActionBar https://imagejdocu.tudor.lu/doku.php?id=plugin:utilities:action_bar:start
ファイル構成
ImageJ/plugins/ActionBar/ 
ImageJ/plugins/ActionBar/icons/ 
ImageJ/plugins/ActionBar/Action_Bar.jar 

3.	_EZGP.txtマクロファイルのインストール
ファイル構成
		ImageJ/pluguins/ActionBar/_EZGP.txt
4.	使用方法
EZGPを起動して、画像ファイルをドロップして開く
視野計測に適した画角に調整
基準線の指定：中心０度か水平に右へ90度までドラッグし、OKボタンをクリック
視野範囲の指定：ツールを選択し、”t”ボタンを押すごとに視野範囲を登録
	点ツール：中心から指定点までの視野範囲を登録
	線ツール：指定した線分の範囲の視野範囲を登録
全ての視野範囲の登録を完了したのちに、測定ボタンをクリック
視標を指定して、結果を画像上に描画
必要に応じて印刷、保存。視標を変えて測定する場合には基準線の指定から繰り返す
（基準線の設定ボタンを押すと測定の記録は全てリセットされますが、すでに描画された結果は残ります）

