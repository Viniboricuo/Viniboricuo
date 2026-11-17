# Vinicius Ribeiro Abel

**Analista de BI Pleno · Do pipeline de dados ao dashboard: decisões confiáveis.**

> BI Analyst in São Paulo building data pipelines (SQL Server, Python) and dimensional models behind Power BI dashboards and Flask apps.
> I make sure the numbers on the dashboard match the source, end to end.

## O que eu faço
- **Pipelines de dados:** cargas incrementais e transacionais em Python (SQLAlchemy) para SQL Server, sem duplicidade de registros.
- **Modelagem e performance:** modelagem dimensional (Star Schema), DAX e T-SQL otimizados para bases com milhões de linhas.
- **Dashboards e apps analíticos:** Power BI e aplicações web em Flask, com cada indicador validado contra o banco.

## Resultados
- Consultas T-SQL de **7 min → segundos**, reestruturando CTEs encadeadas em tabelas temporárias por etapas
- Modelo Power BI de **1,1 GB → 766 MB (-31%)** após diagnóstico com VertiPaq Analyzer, sem alterar nenhuma medida
- Modelos até **58% menores** com reestruturação em Star Schema
- Automação em Python que eliminou **mais de 1h/dia** de trabalho manual
- Manual de **governança de BI**: nomenclatura, padrões de dashboard e catálogo de tabelas

## Stack
| Área | Ferramentas |
|---|---|
| Dados | SQL Server · T-SQL (CTEs, window functions, otimização) |
| Python | Pandas · SQLAlchemy · pyodbc · Flask |
| BI | Power BI · DAX · Power Query (M) · VertiPaq Analyzer · Tabular Object Model |
| Modelagem | Star Schema · modelagem dimensional · ETL incremental |
| Outros | Git · SAP · IA generativa como par de programação |

## Projetos em destaque
Painéis de varejo reconstruídos do zero para uma marca fictícia (Demo Retail Co.), com dados sintéticos gerados por semente. Todos rodam no navegador, sem servidor.

| Projeto | O que mostra | Demo |
|---|---|---|
| [inventory-flow-analytics](https://github.com/Viniboricuo/inventory-flow-analytics) | Star Schema de estoque (2 fatos, 3 dimensões), aging, cobertura, giro e **validação contra a origem** com regras de qualidade | [abrir](https://viniboricuo.github.io/inventory-flow-analytics/) |
| [sellin-sellout-analytics](https://github.com/Viniboricuo/sellin-sellout-analytics) | Sell-in × sell-out de lançamentos por canal, sell-through 4S, filtros em cascata, exportação para Excel e modo TV | [abrir](https://viniboricuo.github.io/sellin-sellout-analytics/) |
| [customer-planning-rfv](https://github.com/Viniboricuo/customer-planning-rfv) | RFV por quintis, k-means, curva ABC, recorrência, safras e funil de CRM | [abrir](https://viniboricuo.github.io/customer-planning-rfv/) |
| [powerbi-customer-base-monitoring](https://github.com/Viniboricuo/powerbi-customer-base-monitoring) | Dashboard Power BI com Star Schema, DAX de variação e rankings dinâmicos | — |

## Estudando agora
AWS · Databricks · certificação PL-300 (Power BI Data Analyst)

## Contato
[LinkedIn](https://www.linkedin.com/in/viniciusribeiroabel)
