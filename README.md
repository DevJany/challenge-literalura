# 📚 Literalura - Catálogo de Livros (Projeto Java & Spring)

![Java](https://img.shields.io/badge/Java-17%2B-blue?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-green?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-blue?style=for-the-badge&logo=postgresql&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-4.0-red?style=for-the-badge&logo=apache-maven&logoColor=white)

## ✍️ Descrição do Projeto

Este projeto foi desenvolvido como parte do desafio da formação **Java e Spring Framework G8 - ONE**, promovida pela Oracle Next Education em parceria com a Alura.

A proposta consiste em criar um **catálogo digital de livros**, capaz de consumir dados da API pública [Gutendex](https://gutendex.com/), armazenando e organizando autores e obras em um banco de dados local. A aplicação é interativa via terminal e permite diversas consultas ao conteúdo literário obtido.

## ⚙️ Funcionalidades Implementadas

- 🔎 **Pesquisar livro por título**  
  Busca na API Gutendex e armazena os dados localmente, caso ainda não existam.

- 📚 **Exibir livros salvos**  
  Lista todas as obras já registradas no banco.

- ✍️ **Listar autores cadastrados**  
  Mostra os autores com seus respectivos livros.

- 📆 **Filtrar autores vivos em um ano específico**  
  Consulta autores que estavam vivos no ano informado pelo usuário.

- 🌍 **Buscar livros por idioma**  
  Permite selecionar obras registradas por idiomas como inglês, português, espanhol ou francês.

## 🧰 Tecnologias Utilizadas

- **Java 17**  
- **Spring Boot 3**  
- **Spring Data JPA + Hibernate**  
- **PostgreSQL 14**  
- **Jackson (para JSON)**  
- **Maven (gerenciador de dependências)**

## 🚀 Como Executar Localmente

### Pré-requisitos

- Java 17+
- Maven 3.8+
- PostgreSQL instalado

### Passos para execução

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. **Clone o repositório:**
   No seu terminal ou cliente PostgreSQL:
   sql
   ```
   CREATE DATABASE catalogo_livros;
   ```

3. **Configure o banco de dados:**
   No arquivo src/main/resources/application.properties:
   ```
   spring.datasource.url=jdbc:postgresql://localhost:5432/catalogo_livros
    spring.datasource.username=SEU_USUARIO
    spring.datasource.password=SUA_SENHA
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true
   ```

4. **Compile e execute o projeto**
5. **Utilize o menu no terminal**

### 🌐 API Externa
Esta aplicação utiliza a Gutendex API para obter dados sobre livros de domínio público. Trata-se de uma API REST gratuita, baseada no Projeto Gutenberg.

## ❤️ Agradecimentos
Este projeto foi possível graças à formação Java e Spring Framework G8 - ONE, uma iniciativa da Oracle Next Education em parceria com a Alura. Foi uma jornada de aprendizado focada em boas práticas de desenvolvimento, integração com APIs externas e persistência com JPA.


Quer sugerir melhorias ou encontrou algum problema? Fique à vontade para abrir uma issue ou enviar um pull request!

Desenvolvido por Janyelle Oliveira

[![Linkedin](https://img.shields.io/badge/Linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](linkedin.com/in/janyelle/)
