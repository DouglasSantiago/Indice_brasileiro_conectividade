# Índice Brasileiro de Conectividade (IBC) – Dashboard em Power BI

Este repositório contém um painel interativo desenvolvido em **Power BI** para análise do **Índice Brasileiro de Conectividade (IBC)**, utilizando dados públicos da **Anatel**, disponibilizados por meio da plataforma **Base dos Dados**.

**Fonte dos dados:**  
https://basedosdados.org/dataset/ad45c5dc-ecc6-43db-ae2c-45d71939e7c5?table=c7166975-1f44-4c54-852a-80a3d22004a4

---

## 📌 Objetivo

O dashboard foi criado com o propósito de:

- Consolidar indicadores de conectividade em nível estadual e municipal.
- Avaliar a infraestrutura de acesso à internet no Brasil (móvel e fixa).
- Identificar desigualdades regionais no acesso à rede.
- Apoiar decisões estratégicas em políticas públicas, investimentos e inclusão digital.

---

## 📊 Visões do Dashboard

### 1. Indicadores Principais (KPIs)

O painel apresenta três métricas centrais:

- **% de moradores com acesso 4G e 5G**  
  Representa a parcela da população com cobertura de rede móvel de alta velocidade.

- **Densidade de acessos de Serviços de Comunicação Multimídia (SCM)**  
  Indica a quantidade de acessos de banda larga fixa por habitante.

- **Densidade de acessos de Serviço Móvel Pessoal (SMP)**  
  Mostra a relação entre linhas móveis ativas e população.

Esses KPIs oferecem uma visão macro da conectividade nacional.

---

### 2. Ranking do IBC por Unidade Federativa (UF)

Visual de barras horizontais que classifica os estados brasileiros com base na **média do IBC**.

Permite:

- Comparar rapidamente o desempenho de cada estado.
- Identificar regiões com melhor ou pior infraestrutura.
- Evidenciar disparidades históricas entre regiões.

---

### 3. Mapa Temático: Média do IBC por Estado

Mapa coroplético destacando a intensidade de conectividade em cada estado.

- Cores mais fortes representam maior conectividade.
- Útil para análises territoriais e comunicação visual de tendências regionais.
- Baseado em limites territoriais oficiais.

---

### 4. Cobertura por Fibra Óptica

Gráfico de setores classificando a situação dos municípios em:

- Totalmente cobertos  
- Parcialmente cobertos  
- Sem cobertura

Este visual evidencia o nível de infraestrutura de fibra e ajuda a identificar gaps estruturais do Brasil.

---

### 5. Adesão de Estações Rádio Base (ERBs) por Estado

Gráfico combinando área preenchida e marcadores, apresentando:

- Quantidade de ERBs instaladas por UF
- Comparação da infraestrutura móvel entre regiões
- Tendências e discrepâncias de implantação

---

## 🗂️ Estrutura de Dados Utilizada

O modelo de dados do dashboard utiliza:

- **id_municipio (IBGE – 7 dígitos)** como chave primária territorial  
- Indicadores de infraestrutura, densidade, cobertura e conectividade  
- Tabelas auxiliares de municípios, estados, e atributos territoriais  

As métricas são processadas em DAX e modeladas de forma relacional.

---

## 🧰 Tecnologias e Ferramentas

- **Power BI Desktop**
- **DAX** para criação de medidas e cálculos estatísticos
- **Power Query (M)** para transformação e limpeza dos dados
- **Bing Maps** / **Shape Map** para visualização geoespacial
- Fonte de dados: **Base dos Dados – Anatel**

---

## 📄 Licença

Este projeto utiliza dados públicos e está sob licença livre. Consulte a política de reutilização da Base dos Dados e da Anatel para fins específicos.

---

## 📬 Contato

Em caso de dúvidas ou sugestões:

**Doulglas Moreira Santiago**  
*Data Analyst – Dashboard & Data Visualization*

---

