◇ 概要 ◇
	学生の第1、第2、第3希望と各研究室の人数制限から研究室配属を提案します。

◇ 動作条件 ◇
	Anacondaパッケージ + PyOt5 + networkx
	Anaconda2-4.3.0では動作確認済みです。


◇ ファイル構成 ◇
	[assign.ipynb]
		配属を提案するcsvファイルを作るプログラム

	[wishable.csv]
		学生の配属希望の例です。これと同じ形式のものを用意する必要があります。

	[lab_capacity.csv]
		研究室の人数の上限の例です。これと同じ形式のものを用意する必要があります。

	[result.csv]
		上記2つのファイルを使って決定した研究室配属です。'1'とあるのが配属する研究室です。
	
	[readme.txt]
		このファイルです。

◇ インストール ◇
	Anaconda
	PyOt5
	networkx

◇ アンインストール ◇
	ディレクトリごと削除してください。

◇ つかいかた ◇
	wishtable.csvと同じ形式で学生の希望を含んだファイルを作成します。
	lab_capacity.csvと同じ形式で研究室の人数の上限を含んだファイルを作成します。
	ファイル名は英語にしてください。
	Jupiter notebookでassign.ipynbを開き、全てのセルを実行します。
	出現するウィンドウの'Student's wish'に拡張子を除いた配属希望表のファイル名を入力します。
	'Lab capacity'に拡張子を除いた人数制限のファイル名を入力します。
	実行すると'result.csv'というファイルが作られます。
	学生ごとに配属先の研究室を'1'、それ以外を'0'で表しています。

