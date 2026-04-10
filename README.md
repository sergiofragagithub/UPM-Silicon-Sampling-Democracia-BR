# UPM-Silicon-Sampling-Democracia-BR
Projeto 1 - Avaliação de Silicon Sampling em Percepções Democráticas: Uma Análise Comparativa entre Random Forest e Large Language Models (LLM)


Este repositório contém o experimento prático realizado para a **Universidade Presbiteriana Mackenzie**, focado na comparação entre modelos de Machine Learning tradicional e Large Language Models (LLM) para simulação de pesquisas de opinião.

## 🚀 Objetivo
Validar a técnica de **Silicon Sampling** utilizando o dataset `04832.SAV` (Percepção sobre a Democracia). O objetivo foi verificar se o modelo **Gemini 2.0 Flash** consegue emular o comportamento de respondentes reais com base em seus perfis socioeconômicos.

## 📊 Resultados Obtidos
A comparação foi feita entre o gabarito (dados reais), uma Random Forest (baseline) e o LLM.

| Modelo | Acurácia |
| :--- | :---: |
| **Random Forest** | 0.98 |
| **Gemini 2.0 Flash** | 0.90 |

## 🛠️ Tecnologias Utilizadas
* **Python 3.12**
* **Google Colab**
* **Pandas & Scikit-Learn** (Random Forest)
* **Google Generative AI API** (Gemini 2.0 Flash)
* **Pyreadstat** (para leitura de arquivos .SAV do SPSS)

## 📁 Estrutura do Repositório
* `projeto_1.ipynb`: Notebook com todo o código do experimento.
* `resultados_finais_projeto.csv`: Base de dados gerada com as predições.
* `grafico_final_projeto1.png`: Gráfico comparativo de distribuição de respostas.

## 🎓 Autor do Projeto: 
**Sérgio Fraga**

**Disciplina Modelos de Linguagem e Generativos**

**Professor Dr.Rogerio** 

Universidade Presbiteriana Mackenzie
