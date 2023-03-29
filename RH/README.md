# Dashboard de Análise de RH

## Funcionalidades

- Identificação do maior número de faltas entre os funcionários;
- Identificação da filial com o maior gasto em termos de despesas;
- Verificação da média de idade dos funcionários por conta da produtividade, para entender se o fator idade está influenciando nos resultados;
- Verificação da soma dos salários para entender o quanto estamos gastando em folha de pagamento.

## Indicadores

- Total de faltas;
- Faltas por  Departamento;
- Média de gastos por filial (em termos de salário);
- Salário por nome;
- Total de despesas por área;
- Funcionarios por gênero.

## Medidas
O dashboard de RH contém as seguintes medidas:

## Soma Salário

A medida "Soma Salário" é usada para calcular o total de salários pagos pela empresa. A fórmula da medida é:

- Soma Salário = SUM(FUNCIONARIOS[SALARIO])

## TotalFaltas

A medida "TotalFaltas" é usada para calcular o número total de faltas dos funcionários da empresa. A fórmula da medida é

- TotalFaltas = SUM(FUNCIONARIOS[QTDE FALTA])

## MédiaIdade

A medida "MédiaIdade" é usada para calcular a média de idade dos funcionários da empresa. A fórmula da medida é:

-  MédiaIdade = AVERAGE(FUNCIONARIOS[IDADE] )

## SomaContratação

A medida "SomaContratação" é usada para calcular o total de contratações feitas pela empresa. A fórmula da medida é:

- SomaContratação = SUM(FUNCIONARIOS[CONTRATACÕES FEITAS] )



## Tecnologias

- Power BI

## Instalação

Para acessar o dashboard, basta abrir o arquivo .pbix usando o Power BI

## Uso

O uso do dashboard é intuitivo e fácil de entender. Cada visualização é interativa e permite filtrar dados e visualizar informações de diferentes maneiras. Basta selecionar a visualização desejada e começar a explorar os dados.





## Link do Dashboard



- https://app.powerbi.com/view?r=eyJrIjoiZWJmNzJhZjItNjVkZS00ZDUzLWJhNDktYzIxN2Q2ZDc3YTIyIiwidCI6ImJkYzMxODdjLTliOWQtNDcwOC05MDYxLTcyYmZlMTZjOWI5MyJ9








![teste](https://github.com/luhcrodrigues/Projetos_PowerBi/blob/main/RH/RH.png)
