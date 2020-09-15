# textlint-sample
日本語の技術記事用の標準的なルールセットを設定した [textlint](https://github.com/textlint/textlint) のサンプルです。

## 使い方
### install
```
$ git clone git@github.com:t0yohei/textlint-sample.git
$ cd textlint-sample
$ yarn install
```

### 任意のテキストに対して textlint を実行
1. 任意のテキストを記載したファイルを作成する。 ( `sample.md` など)
2. `yarn run textlint 作成したファイル名` を実行する。( `yarn run textlint sample.md` など)
3. 結果がコンソールに出力されるので、必要に応じて修正する。
