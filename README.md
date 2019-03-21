# Application Configuration

This demo application serves to illustrate secure application configuration on Kubernetes.

## architecture
![Architecture](architecture.png)

## local development

first install all dependencies for the backend
```
npm install
```
...and for the frontend
```
cd solar-frontend
npm install
```

Start the database
```
cd infrastructure/docker
docker-compose up -d
```
start the development server
```
cd solar-frontend
npm start
```
