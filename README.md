<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Space</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2 {
            color: #333;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Projeto Space</h1>
    <p>Este é um projeto Django criado para fins de aprendizado e desenvolvimento.</p>
    
    <h2>Instalação</h2>
    <p>Para instalar e executar o projeto, siga os passos abaixo:</p>
    <pre>
    git clone https://github.com/seu-usuario/space.git
    cd space
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    venv\Scripts\activate  # Windows
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver
    </pre>
    
    <h2>Estrutura do Projeto</h2>
    <ul>
        <li><strong>setup/</strong> - Configuração principal do projeto.</li>
        <li><strong>galeria/</strong> - Aplicação principal do projeto.</li>
        <li><strong>templates/</strong> - Arquivos de template HTML.</li>
        <li><strong>static/</strong> - Arquivos estáticos (CSS, JS, imagens).</li>
        <li><strong>db.sqlite3</strong> - Banco de dados SQLite padrão.</li>
    </ul>
    
    <h2>Configuração</h2>
    <p>O arquivo <code>settings.py</code> inclui configurações essenciais como:</p>
    <ul>
        <li>Uso de <code>dotenv</code> para variáveis de ambiente.</li>
        <li>Configuração de banco de dados SQLite.</li>
        <li>Gerenciamento de arquivos estáticos.</li>
    </ul>
    
    <h2>Licença</h2>
    <p>Este projeto está licenciado sob a licença MIT.</p>
</body>
</html>
