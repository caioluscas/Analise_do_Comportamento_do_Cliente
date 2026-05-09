# Projeto de Análise de Dados

## Visão Geral
Este projeto demonstra um fluxo completo de análise de dados, incluindo:
- carregamento de dados com Python,
- análise exploratória (EDA),
- limpeza e tratamento dos dados,
- consultas SQL,
- criação de dashboard no Power BI,
- geração de relatórios e insights.

O objetivo principal é transformar dados brutos em informações úteis para tomada de decisão.

---

## Dashboard

<p align="center">
  <img src="Painel de comportamento do usuario_page-0001.jpg" width="800">
</p>

---

## Ferramentas Utilizadas
- Python (Pandas, NumPy, Matplotlib)
- SQL (PostgreSQL / MySQL / SQL Server)
- Power BI
- Jupyter Notebook
- Gamma

---

## Etapas do Projeto

### 1. Carregamento dos Dados
```python
import pandas as pd

df = pd.read_csv("dados.csv")
```

### 2. Limpeza dos Dados
- Remoção de valores nulos
- Padronização
- Tratamento de inconsistências

```python
df.dropna()
```

### 3. Análise Exploratória (EDA)
- Identificação de padrões
- Geração de estatísticas
- Análise de tendências

```python
df.groupby("categoria").mean()
```

### 4. Consultas SQL
Utilização de SQL para filtros, agregações e cruzamento de dados.

```sql
SELECT cidade, COUNT(*)
FROM clientes
GROUP BY cidade;
```

### 5. Criação do Dashboard
Desenvolvimento de dashboard interativo no Power BI com:
- KPIs
- gráficos
- filtros
- indicadores estratégicos

---

## Resultados
O projeto permitiu:
- identificar padrões relevantes,
- gerar insights,
- melhorar a visualização dos dados,
- apoiar decisões baseadas em dados.

---

## Como Executar

Instalar dependências:

```bash
pip install pandas numpy matplotlib
```

Iniciar o Jupyter Notebook:

```bash
jupyter notebook
```

---

## Conceitos Trabalhados
- ETL
- Limpeza de Dados
- Análise Exploratória
- SQL
- Dashboards
- Visualização de Dados
- Geração de Insights
