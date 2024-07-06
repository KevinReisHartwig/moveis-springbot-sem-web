# Screenmatch Application
Este projeto é uma aplicação Java Spring Boot que inclui duas versões: uma versão sem web e uma versão com web, utilizando uma página web pronta. A aplicação foi projetada para gerenciar séries e episódios, oferecendo funcionalidades tanto através de uma API quanto através de uma interface web.

## Estrutura do Projeto
- API: Desenvolvida em Java com Spring Boot, a API oferece endpoints para gerenciar séries e episódios.
- Interface Web: Uma página web pré-construída que interage com a API para fornecer uma interface amigável ao usuário.
## Tecnologias Utilizadas
### Backend:

- Java
- Spring Boot
- JPA (Java Persistence API)
- Hibernate
- PostgreSQL
### Frontend:

- HTML
- CSS
- JavaScript
### Ferramentas de Desenvolvimento:

- IntelliJ IDEA (para rodar a API)
- Visual Studio (para rodar a página web)
- Spring Data JPA
## Requisitos
- Java: Versão 11 ou superior
- Maven: Para gerenciamento de dependências
- IntelliJ IDEA: Para desenvolvimento e execução da API
- Visual Studio: Para desenvolvimento e execução da página web
## Configuração do Ambiente

### Passo 1: Configurar o Banco de Dados
- Configure o banco de dados no arquivo application.properties.
### Passo 2: Rodar a API no IntelliJ IDEA
- Abra o projeto no IntelliJ IDEA.
- Configure as dependências do Maven.
- Rode a aplicação Spring Boot através da classe ScreenmatchApplication para rodar com web.
- Se for rodar sem web é o ScreenmatchSemWebApplication
### Passo 3: Rodar a Página Web no Visual Studio
- Abra a pasta da página web no Visual Studio.
- Configure o Live Server para rodar na porta 5501.
- Inicie o servidor para visualizar a página web.
