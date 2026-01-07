## 準備
1. Friction.zipをダウンロードして解凍しておく
2. カーネルのパスを変更  
Friction\python_env\share\jupyter\kernels\python3\kernel.jsonをエディタで開き，  
3行目を現在のpython.exeの場所に書き換える  
バックスラッシュは2個ずつ書く  

## ディレクトリ構成
Friction  
|____ Analysis       * 結果の出力はここ  
|____ Data             * 入力データ一式とconditions.csvをここに置く  
|____ Scripts          * スクリプト一式  
|____ python_env  * python実行環境  
|____ run.bat         *起動バッチ，ここのダブルクリックで開始  

## 使い方
1. 入力データの格納  
解析したいデータとconditionsファイルをここに置く
2. run.batをダブルクリックしてブラウザでjupyter labが表示されるのを待つ
セキュリティの警告が出たら実行をクリック
3. 左サイドバーからScripts/analysis.ipynbをクリック
4. jupyter lab上の実行ボタンで解析
