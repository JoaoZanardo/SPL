# Estacionamento Inteligente - Documentação

Este repositório contém o **código-fonte** e a **documentação completa** para o projeto de Estacionamento Inteligente. O objetivo deste projeto é **facilitar** e melhorar a experiência de estacionamento para os usuários. O projeto é composto por diferentes partes, cada uma desempenhando um papel importante no funcionamento geral do estacionamento.

## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- Node.js: Plataforma de desenvolvimento de aplicações web backend.
- React.js: Framework JavaScript para construção de interfaces de usuário.
- Arduino: Plataforma de prototipagem eletrônica para controle dos sensores e motores.
- Prisma: ORM (Object-Relational Mapping) para interação com o banco de dados.
- MongoDB: Banco de dados NoSQL utilizado para armazenar os dados do estacionamento.
- I/O: Comunicação e interação com dispositivos de entrada/saída.

## Estrutura do Projeto

O projeto está organizado nas seguintes pastas:

### App

A pasta "app" contém a aplicação visual do estacionamento, onde os usuários finais podem interagir e obter uma experiência aprimorada. Esta parte do projeto é responsável por exibir informações sobre as vagas disponíveis, permitir reservas e fornecer recursos adicionais, como pagamentos e feedbacks.

### Search App

A pasta "search-app" contém um aplicativo específico para busca de veículos estacionados. Com base na placa do veículo ou no número da vaga, os usuários podem encontrar facilmente a localização exata do seu veículo no estacionamento.

### Server

A pasta "server" contém o backend da aplicação, responsável por toda a lógica de negócio, comunicação com o banco de dados e integração com os demais componentes do sistema. Nesta parte do projeto, são implementadas as rotas, controladores e serviços para gerenciar o fluxo de dados e as operações relacionadas ao estacionamento.

### Parking Lot
A pasta "parking-lot" contém o código para o Arduino, onde são controlados os sensores e motores utilizados no projeto. Por meio da integração com o Arduino, é possível obter informações em tempo real sobre a ocupação das vagas e controlar os mecanismos de abertura e fechamento das cancelas.

## Funcionalidades

O Estacionamento Inteligente possui as seguintes funcionalidades principais:

- Exibição de vagas disponíveis: Os usuários podem visualizar a quantidade de vagas disponíveis no estacionamento em tempo real.
- Reserva de vagas: Os usuários podem reservar uma vaga com antecedência, garantindo sua disponibilidade.
- Possibilidade de escanear um QR Code que te levará até sua vaga.
- Busca de veículos estacionados: Os usuários podem encontrar a localização exata do seu veículo no estacionamento usando a placa do veículo ou o número da vaga.
- Controle de acesso: O sistema controla o acesso de veículos por meio de cancelas automatizadas.
- Painel administrativo com todas os informações necessárias para análise de dados e controle de fluxo

**Agradecemos seu interesse no projeto e esperamos proporcionar uma experiência de estacionamento mais eficiente e agradável para todos.**
