# aws-global

Global AWS setup for e.g. personal IAM user.

## Deploy

```sh
aws cloudformation deploy \
  --stack-name aws-global \
  --template-file cf.yaml \
  --capabilities CAPABILITY_IAM \
  --no-fail-on-empty-changeset
```
