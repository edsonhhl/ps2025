# Servidor Apache Docker

### Servidor simples Docker + docker compose

Para usar os containers, é necessário ter o Docker e o Docker Compose instalados. O aplicativo está disponível em [http://localhost/](http://localhost/) e o phpMyAdmin está rodando na porta 88 [http://localhost:88/](http://localhost:88/).

- Apache
- PHP 7.4
- MariaDB
- phpMyAdmin
- Redis

## Basta entrar no diretório e executar os comandos abaixo.

### Subir servidor
- `docker-compose up -d`

### Baixar servidor
- `docker-compose down`

### Listar containers
- `docker ps`

### Acessar terminal do container
- `docker exec -it id-terminal bash`

### Pausar container
- `docker stop id-container`
