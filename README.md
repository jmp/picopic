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

* [picopic-frontend-infrastructure](https://github.com/jmp/picopic-frontend-infrastructure): CDK project for managing the AWS resources required for hosting the frontend
* [picopic-frontend](https://github.com/jmp/picopic-frontend): the React frontend written in TypeScript

### Backend

* [picopic-backend-infrastructure](https://github.com/jmp/picopic-backend-infrastructure): CDK project for managing common AWS resources for the different backend services
* [picopic-backend-optimization-service](https://github.com/jmp/picopic-backend-optimization-service): A backend service for optimizing image files
