# Arquivos em anexo

- Automação API Test Webmotors.postman_collection
- Environment Test Webmotors.postman_environment

## Dependencias

Node.js >= v10 https://nodejs.org/en/download/package-manager/

Instalando o newman:

```cmd
npm install -g newman
```

## Executar os comandos abaixo para realizar os testes na api webmotors , no final é gerado um report dos testes feitos na api

```cmd
newman run Automação_API_Test_Webmotors.postman_collection.json -e Environment_Test_Webmotors.postman_environment.json --delay-request 2 -r htmlextra,cli --reporter-htmlextra-export index.html
```
