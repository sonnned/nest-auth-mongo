# Get started

## Setting .env
Your env should have
```txt
DATABASE_NAME=db_example
DATABASE_PORT=1000
API_KEY='api_example_123'
PORT=port_example_3000
MONGO_INITDB_ROOT_USERNAME=admin_example
MONGO_INITDB_ROOT_PASSWORD=password_example
MONGO_DB=db_name_example
MONGO_PORT=mongo_port_example_27017
MONGO_HOST=gost_example
MONGO_CONNECTION=mongodb
```

## Run with npm

```shell
npm run start:dev
```

## Run with docker

1. 
```shell
docker-compose up -d mongo
```

2. 
```shell
docker-compose ps
```