# 📉 Análise de Churn em Python

Este projeto apresenta uma análise exploratória de churn com o objetivo de identificar padrões de cancelamento, entender o comportamento dos clientes e destacar fatores que influenciam a retenção.  
A análise foi conduzida utilizando Python e bibliotecas amplamente utilizadas em ciência de dados.

---

## 🔗 Acesso rápido

- 📘 **Notebook completo:** [notebooks/churn_analysis.ipynb](notebooks/churn_analysis.ipynb)  
- 📊 **Dataset utilizado:** [data/churn_clientes.csv](data/churn_clientes.csv)

---

## 🧠 Objetivo do projeto

O churn (cancelamento) é um dos principais desafios de empresas que operam com receita recorrente.  
Este projeto busca responder:

- Quais fatores mais influenciam o churn  
- Existem padrões de comportamento entre clientes que cancelam  
- Quais segmentos apresentam maior risco  
- Como variáveis como atrasos, suporte e ticket médio se relacionam com o cancelamento  

---

## 🔍 Principais insights

- Clientes com maior número de **atrasos de pagamento** apresentam maior probabilidade de churn.  
- Segmentos com **menor ticket médio** concentram proporcionalmente mais cancelamentos.  
- **Queda de uso** do produto é um forte indicador de risco.  
- Clientes que acionam muito o **suporte** tendem a cancelar mais.  
- A matriz de correlação reforça que **engajamento e comportamento financeiro** são fatores críticos.

---

## 📊 Visualizações

As principais visualizações geradas no notebook incluem:

| Churn por segmento | Churn por canal |
|--------------------|-----------------|
| ![](images/churn_por_segmento.png) | ![](images/churn_por_canal.png) |

| Tempo de casa | Correlação |
|----------------|------------|
| ![](images/churn_tempo_de_casa.png) | ![](images/matriz_correlacao.png) |

> As imagens acima são placeholders. Quando você gerar os gráficos no Jupyter, basta substituir os arquivos na pasta `images/`.

---

## 🛠️ Tecnologias utilizadas

- **Python**
  - pandas  
  - numpy  
  - seaborn  
  - matplotlib  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## ▶️ Como reproduzir o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/llfaraco/churn-analysis-python.git
2. Instale as dependências: pip install -r requirements.txt
3. Abra o notebook:jupyter notebook notebooks/churn_analysis.ipynb

🚀 Próximos passos
Criar um modelo preditivo de churn (Logistic Regression, Random Forest).

Implementar um dashboard interativo (Power BI ou Streamlit).

Criar um score de risco para priorização de clientes.

Automatizar o pipeline de ingestão e limpeza de dados.

📬 Contato
Se quiser trocar uma ideia sobre o projeto ou oportunidades:

Lucas Faraco 📧 llfaraco@gmail.com 🔗 https://www.linkedin.com/in/llfaraco
