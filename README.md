# 🧠 Estudos em Machine Learning com Scikit-Learn

Este repositório contém dois projetos desenvolvidos como parte dos meus estudos em **ciência de dados** e **machine learning**, com foco em **análise de dados**, **modelagem preditiva**, **validação** e **avaliação de desempenho de modelos**, utilizando a biblioteca **Scikit-Learn**.

---

## 📁 Projeto 1 – Modelos Básicos de Classificação

### ✅ Objetivos:
- Identificar a variável alvo;
- Tratar valores nulos e inconsistentes;
- Realizar análise exploratória de dados com gráficos;
- Preparar os dados para machine learning.

### ⚙️ Etapas Desenvolvidas:
- Transformação de variáveis categóricas com `OneHotEncoder`;
- Conversão da variável alvo com `LabelEncoder`;
- Separação entre dados de treino e teste;
- Criação e avaliação de modelos:
  - `DummyClassifier`
  - `DecisionTreeClassifier`
  - `KNeighborsClassifier` com normalização;
- Comparação de desempenho entre modelos;
- Visualização com `plot_tree`;
- Salvamento do modelo com `pickle`.

---

## 📁 Projeto 2 – Validação de Modelos e Dados Desbalanceados

### ✅ Objetivos:
- Criar um modelo com **árvore de decisão** e aplicar **poda da árvore** para evitar overfitting;
- Avaliar o modelo utilizando **acurácia**, **precisão**, **recall** e **matriz de confusão**;
- Analisar o desempenho com métricas apropriadas para o problema proposto.

### ⚙️ Etapas Desenvolvidas:
- Extração de métricas a partir da matriz de confusão;
- Geração de gráficos:
  - Curva **ROC**
  - Curva **Precisão x Recall**
- Construção de **relatório de desempenho** dos modelos;
- Aplicação de **validação cruzada (KFold e StratifiedKFold)** com diferentes métricas;
- Aplicação de técnicas para lidar com **dados desbalanceados**:
  - **Oversampling**
  - **Undersampling**
- Criação de **pipeline de machine learning** integrando validação cruzada;
- Comparação de modelos de classificação com dados balanceados.

---

## 📚 O que aprendi:
- Técnicas de preparação de dados para modelos supervisionados;
- Como construir, treinar e avaliar modelos de classificação;
- Como selecionar métricas adequadas para diferentes problemas;
- Como lidar com dados desbalanceados;
- Como evitar overfitting com poda e validação cruzada;
- Como aplicar pipelines de forma profissional.
