
# Machine Learning Classification and Model Evaluation

Este projeto implementa diversos modelos de classificação, incluindo **Regressão Logística**, **Naive Bayes** e **Árvore de Decisão**, e compara suas performances utilizando métricas de avaliação comuns como **F1 Score**, **Precisão**, **Recall** e **Acurácia**.

## Pré-requisitos

- Python 3.x
- Bibliotecas:
  - `pandas`
  - `matplotlib`
  - `sklearn`

## Instalação

Para rodar o projeto, instale as bibliotecas necessárias executando o seguinte comando:

```bash
pip install pandas matplotlib scikit-learn
```

## Descrição dos Modelos

O código inclui duas versões principais de modelos:

1. **Versão 1 - Modelos de Regressão Logística e Naive Bayes**:
   - Treinamento e predição são realizados usando os algoritmos `LogisticRegression` e `GaussianNB`.
   - Métricas de avaliação como **F1 Score**, **Precisão**, **Recall** e **Acurácia** são calculadas para ambos os modelos.
  
2. **Versão 2 - Árvore de Decisão**:
   - Utiliza o classificador `DecisionTreeClassifier`.
   - Avalia o modelo nas mesmas métricas mencionadas.

## Avaliação dos Modelos

O código gera uma tabela comparativa e um gráfico de barras para visualizar as métricas de desempenho para cada um dos modelos implementados.

### Métricas utilizadas:
- **F1 Score**
- **Precisão**
- **Recall**
- **Acurácia**

## Como Usar

1. Certifique-se de que os dados estejam pré-processados e divididos em conjuntos de treino (`X_treino`, `y_treino`) e teste (`X_teste`, `y_teste`).
2. Execute o script para treinar os modelos e gerar previsões.
3. O gráfico final exibirá a comparação das métricas para os modelos treinados.

## Resultados Esperados

A saída do código é um gráfico de barras mostrando a performance dos diferentes modelos em termos das quatro métricas de avaliação.

## Contato

Para mais informações, entre em contato com o desenvolvedor.
