# 🤖 QA Assistant – LLM Prompt Testing Lab

Projeto prático de **Prompt Engineering + LLM Evaluation** usando **Promptfoo** e **OpenAI API**.

Este projeto simula um fluxo real de QA para aplicações com IA, automatizando a validação de respostas de LLM usando testes e critérios objetivos.

---

## 📌 Objetivo

Avaliar automaticamente respostas de um LLM verificando se:

- responde em português
- explica de forma simples e didática
- mantém respostas curtas
- fornece exemplos práticos

---

## 🧠 Tecnologias utilizadas

- Node.js
- Promptfoo
- OpenAI API
- CSV test cases
- Git & GitHub

---

## 📁 Estrutura do projeto

promptfooconfig.yaml → configuração dos testes  
prompt.txt → prompt avaliado  
qa_tests.csv → casos de teste  
.env → chave da OpenAI (não versionado)

---

## ▶️ Como executar o projeto

1️⃣ Clonar o repositório
git clone https://github.com/igorrodrigo07/LLM-qa-testing-lab.git
2️⃣ Acessar a pasta do projeto
cd LLM-qa-testing-lab
3️⃣ Abrir no VS Code (opcional)
code .
4️⃣ Instalar o Promptfoo (caso não tenha)
npm install -g promptfoo
5️⃣ Criar o arquivo de variáveis de ambiente

Na raiz do projeto, crie um arquivo chamado:

.env

E adicione sua chave da OpenAI:

OPENAI_API_KEY=sua_chave_aqui

⚠️ Este arquivo não deve ser enviado ao GitHub.

6️⃣ Executar os testes de prompts
promptfoo eval

Resultado esperado:![Resultado Promptfoo](https://raw.githubusercontent.com/igorrodrigo07/LLM-qa-testing-lab/refs/heads/main/print-resultados.png)

✓ 10 passed (100%)
0 failed
0 errors

---

### Exemplo de execução

![Resultado Promptfoo](https://raw.githubusercontent.com/igorrodrigo07/LLM-qa-testing-lab/refs/heads/main/print-resultados.png)

👨‍💻 Autor

Igor Rodrigo
QA Engineer | Explorando testes de IA e automação
