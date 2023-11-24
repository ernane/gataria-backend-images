# Gataria Backend Images

Variáveis de ambiente necessárias:

- CATAPI_URL

Exemplo:

```
export CATAPI_URL="https://api.thecatapi.com/v1/images/search"
```

Iniciando o backend

```
npm start
```

Para rodar os testes

```
npm test
```

# Execução local com Docker

```bash
docker run --name gataria-backend-images \
-e CATAPI_URL=$CATAPI_URL \
-p 3020:3020 \
-d gataria-backend-images:dev
```