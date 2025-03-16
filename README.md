# Previsão de Rotatividade (Churn) de Cartão de Crédito

<p align="center">
    <img src="https://miro.medium.com/v2/resize:fit:800/1*3xEPKteLmsRwSUK6bfbpFQ.jpeg" alt="Alex Assunção Data Scientist" width="800">
</p>
## Situação
Um banco enfrenta um aumento significativo no número de cancelamentos de cartões de crédito, impactando diretamente sua receita e base de clientes. A instituição necessita identificar proativamente clientes com alto risco de cancelamento para implementar estratégias de retenção eficazes.

## Tarefa
Desenvolver um modelo de machine learning capaz de:
- Prever a probabilidade de cancelamento de cartão de crédito por cliente
- Identificar os principais fatores que influenciam o cancelamento
- Fornecer insights acionáveis para estratégias de retenção
- Implementar uma solução em produção para uso contínuo

## Ações

### 1. Análise Exploratória de Dados
- Identificação de taxa de churn de 16% na base de clientes
- Análise de correlação entre variáveis numéricas e churn
- Investigação de padrões comportamentais dos clientes
- Detecção de features mais relevantes para o cancelamento

### 2. Preparação dos Dados

- Tratamento de dados faltantes e outliers
- Codificação de variáveis categóricas
- Normalização de features numéricas

### 3. Modelagem
- Implementação de diversos algoritmos:
  - LightGBM
  - XGBoost
  - Random Forest
- Otimização de hiperparâmetros via Bayesian Search
- Validação cruzada com 5 folds
- Avaliação através de múltiplas métricas:
  - Acurácia
  - ROC-AUC
  - Precisão
  - Recall
  - F1-Score

### 4. Sujestão de Implementação em Produção
- Desenvolvimento de API REST com Flask
- Interface web interativa com Streamlit
- Sistema de logging para monitoramento
- Pipeline automatizado de treino e predição

## Resultados

### Métricas de Performance
- Acurácia: 96.5%
- ROC-AUC: 0.991
- Precisão: 94.3%
- Recall: 93.8%
- F1-Score: 94.0%



### Principais Insights
1. Clientes com maior probabilidade de cancelamento apresentam:
   - Menor limite de crédito
   - Menor volume de transações
   - Maior número de contatos com o banco
   - Períodos mais longos de inatividade

2. Fatores críticos para retenção:
   - Engajamento nos primeiros 3 meses
   - Utilização regular do cartão
   - Resposta rápida a reclamações
   - Adequação do limite de crédito

## Tecnologias Utilizadas
- Python 3.11.4
- Scikit-learn
- LightGBM
- Flask
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn


```

## Próximos Passos que poderão ser analisados
1. Implementação de monitoramento de drift do modelo
2. Desenvolvimento de features adicionais baseadas em comportamento temporal
3. Integração com sistemas de CRM do banco
4. Automatização completa do pipeline de retreinamento
5. Implementação de testes A/B para estratégias de retenção


```	
## Dataset Utilizado
O dataset utilizado neste projeto foi disponibilizado pela [Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data).
## Autor
Alex Silva de Assunção

## Contato 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexassuncaodata/)

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alexassuncao.dados@gmail.com)

[![whatsapp](https://img.shields.io/badge/Whatsapp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=5541987986571&text=Ol%C3%A1%2C%20Alex!)