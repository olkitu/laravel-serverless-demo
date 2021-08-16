# Laravel-serverless-demo

This is just for testing Laravel with bref

### Running locally in Docker

Copy `.env.example` to `.env` and setup the environment variables.

Start environment

```
docker-compose up -d
```

Install with composer all packages. 

```
docker run -v $PWD:/app ghcr.io/olkitu/composer-builder:7.4 composer install
```

