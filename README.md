# my gitlab
## 作り方
- 環境変数を設定する。env.sample.shを参考に。

```
. .env.sample.sh
```

- 起動
```
docker-compose up -d
```

## Configを改造したいとき
- 以下参考に付け足せばOK
- https://gitlab.com/gitlab-org/omnibus-gitlab/blob/master/files/gitlab-config-template/gitlab.rb.template
