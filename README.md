ForumHub
ForumHub é uma aplicação para gerenciar tópicos de discussão em um fórum, desenvolvida com Java e o framework Spring Boot.

Visão Geral
O ForumHub permite que usuários criem e gerenciem tópicos de discussão sobre diversos assuntos, interajam através de respostas e administrem conteúdos relacionados a cursos.

Funcionalidades
Criação de Tópicos: Criar novos tópicos com título, mensagem e associação a cursos específicos.

Listagem de Tópicos: Exibição paginada dos tópicos disponíveis no fórum.

Atualização de Tópicos: Atualizar título e mensagem de tópicos existentes.

Respostas: Usuários podem responder aos tópicos.

Gestão de Cursos: Administração dos cursos vinculados aos tópicos.

Estrutura do Projeto
src/main/java: Código-fonte Java.

br.com.alura.forumhub.forumHub.controller: Controladores da aplicação.

br.com.alura.forumhub.forumHub.domain: Entidades do domínio (ex.: Tópico, Curso, Autor).

autor: Classes relacionadas aos autores dos tópicos.

curso: Classes relacionadas aos cursos.

topicos: Classes relacionadas aos tópicos do fórum.

br.com.alura.forumhub.forumHub.repository: Repositórios para acesso a dados.

src/main/resources: Recursos da aplicação, incluindo:

application.properties: Configurações da aplicação (ex.: banco de dados).

data.sql: Script SQL para inicialização dos dados.

Tecnologias Utilizadas
Java 17

Spring Boot

Spring Data JPA

Hibernate

MySQL

Como Executar o Projeto
Pré-requisitos
Java JDK 11 instalado

MySQL Server instalado e configurado

Configuração do Banco de Dados
Crie um banco de dados no MySQL chamado forumhub

Configure as credenciais no arquivo application.properties

Execução
Clone o repositório

Importe o projeto na sua IDE (IntelliJ IDEA, Eclipse, etc.)

Execute a classe principal ForumHubApplication.java

Testando a Aplicação
Acesse http://localhost:8080 no navegador

Use Postman ou curl para testar as APIs REST

