# Gerenciador de Livros e Autores - Literalura

## Sobre o Projeto
Literalura é um sistema back-end simples em **Java** com **Spring Boot** para gerenciar livros e autores. Oferece recursos como:
- Busca de livros por título.
- Cadastro e listagem de livros e autores.
- Estatísticas de downloads.
- Ranking dos 10 livros mais baixados.

Integra-se com uma **API externa** para buscar dados de livros e usa **PostgreSQL** para armazenamento.

## Principais Recursos
- **Busca por Título**: Consulta livros via API externa e os cadastra no banco.
- **Gerenciamento**: Registra livros e autores.
- **Listagens**: Exibe livros, autores e dados filtrados por idioma.
- **Estatísticas**: Mostra números de downloads e top 10 livros mais baixados.

## Tecnologias
- **Java** e **Spring Boot**.
- **PostgreSQL**.
- **Gutendex API** para busca de livros.
- **Maven** e **Lombok**.

## Organização do Código
- **model**: Classes principais como Livro e Autor.
- **repository**: Acesso ao banco com Spring Data JPA.
- **service**: Integração com APIs externas.
- **principal**: Classe principal para interação via terminal.

## Como Usar
1. Clone o repositório:  
   `git clone https://github.com/Lumabarbosa/challenge_literalura.git`
2. Entre na pasta do projeto:  
   `cd challengeliteralura`
3. Configure o PostgreSQL no arquivo `application.properties`.
4. Execute com:  
   `mvn spring-boot:run`
5. Use o terminal para interagir com o sistema.
