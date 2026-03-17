# GoodWe App — Plataforma de Monitoramento Energético e Automação

Aplicação completa para monitoramento de plantas energéticas com integração à GoodWe/SEMS, incluindo dashboard moderno, backend robusto, assistente inteligente e automações residenciais.

## 🚀 Visão Geral

A aplicação permite monitorar, analisar e automatizar o consumo de energia em tempo real, integrando dispositivos inteligentes e fornecendo insights para otimização energética.

O sistema é composto por:

- **Backend (Node.js + Express)** → Integração com GoodWe, APIs e automações  
- **Frontend (React + Vite + Tailwind)** → Dashboard interativo  
- **Assistente Inteligente** → Execução de comandos e análise de dados  
- **Integrações residenciais** → SmartThings, Tuya e Hue  
- **MQTT** → Automação com Home Assistant  

---

## ⚙️ Principais Funcionalidades

### 🔌 Monitoramento Energético
- Visualização de geração, consumo e fluxo de energia  
- Monitoramento de inversores e dispositivos  
- Alertas e análise de desempenho  

### 🤖 Assistente Inteligente
- Interação em linguagem natural (pt-BR)  
- Execução de comandos em tempo real  
- Consulta de dados energéticos  
- Controle de dispositivos conectados  

### 🏠 Integrações IoT
- SmartThings (controle e automação)  
- Tuya / Smart Life (dispositivos e status)  
- Philips Hue (iluminação inteligente)  

### 📊 AI & Analytics
- Previsão de geração e consumo energético  
- Sugestões de economia baseadas em dados  
- Coleta e análise de histórico  

### 🔊 TTS (Text-to-Speech)
- Geração de voz local (Piper)  
- Fallback via servidor HTTP  

### 📡 MQTT (Opcional)
- Integração com Home Assistant  
- Publicação de métricas energéticas  

---

## 🛠️ Tecnologias Utilizadas

- **Backend:** Node.js, Express  
- **Frontend:** React, Vite, TailwindCSS  
- **Banco de dados:** SQLite / PostgreSQL  
- **APIs externas:** GoodWe (SEMS)  
- **Integrações:** SmartThings, Tuya, Hue  
- **Outros:** MQTT, OpenAI (assistente), TTS (Piper)  

---

## 🧩 Arquitetura

O sistema foi desenvolvido seguindo separação de responsabilidades:

- Camada de integração (APIs externas)  
- Camada de lógica de negócio  
- Camada de dados  
- Interface de usuário (frontend)  

---

## 👨‍💻 Minha Contribuição

- Desenvolvimento de funcionalidades backend para monitoramento e automação energética  
- Implementação da integração com a API GoodWe (SEMS)  
- Criação de endpoints REST para comunicação com o frontend  
- Modelagem de dados para dispositivos e consumo energético  
- Implementação de regras de negócio para automação inteligente  
- Participação na arquitetura e organização do sistema  

---

## 🧩 Desafios e Aprendizados

- Integração com múltiplas APIs externas  
- Tratamento e normalização de dados em tempo real  
- Desenvolvimento em equipe com divisão de responsabilidades  
- Aplicação prática de conceitos de backend em um cenário real  
- Construção de um sistema escalável e integrado com IoT  

---

## ▶️ Como Executar

### Backend

    git clone https://github.com/rafaelalves3070/Projeto-GoodWe---BrighTech
    cd backend
    npm install
    npm run dev

### Frontend

    cd frontend
    npm install
    npm run dev

---

## ⚙️ Variáveis de Ambiente

Configure o arquivo `.env` no backend com:

- Credenciais da GoodWe  
- Configurações de API  
- Integrações (SmartThings, Tuya, etc.)  
- Banco de dados (opcional)  

---

## 🏆 Reconhecimento

Projeto finalista no **FIAP NEXT 2025**, em parceria com a GoodWe.

---

## 👨‍💻 Autor

Rafael Alves da Silva  
https://github.com/rafaelalves3070
