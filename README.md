FórumHub

Um fórum é um espaço onde todos os participantes de uma plataforma podem colocar suas perguntas sobre determinados assuntos. Aqui na Alura, os alunos e alunas utilizam o fórum para tirar suas dúvidas sobre os cursos e projetos em que estão participando. Este lugar mágico está cheio de muita aprendizagem e colaboração entre alunos, professores e moderadores.

Sobre o Projeto

Já sabemos para que serve o fórum e sabemos sua aparência, mas sabemos como ele funciona por trás dos panos? Isto é, onde se armazenam as informações? Como são tratados os dados para que se relacione um tópico com uma resposta, ou como se relacionam os usuários com as respostas de um tópico?

Este é o nosso desafio, chamado de FórumHub: nele, vamos replicar este processo no nível do back end e, para isso, criaremos uma API REST usando Spring.

Funcionalidades

Nossa API se concentrará especificamente nos tópicos e deve permitir aos usuários:

Criar um novo tópico;

Mostrar todos os tópicos criados;

Mostrar um tópico específico;

Atualizar um tópico;

Eliminar um tópico.

Isso é conhecido como CRUD (CREATE, READ, UPDATE, DELETE) e é muito parecido com o que desenvolvemos no LiterAlura, mas agora de forma completa, agregando as operações de UPDATE e DELETE, e usando um framework que facilitará muito o nosso trabalho.

Tradução livre (em ordem): Criar, Consultar, Atualizar e Deletar.

Objetivos do Challenge

Nosso objetivo com este challenge é implementar uma API REST com as seguintes funcionalidades:

API com rotas implementadas seguindo as melhores práticas do modelo REST;

Validações realizadas segundo as regras de negócio;

Implementação de uma base de dados relacional para a persistência da informação;

Serviço de autenticação/autorização para restringir o acesso à informação.

Tecnologias Utilizadas

Para desenvolver a API do FórumHub, utilizaremos as seguintes tecnologias:

Java 17+

Spring Boot

Spring Security

Spring Data JPA

Hibernate

Banco de Dados Relacional (PostgreSQL/MySQL)

JWT para autenticação

Swagger/OpenAPI para documentação
Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu-usuario/forumhub.git

Entre no diretório do projeto:

git clone https://github.com/seu-usuario/forumhub.git

cd forumhub

Configure as variáveis de ambiente no arquivo application.properties.

Execute o projeto:
./mvnw spring-boot:runFórumHub - API REST para um Fórum

Um fórum é um espaço onde todos os participantes de uma plataforma podem colocar suas perguntas sobre determinados assuntos. Aqui na Alura, os alunos e alunas utilizam o fórum para tirar suas dúvidas sobre os cursos e projetos em que estão participando. Este lugar mágico está cheio de muita aprendizagem e colaboração entre alunos, professores e moderadores.
Sobre o Projeto

Já sabemos para que serve o fórum e sabemos sua aparência, mas sabemos como ele funciona por trás dos panos? Isto é, onde se armazenam as informações? Como são tratados os dados para que se relacione um tópico com uma resposta, ou como se relacionam os usuários com as respostas de um tópico?

Este é o nosso desafio, chamado de FórumHub: nele, vamos replicar este processo no nível do back end e, para isso, criaremos uma API REST usando Spring.
Funcionalidades

Nossa API se concentrará especificamente nos tópicos e deve permitir aos usuários:

    Criar um novo tópico;

    Mostrar todos os tópicos criados;

    Mostrar um tópico específico;

    Atualizar um tópico;

    Eliminar um tópico.

Isso é conhecido como CRUD (CREATE, READ, UPDATE, DELETE) e é muito parecido com o que desenvolvemos no LiterAlura, mas agora de forma completa, agregando as operações de UPDATE e DELETE, e usando um framework que facilitará muito o nosso trabalho.

    Tradução livre (em ordem): Criar, Consultar, Atualizar e Deletar.

Objetivos do Challenge

Nosso objetivo com este challenge é implementar uma API REST com as seguintes funcionalidades:

    API com rotas implementadas seguindo as melhores práticas do modelo REST;

    Validações realizadas segundo as regras de negócio;

    Implementação de uma base de dados relacional para a persistência da informação;

    Serviço de autenticação/autorização para restringir o acesso à informação.

Tecnologias Utilizadas

Para desenvolver a API do FórumHub, utilizaremos as seguintes tecnologias:

    Java 17+

    Spring Boot

    Spring Security

    Spring Data JPA

    Hibernate

    Banco de Dados Relacional (PostgreSQL/MySQL)

    JWT para autenticação

    Swagger/OpenAPI para documentação

Como Executar o Projeto

    Clone o repositório:
    git clone https://github.com/seu-usuario/forumhub.git

    Entre no diretório do projeto:
    cd forumhub

    Configure as variáveis de ambiente no arquivo application.properties.

    Execute o projeto:
    ./mvnw spring-boot:run

    Acesse a API via http://localhost:8080.

Documentação da API

A documentação interativa da API pode ser acessada através do Swagger UI:

http://localhost:8080/swagger-ui.html
Autores

Este projeto foi desenvolvido pela comunidade da Alura como parte de um desafio de aprendizado.

Dúvidas? Entre em contato através do nosso fórum!
