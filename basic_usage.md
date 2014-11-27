# 基本的な使い方

## BaseXサーバを起動する

BaseXサーバを起動するのは
```
basexserver
```
を実行すればよい。  
ただし、何もオプションを付けずに起動すると、フロントで動いてしまうので、バックエンドで動かしたい場合は-Sオプションを付けて起動する。
```
basexserver -S
```
バックエンドで動いているbasexserverを停止させる場合は
```
basexserver stop
```
とすることで、停止させることができる。

## BaseXサーバにBaseXクライアントから接続する
BaseXサーバに接続をするには、BaseXクライアントを使用する。
```
basexclient
```
を起動すると、usernameとpasswordを聞いてくるので、設定しているユーザー名/パスワードか、もしくはデフォルトのadmin/adminを入力すると、認証を完了してクライアントを使用することが出来る。
```
デフォルトではadmin/adminでログイン出来る
Username: admin
Password: admin
```
