# phore-masternode-automation
script of masternode setup. include updating.

this script helps your masternode setup, or update.
it supports automatic setup and update.

このスクリプトはマスターノードをセットアップ・アップデートしたい方用です。
自動的なセットアップ・アップデートを行います。
## やっていること
1. 各種パッケージ・アップデート
2. phored, phore-cli, phore-tx のダウンロード・インストール
3. 新規インストールの場合プライベートキーを入力する必要があります。
## 使い方
```
curl https://github.com/liray-unendlich/phore-masternode-automation/raw/master/JPN-masternode-setup.sh | sh -v 1.2.2 -u
```

### オプション説明
- -v | --version : バージョンを指定します。 ex. -v 1.2.2
- -u | --update : クライアントのアップデート ex. -u
- -i | --install : クライアントの新規インストール ex. -i

マスターノードを新規にインストールされる場合は -i オプションを
既存のマスターノードをアップデートする場合は -u オプションをご利用ください。
