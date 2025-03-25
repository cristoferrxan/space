# 📸 Galeria - Aplicação Django

Bem-vindo ao repositório do projeto **Galeria**, uma aplicação Django para gerenciamento de imagens.

## 📌 Sobre o Projeto

Este projeto utiliza Django como framework principal e está configurado para servir arquivos estáticos e templates.

## 🏗 Estrutura do Projeto

```
├── galeria/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│
├── setup/
│   ├── static/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── static/
│   ├── admin/
│   ├── assets/
│   ├── styles/
├── templates/
├── venv/ (ambiente virtual)
├── .gitignore
├── db.sqlite3
├── manage.py
├── README.md
├── requirements.txt
```

## 🚀 Como Executar o Projeto

### 📌 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Python 3.8+](https://www.python.org/downloads/)
- [Virtualenv](https://virtualenv.pypa.io/en/latest/)

### 🔧 Passo a Passo

1️⃣ Clone o repositório:

```sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2️⃣ Crie e ative um ambiente virtual:

```sh
python -m venv venv
# Ativar no Windows
venv\Scripts\activate
# Ativar no Linux/macOS
source venv/bin/activate
```

3️⃣ Instale as dependências:

```sh
pip install -r requirements.txt
```

4️⃣ Crie e aplique as migrações do banco de dados:

```sh
python manage.py makemigrations
python manage.py migrate
```

5️⃣ Crie um superusuário para acessar o painel administrativo:

```sh
python manage.py createsuperuser
```

6️⃣ Execute o servidor Django:

```sh
python manage.py runserver
```

Acesse o projeto em [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## 📂 Configuração de Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto e defina a variável **SECRET_KEY**:

```sh
SECRET_KEY=sua_chave_secreta_aqui
```

## 🛠 Tecnologias Utilizadas

- Django 4.1
- Python 3.8+
- SQLite3

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo!

---

✉️ **Dúvidas ou sugestões?** Entre em contato! 🚀
