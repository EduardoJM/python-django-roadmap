# 1. Python/Django Roadmap

## 1.1 Python

### 1.1.1 Ambiente

- [x] [pyenv](https://github.com/pyenv/pyenv)
- [x] virtualenv
- [x] python
- [x] pip
- [x] gerenciar dependências (pip/pyproject, poetry)

### 1.1.2 Python

- [ ] Strings e seus Métodos
- [ ] Operadores Lógicos no Python
- [ ] Funções em Python
- [ ] Laços de Repetição
- [ ] Dicionários e seus Métodos
- [ ] Listas e seus Métodos
- [ ] Compreensão de Listas

### 1.1.3 Docker

- [ ] Entender sobre Docker
- [ ] Usar imagens do dockerhub
- [ ] Dockerizar aplicação

## 1.2 Django Inicial

TODO: elaborar um tópico sobre aplicações web

### 1.2.1 Primeiro Projeto

- [ ] Criando o nosso primeiro projeto
- [ ] Entendendo a estrutura de um projeto django
- [ ] Entendendo os arquivos iniciais do projeto
- [ ] Criando nossa primeira App no Django
- [ ] Camadas no Django
- [ ] Entender como funcionam os apps de terceiros
- [ ] Rodar a aplicação
- [ ] Acessar a aplicação (Acessando o Admin do Django)

### 1.2.2 Models

> **Recado para o Eduardo do Futuro**: Pensar em um tipo de tabela que dê pra explorar várias configurações do django-admin posteriormente.

- [ ] Banco de dados relacional (Resumo)
- [ ] ORM
- [ ] Criar models
- [ ] Foreign Key (Chave estrangeira)
- [ ] Comando makemigrations
- [ ] Comando migrate

### 1.2.3 Django-Admin

- [ ] Acessando o Admin do Django
- [ ] Configurando o Admin do nosso model
- [ ] Lidar com Foreign Key (autocomplete)
- [ ] Lidar com Foreign Key de outra forma (inline editors)
- [ ] Outras opções de configuração do admin do model (TODO: listar opções)

### 1.2.4 ImageField

- [ ] Configurando o envio de Imagens
- [ ] Instalando a biblioteca Pillow

### 1.2.5 URLs, Views, Templates

> TODO: pensar nisso aqui para depois ir para as APIs

- [ ] Visão de admin VS visão de usuário
- [ ] Entendendo URLs e Views
- [ ] Ordens de precedência de URLs (quando uma URL sobrescreve a outra)
- [ ] Criando views
- [ ] Entendendo Templates
- [ ] Retornando Templates para o usuário
- [ ] Linguagem de Templates do Django
- [ ] Static files

## 1.3 APIs com Django

### 1.3.1 APIs

- [ ] O que é uma API?
- [ ] Django Rest Framework
- [ ] APIViews (function views and class-based-views)
- [ ] URLs (parecidas com as URLs do tópico 1.2.5)

### 1.3.2 ViewSets

- [ ] ViewSet (conjunto de views)
- [ ] Serializers (ModelSerializer)
- [ ] Routers
- [ ] Requests e Responses
- [ ] Relations (Foreign Key)
- [ ] Relations com Hyperlinks
- [ ] Custom actions
- [ ] Testes de API's

### 1.3.3 Documentação

- [ ] [Swagger](https://swagger.io/solutions/api-documentation/)
- [ ] [drf-spectacular](https://drf-spectacular.readthedocs.io/en/latest/)
- [ ] schema-generation (static and runtime)

### 1.3.4 Autenticação

> Mostrar e configurar todos os meios de autenticação.

- [ ] Autenticação vs. Permissão
- [ ] Como o django-admin faz autenticação
- [ ] Meios de ter autenticação via API
- [ ] autenticação por token
- [ ] simplejwt
- [ ] session

### 1.3.5 Mais configurações

- [ ] CORS

## 1.4 Tópicos Avançados

### 1.4.1 ORM

- [ ] Roteamento de banco de dados
- [ ] Mapear ORM com tabelas já existentes

## 1.5 Views clássicas do Django

TODO: elaborar esse tópico

## Referências

- https://pycodebr.com.br/
- https://www.alura.com.br/formacao-django?srsltid=AfmBOopIkSnbW8i8b9OTPC3-OdSiK_rCc2xNbVhSGVZLrNOHdqI9H0yn
- https://www.alura.com.br/formacao-django-rest?utm_term=&utm_campaign=&utm_source=adwords&utm_medium=ppc&hsa_acc=7964138385&hsa_cam=21045490451&hsa_grp=158851964763&hsa_ad=691754664154&hsa_src=g&hsa_tgt=dsa-2276348409543&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjwreW2BhBhEiwAavLwfEiIQXDF3dgsP9QIuj5_pqqAsr3eHqL2UrOlncFc1SzVPYnyrQ5alRoCjekQAvD_BwE
