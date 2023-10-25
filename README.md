# Projeto para teste na empresa Visie - Lista de Pessoas

Este projeto é uma aplicação dividida em duas partes distintas, com o objetivo de criar uma Lista de Pessoas. Ele se destina a ser um projeto de teste para a empresa Visie, no qual os candidatos demonstrarão suas habilidades de desenvolvimento tanto no back-end quanto no front-end. O projeto abrange a criação, leitura, atualização e exclusão (CRUD) de informações de pessoas, com os dados sendo armazenados em um banco de dados.

A aplicação é organizada da seguinte forma:

## Pasta Backend
A pasta "Backend" contém a parte do servidor da aplicação, construída com o framework Flask. O objetivo do backend é fornecer as funcionalidades necessárias para realizar operações CRUD e salvar os dados no banco. Para configurar e executar o backend, siga estas etapas:

### 1. Configuração do Ambiente
- Navegue até a pasta "backend".
- Crie um ambiente virtual para isolar as dependências do projeto. Dependendo do sistema operacional, utilize os seguintes comandos:
  - Para Windows: `python -m venv .venv`
  - Para Linux: `python3 -m venv .venv`

- Ative o ambiente virtual:
  - Para Windows: `.venv/Scripts/activate`
  - Para Linux: `source .venv/bin/activate`

### 2. Atualização de Pacotes
- Certifique-se de que o utilitário `pip` está atualizado executando o seguinte comando:
  - `python -m pip install --upgrade pip`

### 3. Instalação de Dependências
- Instale as dependências do projeto a partir do arquivo `requirements.txt` executando o seguinte comando:
  - `pip install -r requirements.txt`

### 4. Variáveis de Ambiente
- Renomeie o arquivo `env.sample` para `.env` e configure as variáveis de ambiente necessárias conforme as especificações do projeto.

### 5. Inicialização do Servidor
- Inicie a aplicação Flask executando o seguinte comando a partir da pasta "backend":
  - `python app.py`

## Pasta Frontend
A pasta "Frontend" contém a parte do cliente da aplicação, construída usando o framework Vue.js. O frontend é responsável por fornecer uma interface de usuário interativa e amigável. Para configurar e executar o frontend, siga estas etapas:

### 1. Instalação de Dependências
- Abra a pasta "Frontend" no terminal.
- Instale as dependências do projeto usando o comando:
  - `yarn install`

### 2. Inicialização do Servidor
- Inicie a aplicação Vue.js com o seguinte comando:
  - `yarn serve`

Após concluir essas etapas, você terá a aplicação em execução, com o frontend servindo como a interface para interação com o usuário e o backend lidando com as operações de CRUD e o armazenamento dos dados no banco de dados.

Este projeto é um teste valioso para avaliar as habilidades dos candidatos na criação de aplicativos web completos, desde a configuração do ambiente até o desenvolvimento de interfaces de usuário funcionais e serviços de back-end robustos. É uma oportunidade de demonstrar proficiência no uso de tecnologias como Flask e Vue.js, bem como habilidades em gerenciamento de ambientes virtuais e controle de dependências.
