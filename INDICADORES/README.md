# Dashboard de Indicadores

## Funcionalidades

- Identificação do valores de vendas;
- Identificação de valores de compras por clientes;
- Verificação de valores de vendas por Ano.

## Indicadores

- Quantidade de Clientes;
- Quantidade de Produtos Vendidos;
- Faturamento;
- Faturamento por Indicador;

## Medidas
O dashboard de INDICADORES contém as seguintes medidas:


## Quantidade de Produtos Vendidos

A quantidade de produtos vendidos é de

`{{SUM(INDICADORES[QUANTIDADE VENDIDA])}}`.

## Quantidade de Clientes

O número de clientes únicos que realizaram compras é de

`{{DISTINCTCOUNT(INDICADORES[CODIGO])}}`.

## Faturamento

O faturamento total  é de

`{{SUM(INDICADORES[Total Venda])}}`.

## Tecnologias

- Power BI

## Instalação

Para acessar o dashboard, basta abrir o arquivo .pbix usando o Power BI

## Uso

O uso do dashboard é intuitivo e fácil de entender. Cada visualização é interativa e permite filtrar dados e visualizar informações de diferentes maneiras. Basta selecionar a visualização desejada e começar a explorar os dados.


<iframe title="Análise_Rh" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZWJmNzJhZjItNjVkZS00ZDUzLWJhNDktYzIxN2Q2ZDc3YTIyIiwidCI6ImJkYzMxODdjLTliOWQtNDcwOC05MDYxLTcyYmZlMTZjOWI5MyJ9" frameborder="0" allowFullScreen="true"></iframe>





![teste](https://github.com/luhcrodrigues/Projetos_PowerBi/blob/main/INDICADORES/imagemdash.png)
