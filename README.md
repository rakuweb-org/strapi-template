# docker利用strapi構築方法

## 普通にstrapiを構築
```sh
$ yarn create strapi-app <directory名> --ts
```

- Installation type: Custom
- database client: postgres
- database name: strapi
- Host: 127.0.0.1
- Port: 5432
- Username: strapi
- Password: strapi
- Enable SSL connection: No

## Dockerfile, docker-compose.yaml, envファイル作成
```sh
$ npm @strapi-community/dockerize
```

## 各種設定
### 日本語化

### 画像のレスポンシブサイズ

### プラグインのインストール
- graphql
- documentation

### emailの設定
