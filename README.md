# Ruby on Railsの学習メモ

## セットアップ

- Railsのインストール

```bash
gem install rails -v x.x.x.x
```

- インストールの確認

```bash
rails -v
```

### Node.js

- RailsでJavaScriptを圧縮する機能が備わっているが、そのためにJavaScriptのランタイムが必要になってくるたえインストールが必要

```bash
brew install node
```

### DB

#### PostgreSQLの場合

- インストール

```bash
brew install postgresql
```

- 確認

```bash
postgres -V
```

- 起動

```bash
brew services start postgresql
```

- 停止

```bash
brew services stop postgresql
```

- コンソールログイン

```bash
psql postgres
```

- コンソールログアウト

```bash
\q
```
