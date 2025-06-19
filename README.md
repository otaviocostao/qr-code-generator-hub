# QR Code Generator

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Licença](https://img.shields.io/badge/licença-MIT-blue)

Um gerador de QR Code simples e funcional construído com Java/Spring no backend e React no frontend, tudo organizado em um monorepo.

![Demonstração do Projeto](./demo.gif)

## Sobre o Projeto

Este projeto foi criado com o objetivo de aprender e aplicar na prática o fluxo completo de uma aplicação web moderna. A ideia é simples: transformar qualquer link em um QR Code. No entanto, a implementação envolve a comunicação entre um frontend reativo, um backend robusto e um serviço de armazenamento em nuvem (AWS S3).

## Funcionalidades Principais

- ✔️ **Geração de QR Code:** Transforma qualquer URL válida em uma imagem de QR Code.
- ✔️ **Interface Reativa:** Construída com React para uma experiência de usuário fluida.
- ✔️ **Backend Robusto:** API RESTful com Java e Spring Boot, com tratamento de erros.
- ✔️ **Armazenamento na Nuvem:** Upload e armazenamento automático da imagem na AWS S3.
- ✔️ **Estrutura Monorepo:** Código do frontend e backend organizados em um único repositório.

## Tecnologias Utilizadas

A aplicação é dividida em duas partes principais:

### Backend
*   **Java 21**
*   **Spring Boot**
*   **Zxing (Zebra Crossing)** para geração do QR Code
*   **AWS SDK for Java** para integração com o S3
*   **Maven** como gerenciador de dependências

### Frontend
*   **React.js**
*   **JavaScript**
*   **TailwindCSS** para estilização
*   **Axios** para requisições HTTP

## ⚙️ Como Rodar o Projeto

Siga os passos abaixo para executar a aplicação localmente.

### Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
*   [Java 21 ou superior](https://www.oracle.com/java/technologies/downloads/)
*   [Maven 3 ou superior](https://maven.apache.org/download.cgi)
*   [Node.js v18 ou superior](https://nodejs.org/en/)
*   Uma conta na **AWS** com credenciais de acesso (Access Key ID e Secret Access Key) e um bucket S3 criado.

### 1. Clonando o Repositório
```bash
git clone https://github.com/otaviocostao/qrcode-generator-fullstack.git
cd qrcode-generator-fullstack
