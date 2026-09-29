# 📊 Pipeline de Dados — Portfólio de Engenheiro de Dados

Projeto ponta-a-ponta de engenharia de dados, construído aos poucos, alimentado pelas práticas e desafios das certificações que estou cursando em paralelo (Google Skills, Rocketseat). Cada etapa nasce de uma trilha de estudo real, versionada aqui desde a primeira linha.

## 🎯 Objetivo

Construir um pipeline de dados completo seguindo a **Arquitetura Medallion** (Bronze → Silver → Gold), do zero até um dashboard final:

```
[Fonte de dado público] -> [Bronze: ingestão bruta] -> [Silver: limpeza/tratamento] -> [Gold: modelagem/agregação] -> [Dashboard/saída]
```

## 🗂️ Estrutura do repositório

```
├── bronze/     # Ingestão de dado público, ainda cru
├── silver/     # Dados limpos e tratados
├── gold/       # Dados modelados/agregados, prontos para análise
├── docs/       # Documentação do projeto (decisões, diagramas, notas)
└── README.md
```

## 🚧 Status atual

| Estágio                           | Alimentado por                     | Status          |
| --------------------------------- | ---------------------------------- | --------------- |
| Repo + README + versionamento     | Git (módulo "Primeiros passos")    | ✅ Concluído    |
| Ingestão de dado público → Bronze | Python/Pandas + Coletando os Dados | ⬜ Não iniciado |
| Limpeza/transformação → Silver    | Tratando os Dados + SQL            | ⬜ Não iniciado |
| Modelagem/agregação → Gold        | BigQuery (Data Engineer/ADP)       | ⬜ Não iniciado |
| Dashboard/saída                   | Looker Studio / Power BI           | ⬜ Não iniciado |

## 🛠️ Stack prevista

- **Versionamento:** Git/GitHub
- **Linguagem:** Python (Pandas, Numpy)
- **Banco de dados / SQL:** PostgreSQL
- **Cloud/Data Warehouse:** Google Cloud Platform (BigQuery)
- **Visualização:** Looker Studio e/ou Power BI

## 📚 Contexto de estudo

Este repositório acompanha minha jornada como Analista de Dados Júnior migrando para Engenharia de Dados, estudando em paralelo:

- Google Skills — Associate Data Practitioner Certification
- Google Skills — Professional Data Engineer Certification
- Rocketseat — Formação Data Analytics
- Rocketseat — Banco de Dados (PostgreSQL)
- Rocketseat — Git e GitHub

Exercícios e práticas soltas dos cursos ficam no repositório [`sandbox-dados`](https://github.com/KaueACLima/sandbox-dados) — este aqui é só a entrega final de cada etapa.

## 📝 Convenção de commits

```
docs(<estagio>): descrição - [detalhe]
feat(<estagio>): descrição - [detalhe]
```

---

_Última atualização: 29/09/2026 — repositório criado, estrutura inicial Bronze/Silver/Gold definida._
