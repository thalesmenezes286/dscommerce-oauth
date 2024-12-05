# DSCommerce-OAuth
##Projeto de autênticação utilizando OAuth2 no SpringBoot

Tabela de Conteúdo
Sobre o projeto
Modelo Conceitual
Requisitos
Funcionalidades
Documentação da API
Acessando localmente
Tecnologias Utilizadas
Aprendizados
Rodando localmente
Rodando os testes
Autores

Sobre o projeto
O projeto DSCommerce é um projeto desenvolvido durante o Curso Java Spring Professional, ministrado pelo Professor Nelio Alves da DevSuperior.

Este projeto consiste em uma API REST de um Comércio Eletrônico, onde é possível gerenciar Produtos, Pedidos e Clientes.


Modelo Conceitual


Modelo de domínio DSCommerce


Requisitos
Java JDK (versão 17 ou superior)
Git - Sistema de controle de versão de código aberto
Uma conta no Github - Plataforma de controle de versões
Postman ou Insomnia - Ferramentas para testar a API
Docker (Opcional) - Para rodar a aplicação localmente
PostgreSQL (Opcional) - Para rodar a aplicação localmente, caso não queira instalar o Docker

Documentação da API

Acessando localmente
Rode a aplicação localmente
Gere um token de acesso
Abra um ferramenta para testar a API (Postman, Insomnia...)
Acesse a url abaixo:
http://localhost:8080/oauth2/token
Na aba Authorization, acrescente as seguintes informações:

Em Auth Type selecione Basic Auth

Preencha os campos Username e Password com os seguintes valores:

Campo	Valor	Descrição
Username	{{client-id}}	Valor do client-id definido no application.properties
Password	{{client-secret}}	Valor do client-secret definido no application.properties
Envie a requisição e obtenha o token

Acesse o endereço:

http://localhost:8080/swagger-ui.html
Adicone o token em Authorize
Acesse as rotas
Funcionalidades
Cadastrar usuário no sistema
Logar usuário no sistema
Gerenciar Pedidos
Gerenciar Produtos
Gerenciar usuários
Gerenciar categorias

Tecnologias Utilizadas
Java
Spring boot
JPA / Hibernate
PostgreSQL
H2

Aprendizados
Neste projeto foi possível aprender sobre Bean Validation, usado para fazer validações dos dados de entrada da API, sobre o Spring Security, usado para permitir a autenticação dos usuários, além de gerenciar a autorização para o uso das rotas da API pelo usuário. E, por fim, foi possível aprender mais sobre a criação e utilização de exceções customizadas.


