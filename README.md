### **Projeto de Machine Learning: Previsão de Churn na TelecomX**

Este repositório contém a segunda parte do projeto de análise de churn, focada na construção de modelos de Machine Learning para prever a evasão de clientes. O objetivo é utilizar o dataset tratado para desenvolver um modelo preditivo robusto e compará-lo com outros modelos.

### **📋 Descrição do Projeto**

O projeto segue um pipeline de Machine Learning completo, que inclui:
- **Pré-processamento**: Preparação e codificação das variáveis para os modelos.
- **Divisão de Dados**: Separação do dataset em conjuntos de treino e teste.
- **Modelagem**: Construção de modelos de **Regressão Logística** e **Árvore de Decisão**.
- **Avaliação**: Análise do desempenho dos modelos usando métricas como acurácia, precisão e recall.

### **🛠️ Tecnologias Utilizadas**

- **Python**: Linguagem principal para a análise.
- **Pandas**: Para a manipulação dos dados.
- **Scikit-learn**: Principal biblioteca para a construção e avaliação dos modelos de Machine Learning.
- **Matplotlib/Seaborn**: Para a visualização de correlação.

### **📁 Estrutura do Repositório**

- `TelecomX_challenge3.ipynb`: O caderno Jupyter que contém todo o código para o pipeline de Machine Learning, desde a preparação dos dados até o relatório final.
- `df_telecom_tratado.csv`: O dataset limpo e preparado, resultado da primeira parte do projeto.

### **📊 Metodologia e Resultados**

- **Preparação dos Dados**: Variáveis categóricas foram transformadas utilizando One-Hot Encoding.
- **Seleção de Variáveis**: Uma matriz de correlação foi utilizada para identificar as variáveis com maior relação com o Churn, como `Contrato` e `Gastos_Mensais`.
- **Avaliação dos Modelos**:
  - **Regressão Logística**: Obteve uma **Acurácia de 82%** e um **Recall de 55%** na identificação de Churn.
  - **Árvore de Decisão**: Obteve uma **Acurácia de 73%** e um **Recall de 50%**.

### **💡 Conclusão Final**

A **Regressão Logística** demonstrou ser o modelo mais eficaz para este problema de classificação, apresentando um desempenho superior na acurácia e, mais importante, na identificação dos clientes propensos ao Churn.

### **🚀 Como Executar o Projeto**

Para executar este projeto, você precisará ter o Python e as bibliotecas listadas instaladas.

1.  Clone este repositório.
2.  Abra o arquivo `TelecomX_challenge3.ipynb` em seu ambiente de desenvolvimento.
3.  Siga o notebook passo a passo para reproduzir a análise.
