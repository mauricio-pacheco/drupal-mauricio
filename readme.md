# Projeto Drupal-Mauricio

Este projeto utiliza Docker para configurar uma aplicação Drupal com MySQL e Swagger. O objetivo é fornecer um ambiente fácil de usar para desenvolvimento e demonstração de um sistema de gerenciamento de cases.

## Pré-requisitos

Antes de começar, você precisa ter as seguintes ferramentas instaladas em sua máquina:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Estrutura do Projeto

```plaintext
/drupal-mauricio/
│
├── docker-compose.yml      # Configurações do Docker
├── swagger.yaml            # Especificações da API
├── drupal_dump.sql         # Dump do banco de dados Drupal