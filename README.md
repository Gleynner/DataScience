<h1 align="center">📊 Gleynner Ghiotto | Portfólio de Ciência de Dados</h1>

<p align="center">
  <a href="https://linkedin.com/in/gleynnerghiotto"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/Gleynner"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="mailto:gleynnerghiotto@outlook"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>


Bem-vindo(a) ao meu portfólio de projetos em Ciência de Dados e Machine Learning. Este repositório reúne estudos, experimentos e projetos desenvolvidos ao longo da minha jornada de aprendizado e aprofundamento na área de dados.

Aqui, busco aplicar na prática conceitos de análise de dados, estatística e Machine Learning por meio de projetos que envolvem desde a exploração e tratamento dos dados até a construção de pipeline para avaliação e otimização de modelos preditivos.

Os projetos foram desenvolvidos com foco em aprendizado contínuo e boas práticas, utilizando ferramentas amplamente empregadas no mercado, como Python, Scikit-Learn, LightGBM, Optuna e Imbalanced-Learn. Sempre que possível, procuro estruturar os estudos de forma organizada e próxima de cenários reais, valorizando tanto a parte técnica quanto a interpretação dos resultados.

Mais do que apresentar modelos, este portfólio representa meu processo de evolução na área de dados, incluindo estudos sobre pré-processamento, feature engineering, pipelines, validação de modelos, tuning de hiperparâmetros e análise orientada à tomada de decisão.

> Observação: os dados utilizados nos projetos possuem finalidade exclusivamente educacional e demonstrativa, respeitando princípios de privacidade, ética e boas práticas no uso de dados.

<br>

## 📑 Sumário

- [Competências Técnicas](#-competências-técnicas)
- [Competências Comportamentais](#-competências-comportamentais)
- [Projetos — Python](#projetos-python)
- [Projetos — SQL](#projetos-sql)
- [Projetos — R](#projetos-r)
- [Vamos conversar](#-vamos-conversar)

---

<a id="projetos-python"></a>
## 🛠️ Competências Técnicas

Análise Exploratória de Dados · Estatística · Feature Engineering · Modelagem Preditiva · Pipelines de Pré-processamento · Balanceamento de Classes (Imbalanced-Learn) · Validação e Otimização de Modelos (Optuna) · Séries Temporais · Storytelling e Comunicação de Dados


## 🤝 Competências Comportamentais

Pensamento analítico · Resolução de problemas · Raciocínio crítico · Documentação técnica · Comunicação · Visão de negócio · Aprendizado contínuo · Trabalho colaborativo

<br>

---

## 🚀 Projetos em Destaque


<a id="projetos-python"></a>

### 🐍 Python

**☕ [Café, Estresse e Sono: Da Análise de Dados à Recomendação de Negócio](https://github.com/Gleynner/coffee-sleep-health-analysis)**

`Python` `Pandas` `Scikit-learn` `LightGBM` `XGBoost` `EDA`

Projeto de ciência de dados que investiga como café, estresse e hábitos de vida se relacionam com a qualidade do sono, aplicado a um caso de negócio simulado para uma empresa de saúde e bem-estar. O trabalho percorre todo o ciclo analítico — análise exploratória, geração de insights, modelagem preditiva (Regressão Logística, LightGBM e XGBoost) e recomendações de negócio.

**Principais resultados:**
- Identificação do nível de estresse como fator mais associado à qualidade do sono (r ≈ -0,91), superando o impacto isolado do café
- Comparação de 3 modelos de classificação (Regressão Logística, LightGBM, XGBoost), com F1-macro de até 0,99
- Diagnóstico crítico de um caso de vazamento de dados (data leakage) estrutural, com discussão técnica sobre suas implicações
- Recomendações de negócio traduzidas a partir dos insights estatísticos

<br>

**💳 [Análise de Risco de Crédito](https://github.com/Gleynner/Analise_de_risco_de_credito)** 

`Python` `LightGBM` `SVC` `Optuna` `Imbalanced-Learn`

Previsão de inadimplência em cenário de dados desbalanceados, com foco na construção de modelos robustos e interpretáveis para apoiar decisões de concessão de crédito.

**Principais resultados:**
- Pipeline completo de pré-processamento, feature engineering e seleção de variáveis
- Avaliação criteriosa de balanceamento: SMOTE testado e descartado por falta de ganho consistente, em favor de ponderação de classes
- Feature engineering avançada com WOE, Information Value e clusterização geográfica
- Otimização de hiperparâmetros com Optuna
- Ajuste de threshold orientado ao trade-off entre recall, precision e custo operacional
- LightGBM e SVC com melhor desempenho na identificação de clientes inadimplentes

<br>
  
**🚲 [Análise Exploratória e Previsão de Demanda - London Bike Sharing](https://github.com/Gleynner/Analise_demanda_bike_sharing)** 

`Python` `Prophet` `Séries Temporais` `Testes de Hipótese` `EDA`
 
Previsão de demanda por bicicletas compartilhadas em Londres, combinando testes estatísticos não paramétricos, tratamento de outliers e validação cruzada temporal para calibrar o modelo Prophet.
 
**Principais resultados:**https://github.com/Gleynner/DataScience/blob/main/README.md
- RMSE relativo de 17,53% (classificação "Boa capacidade preditiva"), após tratamento de outliers e tuning via cross-validation temporal
- Testes de Shapiro-Wilk e Mann-Whitney U confirmando diferença estatisticamente significativa entre estações do ano (p = 0,00048)
- Identificação de um pico de demanda atípico causado pela greve do metrô de Londres em 2015 — validado com fontes jornalísticas externas
- Modelo capturando sazonalidade diária, semanal e anual, com aplicação direta a planejamento operacional de mobilidade urbana


<br>

---

<a id="projetos-sql"></a>
### 🗄️ SQL

**📈 [Análise Estratégica de Vendas e Precificação - PostgreSQL](https://github.com/Gleynner/commercial_data_analysis-SQL)**

`PostgreSQL` `CTEs` `Joins` `Subqueries`

Análise de dados comerciais com foco em desempenho de vendas, precificação e análise competitiva, transformando dados transacionais em indicadores estratégicos.

**Principais resultados:**
- Consultas relacionais para avaliação de indicadores de vendas e comportamento de categorias
- Identificação de inconsistências cadastrais com potencial impacto financeiro
- Uso de agregações, joins, subqueries e CTEs para geração de informação analítica

<br>
  
**🛒 [Análise de Dados Comerciais - SQL Server](https://github.com/Gleynner/SQL_server_Project)** 

`SQL Server` `Modelagem Relacional` `CTEs`

Exploração de dados transacionais integrando pedidos, produtos, clientes e métodos de pagamento para geração de indicadores de negócio.

Principais resultados:

Análise de comportamento de vendas, sazonalidade e preferências de pagamento
Consultas analíticas com lógica condicional para responder perguntas de negócio

<br>

---

<a id="projetos-r"></a>
### 📉 R

**🧑‍🤝‍🧑 [Análise de personalidade de clientes](https://github.com/Gleynner/AnaliseDePersonalidadeDeClientesComR/blob/main/README.md)**

`R` `Segmentação` `Estatística`

Estudo de perfis de clientes a partir de traços de personalidade, aplicando técnicas estatísticas para segmentação e geração de insights de comportamento.

<br>

**📐 [Análise de Variância - ANOVA](https://github.com/Gleynner/Analise_de_variancia-ANOVA/blob/main/README.md)**

`R` `ANOVA` `Testes de Hipótese`

Aplicação de testes estatísticos (ANOVA) para comparação de médias entre grupos, com interpretação dos resultados e validação das premissas do teste.

<br>
---

<a id="-vamos-conversar"></a>
### 📬 Vamos conversar?

Estou aberto(a) a oportunidades em Ciência de Dados, Analytics e áreas correlatas. Se você quer discutir algum desses projetos, trocar uma ideia sobre dados ou tem uma oportunidade que combine com meu perfil, me chame!

- 💼 LinkedIn: [in/gleynnerghiotto](https://linkedin.com/in/gleynnerghiotto)
- ✉️ Email: [gleynnerghiotto@outlook.com](mailto:gleynnerghiotto@outlook.com)
- 🔗 Perfil GitHub: [github.com/Gleynner](https://github.com/Gleynner)

