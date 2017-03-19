# **WshShell.Popup()** 

  ポップアップ メッセージ ボックスにテキストを表示します。

---------------------------------------------------------------

## 引数定義
intButton = object.Popup(strText,[nSecondsToWait],[strTitle],[nType])

---------------------------------------------------------------

## 引数
+ object 
    + WshShell オブジェクトです。 
+ strText 
    + ポップアップ ウィンドウに表示するテキストです。 
+   nSecondsToWait 
    + 省略可能です。ポップアップ ウィンドウを閉じるまで待機する秒数を指定します。 
+ strTitle 
    + 省略可能です。ポップアップ ウィンドウのタイトルに表示するテキストです。 
+ nType 
    + 省略可能です。ポップアップ メッセージ ボックスに表示するボタンとアイコンの種類を示す数値です。選択する種類によってメッセージ ボックスの使い方が決まります。 
+ IntButton 
    + メッセージ ボックス終了時にクリックするボタンの番号を示す整数値です。これは Popup メソッドの戻り値です。 

---------------------------------------------------------------


### ボタンの種類

+ 値 内容 
+ 0 [OK] ボタンを表示します。 
+ 1 [OK] ボタンと [キャンセル] ボタンを表示します。 
+ 2 [中止] ボタン、[再試行] ボタン、および [無視] ボタンを表示します。 
+ 3 [はい] ボタン、[いいえ] ボタン、および [キャンセル] ボタンを表示します。 
+ 4 [はい] ボタンと [いいえ] ボタンを表示します。 
+ 5 [再試行] ボタンと [キャンセル] ボタンを表示します。 

---------------------------------------------------------------

###  アイコンの種類

+ 値 内容 
+ 16 [Stop] アイコンを表示します。 
+ 32 [?] アイコンを表示します。 (question)
+ 48 [!] アイコンを表示します。(alert) 
+ 64 [i] アイコンを表示します。(infomation)
