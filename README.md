- Criar uma virtual env:

python -m vev "nome_da_pasta"

cd .\nome_da_pasta\ -> Para Acessar a pasta.

- Ativar:
.\Scripts\activate

- Instalar o Django:
pip install django

- Criar o projeto django:
cd "endereço onde quer salvar"

pip freeze -> Para verificar se tudo ocorreu bem.

django-admin startproject "nome_do_arquivo"

* No projeto instalar o "runserver"
	python manage.py runserver

* No Terminal do Pycharm digitar:
	django-admin startapp core

-- Abrir o arquivo settings e inserir o "core" na linha "Installed App"
