# hugo-ocitutorials-poc

# 設定

## ▼ 前準備
### ● dev containersの準備

拡張機能から検索してインストール

![alt text](content/images/README/search_devcontainers.png)

### ● Rancher Desktopを用意する

Rancher Desktopインストール後、起動しておく

## ▼ setup手順

適当なディレクトリで`git clone`して`hugo-ocitutorials-poc`ディレクトリを作成

```
git clone https://github.com/koi141/hugo-ocitutorials-poc
```

`hugo-ocitutorials-poc`ディレクトリをVS Codeで開いた後、以下のポップアップがでてくるので、「コンテナーで再度開く」を選択

![alt text](content/images/README/reopen_container.png)

出てこなければ、コマンドパレットから実行
![alt text](content/images/README/rebuild_container.png)

無事作成できたら続くコマンドを実行
```
hugo server -D --poll 700
```

以下のリンクにフォワーディングされるので、アクセスするとテストページが見れる。

```
http://127.0.0.1:1313
```