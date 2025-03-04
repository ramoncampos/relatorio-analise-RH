# Análise de RH no Power BI

## Visão Geral do Projeto
Este projeto teve como objetivo construir um relatório abrangente de análise de RH para a equipe de RH da Orion Tech, utilizando o Power BI. O relatório auxilia no acompanhamento de métricas-chave de RH e fatores que impactam a rotatividade de funcionários.

## Metas e Objetivos
- **Meta Principal:** Monitorar métricas-chave de RH relacionadas aos funcionários.
- **Meta Secundária:** Compreender quais fatores impactam a rotatividade de funcionários.

## Escopo do Trabalho
Utilizando a abordagem do modelo Kimball, trabalhei com fatos e dimensões para construir um modelo de dados. Foi adicionada uma tabela de dimensão de data, seguida pela análise dos dados.

## Público-Alvo
Equipe de RH da Orion Tech

## Fontes de Dados
- `Employee.csv`
- `EducationLevel.csv`
- `PerformanceRating.csv`
- `RatingLevel.csv`
- `SatisfiedLevel.csv`

O conjunto de dados inclui uma tabela fato que armazena as avaliações de desempenho e cinco tabelas de dimensão: Employee, EducationLevel, RatingLevel, SatisfiedLevel e Date. O modelo de dados final segue um esquema snowflake.

## Métricas e KPIs
As principais métricas e KPIs utilizados para medir o sucesso incluem:
- Taxa de rotatividade
- Demografia dos funcionários
- Avaliações de desempenho
- Distribuição por cargo
- Métricas departamentais

## Principais Insights

![Visão Geral da Análise de RH](https://github.com/krystalbrantley/hr_analytics_report/blob/main/HR%20Analytics%20Overview.png?raw=true)

### Taxa de Rotatividade
- **Taxa geral de rotatividade:** 16,1%
- **Departamento e cargo com maior taxa de rotatividade:** Vendas e Representante de Vendas (39,8%)
- **Taxa de rotatividade de funcionários que viajam com frequência:** 24,9%

### Crescimento de Funcionários
- O maior crescimento na contratação de novos funcionários ocorreu no 1º trimestre de 2022, com 130 novas contratações.

### Distribuição por Departamento
- Mais da metade dos funcionários ativos trabalham no departamento de tecnologia.
- Cargos mais comuns: Engenheiro de Software e Cientista de Dados.

### Demografia

![Demografia da Análise de RH](https://github.com/krystalbrantley/hr_analytics_report/blob/main/HR%20Analytics%20Demo.png?raw=true)
- A maioria dos funcionários tem entre 20 e 29 anos.
- Funcionários que se identificam como brancos possuem o maior salário médio.
- Funcionários que se identificam como multirraciais têm o menor salário médio (US$ 106K).
- Mulheres representam apenas 2,7% da organização.
- A classificação gerencial e a autoavaliação de desempenho muitas vezes não estão alinhadas.

![Rastreamento de Desempenho na Análise de RH](https://github.com/krystalbrantley/hr_analytics_report/blob/main/HR%20Analytics%20Performance.png?raw=true)

![Rotatividade na Análise de RH](https://github.com/krystalbrantley/hr_analytics_report/blob/main/HR%20Analytics%20Attrition.png?raw=true)

## Recomendações
1. **Apoiar o Crescimento dos Funcionários:**
   - Organizar reuniões individuais para discutir necessidades e criar planos de melhoria.
   - Implementar programas regulares de treinamento e desenvolvimento para aprimorar as habilidades dos funcionários.

2. **Revisar Políticas de Viagem:**
   - Realizar pesquisas com os funcionários para entender suas percepções sobre a frequência de viagens e ajustar as políticas conforme necessário.

3. **Aprimorar Estratégias de Contratação:**
   - Focar na diversidade na contratação para aumentar a representatividade de mulheres e outros grupos sub-representados na organização.
   - Melhorar os processos de integração para garantir que novos funcionários sejam bem recebidos e apoiados desde o início.

4. **Monitorar e Ajustar a Remuneração:**
   - Revisar e ajustar regularmente os salários para garantir competitividade e equidade.

## Conclusão
A equipe de RH da Orion Tech agora pode navegar facilmente pelas principais métricas relacionadas aos funcionários da empresa, permitindo decisões mais informadas sobre contratação, monitoramento de diversidade e inclusão, além do acompanhamento de desempenho e rotatividade.

## Como Executar o Projeto

1. **Clonar o repositório:**
    ```bash
    git clone https://github.com/ramoncampos/relatorio-analise-RH
    cd ./relatorio-analise-RH
    ```

2. **Abrir o Relatório no Power BI:**
    - Abra o arquivo `Relatorio Analise RH.pbix` no Power BI Desktop.
    - Revise e interaja com os dashboards para explorar a análise.

3. **Revisar a Análise e os Insights:**
    - Examine as visualizações e os insights apresentados no relatório do Power BI.
    - Considere as recomendações e como elas podem ser aplicadas para melhorar as métricas de RH.


