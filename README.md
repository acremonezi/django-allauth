# Django AllAuth

Source: https://www.youtube.com/watch?v=Q4Q3S7HLp4w


1. Criação do ambiente virtual:
    1. `python3 -m venv venv`

2. Ativar o ambiente virtual:
    1. `source venv/bin/activate`

3.  Instalar as Bibliotecas:
    1. `pip install django django-allauth`

4. Criar a estrutura base do projeto Django:
    1. `django-admin startproject allauth_introducao .`

5. Editar Settings.py
    1. `LANGUAGE_CODE = 'pt-BR'`
    2. `TIME_ZONE = 'America/Sao_Paulo'`
    3. Adicionar outras linhas explicadas no video.

6. Cria Banco de Dados:
    1. `python3 manage.py makemigrations`
    2. `python3 manage.py migrate`

7. Criar SuperUser:
    1.  `python3 manage.py createsuperuser`

8. Roda Servidor de Desenvolvimento:
    1.  `python3 manage.py runserver`

9. Adicionar essa linha em Settings.py temporariamente enquanto nao configurar um SMTP server
    1.  `EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'`

