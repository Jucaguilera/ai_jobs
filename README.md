#  Projeto Final – Análise do Mercado de Trabalho em Inteligência Artificial (IA)

Este repositório contém o projeto final do curso de Analista de Dados, com uma análise completa sobre o mercado de trabalho voltado à Inteligência Artificial. O estudo envolve **tratamento, exploração, visualização e cruzamento de dados** de três bases públicas, com foco em cargos, salários, adoção de IA e risco de automação.

---

##  Objetivo

Investigar, por meio de dados reais, **como o mercado de trabalho em IA se comporta globalmente** – com ênfase em:
- Salários médios por função
- Projeções de crescimento de cargos
- Adoção de IA por área
- Risco de automação de ocupações
- Distribuição por país, experiência e tipo de trabalho

---

##  Estrutura do Projeto

### ▶ `Notebooks/`
Contém todos os scripts em Python usados ao longo do projeto:

- **`tratamento_dados_ai_jobs (1).ipynb`**  
  Limpeza, preenchimento e enriquecimento do dataset `ai_job_dataset.csv`.

- **`tratamento_salaries_market (1).ipynb`**  
  Tratamento dos dados de salários e adoção de IA (`salaries.csv` e `ai_job_market_insights.csv`), incluindo criação de colunas derivadas como:
  - `nivel_experiencia_label`
  - `Risco_Automacao_Label`

- **`cruzamento_dados_tratados.ipynb`**  
  Cruzamento entre os datasets tratados, unindo as informações de adoção, salários e cargos em um panorama integrado.

- **`analise_exploratoria_ai_jobs_analizado.ipynb`**  
  Análise exploratória completa com gráficos e insights, usada como base para o dashboard.

---

###  `Datasets/`

Contém os arquivos `.csv` já tratados e prontos para análise e visualização:

- `ai_job_dataset_limpo.csv`
- `ai_job_market_insights_limpo.csv`
- `salaries_limpo.csv`
- `cruzamento_adoção_ai.csv`
- `cruzamento_ai_jobs.csv`

---

##  Fontes dos Dados

Todos os dados utilizados neste projeto são públicos e foram obtidos no Kaggle:

- 📁 [AI Powered Job Market Insights](https://www.kaggle.com/datasets/uom190346a/ai-powered-job-market-insights)
- 📁 [AI & ML Salaries](https://www.kaggle.com/datasets/cedricaubin/ai-ml-salaries)
- 📁 [Global AI Job Market and Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)

---

##  Visualizações

Foi construído um **Dashboard interativo no Looker Studio**, com base nos datasets cruzados. Algumas visualizações incluem:

- **Gráfico de barras horizontais**: Salário médio por função (foco entre 60k–100k)
- **Gráfico de pizza**: Distribuição por nível de experiência
- **Gráfico de linhas**: Tendência de crescimento do Salário médio por ano
- **Indicador numérico**: Salário médio geral
- **Gráfico de visualização geral 'Nível do uso de IA por cargo', que corresponde ao quanto IA é usada em cada cargo** 

- Link looker Studio: https://lookerstudio.google.com/reporting/5be2c7cf-7d59-4acd-b0d2-ba3af317f02a
---

##  Relatórios

- [`Relatório_AI_JOBS.pdf`](./Relatório_AI_JOBS.pdf): Relatório visual final com gráficos exportados do Looker Studio.
- [`Relatorio_Analitico_IA.pdf`](./Relatorio_Analitico_IA.pdf): Relatório escrito com os objetivos, métodos, insights e conclusão do projeto.

---

##  Conclusão

O estudo demonstra que o mercado de IA é um dos mais promissores do mundo, com salários competitivos, alta demanda e rápida adoção. Os dados revelam que cargos técnicos, como **AI Researcher** e **Software Engineer**, estão entre os mais valorizados, enquanto funções com **baixo risco de automação** também recebem maiores remunerações.

---

##  Autor

**José Lucas Aguilera**  
Projeto realizado como parte do curso de formação em Análise de Dados – EBAC.

---
