# bootstrap-neetcoin
This is the NEETCOIN Wallet Bootstrap-file for local synchronization.  
This file is compressed and has a file name indicating the date of update.  

これは、NEETCOINウォレットのローカル同期用のBootstrapファイルです。  
このファイルは圧縮されており、ファイル名は生成時期の日付を示しています。
（日本語の説明は下部）  

## How to
When using, it need to __uncompress__ and __copy__ to the correct place with the correct file name.  
This copy works needs to be done in the state where the wallet is not in active(no working). 

* The correct filename is 'bootstrap.dat'.
* The correct place(PATH) to be copied is the root directory where the executable file(.exe) of the wallet is located.  
 
After copy completed, start up wallet exe.  
Until the file date of update, synchronization from localfile'bootstrap.dat' will begin.  

## Note
* Even if you quit Wallet exe on the way, synchronization will start from the continuation point though, it is not recommended. If possible, it is necessary to finish as the end point. So please do this work when your device has time.  
* Synchronization is until the update date when Bootstrap was created. In order to bring it up to date, so need a net sync after that.  
* After synchronization is all completed, you can be deleted 'bootstrap.dat'.

## 使い方
使用する前に、圧縮を解凍し所定の正しい場所へ正しい名前にリネームしてコピーする必要があります。  
このコピーを行う際は、ウォレットは動作していない状態で行ってください。  

* リネームする正しい名前は「bootstrap.dat」です。
* コピーする場所は、ウォレットの実行ファイル（exe）があるルートフォルダーです。

コピー完了後、ウォレットを起動します。  
ローカル同期は生成された更新日まで行われます。  

## 注意
* 同期途中でウォレットを終了しても同期は継続点から開始されますが、推奨できません。 可能であれば、中途でやめず完了してください。 その為、時間があるときにしてください。
* 同期は、Bootstrapが生成されたときの更新日までです。 それを最新の状態にするためには、その後ネット同期が必要です。
* 同期がすべて完了したら、 'bootstrap.dat'を削除することができます。
