# zenn_article
zennへ投稿する記事を管理しています。

### セットアップ時のコマンド

```sh
npm init --yes # プロジェクトをデフォルト設定で初期化
npm install zenn-cli # zenn-cliを導入
npx zenn init
```

### zennで記事を作成する時のコマンド

```sh
# 新しい記事を作成する
npx zenn new:article

# 新しい本を作成する
npx zenn new:book

# 投稿をプレビューする
npx zenn preview
```
#### ポート番号を指定して記事を作成する

```sh
npx zenn preview --port 8010
```

### 参考資料

- [GitHubリポジトリでZennのコンテンツを管理する](https://zenn.dev/zenn/articles/connect-to-github)
- [Zenn CLIをインストールする](https://zenn.dev/zenn/articles/install-zenn-cli)
- [Zenn CLIで記事・本を管理する方法](https://zenn.dev/zenn/articles/zenn-cli-guide)