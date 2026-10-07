# InfoOnibus - API Backend (SISMOB / SEMOB-DF)

API de serviços e monitoramento do transporte público do Distrito Federal, desenvolvida em NestJS para a Secretaria de Mobilidade do Distrito Federal (SEMOB-DF).

---

## Sobre o Projeto

Este repositório contém o backend do sistema InfoOnibus. A API é responsável por gerir a comunicação com a base de dados relacional e espacial, processar consultas de linhas, horários oficiais, itinerários descritivos e fornecer os dados de geolocalização das frotas em tempo real.

---

## Tecnologias Utilizadas

- Node.js
- NestJS (Framework server-side)
- TypeScript
- TypeORM (Mapeamento Objeto-Relacional)
- PostgreSQL / PostGIS
- Docker & Docker Compose (Ambiente containerizado)

---

## Estrutura do Projeto

- **Módulos e Controladores**: Organização modular para separação de responsabilidades (linhas, horários, itinerários e dados espaciais).
- **Entidades TypeORM**: Mapeamento de tabelas direcionado ao esquema de dados de mobilidade da SEMOB.
- **Integração de Dados Espaciais**: Tratamento de geometrias geoespaciais e consultas por sentido (Ida, Volta ou Circulares).

---

## Instalação e Execução

1. Instale as dependências do projeto:
   ```bash
   npm install

   Licença
Desenvolvido para fins institucionais e operacionais no âmbito da Secretaria de Transporte e Mobilidade do Distrito Federal (SEMOB-DF).
