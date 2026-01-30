# 💳 PROJETO 2: ANÁLISE DE RISCO PARA CONCESSÃO DE EMPRÉSTIMOS

Este projeto foi desenvolvido como parte da disciplina de **Pré-Processamento de Dados**, sob orientação do **Professor Albaro Ramon Paiva Sanz**. O objetivo central é construir um modelo preditivo capaz de identificar, com base em dados históricos, quais novos clientes possuem perfil para acessar o crédito solicitado.

---

### 📌 Descrição da Atividade

Uma empresa que oferece empréstimos a pessoas físicas precisa mitigar riscos financeiros. O desafio consistiu em transformar dados brutos em inteligência de negócio através de:

1. **Tratamento de Dados:** Limpeza, tratamento de valores ausentes e codificação de variáveis categóricas.
2. **Análise Exploratória (EDA):** Identificação de padrões de comportamento financeiro através de visualizações gráficas.
3. **Modelagem Preditiva:** Implementação e comparação de algoritmos de classificação para prever a aprovação de crédito.

**Pergunta norteadora:** *Qual é a probabilidade de aprovação/risco de cada novo cliente, considerando suas informações cadastrais e financeiras?*

---

### 🛠️ Tecnologias e Bibliotecas

Para este projeto, utilizamos o **CatBoost** como modelo principal devido à sua excelente performance com dados categóricos, além de outras ferramentas essenciais:

* **Manipulação e Processamento:** `Pandas`, `Numpy`.
* **Visualização de Dados:** `Matplotlib`, `Seaborn`, `Plotly Express`, `Plotly Graph Objects`.
* **Machine Learning (Scikit-Learn):** `train_test_split`, `LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`.
* **Boostings:** `CatBoostClassifier`, `XGBClassifier`.
* **Métricas de Avaliação:** `accuracy_score`, `precision_score`, `recall_score`, `f1_score`.

---

### 🚀 Fluxo de Trabalho (Pipeline)

1. **Ingestão e Limpeza:** Preparação dos dados e tratamento de inconsistências.
2. **Modelagem:** Divisão de treino/teste e treinamento de múltiplos modelos (Baseline vs. Boostings).
3. **Avaliação:** Comparação rigorosa de métricas para garantir a minimização de prejuízos (foco em reduzir Falsos Negativos).

---

### 💾 Como Executar

1. Baixe o arquivo disponibilizado neste repositório
2. Importe o arquivo baixado
3. Importe as bibliotecas informadas acima
4. Execute o arquivo Jupyter Notebook para visualizar todo o processo de pré-processamento e treinamento.

---

### 👥 Equipe

* Ayryslaine Kelle
* Brenno Vale
* Jeová Anderson
