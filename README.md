# aws-ecs-wp
Running WordPress on Amazon ECS

# Features
開発マシンから docker コマンドで AWS にデプロイする。

# Usage
## Development
```sh
$ docker-compose up
```

```sh
$ open http://localhost/
```

上記にて、ローカル環境に Wordpress の導入が完了。

## For AWS
AWS Profile があればそれを利用する。
ない場合はプロファイルを作成する。
その際、アクセスキーは　 AWS の IAM より作成する。

### デプロイ
