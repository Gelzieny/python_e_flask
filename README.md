<h1 align="center"> 🚀 Construindo uma API E-commerce com Flask 🚀 </h1>

## 💻 Sobre o projeto

<p align="justify">
Bem-vindo ao repositório da API de E-commerce desenvolvida com Flask. Este projeto simula um backend para uma aplicação de e-commerce, com funcionalidades como autenticação de usuários, gerenciamento de produtos, carrinho de compras e checkout.
</p>

<p align="center" style="display: flex; align-items: flex-start; ">
  <img alt="" title="" src="https://github.com/Gelzieny/python_e_flask/blob/main/.github/img/image.png?raw=true" width="400px">

  <img alt="" title="" src="https://github.com/Gelzieny/python_e_flask/blob/main/.github/img/image1.png?raw=true" width="400px">
</p>

## 🔨 Funcionalidades do projeto

- `Autenticação`:
  - Login e logout de usuários.
  - Proteção de rotas com autenticação baseada em sessão.
- `Produtos`
  - Adicionar, atualizar, visualizar e excluir produtos.
  - Listagem de todos os produtos disponíveis.
- `Carrinho de Compras`
  - Adicionar e remover itens.
  - Visualizar os itens no carrinho.
  - Realizar checkout e limpar o carrinho.

## 🛠 Tecnologias

<p align="justify">Este projeto utiliza um conjunto de tecnologias modernas para garantir uma aplicação eficiente e escalável, incluindo:</p>

- [Python](https://www.python.org/) e [Flask](https://flask.palletsprojects.com/en/stable/) - Base da aplicação
- [Flask-Login](https://flask-login.readthedocs.io/en/latest/) - Gerenciamento de sessões de usuários.
- [Flask-SQLAlchemy](https://flask-sqlalchemy.readthedocs.io/en/stable/) - ORM para manipulação do banco de dados.
- [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/api.html) - Para permitir interações entre diferentes origens.
- [SQLite](https://flask.palletsprojects.com/en/stable/patterns/sqlite3/) - Banco de dados utilizado para armazenar as informações.

## 🚀 Como executar o projeto

### Pré-requisitos

<p align="justify">Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:</p>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=git,python,vscode" />
</a>

### 🎲 Rodando aplicação

```bash
# Clone este repositório
$ git clone <https://github.com/Gelzieny/python_e_flask.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd python_e_flask

# Instale as dependências no Windows
$ python -m venv venv && venv\Scripts\activate && pip install -r requirements.txt

# Instale as dependências no Linux ou MacOS
$ python3 -m venv venv && source venv/bin/activate && pip install -r requirements.txt
```

### 🎲 Configure o banco de dados

```bash
# Abra o terminal Python e execute
$ flask --app src/app shell

# Criando BD
$ db.create_all()
```

## 🧑🏻‍💻 Autor

Feito com ❤️ por Gelzieny R. Martins 👋🏽 [Entre em contato!](https://www.linkedin.com/in/gelzieny/)

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).
