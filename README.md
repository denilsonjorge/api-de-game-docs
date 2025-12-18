# API de Games
Essa API é utilizado para tal de tal...
## Endpoints
### GET  /games
Esse endpoint é responsavel por retornar a listagem de todos os games cadastrados.
### Paramentros
Nenhum
### Respostas
### OK! 200
caso essa resposta você  vai receber a listagem de todos os games
Exemplo de resposta:
```
[
    {
        "id": 23,
        "title": "Call of duty MW",
        "year": 2019,
        "price": 80
    },
    {
        "id": 65,
        "title": "Sea of thieves",
        "year": 2018,
        "price": 40
    },
    {
        "id": 2,
        "title": "Call of duty MW",
        "year": 2012,
        "price": 20
    }
]

````
### Falha  na autenticação!   4001
caso essa resposta aconteça, isso signigica que aconteceu algum falha durante o processo de autenticação de requisição. Motivos: token invavalido,token expirou.
Exemplo de falha:
```

{
    "err": "Token invalido"
}

```
