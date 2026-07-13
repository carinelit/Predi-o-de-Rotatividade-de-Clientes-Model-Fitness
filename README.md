# Predição de Rotatividade de Clientes — Model Fitness

## Sobre o projeto
Projeto de análise preditiva para a rede de academias Model Fitness, com o objetivo de reduzir a rotatividade (churn) de clientes. O trabalho inclui análise exploratória de dados, construção de modelos de classificação binária para prever a probabilidade de churn no mês seguinte, e segmentação de clientes via clustering para identificar perfis de risco e propor estratégias de retenção.

## Objetivos
- Prever a probabilidade de rotatividade de cada cliente para o próximo mês.
- Criar perfis (clusters) de clientes típicos e descrever suas características.
- Identificar os fatores que mais impactam a rotatividade.
- Propor recomendações de retenção baseadas nos dados.

## Metodologia
- Análise exploratória de dados (EDA)
- Modelos de classificação: Regressão Logística e Random Forest
- Métricas de avaliação: acurácia, precisão e recall
- Clustering hierárquico (dendrograma) e K-Means
- Conclusões e recomendações de negócio

## Tecnologias
Python, pandas, scikit-learn, scipy, matplotlib/seaborn

## Dataset
`gym_churn_us.csv` — dados demográficos, de contrato e de comportamento de uso dos clientes da academia.
