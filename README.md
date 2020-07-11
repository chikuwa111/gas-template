# gas-template

Google Apps Script（GAS）の開発用テンプレート

## 初期設定

```sh
# 1. このテンプレートをダウンロードする

# 2. 依存パッケージのダウンロード
$ yarn

# 3. GASのプロジェクト作成
# 必要に応じて`--title <project-title>`をつける（つけない場合はディレクトリ名が使われる）
$ yarn -s run clasp create --rootDir src
```

## 開発時

```sh
# 自動でpushするのでpushしたくない場合は実行しない
$ yarn dev
```

## 注意事項

- `appsscript.json`は web editor 上でいろいろいじると更新されるので、うっかりローカルの`src/appsscript.json`で上書きしないように注意しましょう。
