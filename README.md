
# 📊 Análise Estatística de Jogos de Futebol

## 📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) a partir de um conjunto de dados de jogos de futebol, buscando identificar padrões de desempenho entre os times com base em métricas ofensivas e defensivas.

A análise foi desenvolvida utilizando Python, com foco em práticas fundamentais de análise de dados, como agregações, criação de métricas e visualização de informações.

---

## 🎯 Objetivo

Analisar o desempenho dos times considerando:

* ⚽ Gols marcados (força ofensiva)
* 🛡️ Gols sofridos (consistência defensiva)
* 📊 Saldo de gols (indicador geral de performance)
* 🚩 Escanteios (pressão ofensiva)

---

## 🗂️ Dataset

O dataset utilizado contém informações de partidas de futebol, incluindo:

* Time
* Jogo
* Gols marcados
* Gols sofridos
* Chutes a gol 
* Escanteios
* Posse (%)
* Amarelos
* Vermelhos
* Impedimentos
* Faltas
* Escanteios
* saldo gols
* eficiencia_ofensiva


## 🧹 Tratamento de Dados

Foram realizadas etapas básicas de limpeza e preparação dos dados:

* Verificação de valores nulos
* Verificação dos tipos de dados
---

## 📊 Análise Exploratória

Durante a análise, foram realizadas:

* Agrupamentos por time (`groupby`)
* Cálculo de métricas agregadas (soma e média)
* Criação de nova variável:

  * **Saldo de gols** = Gols marcados - Gols sofridos

Também foram geradas visualizações para facilitar a interpretação dos dados.

---

## 📈 Principais Insights

* Times com maior número de gols marcados tendem a apresentar melhor desempenho geral.
* O saldo de gols se mostrou um indicador mais completo do que apenas gols marcados.
* Alguns times possuem alta produção ofensiva, mas também apresentam fragilidade defensiva.
* A quantidade de escanteios pode indicar maior presença ofensiva ao longo das partidas.

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib

---

## 📌 Conclusão

A análise permitiu identificar padrões importantes no desempenho dos times, destacando a importância do equilíbrio entre ataque e defesa.

Além disso, o projeto reforça conceitos fundamentais de análise de dados, sendo um passo importante no desenvolvimento de habilidades práticas na área.

---

