# web_blog
Web blog REST desenvolvido em python e mongodb

## 1. Configuração do Ambiente Local

**Passo:1** Instalar o Python

`sudo apt-get install python3`

**Passo:2** Instalar o Mongodb

`sudo apt-get install -y mongodb-org`

**Passo:3** Fazer o clone no projeto

`git clone https://github.com/wescley/web_blog`

**Passo:4** Executar o script *app.py* na pasta /src

`python app.py` 

**Passo:5** Acessar no browser a url: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## 2. API's REST Disponíveis

### 2.1. Registro de um novo usuário
[http://127.0.0.1:5000/register](http://127.0.0.1:5000/register)

### 2.2. Login de usuário cadastrado
[http://127.0.0.1:5000/login](http://127.0.0.1:5000/login)

### 2.3. Lista de blogs do um usário logado
[http://127.0.0.1:5000/blogs](http://127.0.0.1:5000/blogs)

### 2.4. Criaçãr de um novo blog
[http://127.0.0.1:5000/blogs/new](http://127.0.0.1:5000/blogs/new)
