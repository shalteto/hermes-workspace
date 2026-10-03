# hermes-workspace

Google OAuth 同意画面(Google Auth Platform)に登録する、ホームページとプライバシー ポリシーを公開するための GitHub Pages 用リポジトリ。

- `index.html` — アプリのホームページ
- `privacy.html` — プライバシー ポリシー

## 公開手順

1. GitHub で `hermes-workspace` リポジトリを作成する(公開リポジトリ)。
2. `git remote add origin <URL>` のあと `git push -u origin main`。
3. リポジトリの Settings → Pages で、Source を `main` ブランチのルートに設定する。
4. 公開された URL を、Google Auth Platform の「ブランディング」に入力する。
   - ホームページ: `https://<user>.github.io/hermes-workspace/`
   - プライバシー ポリシー: `https://<user>.github.io/hermes-workspace/privacy.html`

## 注意

- 認証情報(client_secret や token)は、このリポジトリに入れないこと。
