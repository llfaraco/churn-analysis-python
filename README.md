# 📉 Churn Analysis com Python  
### Identificação de risco, padrões de cancelamento e oportunidades de retenção

Este projeto simula um cenário de carteira de clientes com risco de churn, inspirado em experiências práticas com retenção, comportamento de carteira e previsibilidade de receita. O objetivo é analisar o perfil dos clientes, identificar padrões de cancelamento e sugerir ações para reduzir churn, usando Python para análise exploratória e visualização.

---

## 🎯 Objetivos do projeto

- Entender o perfil dos clientes que mais cancelam  
- Identificar variáveis que mais influenciam o churn  
- Criar segmentações de risco (baixo, médio, alto)  
- Sugerir ações de retenção com base em dados  
- Demonstrar um fluxo completo de análise: dados → EDA → insights  

---

## 🧩 Estrutura do projeto

### 1. Dados

O dataset utilizado contém colunas como:

- `customer_id`  
- `idade`  
- `tempo_de_casa`  
- `ticket_medio`  
- `segmento`  
- `canal`  
- `uso_produto`  
- `atendimentos_suporte`  
- `atrasos_pagamento`  
- `churn` (0 = ativo, 1 = cancelado)

Os dados podem ser sintéticos ou adaptados de datasets públicos, com foco em simular um cenário real de análise de churn.

---

### 2. Análise exploratória (EDA)

No notebook `churn_analysis.ipynb` são feitas análises como:

- Distribuição de churn por segmento e canal  
- Relação entre tempo de casa e probabilidade de churn  
- Impacto de atrasos de pagamento no churn  
- Relação entre uso do produto e cancelamento  
- Correlações entre variáveis numéricas e churn  

Principais bibliotecas utilizadas:

- `pandas` para manipulação de dados  
- `numpy` para operações numéricas  
- `matplotlib` e `seaborn` para visualizações  

---

### 3. Segmentação de risco

Com base nos padrões observados na EDA, é criada uma classificação simples de risco de churn, utilizando regras de negócio, por exemplo:

- **Alto risco:** clientes com alto número de atrasos, alto número de atendimentos de suporte e queda de uso  
- **Médio risco:** clientes com alguns sinais de insatisfação ou redução de uso  
- **Baixo risco:** clientes engajados, com bom uso e poucos problemas

Essa segmentação pode ser usada para orientar ações da área de retenção.

---

## 🛠️ Tecnologias utilizadas

- **Python**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`  

- **Jupyter Notebook / VSCode** para desenvolvimento  
- **Git/GitHub** para versionamento e portfólio  

---

## 📂 Estrutura de pastas

```text
📁 data
    └── churn_clientes.csv

📁 notebooks
    └── churn_analysis.ipynb

📁 images
    ├── churn_por_segmento.png
    ├── churn_por_canal.png
    ├── churn_tempo_de_casa.png
    └── matriz_correlacao.png

README.md
