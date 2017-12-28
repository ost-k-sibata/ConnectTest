# ConnectTest
アカウント接続確認リポジトリ

プッシュ確認済み
公開鍵をGit Bashのssh-keygenで作成
アプリごとのpersonal tokenで認証
権限情報は上長に常に確認

やっぱり、OAuth 認証はだめ。
どの端末のSourceTreeか、確証が持てないため(課の人間でない者のアクセスの可能性有)
認証方法は、「Basic」にして、生成したトークンをパスワード欄に入れる。
優先プロトコルはSSHで、トークンにはSSH公開鍵の
読み込み権限「read:public_key」を与えることで、認証可能となる。
(現在 OAuth 認証済みアプリから、「Sourcetreeforwindows」はrevoke済み。)
