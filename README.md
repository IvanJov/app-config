# Application Configuration

This demo application serves to illustrate secure application configuration on Kubernetes.

## architecture
![Architecture](architecture.png)

## local development

first install all dependencies for the backend and the frontend. From the repo root run:
```
npm install-all
```
Start the frontend, backend development servers and the postgres database:
```
npm start-all
```
All the logs will be visible in the same shell.

## deployment to kubernetes

This application contains [helm](https://helm.sh/) chart to manage the deployment to kubernetes


