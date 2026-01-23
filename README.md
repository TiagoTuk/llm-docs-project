# Whats Up Docs? – LLM Project

O objetivo desse projeto é utilizar modelos de linguagem (LLMs) para analisar e extrair informações relevantes de documentos textuais.

O foco principal do projeto é aplicar técnicas de Processamento de Linguagem Natural (NLP) e Large Language Models, seguindo boas práticas de organização, versionamento e reprodutibilidade.

---

## 🎯 Objetivo do Projeto

- Desenvolver um pipeline de análise de documentos utilizando LLMs
- Realizar pré-processamento e padronização dos textos
- Testar estratégias de inferência com modelos de linguagem
- Gerar previsões de acordo com o problema proposto

---

## 🗂 Estrutura do Projeto

llm-docs-project/
│
├─ data/
│ ├─ raw/ # Dados brutos (originais)
│ └─ processed/ # Dados tratados e prontos para modelagem
│
├─ notebooks/ # Explorações e experimentos
│
├─ src/
│ ├─ preprocessing.py # Limpeza e preparação dos dados
│ ├─ inference.py # Inferência com modelos LLM
│ └─ utils.py # Funções auxiliares
│
├─ check_env.py
├─ requirements.txt
└─ README.md

---

## 🛠 Tecnologias Utilizadas

- Python 3.10
- Miniconda
- VS Code
- Git / GitHub
- Bibliotecas de NLP e LLM (em definição)

---

## 🚀 Como Executar o Projeto

1. Criar o ambiente conda:
conda create -n llm-docs python=3.10
conda activate llm-docs

2. Instalar as dependências:
pip install -r requirements.txt

3. Executar scripts ou notebooks conforme a etapa do projeto.

---

📌 Observações

- Os dados não são versionados no Git (data/ está no .gitignore)
- Este projeto está em fase inicial e será evoluído gradualmente

---

👤 Autor

Tiago Barros
Projeto desenvolvido para estudo e portfólio em Data Science e LLMs.