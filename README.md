# API Escola - Django Rest Framework

### [Requisitos]

* Python 3.11 +
* Django 4.2
* Django Rest Framework 3.14


### [Instalação]

* Criar um ambiente virtual: `python -m venv venv`
*  Ativar ambiente virtual: `.\venv\Scripts\activate`
* Instalar dependências: `pip install -r requirements.txt`
* Criar um superuser do Django: `python manage.py createsuperuser`
* Rodar o projeto: `python manage.py runserver`

### [Endpoints]

* http://localhost:8000/alunos - Retorna Todos os Alunos
* https://localhost:8000/alunos/:id - Retorna um aluno
* https://localhost:8000/alunos/:id/matriculas/ - Retorna todas os cursos de um aluno
* https://localhost:8000/cursos - Retorna todos os cursos
* https://localhost:8000/cursos/:id - Retorna um curso
* https://localhost:8000/cursos/:id/matriculas - Retorna todos os alunos em um curso
* https://localhost:8000/matriculas - Lista geral dos Alunos Matriculados em Cursos</p>
