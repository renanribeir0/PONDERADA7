**Caso de Teste: Listar Usuários**
**Objetivo:** Verificar se a rota GET /usuarioEP/listar retorna a lista de usuários corretamente.

**Pré-condição:** A aplicação está em execução e acessível em http://localhost:3000 (ou a URL apropriada). Existem usuários cadastrados na base de dados.

**Procedimento de Teste:**

Realizar uma solicitação GET para a rota /usuarioEP/listar.
Aguardar a resposta da API.

**Resultado Esperado:**

A API deve responder com um código de status 200 (OK).
O corpo da resposta deve conter uma lista de objetos de usuário.
Resultado Obtido (Exemplo):
