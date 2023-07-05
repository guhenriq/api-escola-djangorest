<h1>API Escola - Django Rest Framework</h1>

<h3>[Requisitos]</h3>
<ul>
  <li>Python 3.11</li>
  <li>Django 4.2</li>
  <li>Django Rest Framework 3.14</li>
</ul>

<h3>[Instalação]</h3>
<ul>
  <li>Criar um ambiente virtual: <strong>python -m venv venv</strong></li>
  <li>Ativar ambiente virtual: <strong>.\venv\Scripts\activate</li></strong>
  <li>Instalar dependências: <strong>pip install -r requirements.txt</strong></li>
  <li>Criar um usuário do Django: <strong>python manage.py createsuperuser</strong></li>
  <li>Rodar o projeto: <strong>python manage.py runserver</strong></li>
</ul>

<h3>[Endpoints]</h3>
<p><a>localhost:8000/alunos</a> - Retorna todos os alunos</p>
<p><a>localhost:8000/alunos/:id</a> - Retorna um aluno</p>
<p><a>localhost:8000/cursos</a> - Retorna todos os cursos</p>
<p><a>localhost:8000/cursos/:id</a> - Retorna um curso</p>
<p><a>localhost:8000/matriculas</a> - Lista geral dos Alunos Matriculados em Cursos</p>
