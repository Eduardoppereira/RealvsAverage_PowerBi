# Dashboard de Análise Real vs Average

## Introdução
O objetivo deste dashboard é fornecer uma análise abrangente e interativa dos dados, utilizando diversas visualizações e métricas essenciais.

**Nota:** Este projeto foi concebido como um desafio para testar minha expertise em manipulação de dados, ETL, extração de diferentes fontes de dados, UX Design e storytelling. O desafio requer que a apresentação seja totalmente em inglês.

## Fontes de Dados
Integramos dados de fontes diversas para garantir uma visão completa, incluindo:
- **API Externa:** Utilizamos uma API externa, seguindo a documentação fornecida.
- **SharePoint:** Exploramos o SharePoint para incorporar informações críticas a partir de arquivos hospedados.
- **PostgreSQL:** Integrados dados de um servidor PostgreSQL para garantir consistência e precisão.

## Modelo de Dados
Ajustamos o modelo de dados inicial para garantir uma correlação adequada entre as diferentes fontes de dados, seguindo as melhores práticas para criar um modelo final robusto.

## Filtros Dinâmicos
Adicionamos filtros dinâmicos para proporcionar uma experiência personalizada ao usuário, incluindo data do pedido, nome do produto, tags do produto, nome da empresa, tipo de empresa, entre outros. Todos os filtros suportam pesquisa de texto, seleção de todos os itens e seleção de vários itens sem a necessidade de pressionar a tecla de controle.

## Indicadores-Chave de Desempenho (KPIs)
Destacamos quatro KPIs essenciais: valor total de pedidos, valor médio por pedido, média de pedidos por cliente e tempo médio de entrega. Implementamos formatação condicional para indicar se as vendas reais estão acima ou abaixo da meta para o período selecionado.

## Gráfico de Barras Dinâmico
Incluímos um gráfico de barras que permite a seleção de uma medida por vez (valor total de pedidos ou valor médio por pedido). A axis-X é dinâmica, podendo exibir dados por ano, trimestre ou mês do ano do pedido, além do tipo de empresa.

## Gráfico de Pizza
Implementamos um gráfico de pizza exibindo o valor total de pedidos por país, com a opção de selecionar os principais 5 clientes ou produtos.

## Tabela Detalhada
Desenvolvemos uma tabela detalhada que apresenta informações cruciais para cada empresa, incluindo nome, país, e-mail, telefone, gasto total, entre outros. Adicionamos formatação condicional para destacar informações relevantes.

Esta abordagem combinada proporciona uma análise holística, enriquecendo o dashboard e oferecendo insights significativos aos usuários finais.
