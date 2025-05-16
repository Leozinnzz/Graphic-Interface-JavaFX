# 🎨 Projeto JavaFX com Scene Builder e Banco de Dados PostgreSQL

## 📄 Descrição

Este projeto é uma aplicação Java que utiliza **JavaFX** para criar uma interface gráfica moderna e intuitiva, desenvolvida visualmente com o auxílio do **Scene Builder**. A aplicação está integrada a um banco de dados **PostgreSQL**, permitindo operações básicas de CRUD para persistência de dados. A conexão com o banco é realizada via **JDBC**, demonstrando a integração entre interface gráfica, lógica de negócios e manipulação de dados em um banco relacional.

---

## 🚀 Tecnologias Utilizadas

- **Java 17**  
- **JavaFX**  
- **Scene Builder** (ferramenta visual para criar interfaces JavaFX)  
- **PostgreSQL**  
- **JDBC** (Java Database Connectivity)  
- **IDE**: IntelliJ IDEA / Eclipse / STS  

## 🧩 Funcionalidades

- Interface gráfica interativa e responsiva  
- Operações CRUD integradas ao banco PostgreSQL  
- Validação básica de dados na interface  
- Comunicação eficiente entre interface e banco via JDBC  

## 🏗️ Estrutura do Projeto

- `view` – Arquivos FXML e controllers para interface JavaFX  
- `model` – Classes que representam as entidades do sistema  
- `dao` – Data Access Objects responsáveis pela comunicação com o banco  
- `main` – Classe principal para inicializar a aplicação

## 📷 Executando na prática

![Captura de tela 2025-05-16 154112](https://github.com/user-attachments/assets/6cdb4b64-26bb-4ead-a481-7bf5e62958a8)


![Captura de tela 2025-05-16 154125](https://github.com/user-attachments/assets/a2706df7-3fdb-4358-8f7f-87a273494c79)


![Captura de tela 2025-05-16 154145](https://github.com/user-attachments/assets/cf5473f4-2c31-424d-8086-34d89fd6e62a)


![Captura de tela 2025-05-16 154314](https://github.com/user-attachments/assets/2b2df980-2de8-49d8-b30d-48b4ccf7eea9)


## 📦 Como Executar

1. Instale e configure o PostgreSQL, criando o banco e as tabelas necessárias.  
2. Ajuste os dados de conexão no arquivo de configuração (ex: `application.properties` ou direto no código DAO).  
3. Clone o repositório:  
   ```bash
   git clone https://github.com/SeuUsuario/nome-do-repo.git
