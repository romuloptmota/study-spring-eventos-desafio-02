# Sistema Evento (Modelo de domínio e ORM)
Sistema para gerenciar as informações dos participantes das atividades de um evento acadêmico.
As atividades deste evento podem ser, por exemplo, palestras, cursos, oficinas práticas, etc. Cada atividade que ocorre possui nome, descrição, preço, e pode ser dividida em vários blocos de horários.
Para cada participante, deseja-se cadastrar seu nome e email.

## 🚀 Tecnologias Utilizadas
- Java 21
- Spring Boot
- Maven
- JPA / Hibernate
- H2


## 🎯 Objetivo do Projeto
- Criação de relacionamento entre entidades
- Seeding de base de dados.
- Perfil de test


## 📁 Estrutura do Projeto

```
src/
└── main/
    └── java/
    └── sistemaevento/
        └── entities/
            └── Atividades
            └── Bloco
            └── Categoria
            └── participnte
    └── resources/
        └── application.properties
        └── application-test.properties
        └── import.sql
```


## 🗂️ Diagramas do Projeto

![diagrama-classes.png](src%2Fmain%2Fjava%2Fcom%2Fdevsuperior%2Fsistemaevento%2Fdocs%2Fdiagrama-classes.png)

![diagrama-er.png](src%2Fmain%2Fjava%2Fcom%2Fdevsuperior%2Fsistemaevento%2Fdocs%2Fdiagrama-er.png)


## ⚙️ Como Executar

### 1️⃣ Clonar o repositório

```bash
git clone git@github.com:romuloptmota/study-spring-eventos-challenge-02.git
```

- Abrir na IDE de preferência








