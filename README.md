# mq-rabbitmq-deploy

mq 命名空间 rabbitmq 部署

## 部署

helm upgrade --install --namespace mq -f values-dev.yaml mq-message ./rabbitmq
