# ecs-rocketchat
ECS構築検証用ロケットチャットのリソース

## コマンド一覧
 - ecs-cliコマンドで操作するクラスター情報の設定<br>
`ecs-cli configure --cluster ${CLUSTER_NAME} --region ${RESGIN} --config-name ${CONFIG_NAME}`
- ECSクラスターの作成<br>
`ecs-cli up --keypair test-instance-keypair --capability-iam --size 1 --instance-type m5.large --cluster-config rocketchat-conf`
