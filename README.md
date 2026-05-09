# mdy

簿記三級の練習問題アプリです。ブラウザだけで動作します。

## 収録問題数

- 第1問: 100問
- 第2問: 50問
- 第3問: 50問

## GitHub Pagesでデプロイする手順

1. このリポジトリをGitHubへpushする。
2. デフォルトブランチを `main` にする（このワークフローは `main` へのpushで動作）。
3. リポジトリの **Settings > Pages** を開く。
4. **Build and deployment > Source** は **GitHub Actions** を選ぶ。
5. `main` にpushすると、`.github/workflows/deploy-pages.yml` により自動デプロイされる。
6. デプロイ完了後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開される。

## 開発前セキュリティ確認

- GitHubアカウントの2段階認証（2FA）をONにする。
- パスワード・APIキーなどの秘密情報は、リポジトリに入れない。
- `.env` ファイルはGitに入れない（コミットしない）。
- このリポジトリが公開か非公開かを先に確認する。
