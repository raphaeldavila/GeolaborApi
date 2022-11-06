
# API Geolabor

Projeto desenvolvido com base experimental para a Geolabor. Este projeto é composto por duas camadas de desenvolvimento.


### API

 - [Visualizar repositório](https://github.com/raphaeldavila/GeolaborApi)


### WebApp

 - [Visualizar repositório](https://github.com/raphaeldavila/GeolaborWebApp)


### Iniciando o projeto


Primeiro, faça o clone do repositório, em seguida rode o YARN para instalar as dependências necessárias do projeto:

```bash
yarn
```

Com as dependências instaladas, precisamos setar as variáveis de ambiente que compoẽ nossa estrutura:




#### Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`DATABASE_URL`

`PORT`

Nesse projeto, estamos utilizando o mongodb como nosso banco não relacional.

#### env.example

`DATABASE_URL=mongodb://localhost:27017/api`

`PORT=5000`

### Iniciar aplicação

Para iniciar o servidor e começar a rodar a aplicação, dê o seguinte comando:

```bash
yarn dev
```

Projeto rodando com sucesso \o/



