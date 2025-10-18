# Instalar libs pip install django djangorestframework django-cors-headers
# Criar projeto django-admin startproject api_root .
# Criar o aplicação python manage.py startapp api_rest
# ----------------------------------------------------------------------------

# Para criar migrations depois que tiver feita o código da model
# Comando: python manage.py makemigrations

# Para rodar as migrations
# Comando python manage.py migrate

# --------------------------------------------------------------------------
# OBS: Para registrar uma model/tabela no painel, precisar criar o código em admin.py
#      Necessário para usar o painel adm distribuindo pelo Django
# Para criar super usuário

# python manage.py createsuperuser

# ---------------------------------------------------------------------------

# Para rodar o servidor
# python manage.py runserver

# LINKS DE ACESSO:

# Get all users
# http://127.0.0.1:8000/api/

# Get user with filter
# http://127.0.0.1:8000/api/data/?user=ytq18Q