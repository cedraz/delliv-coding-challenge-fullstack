# Setup

```sh
docker run --name api-delliv-pg -e POSTGRESQL_USERNAME=docker -e POSTGRESQL_PASSWORD=docker -e POSTGRESQL_DATABASE=api-delliv -p 5432:5432 bitnami/postgresql
```

# App

Aplicativo de rastreamento de entregas

## RFs (Requisitos funcionais)

- [ ] O usuário deve poder se cadastrar na aplicação
- [ ] O usuário deve poder se autenticar na aplicação
- [ ] O usuário deve poder cadastrar uma encomenda
- [ ] O usuário deve poder listar suas encomendas
- [ ] O usuário deve poder atualizar o status de uma encomenda

## RNs (Regras de negócio)

- [ ] O usuário não pode se cadastrar com um e-mail já cadastrado

## RNFs (Requisitos não-funcionais)

- [ ] Utilizar o framework NestJS
- [ ] Utilizar o banco de dados PostgreSQL
- [ ] Utilizar o Prisma ORM
- [ ] Utilizar o Docker
- [ ] Utilizar o Swagger para documentação da API
- [ ] Utilizar o Jest para testes
- [ ] Autenticação deve ser feita utilizando JWT