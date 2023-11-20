<h1 align="center" style="text-align: center;">
  <img alt="Logo do Food Explorer" src="./src/assets/favicon.svg" style="vertical-align: middle; margin-right: 10px;">
  Food Explorer
</h1>

> Cardápio digital de restaurante fictício

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#structure">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<h2 id="project">Sobre o Projeto</h2>

Food Explorer é o desafio final do curso Explorer da Rocketseat. Se resume a uma aplicação de cardápio digital para um restaurante fictício.

O Back-end deste projeto está disponível neste repositório. Já o front-end, está disponível [aqui](https://github.com/thYuri/frontend-FoodExplorer).

<h2 id="structure">Estrutura</h2>

- Usuários
- Pratos
- Ingredientes dos pratos
- Favoritos
- Carrinhos
- Itens dos carrinhos
- Pedidos
- Itens dos pedidos

<h2 id="technologies">Tecnologias</h2>

- Bcrypt.js
- CORS
- Dotenv
- Express.js
- express-async-errors
- JSON Web Token
- Knex.js
- Node.js
- Multer
- PM2
- SQLite
- SQLite3

<h2 id="usage">Utilização</h2>

O back-end do projeto está hospedado no endereço https://food-explorer-backend-oxwh.onrender.com. A aplicação Food Explorer está disponível para uso [aqui](https://food-explorer-frontend-80e47f.netlify.app/).

**Aviso:** Este projeto utiliza uma hospedagem gratuita para o back-end, portanto, pode haver atrasos no tempo de resposta do servidor.

Você também pode executá-lo em sua máquina localmente. Certifique-se de ter o ``Node.js`` e o ``npm`` instalados antes de prosseguir com as etapas abaixo:

1. Clone o projeto:

```
$ git clone https://github.com/thYuri/backend-FoodExplorer
```

2. Acesse a pasta do projeto:

```
$ cd food-explorer-backend
```

3. Instale as dependências:

```
$ npm install
```

4. Execute as migrações:

```
$ npm run migrate
```

5. Inicie o servidor:

```
$ npm start
```

**Importante**: Crie um arquivo .env de acordo com o arquivo .env.example e preencha os campos AUTH_SECRET e PORT com suas respectivas informações.

- Para gerar o valor para o campo AUTH_SECRET, você pode utilizar o MD5 Hash Generator para gerar uma sequência de caracteres segura

- Preencha o campo PORT com o número da porta desejada para executar o servidor da aplicação

---

Feito por Yuri Branco,  

Minhas redes sociais:

<div style="display: flex;">
  <a href="https://www.linkedin.com/in/yuri-branco-810a68271/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="margin-right: 2vw" target="_blank"></a>
  <a href="mailto:yuribranco28@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" style="margin-right: 2vw" target="_blank"></a>
  <a href="http://discordapp.com/users/" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" style="margin-right: 2vw" target="_blank"></a>
  <a href="https://www.instagram.com/yuri.branco/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
</div>