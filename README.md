

readme_filename = "README.html"
readme_content = """<!DOCTYPE html>
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
            line-height: 1.6;
        }
        h1, h2 {
            color: #333;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            background: #ddd;
            padding: 2px 5px;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <h1>Projeto Space</h1>
    <p>O <strong>Space</strong> é um projeto baseado no framework <strong>Django</strong> para desenvolvimento web. 
       Este projeto foi criado para fins de aprendizado e desenvolvimento, permitindo que qualquer pessoa, 
       mesmo iniciantes, consiga rodá-lo sem dificuldades.</p>
    
    <h2>Pré-requisitos</h2>
    <p>Antes de instalar o projeto, certifique-se de ter os seguintes requisitos:</p>
    <ul>
        <li>Python 3.8 ou superior instalado (<a href="https://www.python.org/downloads/">Baixar aqui</a>)</li>
        <li>Git instalado (<a href="https://git-scm.com/downloads">Baixar aqui</a>)</li>
        <li>Gerenciador de pacotes <code>pip</code></li>
        <li>Virtualenv para criar ambientes isolados (opcional, mas recomendado)</li>
    </ul>
    
    <h2>Instalação</h2>
    <p>Para instalar e executar o projeto no seu computador, siga os passos abaixo:</p>
    <pre>
    # Clone o repositório
    git clone https://github.com/seu-usuario/space.git
    
    # Entre no diretório do projeto
    cd space
    
    # Crie e ative um ambiente virtual (opcional, mas recomendado)
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    venv\Scripts\activate  # Windows
    
    # Instale as dependências do projeto
    pip install -r requirements.txt
    
    # Realize as migrações do banco de dados
    python manage.py migrate
    
    # Execute o servidor local
    python manage.py runserver
    </pre>
    <p>Após executar o servidor, o projeto estará disponível em <a href="http://127.0.0.1:8000" target="_blank">http://127.0.0.1:8000</a>.</p>
    
    <h2>Estrutura do Projeto</h2>
    <p>O projeto Space segue a estrutura padrão do Django:</p>
    <ul>
        <li><strong>setup/</strong> - Diretório principal do projeto.</li>
        <li><strong>galeria/</strong> - Aplicação principal do projeto.</li>
        <li><strong>templates/</strong> - Arquivos de template HTML.</li>
        <li><strong>static/</strong> - Arquivos estáticos (CSS, JS, imagens).</li>
        <li><strong>db.sqlite3</strong> - Banco de dados SQLite padrão.</li>
    </ul>
    
    <h2>Configuração do Projeto</h2>
    <p>O arquivo <code>settings.py</code> contém todas as configurações essenciais do projeto, incluindo:</p>
    <ul>
        <li>Uso de variáveis de ambiente com <code>dotenv</code>.</li>
        <li>Configuração do banco de dados SQLite.</li>
        <li>Gerenciamento de arquivos estáticos.</li>
    </ul>
    
    <h2>Como Contribuir</h2>
    <p>Se quiser contribuir para o desenvolvimento do projeto, siga os passos:</p>
    <ol>
        <li>Crie um fork do repositório.</li>
        <li>Crie uma branch para suas alterações: <code>git checkout -b minha-branch</code></li>
        <li>Faça as alterações e as submeta: <code>git commit -m "Minha contribuição"</code></li>
        <li>Envie as alterações: <code>git push origin minha-branch</code></li>
        <li>Abra um Pull Request.</li>
    </ol>
    
    <h2>Licença</h2>
    <p>Este projeto está licenciado sob a licença MIT, permitindo seu uso, modificação e distribuição.</p>
</body>
</html>"""


