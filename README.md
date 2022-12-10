# Digimon Search

Desafio/teste desenvolvido com Nest.js e Angular.

### Objetivos:

-   [x] Listar Digimons;
    -   Possuir um filtro por nome e por digievolução.
-   [x] Escolher Digimons por meio da sua digievolução.

### Condições:

-   Criar um projeto em Angular.
-   Criar uma API para realizar as consultas.

## Inicializando

### 1. Clone o repositório e seus submódulos

Em algum terminal, utilize o comando:

```
git clone --recurse-submodules https://github.com/Pentodo/digimon-search.git
```

### 2. Instale as dependências e inicialize as aplicações

Agora, nas duas pastas disponíveis — `digimon-api` e `digimon-frontend` —, use os comandos:

```
npm install
npm start
```

### 3. Acesse as aplicações

Para utilizar a API, acesse o `localhost` através da porta `3000`. O front-end utiliza a porta `4200`.\
Caso queira expor as aplicações via host, configure a variável de ambiente `apiUrl` em [enviroment.ts](https://github.com/Pentodo/digimon-frontend/blob/main/src/environments/environment.ts).

## Considerações

### `REST API`

Você pode utilizar os seguintes endpoints:

-   GET: `/` ou `/digimons`. Retorna uma lista com todos os Digimons.

### `Website`

Suas funcionalidades:

-   Realizar a busca dos Digimons utilizando o nome ou digievolução.
-   Listar os Digimons por nome ou digievolução. A digievolução também é ordenada por nome.
