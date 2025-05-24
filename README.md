# 🌊 AQMonitor – Monitorar o hoje para sustentar o amanhã

Sistema inteligente para monitoramento da **qualidade da água** em tempo real.

---

## 📌 Visão Geral

O **AQMonitor** é um sistema inteligente e automatizado de monitoramento hídrico direcionado para propriedades rurais, com foco inicial em animais. Ele monitora a **qualidade da água** em tempo real, promovendo o bem-estar animal e otimizando a gestão hídrica nas atividades pecuárias e agrícolas.

---

## 🔧 Tecnologias Utilizadas (Stack)

### ⚙️ Sistema Embarcado
- ESP32 com Wi-Fi integrado
- Linguagem: C++ (Arduino Framework)
- Comunicação: HTTP para envio de dados ao backend

**Sensores Utilizados:**
- pH
- Turbidez
- Temperatura
- TDS (Sólidos Totais Dissolvidos)

---

### 🌐 Web Platform

#### Frontend (Interface Web/App)
- [React.js](https://reactjs.org/) (Vite)
- [Tailwind CSS](https://tailwindcss.com/) para estilização
- [Recharts](https://recharts.org/en-US) para gráficos interativos
- [Axios](https://axios-http.com/) para requisições HTTP
- Suporte a PWA para uso como app em dispositivos móveis

#### Backend (API)
- [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/) (opcional)
- [MongoDB](https://www.mongodb.com/) com [Mongoose](https://mongoosejs.com/) para modelagem
- Autenticação com JWT
- API RESTful com endpoints para receber e consultar dados dos sensores

#### Hospedagem / Deploy
- Frontend: [Vercel](https://vercel.com)
- Backend: [Render](https://render.com)
- Banco de dados: [MongoDB Atlas](https://www.mongodb.com/atlas)

---

## 🧪 Funcionalidades

### Dispositivo IoT
- Coleta automática de dados hídricos
- Envio periódico dos dados ao servidor (HTTP)
- Alertas locais em caso de anomalias (LED/buzzer)

### Plataforma Web
- Alertas automáticos por parâmetro (ex: pH alto, turbidez elevada)
- Recomendações práticas para correção de qualidade
- Painel de controle para produtores e técnicos
- Autenticação e segurança

---

## 🧬 Contribuição da Zootecnia

- Definição dos limites ideais de qualidade da água para bovinos
- Conteúdo técnico sobre impactos da água imprópria
- Banco de soluções e recomendações práticas por parâmetro
- Avaliação dos impactos do sistema na saúde animal e produtividade
- Educação e apoio aos produtores

---

## 🚀 Como Executar Localmente

### Backend
```bash
cd backend
npm install
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

---

## 🛡️ Segurança

- Autenticação via JWT
- Restrições por perfil (produtor, técnico, admin)
- Proteção de rotas sensíveis na API

---

## 📘 Licença

Este projeto é de uso aberto para fins educacionais e de pesquisa. Para uso comercial, entre em contato com a equipe CETHAP.

---

## 📞 Contato

Para dúvidas, sugestões ou parcerias:

- E-mail: cethap.cont@gmail.com 
- Instagram: [@cethap.tech](https://instagram.com/_cethap)
- Site oficial: https://cethap.onrender.com/

---
