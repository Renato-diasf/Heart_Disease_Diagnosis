# 💓 Heart Disease Diagnosis

Este repositório contém um projeto de Machine Learning voltado para o diagnóstico de doenças cardíacas com base em dados clínicos de pacientes. O objetivo principal é prever a presença ou ausência de doença cardíaca a partir de variáveis como idade, sexo, pressão arterial, colesterol, entre outras.

## 📁 Estrutura do Projeto

- `Heart_Disease_Diagnosis.ipynb`: Notebook principal com todo o processo de análise exploratória de dados (EDA), pré-processamento e aplicação de algoritmos de machine learning para diagnóstico.

## 📊 Tecnologias e Bibliotecas Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Etapas do Projeto

1. **Importação dos Dados**  
   Leitura e verificação inicial do dataset.

2. **Análise Exploratória de Dados (EDA)**  
   Visualizações e estatísticas para entender as variáveis.

3. **Pré-processamento**  
   - Tratamento de dados ausentes  
   - Normalização e codificação de variáveis

4. **Modelagem**  
   - Teste de diversos modelos (ex: Árvore de Decisão, MLP, KNN, Naive Bayes)  
   - Avaliação de performance com métricas como accuracy, precisão, recall e F1-score

## 📌 Conclusão

Após a aplicação e avaliação de diversos algoritmos de machine learning, o modelo **K-Nearest Neighbors (KNN)** apresentou o melhor desempenho no contexto do diagnóstico de doenças cardíacas. Embora outros modelos tenham alcançado valores competitivos de acurácia e precisão, o KNN se destacou por apresentar a **maior taxa de revocação (recall)**.

A revocação mede a capacidade do modelo de identificar corretamente os casos positivos — ou seja, os pacientes que realmente possuem a doença. Em cenários médicos, essa métrica é **crucial**, pois **minimizar falsos negativos** (casos em que o modelo afirma que o paciente está saudável, mas ele tem a doença) é fundamental para garantir segurança e tratamento adequado aos pacientes.

Portanto, mesmo que outros modelos tenham apresentado bom desempenho geral, a escolha do **KNN como o modelo preferido** se justifica pela sua **superioridade na revocação**, alinhando-se melhor aos objetivos de um sistema de suporte ao diagnóstico médico.

