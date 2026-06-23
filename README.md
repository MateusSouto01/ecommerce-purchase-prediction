# E-commerce Purchase Prediction

## Objetivo

Desenvolver modelos de Machine Learning capazes de prever a intenção de compra online de clientes a partir de características demográficas e comportamentais.

## Tecnologias

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Principais Insights

- Clientes com maior renda apresentam maior propensão à compra online.
- Clientes com menor quantidade de crianças em casa tendem a comprar mais.
- O histórico de gastos foi o principal fator associado à intenção de compra.
- Produtos como vinhos e carnes apresentaram forte relação com compras futuras.

## Modelos Avaliados

| Modelo | Accuracy | F1-Score |
|----------|----------|----------|
| Logistic Regression | 0.85 | 0.85 |
| Random Forest | 0.91 | 0.91 |

## Melhor Modelo

Random Forest

Accuracy: 91%

## Variáveis Mais Importantes

- TotalSpent
- MntWines
- MntMeatProducts
- NumStorePurchases
- Income