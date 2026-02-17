# 📊 TelecomX - Churn Prediction Project

## 🎯 Objetivo
Desenvolver um modelo de Machine Learning capaz de prever a evasão (Churn) de clientes da TelecomX e identificar os principais fatores que influenciam o cancelamento.

---

## 📁 Dataset
Base de dados contendo informações demográficas, contratuais, serviços contratados e valores de cobrança.

Target:
- Churn (Yes/No)

---

## ⚙️ Etapas do Projeto

### 🔹 1. Data Preparation
- Limpeza de dados
- Conversão de variáveis
- Encoding (One-Hot Encoding)
- Normalização (StandardScaler)
- Split treino/teste com estratificação

### 🔹 2. Modelagem
Modelos utilizados:
- Logistic Regression
- Random Forest

Também foi aplicado:
- SMOTE para balanceamento da classe minoritária

---

## 📊 Resultados

Principais métricas avaliadas:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

O modelo com melhor desempenho geral foi:

👉 Random Forest + SMOTE

---

## 🔍 Principais Fatores que Influenciam o Churn

1. Contrato mensal (Month-to-month)
2. Baixo tempo de permanência (tenure)
3. Alta mensalidade
4. Pagamento via Electronic Check
5. Ausência de TechSupport
6. Ausência de OnlineSecurity

---

## 🚀 Conclusão Estratégica

A evasão está fortemente associada a clientes novos, com contratos mensais e maior valor de cobrança.

Recomendações:

- Incentivar migração para contratos anuais
- Criar programa de retenção nos primeiros meses
- Oferecer pacotes com serviços agregados
- Incentivar pagamento automático

---

## 🧠 Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Seaborn

---

## 📈 Impacto de Negócio

A implementação desse modelo permite:

- Identificação antecipada de clientes com alto risco
- Redução de churn
- Aumento de Lifetime Value (LTV)
- Melhoria da estratégia de retenção


