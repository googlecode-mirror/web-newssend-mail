PHPでメール送受信を行うためのサンプルプログラム。主な利用目的はWeb上で見つけたテキスト情報をメールとして送信し、（タイトルに含まれる文字列でメールボックスの自動振り分けが出来るGMailなどの）メールサーバで整理・閲覧するためのWebインターフェース。

ここは、[メインSubversion](http://oasis.halfmoon.jp/cgi-bin/websvn/listing.php?repname=web-newsend-mail)のバックアップです。

### 主な機能 ###
  1. web-newssend
    * ニュース記事送信（送信先アドレス固定、タイトルに振り分け用文字列付加）
  1. web-newsread
    * ニュース記事閲覧（読み取りアカウント固定）
  1. mailviewsend
    * Net\_IMAPによるIMAPサーバの閲覧
    * Net\_POP3によるPOP3サーバの受信トレイ閲覧
    * Net\_SMTPによるメール送信
    * Net\_MIMEによるメール送信

### 動作画面 ###

![https://lh4.googleusercontent.com/-789D7VC-l54/UUBaCekyIKI/AAAAAAAABXI/B6iRtQyE7uQ/s800/web-newssend.jpg](https://lh4.googleusercontent.com/-789D7VC-l54/UUBaCekyIKI/AAAAAAAABXI/B6iRtQyE7uQ/s800/web-newssend.jpg)
<br />web-newssend : ニュース記事送信 Webインターフェース


![https://lh3.googleusercontent.com/-rXIChdx6zoQ/UUBaDihYcMI/AAAAAAAABXI/wRpKEddnGpA/s800/web-newsread.jpg](https://lh3.googleusercontent.com/-rXIChdx6zoQ/UUBaDihYcMI/AAAAAAAABXI/wRpKEddnGpA/s800/web-newsread.jpg)
<br />web-newsread : ニュース記事閲覧 Webインターフェース


### 動作環境 ###
  * Linux/Free BSD
  * PHP