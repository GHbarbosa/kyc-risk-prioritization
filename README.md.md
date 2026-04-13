# 📊 Análise de Engajamento e Comportamento de Usuários no Instagram

## 📌 Visão Geral

Este projeto apresenta uma análise completa de dados voltada à compreensão do comportamento e do nível de engajamento de usuários em uma plataforma de rede social, utilizando técnicas de **Data Analytics** e **Machine Learning** em Python.

O estudo combina análise exploratória, segmentações demográficas e geográficas, visualizações estatísticas e modelagem preditiva para identificar fatores associados ao engajamento digital.

---

## 🎯 Objetivos

* Compreender padrões de comportamento dos usuários
* Identificar fatores associados ao engajamento
* Analisar diferenças demográficas e regionais
* Desenvolver modelo preditivo de engajamento
* Demonstrar aplicação prática de Data Analytics

---

## 📂 Dataset

O conjunto de dados contém aproximadamente **1,5 milhão de registros** e 58 variáveis, incluindo:

* Informações demográficas (idade, gênero, país, educação)
* Variáveis de estilo de vida (sono, exercícios, hábitos)
* Métricas de uso da plataforma (tempo, sessões, interações)
* Indicadores comportamentais e tecnológicos
* Score de engajamento do usuário

Variável alvo utilizada no modelo:

👉 **user_engagement_score**

> ⚠️ O dataset completo não está incluído no repositório devido ao tamanho.

---

## ⚙️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* Jupyter Notebook

---

## 🔎 Etapas do Projeto

### 1️⃣ Preparação e Tratamento de Dados

* Verificação de consistência
* Criação de faixas etárias
* Engenharia de variáveis geográficas (continente)
* Estruturação para análise

### 2️⃣ Análise Exploratória (EDA)

* Distribuições demográficas
* Segmentações por país e continente
* Heatmaps comparativos
* Visualizações estatísticas

### 3️⃣ Modelagem Preditiva de Engajamento

Modelo utilizado:

**Regressão Linear**

Resultados obtidos:

* **MSE:** 1.469
* **R²:** 0.56

O modelo apresentou capacidade preditiva moderada, indicando que variáveis comportamentais e padrões de uso possuem influência significativa no engajamento dos usuários.

---

## 📊 Principais Insights

* Predominância de usuários em faixas etárias intermediárias
* Diferenças regionais relevantes no comportamento digital
* Métricas de atividade na plataforma influenciam diretamente o engajamento
* Segmentação demográfica melhora a compreensão do comportamento do usuário

---

## 🚀 Possíveis Expansões Futuras

* Modelos mais avançados (Random Forest, Gradient Boosting)
* Clusterização de perfis de usuários
* Análise temporal de comportamento
* Sistemas de recomendação

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/instagram-engagement-analysis.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute o notebook no Jupyter.

---

## 👨‍💻 Autor

**Gustavo Henrique Barbosa da Silva**

Analista Regulatório com experiência em governança, controles e análise de dados, em transição para atuação em **Data Analytics**.

📍 Brasil
🔗 LinkedIn: https://www.linkedin.com/in/gustavohenriquebarbosadasilva/
---

## ⭐ Finalidade

Projeto desenvolvido para fins educacionais e portfólio profissional, demonstrando competências em análise de dados, visualização e modelagem preditiva aplicadas ao contexto digital.
