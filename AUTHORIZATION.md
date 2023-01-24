## CUSTOM DECORATOR

- Deverá criar um **Custom Decorator** com o nome _CurrentUser_ para retornar os dados do usuário, esse decorator deverá estar na rota `/me`.
- Os dados do usuário deverá ser injetado pela **Middleware** de _authorization_ na **Request** da requisição.

## PIPE

- Deverá ser criado um **Pipe** que irá converter todos os parâmetros do tipo _ID_ recebido na **URL** de _string_ para _number_.

## INTERCEPTOR

- Deverá criar um **Interceptor**, declarar no escopo global, esse **interceptor** deverá interceptar todas as **Responses**, varificar se é um sucesso ou erro, e injetar o formato abaixo:

```json
{
  "status": "APPROVED" | "FAILED",
  "data": "retorno da controller"
}
```
