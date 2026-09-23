
<h1 align="center">🎬 Catálogo de Filmes</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java%20SE-17%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Java%20Puro-100%25-5382A1?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/POO-Programação%20Orientada%20a%20Objetos-6A5ACD?style=for-the-badge">
</p>

<p align="center">
  Sistema de catálogo de filmes desenvolvido utilizando <strong>Java puro</strong>, sem frameworks ou bibliotecas externas.
</p>

---

## 📌 Sobre o projeto

O **Catálogo de Filmes** é uma aplicação desenvolvida em **Java puro (Java SE)** para gerenciamento de filmes, usuários e avaliações.

O projeto foi desenvolvido com foco no aprendizado de **Programação Orientada a Objetos**, organização de código e aplicação de boas práticas de desenvolvimento.

Todos os recursos utilizados pertencem à própria plataforma Java, sem utilização de frameworks como Spring, Hibernate ou outras tecnologias externas.

---

## 🎯 Objetivos

* Praticar Java puro
* Aplicar conceitos de Programação Orientada a Objetos
* Trabalhar com classes e objetos
* Criar relacionamentos entre entidades
* Utilizar Collections
* Trabalhar com interfaces
* Aplicar encapsulamento
* Organizar o projeto em camadas
* Praticar Git e GitHub

---

## ⚙️ Funcionalidades

### 🎬 Filmes

* Cadastrar filme
* Listar filmes
* Buscar filme por título
* Buscar filme por gênero
* Atualizar filme
* Remover filme

### 👤 Usuários

* Cadastrar usuário
* Listar usuários
* Associar avaliações aos usuários

### ⭐ Avaliações

* Avaliar filmes
* Consultar avaliações
* Calcular média das avaliações

---

## 🏗️ Estrutura do sistema

O projeto utiliza uma organização baseada em responsabilidades:

```text
Controller
    ↓
Service
    ↓
Repository
    ↓
Model
```

### Model

Representa as entidades do sistema:

```text
Filme
Usuario
Avaliacao
```

### Repository

Responsável pelo armazenamento dos dados durante a execução da aplicação.

```text
FilmeRepository
UsuarioRepository
AvaliacaoRepository
```

### Service

Responsável pelas regras de negócio.

```text
FilmeService
UsuarioService
AvaliacaoService
```

### Controller

Responsável pela interação entre o usuário e o sistema.

---

## 📂 Estrutura do projeto

```text
catalogo-filmes/
│
├── src
│   │
│   ├── model/
│   │   ├── Filme.java
│   │   ├── Usuario.java
│   │   └── Avaliacao.java
│   │
│   ├── repository/
│   │   ├── FilmeRepository.java
│   │   ├── UsuarioRepository.java
│   │   └── AvaliacaoRepository.java
│   │
│   ├── service/
│   │   ├── FilmeService.java
│   │   ├── UsuarioService.java
│   │   └── AvaliacaoService.java
│   │
│   ├── controller/
│   │   └── FilmeController.java
│   │
│   └── Main.java
│
├── .gitignore
└── README.md
```

---

## ☕ Tecnologias utilizadas

| Tecnologia       | Utilização                       |
| ---------------- | -------------------------------- |
| Java SE          | Linguagem principal              |
| Git              | Controle de versão               |
| GitHub           | Versionamento e compartilhamento |

### 🚫 Não utiliza

* ❌ Spring
* ❌ Spring Boot
* ❌ Hibernate
* ❌ JPA
* ❌ Maven
* ❌ Gradle
* ❌ Banco de dados
* ❌ Frameworks externos

**O projeto é desenvolvido exclusivamente com Java puro.**

---

## 🧠 Conceitos de Java aplicados

* Classes e objetos
* Encapsulamento
* Construtores
* Atributos e métodos
* Getters e Setters
* Herança
* Polimorfismo
* Interfaces
* Service, repository e controller
* `ArrayList`
* `List`
* `Swing`
* `Optional`
* `Exception`
* Métodos estáticos
* Modificadores de acesso
* Organização em pacotes

---

## 🖥️ Funcionamento

A aplicação funciona através do **terminal/console**.

Ao iniciar o sistema, o usuário encontra um menu:

```text
========================================
        🎬 CATÁLOGO DE FILMES
========================================

1 - Cadastrar filme
2 - Listar filmes
3 - Buscar filme
4 - Atualizar filme
5 - Remover filme
6 - Avaliar filme
7 - Listar avaliações
0 - Sair

Escolha uma opção:
```
---

## 🔮 Próximas melhorias

O projeto pode evoluir futuramente para:

* [ ] Persistência de dados
* [ ] Banco de dados MySQL
* [ ] Interface gráfica
* [ ] API REST
* [ ] Sistema de login
* [ ] Sistema de favoritos
* [ ] Testes unitários
* [ ] Integração com API externa de filmes

---

## 📚 Objetivo acadêmico

Este projeto foi desenvolvido com finalidade **acadêmica e educacional**, tendo como principal objetivo colocar em prática os conhecimentos de **Java e Programação Orientada a Objetos**.

A proposta é começar utilizando Java puro e evoluir gradualmente o sistema conforme novos conhecimentos são adquiridos.

---

## 👩‍💻 Autora

**Thamires Vitória Muniz da Silva**

🎓 Estudante de Análise e Desenvolvimento de Sistemas

💻 Desenvolvimento de Software | Java | Desenvolvimento Web

---

<p align="center">
  ☕ Desenvolvido em Java puro
</p>

