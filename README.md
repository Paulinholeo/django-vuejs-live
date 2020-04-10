# django-vuejs-live

django-vuejs-live

Exemplo de como fazer um projeto com Django e VueJS completo.

E neste exemplo temos a participação especial do Alefe Souza.

## Este projeto foi feito com:

* Python 3.6
* Django 2.2.12
* Bootstrap 4.0
* VueJS 2.6.11

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/rg3915/django-vuejs-live.git
cd django-vuejs-live
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

