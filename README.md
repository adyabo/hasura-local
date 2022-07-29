# Hasura+Postgres docker-compose template

## Note
hasura-cliインストール(OS端末にインストール)
```
yarn install -D hasura-cli
```
利用するPORT: 8080,9065

## Usage

コンテナビルド・起動
```
docker-compose up -d --build
```

hasura-console
```
 hasura console --admin-secret "1234"
```
