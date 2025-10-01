Detecção de Fraudes em Transferências Bancárias

📋 Sobre o Projeto
Este projeto implementa um sistema de detecção de fraudes em transferências bancárias utilizando técnicas avançadas de Machine Learning. O modelo é capaz de identificar transações fraudulentas com alta precisão, ajudando instituições financeiras a prevenir perdas e proteger seus clientes.

🎯 Problema de Negócio
O dataset contém mais de 200,000 transações de transferências entre contas de uma mesma instituição financeira, sendo apenas 490 transações fraudulentas (0.245% do total). O desafio principal é lidar com o extremo desbalanceamento das classes enquanto mantém alta capacidade de detecção de fraudes.

Objetivos:

Desenvolver um modelo preditivo para identificar transações fraudulentas

Lidar com o desbalanceamento crítico das classes (0.245% de fraudes)

Otimizar o trade-off entre detectar fraudes e minimizar falsos positivos

Implementar uma solução robusta e escalável para produção

🛠️ Tecnologias Utilizadas
Python 3.x

Pandas & NumPy - Manipulação de dados

Scikit-learn - Machine Learning

XGBoost, LightGBM, Random Forest - Algoritmos

Imbalanced-learn - Tratamento de classes desbalanceadas

Matplotlib & Seaborn - Visualização de dados

Kaggle Hub - Acesso ao dataset

📊 Metodologia
1. Análise Exploratória
Análise do desbalanceamento das classes

Identificação de correlações entre features

Detecção de outliers e padrões comportamentais

Análise de distribuições multivariadas

2. Pré-processamento
Balanceamento com SMOTE - Synthetic Minority Over-sampling Technique

Divisão estratificada dos dados (70% treino, 30% teste)

Validação cruzada para avaliação robusta dos modelos

3. Modelagem
Foram testados e comparados múltiplos algoritmos:

XGBoost

LightGBM

Random Forest

Regressão Logística

4. Otimização
Seleção de features baseada em importância

Otimização de threshold para maximizar F1-Score

Análise de custo-benefício considerando impacto financeiro

📈 Resultados
Performance do Melhor Modelo
Algoritmo: XGBoost

AUC: 0.99+

F1-Score: 0.95+

Threshold Otimizado: 0.917

Métricas de Negócio
Recall: >90% (detecção de fraudes reais)

Precisão: >85% (minimização de falsos positivos)

Economia Estimada: Redução significativa em perdas por fraudes
