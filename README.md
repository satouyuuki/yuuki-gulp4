### ローカル環境
* macOS
* node 12.1.0
* nodebrew 8.9.4(nodejsのバージョン管理ツール)<br>
※なくてもいいですが、あると便利です<br>


### 始め方
1. node.jsのバージョン切り替え
```
nodebrew --version
```
ここでバージョンが出ないときはインストール<br>
[わかりやすい参考記事](https://qiita.com/ucan-lab/items/517ee13a2f8769ab866c)
nodeのバージョン12をインストール
```
$ nodebrew install v12.1.0
```
```
$ nodebrew use v12.1.0
```
バージョンが切り替わってるか確認
```
$ node -v
```

1. プロジェクトのクローン

```
$ git clone git@github.com:satouyuuki/yuuki-gulp4.git

ディレクトリを移動
$ cd yuuki-gulp4
```

2. パッケージのインストール

```
npm install
```
3.  gulp4をビルドをする

```
npm start
```
4. コーディング開始

```
npm run watch
```
