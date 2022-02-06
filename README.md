# Yet Another Web API - JS Edition

Base project for a REST API based on node.js

## Requirements

1. Docker
1. MySQL8
2. Node.js
3. Express.js
4. Sequelize

## Clone from GitLab

Clone project using:

```
git clone https://gitlab.com/mauriziomollicone/yawapi-js.git
```

## Setup MySQL8 Container


```
docker run --detach --name mariadb --env MARIADB_USER=yar --env MARIADB_PASSWORD=12345678 --env MARIADB_ROOT_PASSWORD=12345678 mariadb:latest

```
## Run

```
cd yawapi-js
npm install
node app.js
```