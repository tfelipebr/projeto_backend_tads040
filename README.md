# Autenticação Spring Boot

Este repositório reúne o projeto **backend-login**: API REST de autenticação em Spring Boot (Java 17 + MySQL).  

## 📂 Estrutura de diretórios

```bash
.
├── src/
├── mvnw
├── pom.xml
└── README.md       # Documentação específica do backend
````

---

## 🚀 Pré-requisitos globais

* **Java 17**
* **Maven** (ou use o wrapper `./mvnw`)
* **MySQL 8+**

---

## 🔧 Como rodar

### 1. Backend (Spring Boot)

```bash
# entre na pasta do backend
cd backend-login

# crie o banco e a tabela (ou ajuste o nome no application.properties)
# exemplo:
# CREATE DATABASE backend_login;
# USE backend_login;
# ... veja o script em backend-login/README.md

# configure as credenciais em src/main/resources/application.properties

# inicie a aplicação
# Linux/macOS
./mvnw spring-boot:run

# Windows
mvnw.cmd spring-boot:run
```

> A API ficará disponível em `http://localhost:8080/api/auth/login`.

---

## 🛠️ Tecnologias

| Camada   | Tecnologias                                                               |
| -------- | ------------------------------------------------------------------------- |
| Backend  | Java 17 · Spring Boot 3.5.0 · Spring Data JPA · MySQL Connector/J · Maven |

---


## 🤝 Contribuição

1. Faça um fork e crie sua branch (`git checkout -b minha-feature`)
2. Commit suas alterações (`git commit -m 'Adiciona nova feature'`)
3. Push para a branch (`git push origin minha-feature`)
4. Abra um Pull Request


