![](https://github.com/luckermos/ML-TuningPython/blob/main/machine-learning.jpg?raw=true)
# *Scripts* de *Machine Learning* em Python com *Tuning* de Hiperparâmetros e *Feature Selection* para Classificação e Regressão

## Descrição

O projeto contém *scripts* com exemplos de aplicação de algoritmos de *machine learning* tanto para regressão quanto para classificação com a implementação de código para *tuning* dos hiperparâmetros a partir do `RandomizedSearchCV()` e seleção do melhor subconjunto de variáveis explicativas a partir do `RFECV()`, quando aplicável, de modo a maximizar uma métrica de avaliação escolhida. Foi criada uma função específica para obter medidas de avaliação a fim de comparar o desempenho dos algoritmos. Foram utilizadas as funções dos pacotes `pandas` e `numpy` para manipulação dos dados, `matplotlib` e `seaborn` para visualização e `scikit-learn` para a modelagem.

## Classificação

Os modelos para classificação maximizam a Acurácia Balanceada e podem ser encontrados no arquivo `ML_Classification_Tuning_FeatureSelect.ipynb`. Contém os algoritmos:

- *KNN*: `KNeighborsClassifier()`
- *Naive Bayes*: `GaussianNB()`
- *Logistic Regression*: `LogisticRegression()`
- *Decision Tree*: `DecisionTreeClassifier()`
- *Random Forest*: `RandomForestClassifier()`
- *Support Vector Machine*: `SVC()`
- *Neural Network*: `MLPClassifier()`

## Regressão

Os modelos para Regressão minimizam o Erro Quadrático Médio (EQM/MSE) e podem ser encontrados no arquivo `ML_Regression_Tuning_FeatureSelect.ipynb`. Contém os algoritmos:

- *Linear Regression*: `LinearRegression()`
- *Decision Tree*: `DecisionTreeRegressor()`
- *Random Forest*: `RandomForestRegressor()`
- *Support Vector Machine*: `SVR()`
- *Neural Network*: `MLPRegressor()`

## Contribuidores

<table>
  <tr>
    <td align="center"><a href="https://github.com/luckermos"><img src="https://avatars.githubusercontent.com/u/49843691?s=100" width="100px;" alt=""/><br /><sub><b>Lucas Emanuel</b></sub></a><br /><a href="https://github.com/luckermos" title="Github"><img src="https://raw.githubusercontent.com/luckermos/logos/main/social/git.png" width="20"></a> <a href="https://www.linkedin.com/in/luckermos/" title="LinkedIn"><img src="https://raw.githubusercontent.com/luckermos/logos/main/social/linkedin.png" width="20"></a> <a href="mailto:luckermos19@gmail.com" title="E-mail"><img src="https://raw.githubusercontent.com/luckermos/logos/main/social/email.png" width="20"></a></td>
  </tr>
</table>
