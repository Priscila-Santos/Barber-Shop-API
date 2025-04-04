# Barber Shop API ✂️

Backend do **Barber Shop Scheduler**, desenvolvido com **Java 21**, **Kotlin**, e gerenciado pelo **Gradle**. Esta API RESTful permite que o front-end em Angular se conecte e gerencie dados relacionados a clientes, horários e serviços.

## 📌 Funcionalidades
- **Gerenciamento de Clientes**: Adicione, edite, liste e remova clientes.
- **Gerenciamento de Serviços**: Cadastramento de serviços como corte de cabelo e barba.
- **Agendamentos**: Criação e gerenciamento de horários para cada cliente.
- **Relatórios Financeiros**: Estatísticas básicas baseadas nos serviços oferecidos.
- **Autenticação e Validação**: Implementação de segurança e validação de dados.

## 🚀 Tecnologias Utilizadas
- **Java 21**: Versão mais recente e poderosa para o backend.
- **Kotlin**: Linguagem moderna e concisa, garantindo um código mais legível.
- **Spring Boot**: Framework para criação de APIs RESTful.
- **Gradle**: Automação de build e gerenciamento de dependências.
- **PostgreSQL**: Banco de dados relacional.
- **Docker**: Containerização para facilitar o desenvolvimento e a implantação.

## 🎯 Benefícios do Backend
1. **Modernidade**: Uso de Kotlin e Java 21 para desempenho e legibilidade.
2. **Modularidade**: Código organizado e fácil de escalar.
3. **Confiabilidade**: Banco de dados robusto com PostgreSQL e arquitetura segura.

## 🛠️ Como Rodar o Projeto
### Requisitos:
- **Java 21** instalado.
- **Gradle** configurado.
- **Docker** para rodar a aplicação containerizada.

### Front-End:
- **Angular** 17
- **Bootstrap** para estilização
- **Ngx-Mask** para máscaras de entrada
- **Angular CDK** para componentes avançados

### Outros:
- **Docker** para containerização
- **Docker Compose** para orquestração de serviços
- **Mermaid** para diagramas
- **Yarn** para gerenciamento de dependências

## 🎯 Valores da Aplicação
1. **Eficiência:** Reduz tempo gasto em tarefas manuais de organização.
2. **Facilidade:** Interface intuitiva para interação com clientes e administradores.
3. **Escalabilidade:** Arquitetura modular para integração futura de novos serviços.
4. **Segurança:** Gerenciamento seguro de dados com Docker e Java.

## 🛠️ Como Rodar o Projeto
### Requisitos:
- **Docker** e **Docker Compose** instalados.
- **Node.js** na versão 20.9.0 (ou superior).
- **Angular CLI** configurado.

### Passo a Passo:
1. Clone o repositório do back-end:
   ```bash
   git clone https://github.com/Priscila-Santos/Barber-Shop-API

1. Clone o repositório do front-end:
   ```bash
   git clone https://github.com/Priscila-Santos/Barber-Shop

### 🗺️ Diagrama do Projeto
Aqui está um diagrama Mermaid para descrever os componentes do projeto:
  ```mermaid
  graph TD
    Client[Usuário / Cliente] -->|Acessa| FrontEnd[Angular App]
    FrontEnd -->|Envia requisições| BackEnd[Java Spring API]
    BackEnd -->|Consulta e Atualiza| Database[PostgreSQL]
    BackEnd -->|Retorna dados| FrontEnd
```
### 🔗 Links Úteis

- **Front-End:** [Barber-Shop-UI](https://github.com/Priscila-Santos/Barber-Shop)
- **Documentação Spring Boot:** [SpringBoot](https://spring.io/projects/spring-boot)
- **Docker:** [Docker Docs](https://docs.docker.com/)

