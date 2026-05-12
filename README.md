🤖 LLM QA Testing Lab

Projeto prático de avaliação de prompts com Promptfoo + OpenAI, simulando testes automatizados para aplicações com IA.

Este projeto demonstra como aplicar práticas de Quality Assurance em sistemas baseados em LLM.

🚀 Objetivo

Criar uma suíte de testes automatizados para validar a qualidade de respostas de um assistente de QA.

O projeto avalia se o modelo:

Responde em português
Mantém respostas curtas (≤ 5 frases)
Explica de forma simples
Dá exemplos práticos quando possível
🧪 Ferramentas utilizadas
Node.js
Promptfoo
OpenAI API
CSV para casos de teste
Git & GitHub
📂 Estrutura do projeto
.
├── prompt.txt
├── promptfooconfig.yaml
├── qa_tests.csv
├── .env (não versionado)
▶️ Como rodar o projeto
1️⃣ Clonar repositório
git clone https://github.com/SEU-USUARIO/LLM-qa-testing-lab.git
cd LLM-qa-testing-lab
2️⃣ Instalar Promptfoo
npm install -g promptfoo
3️⃣ Criar arquivo .env
OPENAI_API_KEY=sua_chave_aqui
4️⃣ Rodar avaliação
promptfoo eval
📊 Exemplo de resultado
✓ 10 passed (100%)
💡 O que este projeto demonstra
Testes automatizados para IA
Avaliação de qualidade de prompts
Engenharia de Prompt aplicada a QA
Uso de métricas e validações automatizadas
👨‍💻 Autor

Igor Rodrigo