実行した手順を以下に示す。

1. ビルドした
`docker-compose build`

1. アプリケーションを作成した
`docker-compose run --rm node sh -c 'npx create-react-app sample_app --template typescript'`

1. material UIを追加した
`docker-compose run --rm node sh -c 'cd sample_app && npm install @material-ui/core'`

1. コンテナの起動
`docker-compose up`

### 参考資料
- [create-react-app：getting-started](https://create-react-app.dev/docs/getting-started/)
- [create-react-app：adding-typescript](https://create-react-app.dev/docs/adding-typescript/)
- [material-ui：getting-started](https://material-ui.com/getting-started/installation/)
- [noImplicitAny](https://typescript-jp.gitbook.io/deep-dive/intro/noimplicitany)