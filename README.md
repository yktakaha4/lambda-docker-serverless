# lambda-docker-serverless

## 注意

以下設定値については書き換えを行ってください

```
$ grep -r "lambda-docker-serverless-deployment" --exclude-dir=node_modules .
./serverless.yml:  deploymentBucket: lambda-docker-serverless-deployment
./infra.yml:      BucketName: lambda-docker-serverless-deployment
```

GitHub Actionsにて、以下Secretsを指定してください

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_DEFAULT_REGION
