# Picopic

Picopic is a small web service for optimizing images. It consists of a React frontend
running at https://picopic.io/, and a backend exposing an API at https://api.picopic.io/.
Currently, the service can be used to optimize PNG images via a web browser.

This is a hobby project. Its purpose was to teach me more about the different AWS services,
serverless/microservice architecture, and infrastructure as code using [CDK](https://aws.amazon.com/cdk/).
Everything in the project, from frontend to backend including all the AWS services, is defined
in code.

## Repositories

### Frontend

| Status | Repository | Description |
| ------ | ---------- | ----------- |
| [![build](https://github.com/jmp/picopic-frontend-infrastructure/actions/workflows/build.yml/badge.svg)](https://github.com/jmp/picopic-frontend-infrastructure/actions/workflows/build.yml) | [picopic-frontend-infrastructure](https://github.com/jmp/picopic-frontend-infrastructure) | Infrastructure for the frontend |
| [![build](https://github.com/jmp/picopic-frontend/actions/workflows/build.yml/badge.svg)](https://github.com/jmp/picopic-frontend/actions/workflows/build.yml) | [picopic-frontend](https://github.com/jmp/picopic-frontend) | The React frontend written in TypeScript |

### Backend

| Status | Repository | Description |
| ------ | ---------- | ----------- |
| [![build](https://github.com/jmp/picopic-backend-infrastructure/actions/workflows/build.yml/badge.svg)](https://github.com/jmp/picopic-backend-infrastructure/actions/workflows/build.yml) | [picopic-backend-infrastructure](https://github.com/jmp/picopic-backend-infrastructure) | Common infrastructure for backend services |
| [![build](https://github.com/jmp/picopic-backend-optimization-service/actions/workflows/build.yml/badge.svg)](https://github.com/jmp/picopic-backend-optimization-service/actions/workflows/build.yml) | [picopic-backend-optimization-service](https://github.com/jmp/picopic-backend-optimization-service) | A backend service for optimizing image files |

### End-to-end tests

| Status | Repository | Description |
| ------ | ---------- | ----------- |
| [![e2e-tests](https://github.com/jmp/picopic-e2e-tests/actions/workflows/e2e-tests.yml/badge.svg?event=workflow_dispatch)](https://github.com/jmp/picopic-e2e-tests/actions/workflows/e2e-tests.yml) | [picopic-e2e-tests](https://github.com/jmp/picopic-e2e-tests) | End-to-end tests |
