# Container building options

## PHP-FPM 8.1

```bash
docker build -t artmalini/php-fpm:8.1  -f ./8.1/v1/Dockerfile ./8.1/v1 --build-arg WITH_DDOS_PROTECTION=0
```

```bash
docker build -t artmalini/php-fpm:8.1 -f ./8.1/v1/Dockerfile ./8.1/v1 --build-arg WITH_DDOS_PROTECTION=1
```