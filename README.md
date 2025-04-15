# Ambiente de Desenvolvimento MySQL + phpMyAdmin (Docker)

Este repositório contém um ambiente básico de desenvolvimento com **MySQL 8** e **phpMyAdmin**, configurado com Docker Compose.

## Serviços

- **MySQL**
  - Porta: `3306`
  - Usuário root: `root`
  - Senha root: `root`
  - Banco inicial: `devdb`
  - Usuário adicional: `devuser` / `devpass`

- **phpMyAdmin**
  - Acesso via navegador: [http://localhost:8080](http://localhost:8080)
  - Login: `root`
  - Senha: `root`

## Como usar

1. Clone este repositório
2. Suba os containers com Docker Compose:

```bash
docker-compose up -d
