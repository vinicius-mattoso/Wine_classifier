![Welcome](/Wine Classifier_cover.png?raw=true)


# Desafio Módulo 02 do BootCamp de Machine Learning do IGIT

## Wine_classifier
 
---

Nesse desafio o aluno deveria completar o jupyternotebook  e responder as perguntas na plataforma.
Analisando esse notebook podemos observar as seguinte estapas no projeto:

### Análise exploratória

- [x] Carregar a base de dado, sabendo que o separador é ponto e virgula;
- [x] Visualização inicial do Dataset;
- [x] Analisar as informaçãoes do Dataset: Tipo de Dado, Existencia de valores nulos e informações estatisticas;
- [X] Avaliar a matriz de correlação dos dados, de forma tabular e por heatmap;
- [x] Separação dos dados em Features e Target.

### Pré-Processamento

- [x] Normalização das Features pelo MinMaxScaler;
- [x] Split dos dados em treino e teste;

### Criação do Modelo

Como esse projeto era simplismente para ensinar os modelos, a parte de criação de modelo foi um pouco simples pois não fez testes com diferentes parâmetros,
apenas gerou os seguintes modelos:

- [x] KNN;
- [X] Decision Tree;
- [x] Random Forest;
- [x] SVM;
- [x] MLP;

### Criação de Novo Target

Nessa parte do projeto, foi criado um novo data set com um target binario, onde vinhos que tinham classificação maiores que 5 foram considerados vinhos bons (0) e menores iguais a 5 vinhos ruins (1).
Novamente foram feitas as seguintes etapas no projeto:

- [x] Separação de features e o Novo Target;
- [x] Normalização das Features pelo MinMaxScaler;
- [x] Split dos dados em treino e teste;
- [x] Criação do Modelo de Random Forest;

