# projeto-padaria
🥐 Sistema Padaria Mongo

Sistema de gerenciamento para padarias, desenvolvido em Java com Spring Boot e MongoDB.

🚀 Tecnologias Utilizadas

Java – Linguagem de programação principal

Spring Boot – Framework para construção de aplicações Java modernas

MongoDB – Banco de dados NoSQL utilizado para armazenamento de dados

Maven – Gerenciador de dependências e automação de builds

Docker – Contêineres para facilitar o desenvolvimento e implantação

👩‍💻 Autoras

 - Kelly Oliveira
 - Raquel Fernandes
 - Jucelaine Teles

📦 Pré-requisitos

Antes de rodar o projeto, certifique-se de ter as seguintes ferramentas instaladas:

Java 17 ou superior

Maven

Docker

MongoDB (ou utilize o Docker para rodar o MongoDB)

📥 Como Rodar o Projeto

Clone este repositório:

git clone https://github.com/kellyoliveira473/Sistema-Padaria-Mongo.git
cd Sistema-Padaria-Mongo


Compile o projeto:

./mvnw clean install


Inicie o MongoDB:

Caso não tenha o MongoDB instalado localmente, execute via Docker:

docker run --name mongodb -d -p 27017:27017 mongo


Execute a aplicação:

./mvnw spring-boot:run


A aplicação estará disponível em:
👉 http://localhost:8080

🔧 Endpoints Disponíveis

Os endpoints exatos não estão documentados no repositório.
Recomenda-se verificar o código-fonte para obter detalhes sobre as rotas disponíveis.

🧪 Testes

Para rodar os testes automatizados:

./mvnw test

🧱 Estrutura de Pastas
├── .mvn/              # Wrapper do Maven
├── src/               # Código-fonte da aplicação
│   ├── main/
│   │   ├── java/      # Código Java
│   │   └── resources/ # Arquivos de configuração
├── .gitignore         # Arquivos a serem ignorados pelo Git
├── Dockerfile         # Arquivo para construção da imagem Docker
├── mvnw               # Wrapper do Maven para Linux/Mac
├── mvnw.cmd           # Wrapper do Maven para Windows
└── pom.xml            # Arquivo de configuração do Maven

📄 Licença

Este projeto está licenciado sob a Licença MIT – veja o arquivo LICENSE
 para mais detalhes.
