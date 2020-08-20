# SNP HackBridge 2020

## 1. START POSTGRES
``
docker-compose -f ./deploy/postgresql.yml up
``

## 2. START FRONTEND
``
cd hackbridge-ui
yarn install
yarn run start
``

## 3. START BACKEND
``
cd hackbridge-service
./gradlew bootRun
``

BACKEND should be served on http://localhost:8080/ 
FRONTEND should be served on http://localhost:3000/ 