@startuml

ユーザー -> webサーバ :ログイン
webサーバ -> dbサーバ :照会
dbサーバ ->dbサーバ :ログイン

