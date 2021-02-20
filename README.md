# NodeJS

## Estrutura do projeto

<img src="assets/estruturanodejs.png" alt="estrutura nodeJS"></img>


## Rotas

- Rota para retornar o total de conexões realizadas;
- Rota para criar uma nova conexão;
- Rota para retornar as aulas;
- Rota para criar uma nova aula;


## :rocket: Tecnologias utilizadas

- [express](https://expressjs.com/)
- [knex](http://knexjs.org/)
- [typescript](https://www.typescriptlang.org/)
- [sqlite3](https://www.sqlite.org/index.html)
- [cors](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Controle_Acesso_CORS)

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e um gerenciador de pacotes [Yarn](https://yarnpkg.com/) ou [npm](https://www.npmjs.com/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)


### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/Luciano-Ferreira/Proffy-NodeJS.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd Proffy-NodeJS

# Instale as dependências
$ yarn 
ou
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start
ou
$ npm run start

# O servidor inciará na porta:3333 - acesse <http://localhost:3333>
```