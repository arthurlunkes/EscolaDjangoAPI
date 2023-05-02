# Primeira API utilizando Django

## Descrição
 API REST feita com Django com acesso ao banco de dados com operações CRUD.
 
## O que foi utilizado nesse projeto

## Passos para a criação
 1. Instale o venv:
  ```bash
pip install venv
```
 2. no terminal, rode o comando:
  ```bash
python3 -m venv ./venv
```
 3. ative o venv:
  - Comando para linux/mac:
  ```bash
source venv/bin/activate
```
  - Comando para windows:
  ```shell
venv\Scripts\activate.bat
```

 4. Instale o Django no ambiente virtualizado:
  ```bash
pip install django
```

 5. Crie um projeto chamado config:
  ```bash
django-admin startproject config .
```

 6. Na pasta config, altere no arquivo settings.py o idioma e o horário:
  ```python
LANGUAGE_CODE = 'pt-br'
TIME_ZONE = 'America/Sao_Paulo'
```

## Avisos
 - Quando fizer novos models, deve se rodar os comandos abaixo:
 ```bash
 python manage.py makemigrations # Django cria o banco de dados e as migrations, mas não realmente aplica as alterações no banco de dados.
 python manage.py migration # Aplica as alterações no banco de dados.
 ```
