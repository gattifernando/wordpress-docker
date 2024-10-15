# Wordpress + Docker

Instalação básica do Wordpress usando Docker, MariaDB e phpMyAdmin.

## Setup

```bash
docker compose up
```

Ao levantar o container Docker, o Wordpress rodará em `http://localhost:8000` e deixará mapeado no projeto a pasta `wp-admin`.

Obs.: Sempre que iniciar uma aplicação nova, lembre-se de trocar os `container_name` de cada serviço no arquivo `docker-compose.yml` para um nome diferente.

