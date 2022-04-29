# receitas_django

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LombaAnderson/receitas_django/blob/main/LICENSE)

# Sobre o projeto
Site completo de receitas do curso da Alura feito em Django. Foi desenvolvido nesse projeto tanto o frontend quanto o backend em Django e possui paginação, filtros,
sistema de busca de receitas, data de envio das receitas e quem as enviou.


## Imagem de exemplo da home do site de receitas
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/166010091-c8c3e1c5-a9d8-454f-92df-9c544647bbae.png" width="700" />
</div>

## Print de exemplo de uma das receitas
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/166013785-10ee4fc3-dee0-4e51-a585-0ae459be022b.png" width="700" />
</div>

# principais Tecnologias utilizadas
- Python

 Principais Frameworks
-Django==4.0

-Pillow

-Python-decouple


# Instruções para compilar, testar e rodar o projeto

```bash
# Clonar repositório
git clone https://github.com/LombaAnderson/receitas_django

# Criação e acesso da pasta do projeto
-mkdir clientes
-cd clientes

# Criação do ambiente de desenvolvimento do Python
-python -m venv venv

# Ativar o ambiente de desenvolvimento(venv)
-source venv/Scripts/.activate

# Instalação do Django (Atenção: instalar somente após a ativação da venv)
-pip install django
 
# Comando de criação do projeto
-django-admin startproject alurareceita .

# Criação do servidor
-python manage.py runserver

# Acesso ao servidor Django
http://127.0.0.1:8000/

# Apps 
-django-admin startapp receitas

# Preparação das migrations
- python manage.py makemigrations

# Envio das migrations configuradas para o banco de dados
- python manage.py migrate

```

# Autor

Anderson Lomba de Oliveira

Linkedin

https://www.linkedin.com/in/anderson-lomba-140279142/

Portfólio

https://www.lombanderson.epizy.com

# Agradecimentos

Agradeço ao meu Deus que sempre me ajuda e a minha esposa que amo muito! 


