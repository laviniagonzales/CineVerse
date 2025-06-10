# 🎬 Cineverse API

API REST construída em Java com Spring Boot que consome filmes populares da API TMDB e os armazena em um banco de dados local.

---

## 🚀 Funcionalidades

✅ Buscar filmes populares da TMDB  
✅ Salvar filmes no banco de dados local  
✅ Expor endpoints REST com documentação via Swagger  

---

## 🔧 Tecnologias Utilizadas

- Java 17 - Linguagem
  
- Spring Boot - FRamework: Rodar ./mvnw spring-boot:run para a API funcionar
  
- Spring Web - Módulo de spring pra criar os Endpoints:  Usamos @RestController, @RequestMapping, e ResponseEntity
  
- Spring Data JPA - Lidou com o banco de dados: Usamos métodos como save(), findAll() e existsById() diretamente
  
- Spring Validation - Validar entradas automáticas nos endpoints:  Usamos @NotNull, @Size, @Valid nas classes modelo e DTO
  
- Lombok - Biblioteca que gerou códigos repetitivos automaticamente (getters, setters, construtores):  Usamos @Data, @AllArgsConstructor, @NoArgsConstructor
  
- H2 Database (em memória):  Banco de dadaos para os testes e desenvolvimento

- Springdoc OpenAPI (Swagger):  Documentação interativa com a API
  
- Maven:  Gerenciador de dependências e build do projeto

- MySQL: Banco de dados usado para armazenar os filmes vindos da API do TMDB de forma definitiva e estruturada

---

## ▶️ Como Rodar o Projeto

### 📌 Pré-requisitos

- Java 17 ou superior
- Maven 3.8+

### 📦 Clonar e rodar

```bash
git clone https://github.com/seu-usuario/cineverse-api.git
cd cineverse-api
./mvnw spring-boot:run

