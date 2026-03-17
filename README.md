# ⚡ BrighTech — Plataforma Inteligente de Monitoramento Energético

🏆 Projeto finalista do FIAP NEXT 2025

Sistema desenvolvido para monitoramento energético inteligente,
integração com dispositivos IoT e análise de consumo em tempo real.

---

## 📌 Visão Geral

O **BrighTech** é uma aplicação fullstack voltada ao acompanhamento
de geração e consumo energético, permitindo análise inteligente
de equipamentos GoodWe e automação residencial.

O objetivo do projeto é auxiliar usuários na tomada de decisões
energéticas através de dados em tempo real.

---

## 🏗️ Arquitetura do Sistema

- Frontend: React
- Backend: Node.js + Express
- Banco de Dados: SQL
- Integração: API GoodWe
- Comunicação: REST APIs

Fluxo da aplicação:

Usuário → Frontend → Backend → Banco de Dados / APIs externas

---

## 🚀 Funcionalidades

- Monitoramento energético em tempo real
- Visualização de geração e consumo
- Controle de dispositivos inteligentes
- Integração com Alexa
- Análise de hábitos energéticos

---

## 👨‍💻 Minha contribuição

- Desenvolvimento de funcionalidades backend para gerenciamento e automação de dispositivos
- Implementação da integração com API externa (GoodWe) para coleta de dados em tempo real
- Modelagem de dados para representar dispositivos e consumo energético
- Criação de endpoints REST para comunicação com o sistema
- Implementação de regras de negócio para automação de rotinas inteligentes

---

## 🛠️ Tecnologias Utilizadas

Node.js • Express • JavaScript • React • SQL • REST APIs • IoT

---

## 🧩 Desafios e aprendizados

- Aprendi a trabalhar com integração de APIs externas e tratamento de dados
- Evoluí na organização de código backend e separação de responsabilidades
- Tive experiência prática com desenvolvimento em equipe e divisão de tarefas

---

## ⚙️ Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/rafaelalves3070/BrighTech.git
cd BrighTech
```

### 2. Instalar dependências

Backend:

```bash
cd backend
npm install
```

Frontend:

```bash
cd frontend
npm install
```

### 3. Configurar variáveis de ambiente

Crie um arquivo `.env`:

```
PORT=3000
DATABASE_URL=your_database_url
GOODWE_API_KEY=your_api_key
```

### 4. Executar aplicação

Backend:

```bash
npm run dev
```

Frontend:

```bash
npm start
```

---

## 📂 Estrutura do Projeto

```
BrighTech
 ├── backend
 ├── frontend
 ├── database
 └── docs
```
