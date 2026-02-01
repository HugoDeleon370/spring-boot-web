# aula-spring-boot-web

Este projeto é uma demonstração de uma aplicação web básica desenvolvida com **Spring Boot**. O objetivo é criar e expor um endpoint REST simples (`/`) que retorna a mensagem "Olá Mundo!".

O projeto serve como um estudo prático de como configurar um ambiente web, gerenciar dependências com Maven e criar controladores REST utilizando a nova especificação **Jakarta EE**.

---

## 🚀 Tecnologias Utilizadas

As seguintes tecnologias e ferramentas foram utilizadas:

*   **Java:** Versão 25+
*   **Spring Boot:** Versão 4.0.2 (incluindo dependência `Spring Web`)
*   **Maven:** Gerenciador de projetos e dependências
*   **Git & GitHub:** Controle de versão
*   **Eclipse IDE:** Ambiente de desenvolvimento

---

## 🛠️ Como Rodar Localmente

Para rodar este projeto em sua máquina, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd spring-boot-web-aula
    ```

3.  **Execute a aplicação via Maven (necessita Java e Maven instalados):**
    ```bash
    mvn spring-boot:run
    ```

A aplicação será iniciada na porta `8085` (configurada no arquivo `src/main/resources/application.properties`).

---

## 🎯 Endpoint Exemplo

Após iniciar a aplicação, você pode acessar a seguinte URL no seu navegador ou via ferramenta como Postman/Insomnia:

*   **URL:** `http://localhost:8085/`
*   **Método:** `GET`
*   **Resposta esperada:** Uma string simples contendo `Olá Mundo!`

---

## Autor

*   **Hugo Deleon** - [@HugoDeleon370](https://github.com)

