# NestJS Microservices

Este repositório contém o código-fonte de uma aplicação backend construída com a arquitetura de microserviços, utilizando o framework NestJS. Ele inclui:

- API Principal (Backend): A API principal que expõe os endpoints para a aplicação cliente. Ela é responsável por orquestrar a comunicação entre os diferentes microserviços.

- Microserviço de Comunicação: Um microserviço interno responsável por gerenciar a comunicação entre os diversos componentes da aplicação.

- Microserviço de Análise: Um microserviço externo responsável por fornecer métricas e insights sobre o uso da aplicação.

# Tecnologias Utilizadas

NestJS: Framework Node.js usado para construir a API Principal e os microserviços.

# Estrutura do Repositório

-  O repositório está organizado da seguinte forma:

    sample-backend: Contém o código-fonte da API Principal.
    sample-communication: Contém o código-fonte do microserviço de Comunicação.
    sample-analytics: Contém o código-fonte do microserviço de Análise (externo).

Cada pasta contém um projeto NestJS independente, com sua própria configuração e dependências.
Uso

Para executar a aplicação, é necessário configurar e implantar cada microserviço individualmente. O README de cada subdiretório contém instruções detalhadas sobre como fazer isso.