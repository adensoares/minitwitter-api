# MiniTwitter API

MiniTwitter API é um projeto Django e Django REST Framework que imita funcionalidades básicas do Twitter. Até agora, ele suporta a criação de usuários, autenticação e a criação e visualização de tweets.

## Funcionalidades

- **Autenticação de usuários:** Os usuários podem se cadastrar e autenticar utilizando email e senha.
- **Criação de tweets:** Os usuários autenticados podem criar novos tweets.
- **Feed geral:** Os usuários autenticados podem visualizar tweets de todos os usuários da rede.
- **Feed personalizado :** Os usuários autenticados pdem visualizar tweets dos usuários seguidos por eles.

## Tecnologias Utilizadas

- Python
- Django
- Django Rest Framework
- Docker
- Docker-compose

## Instalação

Este projeto utiliza Docker para facilitar o processo de configuração e execução. Aqui estão as etapas para você começar:

### Pré-requisitos

- Docker
- Docker-compose

### Passos

1. Clone este repositório: `git clone https://github.com/adensoares/minitwitter-api.git`

2. Acesse o diretório do projeto: `cd minitwitter-api`

3. Construa e inicie os containers do Docker: `docker-compose up --build`

## Uso da API

Aqui estão algumas rotas básicas disponíveis nesta API:

- /api/v1/users/signup/ - Cadastro de usuários (POST)
- /api/v1/users/signin/ - Login de usuários (POST)
- /api/v1/tweets/create/ - Criação de tweets (POST)
- /api/v1/tweets/feed/general/ - Feed geral de tweets (GET)
- /api/v1/tweets/feed/personalized/ - Feed personalizado de tweets (GET)

# docker-compose run web python manage.py
