# API de Chamados de Suporte


## Objetivo do projeto

Criar a estrutura inicial de uma API de chamados de suporte usando Python, Flask e uv. Nesta etapa, a API possui apenas a rota inicial, que confirma que a aplicação está funcionando.

## Instalar as dependências

```
uv sync --locked
```

## Executar a aplicação

```
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Acessar a rota inicial

Rota: `GET /`

Pelo navegador ou pelo terminal:

```
curl -i http://localhost:5000/
```

### Resposta esperada

- Status: `200 OK`
- Cabeçalho `Content-Type`: `application/json`
- Corpo:

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```