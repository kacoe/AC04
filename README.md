# Projeto para conexão da api Flask com MongoDB
- clone o projeto na sua maquina
- baixe o python [Python](https://www.python.org/downloads/)
- baixe o [Postman](https://www.postman.com/downloads/)
- baixe o [Mongo Compass](https://www.mongodb.com/try/download/compass)

## Executando projeto em ambiente "local"

### Back-end

Após a instalação, no terminal de sua preferência:
- execute o **`pip install flask pymongo`** para baixar as dependências do projeto
- deipos execute **`python main.py`** para startar a api

O projeto será executado na versão de desenvolvimento (development mode).
Para verificação das rotas da api utilize a url base, [http://localhost:5000](http://localhost:5000), no postman e utilizando as rotas para as chamadas.

### Postman

Após startar a api:
- utilize a url [http://localhost:5000/produtos](http://localhost:5000/produtos) para executar as rotas GET e POST.
- para a ação de POST utilize o json a seguir como exemplo
{
    "name":"Jose",
    "price":"22"
}
