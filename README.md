# vendas_azure_ml_1st_model

# 🧊 Previsão de Vendas com Machine Learning no AZURE

Projeto de Machine Learning para prever vendas de sorvete com base na temperatura do dia, usando regressão linear e MLflow para rastreabilidade.

## 🔍 Etapas
- Análise exploratória dos dados
- Criação do modelo preditivo utilizando automl e designer
- Registro de experimentos com MLflow
- Pipeline pronto para execução e deploy no Azure ML

## 📊 Resultados
AUTOML
- Correlação entre temperatura e vendas: **0.95**
- Melhor modelo: **Nome do algoritmo: PCA, XGBoostRegressor**
- Erro absoluto médio (MAE): **3.83**

DESIGNER
- Coeficiente de determinação: **0.86**
- Erro absoluto médio (MAE): **6.87**

## 📌 Prints

AUTOML
- ![image](https://github.com/user-attachments/assets/83ce1a4b-0b7d-42eb-ab38-585590f4273d)
- ![image](https://github.com/user-attachments/assets/0aa085be-b73a-44bf-b7a4-c0a6a0d88177)

DESIGNER
![image](https://github.com/user-attachments/assets/a43c4378-e8cc-414c-92ae-85afbec71caa)


## 🤖 Possibilidades futuras
- Adicionar mais variáveis: custo produto, prejuízo, etc.
- Deploy em nuvem com Azure ML
