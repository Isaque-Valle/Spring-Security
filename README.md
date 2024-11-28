# Clínica Voll - Projeto Spring Security

Este projeto foi desenvolvido durante o curso de **Spring Security** da [Alura](https://www.alura.com.br/). A aplicação é baseada no site fictício "Clínica Voll", onde é possível analisar dados de médicos e consultas. O sistema inclui uma página inicial de login, onde as credenciais do usuário são validadas em um banco de dados MySQL.

## 🚀 Funcionalidades

- **Autenticação e autorização de usuários**: Implementação de login utilizando Spring Security.
- **Gerenciamento de dados**: Consultas e manipulação de informações relacionadas a médicos e consultas.
- **Persistência de dados**: Utilização de banco de dados MySQL com controle de versão de schema usando Flyway.

## 🛠️ Tecnologias Utilizadas

- **Java **
- **Spring Boot 3.x**
- **Spring Security**
- **MySQL 8**
- **Flyway** (para controle de versão do banco de dados)

## 🗂️ Pré-requisitos

Antes de executar a aplicação, certifique-se de ter o **MySQL 8** instalado. Caso precise de ajuda para instalar o MySQL, consulte o artigo [MySQL: da instalação até a configuração](https://www.alura.com.br/artigos/mysql-da-instalacao-ate-a-configuracao).

### 🎯 Passos para configurar o banco de dados:

1. Acesse o console do MySQL e execute o seguinte comando para criar o banco de dados:
   ```sql
   create database vollmed_web;


O MySQL deve retornar:
Query OK, 1 row affected (0.00 sec)
Isso confirma que o banco foi criado com sucesso.

2. Selecione o banco de dados recém-criado:
use vollmed_web;



3. Verifique as tabelas criadas automaticamente pelo Flyway com o seguinte comando:
show tables;

As tabelas esperadas são:

**medicos**
**consultas**
**flyway_schema_history**


## Testando a Aplicação
Crie registros iniciais: Após a inicialização da aplicação, insira dados nas tabelas usando o MySQL ou a interface da aplicação.
Acesse a página de login: Teste o sistema utilizando as credenciais cadastradas no banco de dados.


## Este projeto proporcionou uma experiência prática em:

Configuração e uso do Spring Security para proteger aplicações web.
Integração com o banco de dados MySQL utilizando o Spring Data JPA.
Controle de versão do banco de dados com Flyway.
Agradecimentos à Alura pelo excelente conteúdo educacional! 😊
