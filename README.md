# Flask E-commerce API

API REST desenvolvida em **Python + Flask** como projeto final do curso introdutório de Flask e Python da **Rocketseat**.

O projeto simula um **backend de e-commerce**, incluindo autenticação de usuários, gerenciamento de produtos, carrinho de compras e checkout, com persistência em banco de dados SQLite.

---

# Tecnologias utilizadas
- Python
- Flask
- Flask-SQLAlchemy
- Flask-Login
- Flask-CORS
- SQLite
- Swagger / OpenAPI

---

Funcionalidades

# Autenticação
- Login de usuário
- Logout
- Proteção de rotas com autenticação (`login_required`)

# Produtos
- Cadastro de produtos
- Listagem de produtos
- Detalhes de um produto
- Atualização de produtos
- Remoção de produtos

# Carrinho de compras
- Adicionar produto ao carrinho
- Remover produto do carrinho
- Listar itens do carrinho
- Checkout (limpa o carrinho)
