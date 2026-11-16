# Shop Flask

API REST de e-commerce desenvolvida com **Flask** e **SQLAlchemy**, com autenticação de usuários, gerenciamento de produtos e carrinho de compras, além de documentação OpenAPI/Swagger (`swagger.yaml`).

## Funcionalidades

- Autenticação de usuários (`POST /login`, `POST /logout`) com **Flask-Login**
- Gerenciamento de produtos (adicionar, listar, visualizar, atualizar e remover)
- Carrinho de compras por usuário (adicionar, remover, listar itens e finalizar compra)
- Documentação da API em `swagger.yaml`

## Tecnologias utilizadas

- Python 3
- [Flask](https://flask.palletsprojects.com/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) (SQLite)
- [Flask-Login](https://flask-login.readthedocs.io/)
- [Flask-Cors](https://flask-cors.readthedocs.io/)

## Como executar

1. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   # venv\Scripts\activate   # Windows
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute a aplicação:
   ```bash
   python app.py
   ```