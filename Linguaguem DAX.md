![Linguagem-dax](https://github.com/Graziiele/Projeto/assets/114547875/94d5a50e-d303-4e0e-8f10-ce1d768081b4)


### Criação de algumas medidas dax

1. [Número de vendas]: contagem de vendas distintas;
2. [Volume vendido]: total da quantidade vendida;
3. [Vendas brutas]: total do valor vendido (quantidade x preço unitário);
4. [Custo total]: total do custo das vendas (quantidade x custo unitário);
5. [Preço médio de venda]: valor médio dos preços unitários;
6. [Desconto total]: total de desconto cedido nas vendas;
7. [Desconto total auditado]: o total de desconto, apenas para as promoções que estavam vigentes no momento da venda;
8. [Vendas líquidas]: vendas brutas sem os descontos (utilizar o [Desconto total] = medida f.);
9. [Média de vendas brutas diárias]: valor, em média, de vendas brutas por dia. Devem ser contabilizados apenas os dias em que houveram vendas.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

A medida DAX "Numero_Vendas" utiliza a função COUNTROWS para contar o número de linhas em uma tabela ou em uma expressão de tabela. Nesse caso, a medida está contando o número de linhas na tabela ou expressão de tabela chamada "fVendas".

![image](https://github.com/Graziiele/Projeto/assets/114547875/1dbb9d18-ca14-4018-a54f-793aaf31738e)

------------------------------------------------------------------------------------------------------------------------------------------------------------------

A medida DAX "Volume_Vendido" utiliza a função SUM para calcular a soma dos valores da coluna "Quantidade" na tabela "fVendas". A medida retorna o volume total vendido, que é a soma de todas as quantidades de venda registradas na tabela.

![image](https://github.com/Graziiele/Projeto/assets/114547875/d5d3529c-6d42-4c5d-ad82-5b560fb1aa78)

------------------------------------------------------------------------------------------------------------------------------------------------------------------

A medida DAX "Vendas_Brutas" utiliza a função SUMX para calcular a soma do resultado de uma expressão para cada linha da tabela "fVendas". A expressão é dada pela multiplicação da coluna "Quantidade" pela coluna "PrecoUnitario" da tabela "fVendas".

![image](https://github.com/Graziiele/Projeto/assets/114547875/77e71491-1f0b-4778-9e45-463fafa712cf)





		

		
