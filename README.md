TeraTerm Macros
===

自作TeraTerm向けマクロ

## Description

### FirstSetup.ttl

CentOS7を対象とした初回セットアップ用マクロ
以下をセットアップします。
* yumアップデート
* wget bzip2 gcc openssl-devel readline-devel zlib-devel makeのインストール
* postfixの削除
* SELinuxの無効化
* dockerのインストール
* gitのインストール
* rubyのインストール
* chefのインストール

### CollectRemoteFile.ttl

リモートサーバのファイルをSSHでローカルPCに取得するマクロ
取得対象のファイルはマクロファイル内に記載してください。

## Requirement

* Windows(execute OS)
	* ttpmacro.exe
* Linux Server(Setup OS)
	* CentOS7

## Usage

### FirstSetup.ttl

対話式でセットアップが進む為、実行するだけでOK

### ColectRemoteFile.ttl

マクロ内に取得するファイルの情報を追記し、実行するだけでOK

## License


## Author

[negimatencho](https://github.com/negimatencho)
