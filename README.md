# Dashboard de Contas a Receber | Accounts Receivable

## Sobre o Projeto

Dashboard desenvolvido em **Power BI** para monitoramento e gestão de contas a receber, com foco no acompanhamento de valores em aberto, recebimentos realizados e títulos vencidos. 
A solução permite analisar o desempenho financeiro por período, acompanhar metas de recebimento e identificar pendências que exigem atenção, contribuindo para uma gestão mais eficiente das cobranças e do fluxo de caixa.

## Dashboard

<img width="900" height="500" alt="Dash Amarelo" src="https://github.com/user-attachments/assets/eb757a20-9aa8-4084-ae75-77d9d261190c" />


## 📊 Principais Indicadores e Funcionalidades

* **Contas a Receber:** visão consolidada dos valores a receber e do saldo em aberto.
* **Recebimentos Acumulados (YTD):** acompanhamento dos valores recebidos no ano em relação às metas estabelecidas.
* **Recebimentos Mensais (MTD):** monitoramento dos valores previstos e realizados no mês.
* **DSO (Days Sales Outstanding):** indicador do prazo médio de recebimento das vendas.
* **Contas Vencidas:** acompanhamento dos valores em atraso e identificação de possíveis riscos de inadimplência.
* **Aging de Recebíveis:** classificação dos valores em aberto por faixa de vencimento, facilitando a priorização das ações de cobrança.
* **Análise Histórica:** visualização da evolução dos valores a receber ao longo do tempo e comparação dos montantes por ano e categoria de negócio.

## Tecnologias Utilizadas

| Tecnologia      | Aplicação                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------ |
| **Power BI**    | Desenvolvimento do dashboard, visualização dos indicadores e análise interativa dos dados. |
| **SQL**         | Consultas diretas ao banco de dados do ERP para extração das informações financeiras.      |
| **Power Query** | Limpeza, transformação e preparação dos dados para análise.                                |
| **ERP**         | Sistema de origem dos dados financeiros utilizados no dashboard.                           |

## Desenvolvimento e Tratamento de Dados

Os dados financeiros são extraídos diretamente do banco de dados do ERP por meio de consultas SQL. Em seguida, são tratados e preparados no Power Query para garantir sua organização e adequação ao modelo analítico do Power BI.

Após essa etapa, os dados são utilizados na construção dos indicadores e das visualizações, permitindo uma análise consolidada dos recebíveis e do desempenho financeiro.

## Objetivos e Benefícios

* Centralizar as informações de contas a receber em uma única interface.
* Monitorar recebimentos realizados e metas financeiras.
* Identificar valores vencidos e pendências de cobrança.
* Analisar a distribuição dos recebíveis por faixa de atraso.
* Acompanhar tendências históricas e indicadores financeiros.
* Apoiar a tomada de decisões baseada em dados.
* Contribuir para o controle da inadimplência e a previsibilidade do fluxo de caixa.

## Resumo do Projeto

O projeto demonstra a aplicação de **Business Intelligence na gestão financeira**, integrando extração de dados via SQL, transformação com Power Query e visualização interativa no Power BI para transformar dados operacionais do ERP em informações relevantes para a tomada de decisões.

**Tecnologias:** Power BI · SQL · Power Query · ERP

# Dashboard de Disponibilidade das Linhas de Produção

## Sobre o Projeto

Dashboard desenvolvido em **Power BI** para monitoramento da disponibilidade e da eficiência operacional das linhas de produção, com foco na análise de indicadores de manutenção e confiabilidade dos equipamentos.

A solução consolida os registros de chamados de manutenção provenientes do Jotform Apps, extraídos por meio de sua API pública, permitindo acompanhar o tempo médio de reparo (MTTR), o tempo médio entre falhas (MTBF) e a disponibilidade operacional das linhas de produção.

O dashboard oferece uma visão consolidada do desempenho operacional, auxiliando na identificação de indisponibilidades, na análise de ocorrências e no acompanhamento dos indicadores de manutenção ao longo do tempo.

## Dashboard

<img width="900" height="517" alt="media-disponibilidade" src="https://github.com/user-attachments/assets/da240d4e-515d-4191-ad07-7f3ff15cab5f" />

## 📊 Principais Indicadores e Funcionalidades

* **Disponibilidade Operacional:** acompanhamento do percentual de tempo em que as linhas de produção permanecem disponíveis para operação.
* **MTTR (Mean Time to Repair):** cálculo do tempo médio necessário para reparar os equipamentos após uma falha.
* **MTBF (Mean Time Between Failures):** cálculo do tempo médio de operação entre falhas, permitindo avaliar a confiabilidade dos equipamentos.
* **Tempo de Reparo:** monitoramento do tempo acumulado de indisponibilidade associado aos chamados de manutenção.
* **Análise por Linha de Produção:** comparação dos indicadores de disponibilidade e manutenção entre diferentes linhas e equipamentos.
* **Análise Temporal:** acompanhamento da evolução dos indicadores por período, facilitando a identificação de tendências e oportunidades de melhoria.

## Tecnologias Utilizadas

| Tecnologia           | Aplicação                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------- |
| **Power BI**         | Desenvolvimento do dashboard, criação de indicadores e visualização interativa dos dados. |
| **DAX**              | Desenvolvimento de medidas e cálculos para MTTR, MTBF e disponibilidade operacional.      |
| **Power Query**      | Tratamento, limpeza e transformação dos dados recebidos da API.                           |
| **Jotform Apps API** | Integração e extração dos registros de manutenção e chamados.                             |

## Integração e Tratamento de Dados

Os dados são extraídos diretamente do **Jotform Apps por meio de sua API pública** e posteriormente tratados no Power Query para adequação ao modelo analítico.

As informações são utilizadas na construção de medidas e indicadores no Power BI, permitindo calcular métricas de manutenção e consolidar os resultados por linha de produção e período de análise.

A utilização dessa integração reduz a necessidade de consolidação manual dos registros e facilita a análise centralizada das informações operacionais.

## Objetivos e Benefícios

* Monitorar a disponibilidade das linhas de produção.
* Avaliar a confiabilidade dos equipamentos por meio do MTBF.
* Acompanhar o tempo médio de reparo por meio do MTTR.
* Identificar períodos de maior indisponibilidade operacional.
* Comparar o desempenho entre linhas de produção.
* Apoiar decisões relacionadas à manutenção e à melhoria contínua.
* Transformar registros operacionais em indicadores para análise de desempenho.

## Resumo do Projeto

O projeto demonstra a aplicação de **Business Intelligence na manutenção industrial**, integrando dados operacionais via API, transformando registros de chamados em indicadores de confiabilidade e disponibilidade e disponibilizando informações estratégicas para apoiar a gestão da manutenção e a eficiência das linhas de produção.

**Tecnologias:** Power BI · DAX · Power Query · Jotform Apps API

# Daily Management Marketing Lead Time

## 📊 Principais Indicadores e Funcionalidades
Este dashboard foi desenvolvido para monitorar, em tempo real, o desempenho operacional do processo de qualificação de leads pelo time de Marketing. A solução permite acompanhar o tempo de maturação dos leads (Lead Time), identificar oportunidades com baixa interação e analisar a eficiência da conversão de leads em MQLs (Marketing Qualified Leads).

##  Preview

<img width="800" height="456" alt="Marketing-dashboard" src="https://github.com/user-attachments/assets/f6a701c4-5512-4d85-a25b-1a65c1390878" />


## Objetivo
Fornecer uma visão consolidada do funil de qualificação, auxiliando gestores e analistas na identificação de gargalos, acompanhamento da produtividade da equipe e redução do tempo necessário para a evolução dos leads até as próximas etapas do processo comercial.

##  Principais Indicadores
- Lead Time médio dos MQLs
- Volume total de MQLs enviados ao CRM
- Leads criados nas últimas 24 horas
- Taxa de conversão de Marketing para CRM
- Quantidade de leads em processo de esfriamento
- Distribuição de leads por faixa de inatividade
- Performance dos usuários responsáveis pelo atendimento

##  Principais Análises
- Monitoramento em tempo real dos leads qualificados pelo Marketing.
- Identificação de MQLs sem interação e com risco de perda.
- Análise do tempo de permanência dos leads em cada etapa do funil.
- Acompanhamento da eficiência operacional por usuário.
- Priorização de ações para recuperação de oportunidades estagnadas.
- Avaliação da qualidade e velocidade da passagem de leads para o CRM.

##  Insights de Negócio
O dashboard permite identificar rapidamente gargalos no processo de qualificação e distribuição de leads, reduzindo o tempo de resposta das equipes e aumentando as chances de conversão. A visualização dos leads "esfriando" possibilita ações preventivas para evitar a perda de oportunidades e melhorar a eficiência do funil de vendas.

## Tecnologias Utilizadas

| Tecnologia             | Aplicação                                                                                 |
| ---------------------- | ---------------------------------------------------------------------------------------   |
| **Power BI**           | Desenvolvimento do dashboard, criação de indicadores e visualização interativa dos dados. |
| **DAX**                | Desenvolvimento de medidas e cálculos para MTTR, MTBF e disponibilidade operacional.      |
| **Integração RD CRM ** | Integração e extração dos registros de manutenção e chamados.                             |


## Resultado Esperado
Aumentar a eficiência do processo de gestão de leads, reduzir o Lead Time médio dos MQLs e melhorar a conversão entre Marketing e Vendas por meio do monitoramento contínuo de indicadores críticos.

