# S-RAF (Sistema de Reposição e Ausência de Facilitadores) 🎓

O **S-RAF** é uma aplicação *full-stack* desenvolvida como **Projeto Integrador do SENAI**. Seu principal objetivo é modernizar e automatizar a rotina de gestão acadêmica, gerenciando de forma eficiente o fluxo de solicitação de ausências e a substituição de docentes.

## 🚀 Funcionalidades

- **Gestão de Usuários:** Cadastro de docentes e coordenadores com diferentes níveis de acesso.
- **Autenticação Segura:** Login protegido via tokens JWT.
- **Solicitação de Ausência:** Docentes podem registrar pedidos de ausência informando datas e motivos.
- **Painel da Coordenação:** Visualização, aprovação e alocação de substitutos para as aulas pendentes.
- **Controle Acadêmico:** Gestão de cargas horárias e grades de aulas.

## 🛠️ Tecnologias Utilizadas

O projeto foi dividido em duas partes principais, utilizando as seguintes tecnologias:

### Backend
- **Java 17**
- **Spring Boot 3.2.5** (Web, Data JPA, Security)
- **Maven** (Gerenciamento de dependências e *wrapper*)
- **MySQL** (Banco de Dados Relacional)
- **JWT (JSON Web Token)** (Autenticação e Autorização)

### Frontend
- **React 19** 
- **TypeScript**
- **React Router Dom** (Navegação de rotas)
- **Axios** (Integração e consumo da API)
- **Lucide React** (Biblioteca de ícones)

## ⚙️ Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado em sua máquina:
- [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Node.js](https://nodejs.org/en/) (versão 18+ recomendada)
- [MySQL](https://www.mysql.com/downloads/) (rodando localmente na porta padrão 3306)
