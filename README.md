# Acompanhamento Financeiro

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power%20Query-107C41?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 🎯 Sobre o Projeto

Este projeto tem como objetivo acompanhar e analisar os resultados financeiros de uma organização a partir da Demonstração do Resultado do Exercício (DRE).

O dashboard em Power BI permite monitorar:

- Receita e Despesas Operacionais

- Margem de Contribuição

- Distribuição por categorias de receita e despesa

- Evolução mensal dos resultados

- Saldo consolidado por contas bancárias

Com isso, gestores e analistas conseguem tomar decisões estratégicas mais rápidas e fundamentadas.

## 🖼️ Visualizações do Dashboard

### Visão Geral

![Visão Geral](/reports/exports/images/slide1.png)

### Análise Detalhada

![Detalhamento](/reports/exports/images/slide2.png)

## 🌐 Dashboard Online

[![Acessar Dashboard Power BI](https://img.shields.io/badge/🔗%20Acessar%20Dashboard%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMDUwNzI2MmMtMjZlYS00NGE0LTlmZjYtNmY1NzBjNWY5MTdmIiwidCI6IjdlYmVmODBjLTEwMjctNDEyOS1iNDg0LWNjZjJiZDNmZDU4ZiJ9&pageName=ReportSection)

## 💡 Insights e Benefícios

- Monitoramento do fluxo operacional e da margem de contribuição

- Análise comparativa Receita x Despesa em diferentes períodos

- Controle do saldo bancário consolidado

- Suporte a decisões financeiras e estratégicas

## 📁 Estrutura do Projeto

```text
📁 acompanhamento_financeiro_powerbi/
├── 📁 data/                              
│   └── raw/                                               # Dados brutos       
│      └── bd_movimentos.xlsx                             
│ 
├── 📁 reports/                                           # Relatórios e análises
│   ├── powerbi/                                         
│   │   └── link_dashboard_financeiro_v1.txt         
│   └── exports/                                           # Arquivos exportados
│       └── images/
│           ├── slide1.png                                 # Capturas de Tela
│           └── slide2.png                      
│
└── 📄 README.md                                           # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas

- **Excel**: Fonte de dados estruturada (bd_movimentos.xlsx)
- **Power Query**: ETL (Extract, Transform, Load) e transformação de dados
- **Power BI Desktop**: Desenvolvimento do dashboard e modelagem de dados
- **DAX (Data Analysis Expressions)**: Criação de medidas calculadas e KPIs
- **Power BI Service**: Publicação e compartilhamento online do dashboard

## ⚙️ Processo de Desenvolvimento

1. **Coleta de dados**: consolidação dos movimentos financeiros no Excel

2. **Transformação com Power Query**: padronização, limpeza e estruturação dos dados

3. **Modelagem no Power BI**: relacionamento de tabelas, criação de medidas DAX e hierarquias

4. **Construção do Dashboard**: desenvolvimento de páginas analíticas (Visão Geral e Detalhamento)

5. **Publicação no Power BI Service**: disponibilização para acesso web
