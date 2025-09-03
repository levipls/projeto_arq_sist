# Sistema de Barbearia - Projeto Acadêmico (Java + SOLID)

## 📌 Descrição
Este projeto tem como objetivo desenvolver um **sistema simples de gerenciamento para uma barbearia**, implementado em **Java** e estruturado de acordo com os princípios **SOLID**.  
A modelagem inicial foi realizada através de um **diagrama UML de classes**, disponível neste repositório.

## 🎯 Objetivos do Projeto
- Aplicar os **princípios SOLID** em um projeto de software orientado a objetos.  
- Modelar as principais entidades de um sistema de barbearia.  
- Separar as responsabilidades em **camadas (Model, Repository, Service, Controller)**.  
- Demonstrar boas práticas de **arquitetura de software** em projetos acadêmicos.  

## 🏛️ Arquitetura do Sistema
O sistema segue uma arquitetura em **camadas**:

- **Model (Entidades)** → Representam os objetos do domínio (Cliente, Barbeiro, Serviço, Agendamento, etc.).  
- **Repository** → Responsável pelo armazenamento e recuperação dos dados.  
- **Service** → Camada de regras de negócio (ex.: validação de horários, cálculo de valores).  
- **Controller** → Camada de entrada que orquestra a comunicação entre usuário e sistema.  

📂 Estrutura esperada:
src/
├── controller/
├── model/
├── repository/
├── service/
└── Main.java
<img width="941" height="798" alt="diagrama_sistema_barbearia drawio (1)" src="https://github.com/user-attachments/assets/c38476df-e1c4-453c-8cf1-d3dce4a6301e" />


