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

ポート番号とは
--------------

    インターネット上の通信において、複数の相手と同時に接続を行うためにIPアドレスの下に設けられたサブ(補助)アドレス。単にポートと略されることもある。

例えるなら
----------

    IP アドレスは住所
    ポート番号は入り口

HTTP のポート番号は **80**

HTTPS のポート番号は **443**

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

OSI 参照モデル
--------------

OSI 参照モデルとは

    国際標準化機構(ISO)によって策定された、コンピュータの持つべき通信機能を階層構造に分割したモデルである。
    OSI基本参照モデル、OSIモデルなどとも呼ばれ、通信機能（通信プロトコル）を7つの階層に分けて定義している。

OSI 参照モデル7階層
-------------------

<img src="https://cacoo.com/diagrams/6f3p1xNvmOy69a0b-AAF42.png" align="center">

アプリケーション層
------------------

    アプリケーション層は、アプリケーションプロセスのための共通アプリケーションサービスへ直接接続して実行する。またプレゼンテーション層に対して要求も行う。

どこで決めてるの？
------------------

IETF (Internet Engineering Task Force)

    インターネットに関連する技術の標準化を促し、インターネットの円滑な運用を図っている国際的組織の名称である。
    インターネットに関連する技術の標準的仕様について議論、策定を行い、主にRFC（Request for Comment）と呼ばれる文書として公開している。

