Nagios 4.x 日本語化
==========

![Nagios!](https://raw.githubusercontent.com/NagiosEnterprises/nagioscore/refs/heads/master/html/images/Nagios-clearbg.png)

[![Nagios Core Tests](https://github.com/NagiosEnterprises/nagioscore/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/NagiosEnterprises/nagioscore/actions/workflows/test.yml?query=branch%3Amaster)

NagiosはC言語で書かれたホスト/サービス/ネットワークプログラムで、
GNU一般公衆利用許諾契約書、バージョン2の下でリリースされています。
CGIプログラムは現在のステータス、履歴、などをWebインターフェースを
通じてみることができるようになっています。

ドキュメント、新規リリース、バグレポート、掲示板の情報などは
Nagiosのホームページ https://www.nagios.org を訪れてください。


[機能](https://www.nagios.org/about/features/)
-----------------------------------------------
* SMTP、POP3、HTTP、PINGなどを経由したネットワークサービスの監視
* CPU負荷、ディスク使用率などのホストリソースの監視
* ユーザが開発したサービス監視方法を許可するインターフェースプラグイン
* 「親」ホストを用いたネットワークホスト階層を定義し、ダウンしているホストと到達不可能なホストの検出と区別を可能にする機能
* 問題発生時および解決時の通知（電子メール、ポケットベル、またはユーザー定義の方法による）
* 積極的な問題解決のためのイベントハンドラ定義機能
* ログファイルの自動ローテーション/アーカイブ
* 現在のネットワーク状態、通知、問題履歴、ログファイルなどを表示するためのオプションのWebインターフェイス


変更履歴
-------
重要な変更と修正の要約は
[Changelog](https://raw.githubusercontent.com/NagiosEnterprises/nagioscore/master/Changelog)
を、より詳細な情報は
[コミット履歴](https://github.com/NagiosEnterprises/nagioscore/commits/master)
をご覧ください。


ダウンロード
--------
最新版は https://www.nagios.org/download/ からダウンロードできます。日本語化パッチについては https://www.momo-i.org/chapter5/nagios/4.x.html をベースにしています。


インストール方法
------------
[クイックスタートインストールガイド](https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/4/en/quickstart.html)
はNagiosの起動や監視に役立ちます。


ドキュメントとサポート
-----------------------
* [ユーザーガイド](https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/4/en/)
* [Nagiosコア ドキュメントライブラリ](https://library.nagios.com/library/products/nagioscore/)
* [サポートフォーラム](https://support.nagios.com/forum/viewforum.php?f=7)
* [追加のサポートリソース](https://www.nagios.org/support/)


貢献
------------
Nagiosのソースコードは、GitHubで公開されています：
https://github.com/NagiosEnterprises/nagioscore

Nagiosをより良くするためのアイデアや機能要求がありますか？
バグは[GitHubで課題を開く](https://github.com/NagiosEnterprises/nagioscore/issues/new)によって報告することができます。
もし、Nagiosでセキュリティ関連の問題を発見した場合、連絡してください。
security@nagios.com

パッチやGitHubのプルリクエストを歓迎します。
GitHubのプルリクエストはバージョン管理下のコミットをレビューと変更の議論にリンクし、
誰が関与したかに加えて、どのように、なぜ変更がなされたかを示すのに役立ちます。

Ethan Galstadによって作成されたNagiosの成功は、それをサポートし、バグレポート、パッチ、
および素晴らしいアイデアを提供する素晴らしいコミュニティのメンバーによるものです。
1999年から貢献した多くの人のために [感謝ファイル](https://raw.githubusercontent.com/NagiosEnterprises/nagioscore/master/THANKS) を参照してください。
