# 🚀 deploy-agent

Autonomous agent to deploy Docker images to **AWS App Runner** from tagged GitHub pushes.

## 🔐 Required GitHub Secrets

- \AWS_ACCESS_KEY_ID\
- \AWS_SECRET_ACCESS_KEY\
- \AWS_REGION\
- \APP_RUNNER_SERVICE_NAME\

## 🚀 Trigger

Push a tag like \1.2.3\ to deploy.

## 🧠 Behavior

- Pulls the Docker image using the tag
- Starts a deployment on AWS App Runner
- Outputs deployment confirmation
