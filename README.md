🧪 LLM QA Testing Lab (Prompt Evaluation com Promptfoo)

Projeto criado para demonstrar prática real de QA aplicado a IA/LLMs, utilizando avaliação automatizada de prompts com a ferramenta Promptfoo.

Aqui simulamos um cenário real de validação de um AI Assistant de QA, criando testes automatizados que verificam se o modelo responde conforme esperado.

🎯 Objetivo do projeto

Este projeto demonstra na prática:

Criação de prompts para LLM
Testes automatizados de respostas de IA
Uso de datasets (CSV) como massa de teste
Avaliação automática com assertions
Organização de projeto real para portfólio QA + IA
🗂️ Estrutura do projeto
LLM-qa-testing-lab
│
├── promptfooconfig.yaml   # Configuração do Promptfoo
├── prompt.txt             # Prompt base do assistente de QA
├── qa_tests.csv           # Massa de testes
├── .env                   # Variáveis de ambiente (não versionado)
└── README.md
🤖 Prompt testado

O projeto valida um assistente de QA que deve:

Responder em português
Explicar de forma simples e didática
Evitar respostas longas
Dar exemplos práticos
🧪 O que está sendo testado?

Cada linha do qa_tests.csv contém:

pergunta → entrada enviada ao modelo
esperado_conter → palavra/frase que deve existir na resposta

O Promptfoo executa automaticamente os testes e valida as respostas.

Exemplo de regra de validação:

assert:
  - type: contains
    value: "{{esperado_conter}}"
🚀 Como executar o projeto

Siga o passo a passo abaixo para rodar a avaliação de prompts localmente.

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

Resultado esperado:

✓ 10 passed (100%)
0 failed
0 errors
📊 Exemplo de execução

O Promptfoo mostra quantos testes passaram/falharam, tempo de execução e consumo de tokens.

Este projeto atingiu:

✓ 10 passed (100%)

👨‍💻 Autor

Igor Rodrigo
QA Engineer | Explorando testes de IA e automação
