<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria - Documentação</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 40px;
            max-width: 800px;
        }
        h1, h2 {
            color: #333;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>📸 Galeria - Aplicação Django</h1>
    <p>Bem-vindo ao repositório do projeto <strong>Galeria</strong>, uma aplicação Django para gerenciamento de imagens.</p>
    
    <h2>📌 Sobre o Projeto</h2>
    <p>Este projeto utiliza Django como framework principal e está configurado para servir arquivos estáticos e templates.</p>
    
    <h2>🏗 Estrutura do Projeto</h2>
    <pre>
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
    </pre>
    
    <h2>🚀 Como Executar o Projeto</h2>
    <h3>📌 Pré-requisitos</h3>
    <p>Antes de começar, certifique-se de ter instalado:</p>
    <ul>
        <li><a href="https://www.python.org/downloads/">Python 3.8+</a></li>
        <li><a href="https://virtualenv.pypa.io/en/latest/">Virtualenv</a></li>
    </ul>
    
    <h3>🔧 Passo a Passo</h3>
    <p>1️⃣ Clone o repositório:</p>
    <pre>
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
    </pre>
    
    <p>2️⃣ Crie e ative um ambiente virtual:</p>
    <pre>
python -m venv venv
# Ativar no Windows
venv\Scripts\activate
# Ativar no Linux/macOS
source venv/bin/activate
    </pre>
    
    <p>3️⃣ Instale as dependências:</p>
    <pre>
pip install -r requirements.txt
    </pre>
    
    <p>4️⃣ Crie e aplique as migrações do banco de dados:</p>
    <pre>
python manage.py makemigrations
python manage.py migrate
    </pre>
    
    <p>5️⃣ Crie um superusuário para acessar o painel administrativo:</p>
    <pre>
python manage.py createsuperuser
    </pre>
    
    <p>6️⃣ Execute o servidor Django:</p>
    <pre>
python manage.py runserver
    </pre>
    <p>Acesse o projeto em <a href="http://127.0.0.1:8000/">http://127.0.0.1:8000/</a>.</p>
    
    <h2>📂 Configuração de Variáveis de Ambiente</h2>
    <p>Crie um arquivo <code>.env</code> na raiz do projeto e defina a variável <strong>SECRET_KEY</strong>:</p>
    <pre>
SECRET_KEY=sua_chave_secreta_aqui
    </pre>
    
    <h2>🛠 Tecnologias Utilizadas</h2>
    <ul>
        <li>Django 4.1</li>
        <li>Python 3.8+</li>
        <li>SQLite3</li>
    </ul>
    
    <h2>📜 Licença</h2>
    <p>Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo!</p>
    
    <hr>
    <p>✉️ <strong>Dúvidas ou sugestões?</strong> Entre em contato! 🚀</p>
</body>
</html>
