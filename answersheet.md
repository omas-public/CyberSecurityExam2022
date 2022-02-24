# CyberSecurity I Exam 2020 回答用紙

## 問1 [netcat]

### 1.
#### サーバー側コマンド

```sh
# nc -nlvp 80

```
#### クライアント側コマンド

```sh
# nc -nv 192.168.33.11 80

```
### 1.
#### サーバー側コマンド 

```sh
# nc -nlvp 80

```
#### クライアント側コマンド

```sh
# nc -nv 192.168.33.11 80

```

## 問2 [Password Crack]

### 1.
```md
<!--  -->

```

### 2.
```md
<!--  ここに回答を記述 -->

```

## 問3 [Port Scanner]

### 1. ping scan

```sh
# nmap -p 192.168.30.0-127

```

### 2. version scan

```sh
# nmapMetasploit Framework --version-all

```

## 問4 [Metasploit Framework]

```sh
# msfconsole
  search vsftpdMetasploitable2上のftpアカウントを辞書攻撃で解析
  use ~//<file>_backdoor 

```

## 問5 [Online Password Cracker]


### 1. コマンド

```sh
# hydra -L user.list -P passwd.list -t 11 192.168.33.11 

```

### 2. 解析結果

```sh
# ここに回答を記述

```

## 問6 [Packet Sniffer]

```sh
# ここに回答を記述

```

## 問7 [不正アクセス]

### 1. rootアクセスの件数

```md
<!--  ここに回答を記述 -->

```

### 2. 不正アクセスユーザーのTOP3

```md
<!--  ここに回答を記述 -->

```
### 3. IPアドレスのアクセス件数と発信国

```md
<!--  ここに回答を記述 -->

```

## 問8 [自己評価]

```md
<!--  100/10 -->

```

## 問9 [講義の感想]

1.

```md
<!--  ここに回答を記述 -->

```

2.
```md
<!--  ここに回答を記述 -->

```
