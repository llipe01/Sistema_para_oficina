🔧 Sistema de Gerenciamento de Oficina

Sistema web desenvolvido em Python para auxiliar no gerenciamento de uma oficina mecânica, facilitando o controle de clientes, veículos, serviços e agendamentos.

📌 Sobre o projeto

O Sistema de Gerenciamento de Oficina foi desenvolvido com o objetivo de organizar as principais atividades de uma oficina mecânica por meio de uma aplicação web integrada a um banco de dados MySQL.

O projeto conta com uma interface web, autenticação de usuários e funcionalidades para facilitar o gerenciamento dos atendimentos.

🚀 Funcionalidades

🔐 Login e autenticação: acesso ao sistema por meio de usuários cadastrados.

👥 Gerenciamento de clientes: cadastro e consulta de informações dos clientes.

🚗 Gerenciamento de veículos: organização dos veículos vinculados aos clientes.

📅 Agendamento de serviços: registro e gerenciamento dos agendamentos.

🛠️ Controle de serviços: cadastro e consulta dos serviços oferecidos pela oficina.

📊 Página principal: acesso às principais áreas do sistema.

🗄️ Banco de dados MySQL: armazenamento e organização das informações.

💻 Tecnologias utilizadas

Python — lógica e processamento da aplicação.

Flask — desenvolvimento do sistema web.

MySQL — gerenciamento do banco de dados.

MySQL Connector — conexão entre Python e MySQL.

HTML5 — estrutura das páginas.

CSS3 — estilização e layout.

JavaScript — interatividade da interface.

bcrypt — proteção de senhas por hash.

📂 Estrutura do projeto

sistema_oficina/
├── app.py
├── autenticacao.py
├── agendamento.py
├── clientes.py
├── veiculos.py
├── rotas.py
├── db.py
├── testar_conexao.py
├── requirements.txt
├── saep_db.sql
├── static/
│   ├── app.js
│   └── style.css
└── templates/
    ├── login.html
    ├── principal.html
    ├── clientes.html
    ├── veiculos.html
    └── agendamentos.html

⚙️ Como executar o projeto

1. Pré-requisitos

Antes de começar, instale:

Python 3.10 ou superior.

MySQL Server.

MySQL Workbench (opcional, para administrar o banco de dados).

2. Clone o repositório

git clone URL_DO_SEU_REPOSITORIO

Entre na pasta do projeto:

cd sistema_oficina

3. Instale as dependências

pip install -r requirements.txt

4. Configure o banco de dados

Abra o MySQL Workbench e execute o script saep_db.sql para criar o banco de dados e as tabelas necessárias.

O banco utilizado pela aplicação é saep_db_v1.

5. Configure a conexão

Defina as variáveis de ambiente para conectar a aplicação ao MySQL:

DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=sua_senha
DB_NAME=saep_db_v1
SECRET_KEY=sua_chave_secreta

Configure essas variáveis no ambiente em que o Python será executado. Não publique senhas ou chaves secretas no GitHub.

Importante: confira o arquivo db.py e garanta que ele utilize as variáveis de ambiente, sem depender de uma senha fixa no código.

6. Execute a aplicação

python app.py

Depois, acesse no navegador:

http://127.0.0.1:5000

🔑 Acesso ao sistema

O script SQL contém usuários de teste para acessar a aplicação:

Usuário

Senha

admin

admin123

carlos

carlos123

ana

ana12345

Essas credenciais são destinadas ao ambiente de teste. Em um ambiente real, utilize senhas seguras e altere as credenciais padrão.

🎯 Objetivo acadêmico

Este projeto tem como objetivo aplicar conhecimentos de desenvolvimento web, programação em Python, integração com banco de dados relacionais, autenticação de usuários e organização de sistemas.

👨‍💻 Autor
Fellipe Guarantani de Oliveira
Desenvolvido como projeto de estudos na área de Desenvolvimento de Sistemas.

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!
