
<p align="center">
  <img width="250" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain-wordmark.svg"/>
</p>

<h1 align="center">django</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=092E20&text=Introdução%20ao%20Django&fontSize=25&fontColor=FFFFFF&fontAlignY=55"/>
</p>

<h3 align="center">Instalando o Django :</h3>

<h4>Criando um ambiente virtual</h4>

<img width="25" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/windows11/windows11-original.svg" /> No **Windows** (*Prompt de Comando ou PowerShell*):
```txt
python -m venv venv
```
**Ativar ambiente virtual** no windows:
```txt
venv\Scripts\Activate
```

<hr>

<img width="25" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" /> No **Linux/macOS:**
```txt
python3 -m venv venv
```

**Ativar ambiente virtual** no linux:
```txt
source venv/bin/activate
```

<hr>

<img  width="25" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" /> Agora, **instale o Django** na versão mais recente:
```txt
pip install django
```

Verifique se a **instalação foi bem-sucedida:**
```txt
django-admin --version
```

<h3 align="center">Criando um Projeto Django :</h3>

Agora, vamos criar um projeto Django chamado "*meuprojeto*":
```txt
django-admin startproject meuprojeto
```

Isso criará uma estrutura de **diretórios como esta:**
```txt
meuprojeto/
│── manage.py
│── meuprojeto/
│   │── __init__.py
│   │── settings.py
│   │── urls.py
│   │── asgi.py
│   │── wsgi.py
```

Explicação dos **arquivos criados:**
- `anage.py` → Comando principal para gerenciar o projeto.
- `settings.py` → Arquivo de configurações do Django.
- `urls.py` → Define as rotas do projeto.
- `wsgi.py` e `asgi.py` → Arquivos usados para rodar o projeto em servidores web.

<h3 align="center">Rodando o Servidor Django :</h3>

Agora, entre no diretório do projeto e execute o servidor Django:

```txt
cd meuprojeto
python manage.py runserver
```

Se tudo estiver certo, você verá esta **saída no terminal:**

```txt
Starting development server at http://127.0.0.1:8000
```

Acesse **http://127.0.0.1:8000/** no navegador e veja a página padrão do Django!

<h3 align="center">Criando um Aplicativo (App) no Django :</h3>

No Django, cada funcionalidade pode ser organizada em **Apps**. Vamos criar um **app chamado "meuapp"**.

```txt
python manage.py startapp meuapp
```

Isso criará uma nova pasta com a seguinte estrutura:

```txt
meuapp/
│── __init_.py
│── admin.py
│── apps.py
│── models.py
│── tests.py
│── views.py
│── migrations/
```

📌 Explicação dos arquivos do App:
- `admin.py` → Configuração do painel administrativo do Django.
- `models.py` → Definição dos modelos (banco de dados).
- `views.py` → Lógica para exibir páginas.
- `urls.py` (*precisamos criar*) → Define as rotas do App.
- `migrations/` → Alterações no banco de dados.

Agora, registre o app em `settings.py` (*para ativá-lo no Django*). Abra `settings.py` e adicione 'meuapp' na lista `INSTALLED_APPS`:

```python
INSTALLED_APPS = [
    ...
    'meuapp',
]
```

<h3 align="center">Criando a Primeira View :</h3>

Uma **View** no Django é responsável por processar **requisições HTTP** e retornar respostas.

Abra `meuapp/views.py` e crie uma view simples:

```python
from django.http import HttpResponse

def home(request):
    return HttpResponse("Hello World")
```

Agora, precisamos criar um arquivo de rotas (`urls.py`) dentro do app meuapp.
Crie o arquivo `meuapp/urls.py` e adicione:

```python
from django.urls import path
from . import views

urlpatterns = [
    path('index/', views.home, name='home'),
]
```
​
Agora, conecte essas rotas ao arquivo principal `urls.py` do projeto.
Abra `meuprojeto/urls.py` e adicione a referência ao app:

```python
from django.contrib import admin
from django.urls import path, include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('meuapp/', include('meuapp.urls')),  # Inclui as URLs do app
]
```
Agora, acesse http://127.0.0.1:8000/ e veja "Hello World" na tela! 

<h3 align="center">Trabalhando com Templates</h3>

Até agora, usamos apenas `HttpResponse`, mas queremos criar páginas HTML completas.

1. Dentro do app `meuapp`, crie uma pasta chamada **`templates`**.
2. Dentro dela, crie outra pasta **`meuapp`** (*boa prática para evitar conflitos entre apps*).
3. Dentro dessa pasta, crie um arquivo **`home.html`**.

**A estrutura ficará assim:**
```txt
meuapp
│── templates/
│   │── meuapp/
│   │   ├── home.html
```

Agora, edite `home.html` :
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial</title>
</head>
<body>
    <h1>Bem-vindo!</h1>
    <p>Tenha um bom dia!</p>
</body>
</html>
```

Agora, altere a **view** em `views.py` para renderizar esse template:

```python
from django.shortcuts import render

def home(request):
    return render(request, 'meuapp/home.html')
```

Agora, acesse **http://127.0.0.1:8000/** e veja a página renderizada!

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=092E20&text=Trabalhando%20com%20Banco%20de%20Dados%20e%20Modelos%20no%20Django&fontSize=25&fontColor=FFFFFF&fontAlignY=55"/>
</p>

<h3 align="center">Configuração do Banco de Dados :</h3>

O Django já vem configurado para usar o **SQLite**, e podemos ver essa configuração no arquivo **`settings.py`**.

Abra `meuprojeto/settings.py` e localize esta seção:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / "db.sqlite3",
    }
}
```

📌 **Explicação:**

- **`ENGINE`** → Define qual banco de dados será usado (`sqlite3` no caso).
- **`NAME`** → Define o nome do arquivo do banco de dados (`db.sqlite3` será criado automaticamente na raiz do projeto).

<h3 align="center">Criando um Modelo de Banco de Dados :</h3>

Agora, vamos criar um **modelo de banco de dados** dentro do nosso **app** (`meuapp`).

Abra o arquivo **`meuapp/models.py`** e adicione o seguinte código:

```python
from django.db import models

class Pessoa(models.Model):
    nome = models.CharField(max_length=100)
    idade = models.IntegerField()
    email = models.EmailField(unique=True)

    def __str__(self):
        return self.nome
```

📌 **Explicação:**

- **`models.Model`** → Todos os modelos devem herdar dessa classe.
- **`CharField(max_length=100)`** → Define um campo de texto com no máximo 100 caracteres.
- **`IntegerField()`** → Define um campo para números inteiros.
- **`EmailField(unique=True)`** → Campo de e-mail, e cada e-mail deve ser único.
- **`__str__`** → Define como o objeto será representado ao ser impresso.

<h3 align="center">Criando as Migrations</h3>

Agora que criamos um modelo, precisamos dizer ao Django para adicioná-lo ao banco de dados.

Execute este comando para criar as **migrations**:

```txt
python manage.py makemigrations meuapp
```

📌 Isso cria um arquivo dentro da pasta `migrations/`, indicando as mudanças a serem aplicadas no banco.

Agora, aplique as migrations e crie a tabela no banco:

```txt
python manage.py migrate
```

Se tudo ocorrer bem, você verá mensagens indicando que a tabela foi criada. O **banco de dados (`db.sqlite3`)** agora contém a tabela **Pessoa**!

<h3 align="center">Testando o Banco de Dados no Shell do Django</h3>

Podemos interagir com o banco de dados diretamente pelo **shell interativo** do Django.

Execute este comando para abrir o shell do Django:

```txt
python manage.py shell
```

No shell, execute os seguintes comandos para testar a criação e consulta de registros:
```python
from meuapp.models import Pessoa

# Criar uma nova pessoa
p1 = Pessoa(nome="Carlos", idade=30, email="carlos@email.com")
p1.save()  # Salva no banco de dados

# Buscar todas as pessoas no banco
pessoas = Pessoa.objects.all()
print(pessoas)

# Buscar uma pessoa específica pelo nome
pessoa = Pessoa.objects.get(nome="Carlos")
print(pessoa)
```

Para sair do shell:
```python
exit()
```
<h3 align="center">Adicionando o Modelo ao Painel Administrativo do Django</h3>
O Django possui um **painel administrativo pronto** que nos permite visualizar e gerenciar os dados.

Para ativá-lo, abra `meuapp/admin.py` e registre o modelo `Pessoa`:

```python
from django.contrib import admin
from .models import Pessoa

admin.site.register(Pessoa)
```

Agora, crie um superusuário para acessar o painel admin:

```
python manage.py createsuperuser
```

Digite um **nome de usuário, e-mail e senha**.

Inicie o servidor:

```
python manage.py runserver
```

Acesse **http://127.0.0.1:8000/admin/** e faça login com o superusuário que você criou.
Agora, você verá "Pessoas" no painel administrativo, onde pode adicionar, editar e excluir registros do banco de dados!
