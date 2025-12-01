
# Predição de Falhas em Máquinas com AI4I 2020

Este projeto utiliza o dataset AI4I 2020 Predictive Maintenance (Kaggle) para treinar modelos capazes de prever falhas em máquinas com base em variáveis de processo e condições de operação. O objetivo é apoiar estratégias de manutenção preditiva, reduzindo paradas inesperadas, otimizando a produção e diminuindo custos.

## Relação com Ciência dos Materiais

Os sinais de falha presentes no dataset refletem fenômenos ligados ao comportamento dos materiais, como desgaste, fadiga, aumento de vibração, deformação por temperatura e perda de resistência mecânica. Assim, prever falhas significa também analisar como os materiais respondem ao uso real.

## O que foi feito no projeto

- ETL do dataset
- EDA para entender padrões e correlações
- Seleção das features mais relevantes
- Treinamento e comparação de três modelos de classificação
- Escolha do melhor modelo
- Salvamento do modelo (`modelo_final.pkl`)
- Pipeline rodado em Google Colab

## Dataset

AI4I 2020 Predictive Maintenance (Kaggle)

Principais variáveis:
- Carga
- Temperatura
- Potência
- Vibração
- Desgaste
- Modos de falha
- Classe binária: falha ou não falha


