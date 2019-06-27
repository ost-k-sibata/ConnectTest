# ConnectTest
アカウント接続確認リポジトリ

プッシュ確認済み
公開鍵をGit Bashのssh-keygenで作成
※Win10端末の場合、SSHクライアントがプリインストール済みのため、そっちのssh-keygenでも可。

## Win10付属SSHクライアントで認証する場合
プル対象のGitサーバへSSH接続をコマンドで試し、known_hostsへの追加を行っておく必要がある。
(TortoiseGit,SourceTree での追加方法は現状ない。それをやるならクライアントをPuttyにする。)
