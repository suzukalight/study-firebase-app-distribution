# study-firebase-app-distribution

Firebase App Distribution を利用して、テスター向けにアプリを自動配布できることを検証するサンプルリポジトリです。

以下のzenn記事を補足する目的で公開しています。詳細は記事の方を御覧ください。  
https://zenn.dev/suzukalight/articles/firebase-app-distribution

## 動作環境

- Firebase App Distribution
- Node.js v18
- React Native v0.73
- GitHub Actions

## できること

main ブランチへ push すると、GitHub Actions 経由で staging ビルドを行い、App Distribution へアプリを送信して、テスターへ通知および配布を行う。
