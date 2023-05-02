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
 3. ative o venv(esse comando para linux/mac):
  ```bash
source venv/bin/activate
```
 4. ative o venv(esse comando para windows):
  ```shell
venv\Scripts\activate.bat
```
 5. Instale o Django no ambiente virtualizado:
  ```bash
pip install django
```

 6. Crie um projeto chamado config:
  ```bash
django-admin startproject config .
```

 7. Na pasta config, altere no arquivo settings.py o idioma e o horário:
  ```python
LANGUAGE_CODE = 'pt-br'
TIME_ZONE = 'America/Sao_Paulo'
```