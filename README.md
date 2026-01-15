
# 🔬 Predição de Mutação do Gene ALDH2 com Machine Learning

Projeto de machine learning para predição de mutação no gene **ALDH2**, utilizando dados simulados baseados em pesquisa científica real (Wagner Ribeiro - Medicina/USP). O objetivo é criar modelos preditivos que possam auxiliar na triagem de indivíduos, reduzindo custos laboratoriais e acelerando investigações clínicas.

---

## 🧬 Contexto

A enzima mitocondrial ALDH2 é fundamental na metabolização do etanol. Uma mutação genética nesse gene reduz sua atividade, comprometendo o metabolismo do álcool. Como a confirmação laboratorial dessa mutação é cara, modelos preditivos baseados em machine learning tornam-se uma alternativa viável para triagem clínica e pesquisa.

---

## 📊 Variáveis Utilizadas

- Índice de Massa Corporal (IMC)
- Percentual de massa magra e gorda
- Testes de força isométrica (pré e pós treino)
- Teste de força máxima no leg-press (1RM)
- Frequência cardíaca (pré, 30 e 60 min pós ingestão de álcool)
- Pressão arterial sistólica e diastólica (pré, 30 e 60 min pós ingestão de álcool)
- Escala de dor muscular (24h e 48h pós treino)
- Autoavaliação e visualização de rubor após ingestão de álcool

---

## ⚙️ Etapas do Projeto

1. **Instalação dos pacotes**
2. **Importação e preparação dos dados**
   - Remoção de variáveis irrelevantes
   - Imputação de dados ausentes (média para quantitativas, moda para categóricas)
   - Label Encoding para variáveis categóricas
   - Padronização das variáveis quantitativas
3. **Modelagem**
   - Random Forest (com ajuste de hiperparâmetros)
   - XGBoost (com ajuste de hiperparâmetros)
   - CatBoost (com ajuste de hiperparâmetros)
4. **Validação**
   - Cross-validation (3 folds)
   - Métricas: Acurácia, AUC, Precisão, Recall, F1
5. **Seleção de Variáveis**
   - Algoritmo Boruta
   - Interpretação com SHAP

---

## 🛠️ Tecnologias e Bibliotecas

- Python (pandas, numpy, scikit-learn, xgboost, catboost, shap, boruta, dfply)
- Google Colab (execução original)
- Visualização de importância de variáveis (SHAP)

---

## 📈 Resultados

- Modelos ajustados e validados via cross-validation.
- Seleção das variáveis mais relevantes para a predição da mutação.
- Interpretação dos modelos com gráficos SHAP.

---

## 📁 Como Executar

1. Instale as dependências listadas no notebook/script.
2. Execute o código em ambiente Python (Google Colab recomendado).

---

## 📄 Observações

- Este projeto utiliza dados simulados para garantir a integridade e confidencialidade dos dados reais de pesquisa.
- O código pode ser adaptado para outros contextos de predição genética ou biomédica.

---

## 🧑‍💻 Autor

Projeto desenvolvido por Giovani Boldrini Custoias, baseado em pesquisa científica realizada na Medicina/USP pelo Doutorando Wagner Ribeiro.


