# sam-cowsay

AWS SAM で
Python で lambda を書いて
それがパッケージ依存のとき
ちゃんと動くかのテスト。

CDK にするための練習。意外と難しそう...

## デプロイ

AWS SAM なので普通に

```sh
sam build
sam deploy -g
sam delete
```

で。
