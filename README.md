# Sample three tier app

This repo contains code for a Node.js multi-tier application.

The application overview is as follows

```
web <=> api <=> db
```

The folders `web` and `api` describe how to install and run each app.

VPC and postgres YAML files helps to create vpc networks and creating database in same vpc.

api folder contains Jenkinsfile and env in which port and DB end details will be exposed

web folder contains Jenkinsfile and env in which application port and api endpoint port will be exposed.


