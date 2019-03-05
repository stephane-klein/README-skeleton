# Continuous Deployment

This project use GitLab-CI jobs to perform Continuous Deployment.

What is deployed by GitLab-CI?

- `deploy-prod` job deploy application (Git master branch) to prod environment
- `deploy-staging` job deploy application (Git develop branch) to staging environment
