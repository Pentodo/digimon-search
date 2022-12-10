# Digimon Search

Desafio/teste desenvolvido com Nest.js e Angular.\
O objetivo era realizar a listagem de Digimons. Sendo assim, criei um simples buscador.

### Requisitos:

-   Criar um projeto em Angular.
-   Criar uma api para realizar as consultas.

### Condições:

-   [x] Listar os digimons;
    -   Possuindo um filtro por nome e por level.
-   [x] Escolher o level do digimon e realizar uma lista com base neste nível.

## Inicializando

### 1. Clone o repositório e seus submódulos

Em algum terminal, use o comando:

```
git clone --recurse-submodules https://github.com/Pentodo/digimon-search.git
```

### 2. Instale as dependências e inicialize as aplicações

Nas duas pastas disponíveis — `digimon-api` e `digimon-frontend` —, use os comandos:

```
npm install
npm start
```

### 3. Acesse as aplicações

Para utilizar a API, use a porta `3000`. O front-end utiliza a porta `4200`.\
Caso queira expor as aplicações via host, configure a variável de ambiente `apiUrl` em [enviroment.ts](https://github.com/Pentodo/digimon-frontend/blob/main/src/environments/environment.ts).

## Considerações

### `REST API`

Você pode utilizar os seguintes endpoints:

-   GET: `/` ou `/digimons`. Retorna uma lista com todos os Digimons.

### `Front-end`

Suas funcionalidades:

-   É possível realizar a busca dos Digimons utilizando o nome ou digievolução.
-   É possível listar os Digimons por nome ou digievolução. A digievolução também é ordenada por nome.
