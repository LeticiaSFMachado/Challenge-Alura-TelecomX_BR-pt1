# 🚀 Challenge-Alura-TelecomX_BR-pt1

## 📊 Churn Analysis - TelecomX BR

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-orange)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

Projeto desenvolvido durante a trilha de Data Science do programa Oracle Next Education (ONE) em parceria com a Alura.

---

# 📋 Sobre o Projeto

Este projeto tem como objetivo analisar a evasão de clientes (Churn) da empresa TelecomX_BR. O foco da análise é identificar padrões comportamentais e financeiros que levam os clientes a cancelarem seus serviços, fornecendo insights para estratégias de retenção.

---

# 🛠️ Tecnologias Utilizadas

- 🐍 **Python** (Linguagem principal)  
- 📊 **Pandas**: Manipulação e tratamento de dados  
- 📈 **Seaborn & Matplotlib**: Visualização de dados e criação de gráficos estatísticos  
- ☁️ **Google Colab**: Ambiente de desenvolvimento  

---

# 🔄 Etapas do Projeto (Pipeline ETL & EDA)

## 1️⃣ Extração e Transformação

- Importação de dados em formato `.json` via API  
- Normalização de dados aninhados para uma estrutura de tabela plana  
- Limpeza de Dados: Conversão da coluna `Charges.Total` para formato numérico e tratamento de valores ausentes (NaN) em registros onde o tempo de contrato era zero  
- Engenharia de Variáveis: Criação da métrica `Contas_Diarias` para analisar o impacto do custo diário no cancelamento  

---

## 2️⃣ Análise Exploratória (EDA)

Foram realizadas análises para cruzar o status de Churn com variáveis demográficas, serviços assinados e métricas financeiras.

- Análise Categórica: Identificação de taxas de churn por tipo de contrato e método de pagamento  
- Análise de Densidade (KDE Plot): Visualização da distribuição de tempo de casa (tenure) e faturamento mensal  

---

# 💡 Principais Insights

- 🔎 **Risco Inicial:** Clientes com baixo tenure (tempo de casa) possuem uma densidade de cancelamento muito maior, indicando que os primeiros meses de contrato são críticos  
- 💰 **Sensibilidade a Preço:** Há uma correlação visual entre mensalidades mais elevadas e o aumento da taxa de evasão  
- 📄 **Estabilidade Contratual:** Clientes com contratos mensais ("Month-to-month") evadem com muito mais frequência do que clientes com contratos anuais  

---

# 📈 Conclusões e Recomendações

Com base nos dados, recomenda-se que a TelecomX_BR foque em:

- 🎯 Campanhas de engajamento para clientes nos primeiros 90 dias  
- 📅 Incentivos para migração de planos mensais para contratos de longo prazo  
- 📊 Monitoramento proativo de clientes com alto valor de fatura diária  

---

## ⭐ Projeto desenvolvido para fins educacionais
