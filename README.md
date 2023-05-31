>   # API Clinica Medica


  
## API Rest com Spring Boot

Este é um repositório contendo um projeto de API Rest desenvolvido com o Spring Boot. A finalidade deste projeto é fornecer um exemplo prático de um CRUD (Create, Read, Update e Delete) completo, juntamente com recursos de validação, paginação e ordenação.

## Objetivos

- Desenvolver uma API Rest utilizando o Spring Boot.
- Implementar as operações de CRUD para cadastro, listagem, atualização e exclusão de informações de Médicos e Pacientes.
- Aplicar validações nos dados recebidos pela API utilizando o Bean Validation.
- Utilizar recursos de paginação e ordenação para melhorar a resposta da API.

## Tecnologias

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- Spring Boot 3
- Java 17
- Lombok
- MySQL/Flyway
- JPA/Hibernate
- Maven
- Insomnia

### Spring Boot 3

O Spring Boot é um framework de desenvolvimento de aplicações Java que facilita a criação de projetos com configurações mínimas. A versão utilizada neste projeto é a mais recente disponibilizada pelo framework, a Spring Boot 3.

### Java 17

O Java 17 é a última versão LTS (Long-term support) do Java, que oferece um maior tempo de suporte para a linguagem. Neste projeto, utilizamos recursos das últimas versões do Java para tornar o código mais simples e expressivo.

### Lombok

O Lombok é uma biblioteca que auxilia na redução da verbosidade do código Java, gerando automaticamente getters, setters, toString e outros métodos repetitivos através de anotações. Utilizamos o Lombok para tornar o código mais limpo e legível.

### MySQL/Flyway

O MySQL é um sistema de gerenciamento de banco de dados relacional amplamente utilizado. Neste projeto, utilizamos o MySQL para armazenar as informações da API. Além disso, integramos o Flyway, uma biblioteca de controle de versão de banco de dados, para gerenciar as migrações e evolução do banco de dados de forma controlada.

### JPA/Hibernate

A Java Persistence API (JPA) é uma especificação que define uma interface comum para frameworks de mapeamento objeto-relacional. Neste projeto, utilizamos o Hibernate como implementação da JPA, juntamente com os módulos do Spring Boot, para simplificar a camada de persistência da aplicação.

### Maven

O Maven é uma ferramenta de gerenciamento de dependências e automação de build. Utilizamos o Maven para gerenciar as dependências do projeto e também para gerar o build da aplicação.

### Insomnia

O Insomnia é uma ferramenta de teste de APIs que permite simular requisições e verificar o funcionamento das funcionalidades implementadas. Utilizamos o Insomnia para testar a API desenvolvida neste projeto.

## Projeto

O projeto consiste em um protótipo de um aplicativo para uma clínica médica fictícia chamada Voll Med. O objetivo do aplicativo é permitir o cadastro de médicos, pacientes e agendamento de consultas. 

O aplicativo possui três telas principais: tela inicial, tela de pesquisa e tela de cadastro. Na tela inicial, há um logotipo da aplicação e três botões retangulares para escolher as seções: Médicos(as), Pacientes e Consultas. Ao selecionar uma seção a tela de pesquisa é exibida, mostrando os resultados da seção selecionada em ordem alfabética. Na tela de cadastro, há um formulário com campos como nome completo, especialidade, CRM, e-mail, telefone ou celular, logradouro, número, complemento e cidade.

## Instruções de Uso

Para executar a API, siga as seguintes etapas:

1. Certifique-se de ter o Java 17 e o Maven instalados em seu sistema.
2. Clone este repositório para o seu ambiente de desenvolvimento.
3. Configure as informações de conexão com o banco de dados MySQL no arquivo `application.properties`.
4. Execute o comando `mvn spring-boot:run` na raiz do projeto para iniciar a aplicação.
5. Utilize o Insomnia ou outra ferramenta similar para testar a API, acessando as rotas disponíveis.

Fique à vontade para explorar o código-fonte e adaptar o projeto de acordo com as suas necessidades.

## Links Úteis
[Spring Initializr](https://start.spring.io/)

[Insomnia](https://insomnia.rest/download)

**Nota:** Lembre-se de substituir os valores das configurações do banco de dados e outras informações de acordo com o seu ambiente.

Espero que este projeto seja útil para você aprender e explorar os conceitos de desenvolvimento de API Rest com o Spring Boot. Divirta-se desenvolvendo e aprimorando suas habilidades!

Caso tenha alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato. Aproveite!

