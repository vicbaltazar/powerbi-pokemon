## Power BI – Pokémon Pokédex Dashboard
Dashboard interativo em Power BI construído a partir de uma Pokédex personalizada, com foco em análise de estatísticas base, tipos, gerações, regiões e Pokémon lendários.

Visão geral
Explora Pokémon por tipo, geração, categoria (Comum, Inicial, Evoluído, Lendário) e região.

Destaque para KPIs como total de Pokémon, quantidade de lendários, quantidade de dual type e média de status totais.

Layout inspirado em dashboards oficiais, com paleta de cores temática de Pokémon.

## Dados utilizados
A base foi montada manualmente em Excel e importada para o Power BI:

Campos principais:

Nome, Tipo1, Tipo2, Geração, Região

HP, Ataque, Defesa, SpAtk, SpDef, Velocidade

Categoria (Comum, Inicial, Evoluído, Lendário)

Coluna calculada no Power BI:

Total = soma de todos os atributos de status de cada Pokémon.

## Principais visuais do relatório
- Cartões (KPIs):

Total Pokémon

Total Legendary

Dual Type

Média de Total

- Gráficos:

Dispersão: Ataque vs Defesa

Rosca: proporção de Pokémon lendários

Colunas: Total de Pokémon por Geração

Colunas: Total de Pokémon por Tipo1

Colunas: Média do Total por Tipo1

- Segmentadores:

Legendary (True/False)

Geração

Região

## Como abrir o projeto
Baixe o arquivo .pbix deste repositório.

Abra o arquivo no Power BI Desktop (versão mais recente recomendada).

Navegue pelos filtros e visuais para explorar a Pokédex.

## Tecnologias
Power BI Desktop

Excel (preparação da base de dados)

GitHub para versionamento e portfólio
