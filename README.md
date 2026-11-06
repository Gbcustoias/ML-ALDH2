# 🧬 Machine Learning para Predição de Mutação no Gene ALDH2

Projeto de Ciência de Dados desenvolvido para explorar o uso de técnicas de Machine Learning na predição de mutações no gene **ALDH2**, utilizando dados simulados baseados em pesquisa científica real conduzida na Faculdade de Medicina da USP.

O objetivo é investigar o potencial de modelos preditivos capazes de identificar padrões associados à mutação genética, contribuindo para estratégias de triagem, redução de custos laboratoriais e apoio à pesquisa biomédica.

---

## 🎯 Objetivo

Desenvolver modelos de Machine Learning capazes de identificar padrões associados à mutações no gene **ALDH2** a partir de variáveis antropométricas, fisiológicas e comportamentais.

O projeto busca demonstrar como técnicas de análise de dados e aprendizado de máquina podem ser utilizadas para apoiar investigações científicas, auxiliar processos de triagem clínica e gerar conhecimento em contextos biomédicos.

---

## 🧬 Contexto

A enzima mitocondrial **ALDH2 (Aldeído Desidrogenase 2)** desempenha papel fundamental na metabolização do etanol.

Uma mutação genética nesse gene reduz significativamente sua atividade, comprometendo o metabolismo do álcool e provocando respostas fisiológicas características após sua ingestão.

Como a confirmação laboratorial dessa mutação possui custos elevados, modelos preditivos baseados em Machine Learning podem representar uma alternativa complementar para triagem, priorização de exames e apoio à pesquisa científica.

---

## 📊 Variáveis Utilizadas

Foram utilizadas variáveis relacionadas a características físicas, fisiológicas e respostas ao consumo de álcool:

- Índice de Massa Corporal (IMC)
- Percentual de massa magra
- Percentual de massa gorda
- Testes de força isométrica (pré e pós-treino)
- Teste de força máxima no Leg Press (1RM)
- Frequência cardíaca:
  - Pré ingestão
  - 30 minutos após ingestão de álcool
  - 60 minutos após ingestão de álcool
- Pressão arterial sistólica:
  - Pré ingestão
  - 30 minutos após ingestão de álcool
  - 60 minutos após ingestão de álcool
- Pressão arterial diastólica:
  - Pré ingestão
  - 30 minutos após ingestão de álcool
  - 60 minutos após ingestão de álcool
- Escala de dor muscular:
  - 24 horas pós-treino
  - 48 horas pós-treino
- Autoavaliação de rubor facial
- Visualização de rubor facial após ingestão de álcool

---

## 🧠 Metodologia

O projeto foi desenvolvido seguindo etapas clássicas de Ciência de Dados:

1. Entendimento do problema
2. Preparação dos dados
3. Engenharia de atributos
4. Treinamento dos modelos
5. Validação estatística
6. Seleção de variáveis
7. Interpretabilidade dos resultados
8. Comparação de desempenho

---

## 🏗️ Pipeline de Machine Learning

```text
Coleta dos Dados
        ↓
Tratamento e Limpeza
        ↓
Codificação das Variáveis
        ↓
Padronização dos Dados
        ↓
Treinamento dos Modelos
        ↓
Validação Cruzada
        ↓
Seleção de Variáveis
        ↓
Interpretação com SHAP
        ↓
Avaliação dos Resultados
```

---

## ⚙️ Etapas do Projeto

### 1. Preparação dos Dados

- Remoção de variáveis irrelevantes
- Tratamento de valores ausentes
- Imputação por média para variáveis numéricas
- Imputação por moda para variáveis categóricas
- Label Encoding para variáveis categóricas
- Padronização das variáveis quantitativas

### 2. Treinamento dos Modelos

Foram avaliados diferentes algoritmos de Machine Learning:

- Random Forest
- XGBoost
- CatBoost

Todos os modelos passaram por ajuste de hiperparâmetros para otimização de desempenho.

### 3. Validação

Os modelos foram avaliados utilizando:

- Cross Validation (3 folds)

Métricas:

- Accuracy
- AUC
- Precision
- Recall
- F1-Score

### 4. Seleção de Variáveis

- Algoritmo Boruta
- Identificação das variáveis mais relevantes

### 5. Interpretabilidade

Utilização da biblioteca SHAP para:

- Explicação das previsões
- Interpretação da importância das variáveis
- Transparência dos modelos desenvolvidos

---

## 🛠️ Tecnologias Utilizadas

### Linguagem

- Python

### Bibliotecas de Manipulação e Análise de Dados

- Pandas
- NumPy
- Dfply

### Bibliotecas de Machine Learning

- Scikit-Learn
- XGBoost
- CatBoost
- Boruta

### Explainable AI

- SHAP

### Ambiente de Desenvolvimento

- Google Colab
- Jupyter Notebook

---

## 💡 Competências Demonstradas

- Ciência de Dados
- Machine Learning Supervisionado
- Classificação Binária
- Data Preprocessing
- Feature Engineering
- Hyperparameter Tuning
- Cross Validation
- Explainable AI (XAI)
- SHAP
- Boruta
- Estatística Aplicada
- Análise Exploratória de Dados
- Python para Ciência de Dados
- Interpretação de Modelos Preditivos
- Pesquisa Científica Aplicada

---

## 📈 Resultados

O projeto possibilitou:

- Construção e comparação de múltiplos modelos preditivos;
- Avaliação de desempenho utilizando validação cruzada;
- Identificação das variáveis mais relevantes para classificação;
- Aplicação de técnicas de Explainable AI para interpretação dos resultados;
- Exploração do uso de Machine Learning em contextos biomédicos e genéticos.

Os resultados demonstram como algoritmos de aprendizado de máquina podem auxiliar investigações científicas e apoiar processos de triagem em estudos clínicos.

---

## 📂 Estrutura do Projeto

```text
├── notebook/
│   └── aldh2_prediction.ipynb
│
├── outputs/
│   ├── shap-Gráfico.png
│   └── shap-force plot.png
│
├── requirements.txt
│
└── README.md
```

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone <url-do-repositorio>
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Abra o notebook

```bash
jupyter notebook
```

ou

Execute diretamente no:

- Google Colab

### 4. Execute as células do notebook

O pipeline completo será executado automaticamente, incluindo:

- Tratamento dos dados
- Treinamento dos modelos
- Avaliação
- Interpretação das variáveis

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conceitos relacionados a:

- Ciência de Dados;
- Machine Learning supervisionado;
- Tratamento e preparação de dados;
- Seleção de variáveis;
- Interpretabilidade de modelos;
- Validação estatística;
- Explainable AI;
- Aplicações de Inteligência Artificial em saúde.

Além dos aspectos técnicos, o projeto demonstrou como conhecimentos provenientes da pesquisa científica podem ser integrados às técnicas modernas de análise de dados para gerar insights e apoiar processos de tomada de decisão.

---

## 📄 Observações

- Este projeto utiliza dados simulados para preservar a confidencialidade dos dados reais de pesquisa.
- Os métodos implementados podem ser adaptados para outros contextos de predição genética e biomédica.
- O foco do projeto é educacional e exploratório, não devendo ser utilizado como ferramenta diagnóstica.

---

## 👨‍💻 Autor

**Giovani Boldrini Custoias**

Projeto desenvolvido com base em pesquisa científica realizada na Faculdade de Medicina da Universidade de São Paulo (USP), conduzida pelo pesquisador Wagner Ribeiro.

---

## 📜 Licença

Este projeto foi desenvolvido para fins acadêmicos, educacionais e de demonstração de competências em Ciência de Dados e Machine Learning.
