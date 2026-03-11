# 📊 Desafio de Projeto: Processamento de Dados com Power BI

Este repositório contém o projeto de ETL (Extração, Transformação e Carga) e modelagem de dados realizado como parte do desafio de Business Intelligence. O foco foi a limpeza técnica de um dataset financeiro e a preparação para visualização de indicadores.

---

## 🏛️ Contexto e Parcerias

*   **Plataforma de Ensino**: [DIO (Digital Innovation One)](https://www.dio.me/)
*   **Empresa Patrocinadora**: [Klabin](https://www.klabin.com.br/)
*   **Desenvolvedor**: [Frederico Cavalheiro]

---

## 🛠️ Tecnologias Utilizadas

*   **[Microsoft Power BI](https://powerbi.microsoft.com/)**: Ferramenta principal utilizada para a limpeza profunda, tipagem de dados e modelagem.
*   **[Power Query](https://learn.microsoft.com/pt-br/power-query/)**: Motor de transformação de dados utilizado para todo o saneamento da base.

---

## 🚀 Etapas do Processo de ETL

O processo foi executado integralmente no Power BI para garantir a integridade dos dados:

### 1. Conexão e Limpeza Inicial (Fase 0 e A)
*   **Importação**: O dataset bruto (arquivo Excel original) foi baixado e conectado diretamente ao Power Query.
*   **Saneamento**: Remoção de linhas duplicadas e tratamento de espaços em branco em colunas de texto.
*   **Tipagem de Dados**: Ajuste dos campos numéricos para o formato **Moeda (Currency)**, assegurando que os cálculos de faturamento e lucro sejam precisos.

### 2. Otimização da Estrutura (Fase B)
*   **Redução de Redundância**: Foram removidas manualmente as colunas `Month Number`, `Month Name` e `Year`. 
    > *Nota: Essa decisão foi tomada para otimizar o modelo, centralizando a inteligência temporal na tabela de calendário (`dCalendario`).*
*   **Modelagem**: Criação da tabela de dimensões de tempo para suporte a análises comparativas (YoY, MoM).

### 3. Encerramento e Cálculos (Fase C)
*   Criação de colunas customizadas e medidas para alimentar os KPIs do dashboard final.

---

## 📂 Entregáveis e Documentação

Abaixo estão os links individuais para cada componente do projeto. Você pode visualizar ou baixar cada arquivo separadamente:

### 📊 Projeto e Dados
*   [📈 **Arquivo Power BI (.pbix)**](./Relatorio_Financeiro.pbix) - Relatório completo com todas as medidas e visões.
*   [📄 **Dataset Original (Dados Brutos)**](./Financial%20Sample-dados%20brutos.xlsx) - Base em Excel utilizada como fonte.

### 🎥 Demonstração
*   [🎥 **Vídeo do Relatório Financeiro**](./Vídeo_Relatorio_Financeiro.mp4) - Tour funcional pelas interações do dashboard.

### 🖼️ Galeria de Capturas (Screenshots)
*   [🖼️ **Página 1: Sales Overview**](./dashboard-pagina-1-Sales%20Overview.png)
*   [🖼️ **Página 2: Profit Analysis**](./dashboard-pagina-2-Profit%20Analysis.png)
*   [🖼️ **Página 3: Geographic & Segment Insights**](./dashboard-pagina-3-Geographic%20&%20Segment%20Insights.png)

---

## 💻 Notas de Desenvolvimento

O fluxo de trabalho foi focado na eficiência do **Power Query**, demonstrando a capacidade de transformar dados brutos em informações estruturadas prontas para a tomada de decisão. Todo o tratamento foi feito localmente após o download da base original.

---
**Projeto desenvolvido para portfólio de análise de dados.**
