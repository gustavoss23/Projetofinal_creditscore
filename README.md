# Projetofinal_creditscore

## Descrição do Projeto  
Este projeto apresenta a construção de um modelo de **credit scoring** para cartão de crédito, utilizando um conjunto de dados com 15 safras e 12 meses de acompanhamento da performance dos clientes. O objetivo principal é prever a probabilidade de inadimplência, auxiliando na tomada de decisão para concessão de crédito de forma mais assertiva e segura.

A modelagem envolve etapas essenciais de ciência de dados, incluindo:  
- Análise exploratória e tratamento de dados (missing values, outliers, transformação de variáveis);  
- Engenharia de atributos e criação de variáveis relevantes;  
- Seleção de variáveis baseada em técnicas robustas como Information Value (IV), Boruta e Feature Importance;  
- Construção e ajuste de modelos de machine learning, com foco no LightGBM;  
- Otimização de hiperparâmetros utilizando pipelines integrados ao PyCaret;  
- Avaliação detalhada do desempenho com métricas como Acurácia, AUC, KS, Gini, Recall, Precisão, F1-score e análise da matriz de confusão;  
- Discussão sobre o impacto do desbalanceamento de classes e estratégias para mitigação.

## Tecnologias e Bibliotecas Utilizadas  
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- LightGBM  
- PyCaret  
- Boruta  
- Jupyter Notebook / JupyterLab  

## Resultados Principais  
- O modelo LightGBM atingiu acurácia média de 92.23% e AUC superior a 0.77;  
- A variável `renda` foi identificada como a mais importante para a predição de inadimplência;  
- Apesar da alta acurácia, o recall para inadimplentes ainda apresenta espaço para melhorias devido ao desbalanceamento da base;  
- Pipeline automatizado com PyCaret facilitou o ajuste fino dos hiperparâmetros e melhorou a performance geral do modelo.
