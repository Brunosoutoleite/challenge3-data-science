### **Projeto de Machine Learning: Previsão de Churn na TelecomX**

Este repositório contém a segunda parte do projeto de análise de churn, com o objetivo principal de construir um modelo preditivo para identificar clientes propensos à evasão. O projeto utiliza o dataset tratado da primeira fase para aplicar técnicas de Machine Learning e fornecer um modelo robusto para a tomada de decisões estratégicas.

### **📋 Estrutura do Projeto**

O projeto é organizado com a seguinte estrutura de arquivos:
- `TelecomX_challenge3.ipynb`: O notebook principal que documenta todo o pipeline de Machine Learning, desde o pré-processamento até a avaliação dos modelos.
- `df_telecom_tratado.csv`: O conjunto de dados tratado, resultado da etapa de limpeza e análise da primeira parte do projeto, servindo como ponto de partida para a modelagem.

### **📊 Metodologia e Processo de Análise**

A metodologia seguiu um fluxo completo de Machine Learning:

#### **1. Preparação dos Dados**

- **Classificação de Variáveis**: As variáveis foram classificadas entre numéricas (e.g., `Gastos_Mensais`) e categóricas (e.g., `Contrato`, `Metodo_Pagamento`).
- **Codificação de Variáveis**: As variáveis categóricas binárias (`Churn`, `Gênero`, `Parceiro`, `Dependentes`) foram codificadas como 0 e 1 (Label Encoding). As demais variáveis categóricas foram transformadas usando **One-Hot Encoding** para que os modelos as interpretassem corretamente.
- **Divisão em Conjuntos de Treino e Teste**: Os dados foram separados em 75% para treino e 25% para teste, garantindo que o modelo fosse avaliado em um conjunto de dados que ele nunca viu antes, evitando o *overfitting*.

#### **2. Modelagem Preditiva e Avaliação**

Dois modelos de classificação foram implementados e comparados:
- **Regressão Logística**: Um modelo simples, mas robusto, que alcançou uma **Acurácia de 82%** e um **Recall de 55%** para a classe de Churn.
- **Árvore de Decisão**: Um modelo mais interpretável, que obteve uma **Acurácia de 73%** e um **Recall de 50%**.

### **🔍 Insights Obtidos e Conclusão**

A análise de correlação (heatmap) revelou insights importantes, como a forte relação entre **contratos mensais** e o **método de pagamento via Cheque Eletrônico** com o Churn.

Com base na avaliação de desempenho, a **Regressão Logística** foi a escolha mais eficaz para este projeto, superando a Árvore de Decisão em todas as métricas-chave.

### **🛠️ Tecnologias e Dependências**

- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn

### **🚀 Como Executar o Notebook**

Para rodar o notebook e reproduzir a análise, certifique-se de que as bibliotecas listadas acima estão instaladas em seu ambiente e siga as instruções:
1.  Clone o repositório.
2.  Faça o upload do arquivo `df_telecom_tratado.csv` para o ambiente do notebook.
3.  Execute as células sequencialmente.
