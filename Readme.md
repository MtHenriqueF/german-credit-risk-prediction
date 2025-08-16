# Previsão de Risco de Crédito Alemão 🏦📊  

Um projeto de aprendizado de máquina para prever se um solicitante de empréstimo representa um risco de crédito **"Bom"** ou **"Ruim"**, com base no **German Credit Dataset**.  

## 📌 Visão Geral  
Este repositório contém:  
- Pré-processamento de dados e análise exploratória (`german_credit_prediction.ipynb`)  
- Modelos de aprendizado de máquina para classificação binária (Árvore de Decisão, Random Forest, XGBoost, etc.)  
- Avaliação dos modelos e métricas de desempenho (F1-score, Precisão, Revocação, ROC-AUC)  

## 📂 Conjunto de Dados  
O **German Credit Dataset** contém 1.000 registros com variáveis (categóricas e numéricas) e uma variável alvo (`Risk` = Bom/Ruim).  

### Atributos:

- Idade (numérico)  
- Sexo (texto: masculino, feminino)  
- Ocupação (numérico:  
  - 0 - não qualificado e não residente  
  - 1 - não qualificado e residente  
  - 2 - qualificado  
  - 3 - altamente qualificado)  
- Habitação (texto: próprio, aluguel ou gratuito)  
- Contas de poupança (texto: pouca, moderada, bastante rica, rica)  
- Conta corrente (numérico, em Marcos Alemães - DM)  
- Valor do crédito (numérico, em DM)  
- Duração (numérico, em meses)  
- Finalidade (texto: carro, móveis/equipamentos, rádio/TV, eletrodomésticos, reformas, educação, negócios, férias/outros)  
