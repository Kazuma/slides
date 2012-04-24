Web 基礎
========

資料 
----
<span id="url-size">
https://github.com/Kazuma/Textbook/
</span>

1. Web
======

Web ってなに？
-------------

直訳すると蜘蛛の巣

<span id="image">イメージ図</span>
<img src="http://upload.wikimedia.org/wikipedia/commons/b/b9/WorldWideWebAroundWikipedia.png" alt="イメージ図" align="center" height="500px">

Web == Internet ?
-----------------

<pre>
WWW (World Wide Web) は、インターネット上で提供されているハイパーテキストシステム。一般的に Web と呼ばれることが多い。
</pre>

<pre>
Internet は、コンピュータネットワーク自体を指す言葉であり、Web はそのアプリケーション(応用技術)である。
</pre>

<span id="image">イメージ図</span>
<img src="https://cacoo.com/diagrams/YtFSVwXWzGEPRbzK-02C69.png" align="center">

Web の概念
----------

URI とは

    インターネット上に存在する情報資源の場所を指し示す記述方式。インターネットにおける情報の「住所」にあたる。

URL とは

    現在インターネットで広く用いられている URL は URI の機能の一部を具体的に仕様化したものである。

> 参考: [IT 用語辞典 - URI](http://e-words.jp/w/URI.html)

URI の記述
----------

<span id="image">イメージ図</span>
<img src="https://cacoo.com/diagrams/Qk926fUQkzvxRlYj-ABE04.png" align="center">

URI スキームって？
------------------

URI スキームとは

    インターネット上の資源の所在を表すURI(URL)の先頭部分で、資源に到達するための手段を表したもの。

つまり、

    http:  https:  ftp:  mailto

の事

HTTP ？
-------

HTTP とは
---------

<pre>
ハイパーテキスト転送プロトコル (HTTP) は、分散・共同体ハイパーメディア情報システムのアプリケーションレベルプロトコルである。 このプロトコルは、リクエストメソッド、エラーコード、ヘッダ等の拡張を経て、ネームサーバや分散オブジェクト管理システム等、ハイパーテキストのために使う以上に多くの作業のために用いる事ができる、一般的でステートレスなプロトコルである。 HTTP の特徴として、データ表現のタイプ付け、及びネゴシエーションがあり、これによって転送されるデータの独立性が確立されるようなシステムが構築できる。
</pre>
> 参考: RFC2616

もっと短く
----------

HTTP とは
---------

    Webサーバとクライアント(Webブラウザなど)がデータを送受信するのに使われるプロトコル

参考: [IT 用語辞典 - HTTP](http://e-words.jp/w/HTTP.html)

送受信できる内容
----------------

* 画像 (jpg, png, gif など)
* 音声 (wave, mp3 など)
* 動画 (mpeg, mp4, avi など) 

etc..

HTTP 通信を行うには
-------------------

* IP アドレス
* ポート番号

ポート番号とは
--------------

    インターネット上の通信において、複数の相手と同時に接続を行うためにIPアドレスの下に設けられたサブ(補助)アドレス。単にポートと略されることもある。

例えるなら
----------

    IP アドレスは住所
    ポート番号は入り口

HTTP のポート番号は **80**

HTTPS のポート番号は **443**

HTTP 通信の流れ
---------------

<span id="image">イメージ図</span>
<img src="https://cacoo.com/diagrams/W98xLM2mXGtMC3nE-70270.png" align="center">


プロトコルとは
--------------

    ネットワークを介してコンピュータ同士が通信を行う上で、相互に決められた約束事の集合。
    通信手順、通信規約などと呼ばれることもある。 

参考: [IT 用語辞典 - プロトコル](http://e-words.jp/w/E38397E383ADE38388E382B3E383AB.html)

よく使われてるプロトコル
-------------------------

* HTTP (HyperText Transfar Protocol)
* FTP (File Transfar Protocol)
* SMTP (Simple Mail Transfar Protocol)
* POP (Post Office Protocol)
* IMAP (Internet Message Access Protocol)

どこで決めてるの？
------------------

W3C (World Wide Web Consortium)

    WWW で利用される技術の標準化をすすめる団体。
    WWW 技術に関わりの深い企業、大学・研究所、個人が集まって発足した。

