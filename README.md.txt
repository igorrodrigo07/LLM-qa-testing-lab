# 🤖 QA Assistant – LLM Prompt Testing Lab

Projeto de avaliação de qualidade de respostas de LLM utilizando Promptfoo + OpenAI.

## 🎯 Objetivo
Criar um pipeline de testes automatizados para validar respostas de um chatbot de QA.

## 🧠 Tecnologias
- Promptfoo
- OpenAI API
- Node.js
- YAML / CSV datasets

## 🧪 O que o projeto testa
O modelo é avaliado automaticamente para verificar se:

- Responde em português
- Explica conceitos de QA corretamente
- Mantém respostas curtas e didáticas
- Fornece exemplos práticos

A avaliação é feita usando **LLM-as-a-judge**.

## ▶️ Como rodar o projeto

### 1. Instalar Promptfoo
```bash
npm install -g promptfoo