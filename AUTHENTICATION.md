# CRUD de USUÁRIOS + AUTH

## Iniciando o projeto

1 - Crie um projeto nest com o comando: nest new users-crud
2 - Rode o projeto com: yarn start:dev

## DEPENDENCIAS NECESSÁRIAS

- bcrypt
- jsonwebtoken

## User

- name String
- email String
- password String

## Casos de uso dos usuários

OBS: Crie um módulo para o usuário
OBS: O banco de dados será em memória, ou seja, um Array de objetos

- Adicione um usuário no banco de dados (A senha deverá ser criptografada antes de persistida)
- Edite um usuário no banco de dados [SÓ COM AUTORIZAÇÃO]
- Liste todos os usuários [SÓ COM AUTORIZAÇÃO]
- Visualize um usuário [SÓ COM AUTORIZAÇÃO]

## Casos de uso do auth

OBS: Será necessário a criação de um middleware de authorization para
validar as rotas após a autenticação

- Autenticação

DICA PARA AUTENTICAÇÃO

1 - Verificar se usuário existe
2 - Validar as senhas
2 - Gerar o token JWT
