# Vincet

## Requisitos para desenvolvimento:

### Clone o repositório
    $ git clone https://github.com/MarianyFerreira/vincet.git

    $ cd vincet

### Crie/Ative uma virtualenv com Python 3.7
    $ virtualenv env -p python3
    $ source env/bin/activate

### Instale as dependências
    $ (env) pip install -r requirements.txt

### Crie o banco com Postgres 11.0
    $ (env) sudo su - postgres

    $ createdb vincet

### Rode as migrações
    $ python manage.py migrate

### Execute o projeto localmente
    $ python manage.py runserver

#### Para criar um novo app
    $ python manage.py startapp app_name
    