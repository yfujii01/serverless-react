## 準備

npm install -g serverless

## APIローカル起動

ターミナルを起動し、以下のコマンドを実行

```
cd serverless-api
yarn
yarn dev
yarn local-db
yarn dev
```

## client起動

ターミナルをもう一つ起動し、以下のコマンドを実行

```
cd client
yarn
yarn dev

open http://localhost:3001
```


## dynammo-adminを使ってGUI管理

```
npm install dynamodb-admin -g
export DYNAMO_ENDPOINT=http://localhost:8000
dynamodb-admin

open http://localhost:8001
```
