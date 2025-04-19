# 🧠 Minha jornada em Machine Learning

Bem-vindo(a) ao meu repositório de estudos em Machine Learning!  

Aqui você encontrará pequenos projetos, experimentos e anotações baseados nos conceitos e ferramentas que estou aprendendo na especialização em Inteligência Artificial da Unicamp.

Este repositório serve tanto como portfólio quanto como diário de aprendizado, com foco em aplicações práticas de técnicas de Machine Learning no contexto de processos industriais.

# 🧰 Ferramentas e Técnicas que estou aprendendo

📊 Divisão e Validação de Dados

**Método Holdout:** Divide o conjunto de dados em partes para treino e teste.

*from sklearn.model_selection import train_test_split*

**Validação cruzada (cross_val_score):** Avalia o modelo em múltiplas divisões de treino e teste.

*from sklearn.model_selection import cross_val_score*

**LeaveOneOut:** Usa uma amostra para teste e o restante para treino, repetindo para todo o conjunto.

*from sklearn.model_selection import LeaveOneOut*

**TimeSeriesSplit:** Validação cruzada para séries temporais, respeitando a ordem dos dados.

*from sklearn.model_selection import TimeSeriesSplit*

# 🔧 Pré-processamento de Dados

**MinMaxScaler:** Normaliza os dados em uma escala de 0 a 1.

*from sklearn.preprocessing import MinMaxScaler*

# 🌳 Modelos de Regressão e Classificação
**DecisionTreeRegressor:** Realiza regressão utilizando árvores de decisão.

*from sklearn.tree import DecisionTreeRegressor*

**SVC (Support Vector Classifier):** Classificador baseado em máquinas de vetor de suporte.

*from sklearn.svm import SVC*

**LogisticRegression:** Modelo de classificação binária baseado em função logística.

*from sklearn.linear_model import LogisticRegression*

# 🎯 Métricas de Avaliação
**mean_squared_error (MSE):** Erro médio quadrático entre valores reais e previstos.

*from sklearn.metrics import mean_squared_error*

**f1_score:** Média harmônica entre precisão e recall, ideal para classes desbalanceadas.

*from sklearn.metrics import f1_score*

#🛠️ Otimização de Hiperparâmetros
**ParameterGrid:** Gera todas as combinações possíveis de hiperparâmetros.

*from sklearn.model_selection import ParameterGrid*

**GridSearchCV:** Busca exaustiva por combinações ideais de parâmetros com validação cruzada.

*from sklearn.model_selection import GridSearchCV*

# 📂 Projetos
Em breve, estarei adicionando os notebooks com aplicações práticas dessas técnicas, com foco em problemas reais de engenharia de processos e análise de dados industriais.

💬 Vamos nos conectar?
Caso queira trocar ideias ou feedbacks, me chama por aqui ou pelo [LinkedIn](https://www.linkedin.com/in/izabellawyne/).

