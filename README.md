# openai-cs-agents-demo (FORK PERSONALIZADO)

Este repositório é um **fork pessoal** do projeto [openai/openai-cs-agents-demo](https://github.com/openai/openai-cs-agents-demo), criado com o objetivo de:

- Estudar a estrutura de agentes multi-turn desenvolvida pela OpenAI;
- Explorar ideias de customização voltadas para aplicações reais (ex: setor de telecom);
- Testar integração com RAG, feedback humano e modificações nos agentes;
- Submeter melhorias relevantes de volta ao projeto oficial.

---

## 🔧 Como rodar localmente

Requisitos:
- Node.js 18+
- Python 3.11+

### 1. Clone o repositório

```bash
git clone https://github.com/victornvilella/openai-cs-agents-demo.git
cd openai-cs-agents-demo
```

### 2. Instale o backend Python

```bash
cd python-backend
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 3. Instale o frontend React/Next.js

```bash
cd ../ui
npm install
```

### 4. Rode o projeto (frontend + backend)

```bash
npm run dev
```

A aplicação ficará disponível em `http://localhost:3000`

---

## ✅ PRs submetidos ao projeto oficial

- [#19 - Add logs when guardrails are triggered](https://github.com/openai/openai-cs-agents-demo/pull/19): loga explicitamente quando um guardrail é ativado (segurança + observabilidade).

---

## 🧠 TODO: ideias para evoluir o fork

### 1. `TelcoAgentContext`
Criar um novo contexto de agentes para simular um atendimento em operadora de telecom:
- Chip, plano, CPF, recarga, fatura, sinal, portabilidade...

### 2. Adicionar agente com RAG simples
Simular um agente que busca informações em base documental (ex: FAQ, contratos, planos).

### 3. Incluir etapa de feedback humano ao final da jornada
Permitir ao cliente dar nota ou escrever feedback após ser atendido pelo agente.

### 4. Reescrever prompts com foco em domínio específico
Testar variações de prompt engineering para domínios como: telecom, seguros, educação.

---

## ✍️ Licença
Este projeto segue a licença MIT. Os direitos do projeto original pertencem à OpenAI.

Fork criado e mantido por [Victor Nardi Vilella](https://github.com/victornvilella).
