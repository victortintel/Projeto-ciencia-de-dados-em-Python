# Análise de Churn em Clientes de Telecomunicações

Este projeto tem como objetivo analisar e prever o churn (rotatividade) de clientes em uma empresa de telecomunicações, identificando os principais fatores que levam ao cancelamento do serviço e propondo ações para reduzir essa taxa.

## 📌 Visão Geral
- **Problema**: Alta taxa de churn em clientes de telecomunicações
- **Objetivo**: Identificar padrões e prever clientes com risco de churn
- **Resultados**: Modelo com 82% de precisão e AUC de 0.85, com insights acionáveis

## 📊 Dados
- Dataset público de clientes de telecomunicações
- 7.043 registros e 20 features
- Variável alvo: Churn (Sim/Não)

## 🛠️ Tecnologias e Bibliotecas
- Python 3
- Jupyter Notebook
- Bibliotecas:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - Imbalanced-learn (SMOTE)

## 📈 Métricas do Modelo
- **Acurácia**: 82%
- **Precisão**: 0.83
- **Recall**: 0.78
- **AUC-ROC**: 0.85

## 📂 Estrutura do Projeto
1. `data/`: Dados originais
2. `notebooks/`: Jupyter notebooks com a análise
3. `reports/`: Relatórios e visualizações
4. `models/`: Modelos treinados

## 🚀 Como Executar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o Jupyter Notebook: `jupyter notebook`

## 📝 Principais Conclusões
- Contrato mensal é o maior fator de risco para churn
- Clientes com serviços adicionais (segurança, backup) têm menor churn
- Recomendações focadas em conversão de contratos e pacotes de serviços
