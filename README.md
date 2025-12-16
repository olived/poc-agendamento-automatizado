# POC – Agendamento Automatizado de Consultas

## 📌 Visão Geral
Prova de conceito de um sistema de agendamento automatizado
integrando chatbot, automação de workflows e Google Calendar.

## 🧠 Objetivo
Demonstrar como é possível automatizar o agendamento de consultas
sem intervenção humana, utilizando ferramentas low-code/no-code.

## 🧩 Stack Utilizada
- Typebot (chatbot)
- n8n (orquestração)
- Google Sheets (persistência)
- Google Calendar (agenda)

## 🔁 Fluxo da Solução
1. Usuário interage com o chatbot
2. Informa nome, telefone, motivo e data/hora
3. Dados são enviados via webhook
4. Registro no Google Sheets
5. Evento criado automaticamente no Google Calendar

## 🚀 Status da POC
- [x] Chatbot funcionando
- [x] Webhook integrado
- [x] Criação de evento no Google Calendar
- [ ] Integração com WhatsApp (Fase 2)

## 🔮 Próximas Evoluções
- Verificação de conflitos de agenda
- Confirmação automática por WhatsApp
- Reagendamento e cancelamento
