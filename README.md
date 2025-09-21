# Todo List - API

API RESTful para gerenciamento de tarefas, construída com Java e Spring Boot. Este é o serviço de backend para a aplicação Todo List.

![Java 21](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)

## Visão Geral

Este repositório contém o código-fonte do backend da aplicação de Lista de Tarefas. A API é responsável por todas as operações de CRUD (Create, Read, Update, Delete) e foi projetada para ser consumida por um frontend em Angular.

* **Repositório do Frontend (Angular):** `[https://github.com/Matheusxd43/Projeto-API-REST_to_do_list.main]`

## Tecnologias Principais

* **Linguagem:** Java 21
* **Framework:** Spring Boot 3
* **Banco de Dados:** H2 (para desenvolvimento) e PostgreSQL (para produção)
* **Build Tool:** Maven
* **Mapeamento ORM:** Spring Data JPA com Hibernate

## 🚀 Guia de Instalação e Execução

Para rodar este projeto localmente, siga os passos abaixo:

1.  **Clone o projeto:**
    ```shell
    git clone [https://github.com/Matheusxd43/Projeto-API-REST_to_do_list.main.git]
    ```

2.  **Acesse a pasta do projeto:**
    ```shell
    cd Projeto-API-REST_to_do_list.main
    ```

3.  **Execute o projeto usando o Maven Wrapper:**
    ```shell
    ./mvnw spring-boot:run
    ```
    *Se você tiver o Maven instalado globalmente, pode usar `mvn spring-boot:run`.*

4.  **Acesso:** A API estará disponível em `http://localhost:8080`.

## Endpoints da API

- `GET /api/tarefas`
  - Retorna todas as tarefas cadastradas.

- `POST /api/tarefas`
  - Adiciona uma nova tarefa. Requer um corpo (body) com os dados da tarefa.

- `PUT /api/tarefas/{id}`
  - Atualiza a tarefa correspondente ao `id` informado.

- `DELETE /api/tarefas/{id}`
  - Exclui a tarefa correspondente ao `id` informado.

---

<p align="center">
  Desenvolvido por <b>[Matheus de Almeida Vaz Rodrigues]</b>
</p>
