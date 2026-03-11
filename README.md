# 📊 Relatório de Processamento de Dados - Power BI & Excel

Este repositório contém o projeto de ETL (Extração, Transformação e Carga) e modelagem de dados realizado como parte do desafio de Business Intelligence. O foco foi a limpeza técnica de um dataset financeiro e a preparação para visualização de indicadores.

---

## 🛠️ Tecnologias Utilizadas

*   **Excel Web**: Utilizado para o tratamento inicial dos dados, garantindo a execução do projeto em ambiente cloud.
*   **Power BI / Power Query**: Ferramenta principal para a limpeza profunda, tipagem de dados e modelagem.
*   **Markdown**: Linguagem de marcação utilizada para esta documentação técnica.

---

## 🚀 Etapas do Processo de ETL

O processo foi dividido em fases lógicas para garantir a integridade dos dados:

### 1. Conexão e Limpeza Inicial (Fase 0 e A)
*   **Importação**: O dataset bruto foi conectado ao Power Query.
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

Para facilitar a navegação pelos resultados do projeto, utilize os links abaixo:

*   [📄 **Dataset Processado**](./caminho/para/seu/arquivo/excel) - Link para a base de dados após o tratamento.
*   [🖼️ **Galeria de Capturas**](./caminho/para/pasta/de/imagens) - Screenshots do dashboard e das etapas no Power Query.
*   [🎥 **Demonstração em Vídeo**](./link/do/seu/video) - Tour funcional pelas interações do relatório.

---

## 💻 Notas de Desenvolvimento

Devido a especificidades do ambiente de trabalho, o fluxo de desenvolvimento foi adaptado para o **Excel Web**. Esta abordagem demonstra a capacidade de entrega de resultados profissionais utilizando ferramentas baseadas em nuvem, superando limitações de instalação de software local.

---
**Desenvolvido por seu portfólio de Dados.**
