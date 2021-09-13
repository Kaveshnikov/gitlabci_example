# GitlabCI Example
An example of GitlabCI pipeline configuration

## Configuration
Don't forget to configure different environment variables in `.gitlab-ci.yml` file.

Also, it's mandatory to add following environment variables into your project CI/CD settings:

KUBECTL_STAGE, KUBECTL_PRE, KUBECTL_PROD - kubectl token for corresponding layer

SLACK_TOKEN - token for slack

GL_TOKEN - gitlab project token

SLACK_CHANNEL_STAGE_ID, SLACK_CHANNEL_PRE_ID, SLACK_CHANNEL_PROD_ID - slack channel id
for notification about events from corresponding layer
