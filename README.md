# Pass-In - Aplicação de Gestão de Participantes em Eventos Presenciais

## Sobre o Projeto

Pass-In é uma aplicação destinada à gestão de participantes de eventos presenciais. Permite que organizadores cadastrem eventos, abram páginas públicas de inscrição e gerenciem o check-in dos participantes de forma eficiente através de credenciais digitais e escaneamento de QR code.

## Recursos

- **Gerenciamento de Eventos:** Organizadores podem criar e visualizar detalhes do evento.
- **Inscrição de Participantes:** Participantes podem se inscrever nos eventos e visualizar seu crachá de inscrição.
- **Sistema de Check-In:** Realização do check-in no evento através de QR code no crachá.

## Como Começar

### Pré-requisitos

- JDK (Java Development Kit)
- Maven
- IDE de preferência que suporte Java (IntelliJ IDEA, Eclipse, etc.)

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Taimisson/Pass-In.git
   ```
2. Navegue até o diretório do projeto e instale as dependências:
   ```bash
   mvn install
   ```
3. Execute a aplicação:
   ```bash
   mvn spring-boot:run
   ```

## Tecnologias Utilizadas

Este projeto é desenvolvido utilizando Java para o back-end, com Maven para gerenciamento de dependências e Spring Boot para configuração e setup simplificados. A aplicação conta com uma API Rest para comunicação eficiente front-back, integração com o banco de dados HSQL para armazenamento de dados, JPA para persistência de dados, migrações de banco de dados gerenciadas pelo Flyway para controle de versão do banco, e utiliza DTOs (Data Transfer Objects) para uma manipulação eficiente dos dados entre as diferentes camadas da aplicação.

## Contribuição

Contribuições são bem-vindas! Por favor, leia as diretrizes de contribuição para mais informações.

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
