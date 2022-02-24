# CyberSecurity I Exam 2022 問題用紙

## 問1 [netcat]

1. netcatを用い，Chatを行うサーバー/クライアント側のコマンドをそれぞれ記述せよ

2. netcatを用い，ファイルを転送するサーバー/クライアント側のコマンドをそれぞれ記述せよ

## 問2 [password crack]

1. リポジトリ上の shadow1 及び passwd1 ファイルから シングルモード及び辞書攻撃を用いてパスワードを解析せよ，辞書ファイルはリポジトリ上の passwd.listを用いよ。formatはcrypt または md5crypt を使用せよ。

回答は **ユーザー名:パスワード** の形式でマークダウンのリスト形式で記述せよ。

2. リポジトリ上の shadow2 及び passwd2 ファイルから シングルモード及び辞書攻撃を用いてパスワードを解析せよ，辞書ファイルはリポジトリ上の passwd.listを用いよ。formatはcrypt または md5crypt を使用せよ。

回答は **ユーザー名:パスワード** の形式でマークダウンのリスト形式で記述せよ。

## 問3 [port scan]

1. nmap を用い 192.168.30.0 - 192.168.30.127 の範囲のIPをPingスキャンするコマンドを記述せよ。

2. nmap を用い metasploitable2のすべてのポートに対してヴァージョンスキャンを行うコマンドを記述せよ。

## 問4 [Metasploit Framework]

Metasploit Frameworkを用いて Metasploitable2上のvftpd の Backdoorを開く Exploit を作成するコマンドをすべて記述せよ

## 問5 [Online Password Cracker]

Metasploitable2上のftpアカウントを辞書攻撃で解析するコマンドおよび結果を記述せよ。 
なお辞書はuser.list および passwd.list とする。

## 問6 [Packet Sniffer]

tcpdump または wireshark にて metasploitable2 との http 通信のみキャプチャーする フィルターコマンドを記述せよ

## 問7 [不正アクセス]

リポジトリの secure.n22.log はアクセスログである
SSHの不正アクセスは正規表現 'pam_unix(sshd:auth): authentication failure' 及び 'Failed password for invalid user' で取得できる。以下の質問に答えよ

1. 不正アクセスのrootアクセスの件数を数えよ
2. 不正アクセスのroot以外の不正アクセスユーザー(invalid user)のユーザーのTOP3をリスト形式で記述せよ
3. 不正アクセスが一番多いIPアドレスのアクセス件数と発信国を記述せよ

## 問8 [自己評価]

この講義に対するあなたの自己評価点は100点満点中何点だと思うか，点数を記述せよ

## 問9 [講義の感想]

1. この講義で学んだことをリスト形式であげよ
2. この講義への感想を記述せよ
