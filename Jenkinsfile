
@Library('kafka-lib') _

def config = [
    SLACK_CHANNEL_NAME  : "new-channel",
    ENVIRONMENT         : "prod",
    CODE_BASE_PATH      : "env/prod",
    ACTION_MESSAGE      : "Kafka deployment started",
    KEEP_APPROVAL_STAGE : true
]

kafkaPipeline(config)
