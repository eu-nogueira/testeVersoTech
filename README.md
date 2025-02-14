Teste Técnico de Conhecimentos em SQL

Bem-vindo ao teste técnico de conhecimentos em SQL! A seguir, você encontrará cinco desafios onde precisará escrever consultas SQL. Utilize apenas as tabelas e dados presentes no arquivo de SQLs fornecido.
Instruções

Desafios: Resolva cada um dos desafios propostos escrevendo as queries SQL apropriadas.
Retorno Esperado: Certifique-se de que as consultas retornem os resultados esperados, incluindo os nomes das colunas especificados.
Validação: Após finalizar todas as consultas, valide suas respostas no compilador online de PostgreSQL: SQL Fiddle.
Entrega: Submeta suas consultas finais em um repositório próprio seu!
Desafios

Consulta de Vendedores: Escreva uma query para listar todos os vendedores ativos, mostrando as colunas id, nome, salario. Ordene o resultado pelo nome em ordem ascendente.
Retorno esperado:
id
nome
salario
2
Vendedor B
4000.00
4
Vendedor D
3800.00
1
Vendedor Z
3000.00

Funcionários com Salário Acima da Média: Escreva uma query para listar os funcionários que possuem um salário acima da média salarial de todos os funcionários. A consulta deve mostrar as colunas id, nome, e salario, ordenadas pelo salario em ordem descendente.
Retorno esperado:
id
nome
salario
5
Vendedor E
4200.00
2
Vendedor B
4000.00
4
Vendedor D
3800.00

Resumo por cliente: Escreva uma query para listar todos os clientes e o valor total de pedidos já transmitidos. A consulta deve retornar as colunas id, razao_social, total, ordenadas pelo total em ordem descendente.
Retorno esperado:
id
razao_social
total
4
Cliente D
530
3
Cliente C
430
2
Cliente B
350
1
Cliente A
250
5
Cliente E
0

Situação por pedido: Escreva uma query que retorne a situação atual de cada pedido da base. A consulta deve retornar as colunas id, valor, data e situacao. A situacao deve obedecer a seguinte regra:
Se possui data de cancelamento preenchido: CANCELADO
Se possui data de faturamento preenchido: FATURADO
Caso não possua data de cancelamento e nem faturamento: PENDENTE
Retorno esperado:
id
valor
data
situacao
1
120.00
2023-07-06
PENDENTE
2
130.00
2023-07-07
PENDENTE
3
170.00
2023-07-08
FATURADO
4
180.00
2023-07-09
CANCELADO
5
210.00
2023-07-10
PENDENTE
6
220.00
2023-07-11
FATURADO
7
260.00
2023-07-12
CANCELADO
8
270.00
2023-07-13
FATURADO

Produtos mais vendidos: Escreva uma query que retorne o produto mais vendido ( em quantidade ), incluindo o valor total vendido deste produto, quantidade de pedidos em que ele apareceu e para quantos clientes diferentes ele foi vendido. A consulta deve retornar as colunas id_produto, quantidade_vendida, total_vendido, clientes, pedidos. Caso haja empate em quantidade de vendas, utilizar o total vendido como critério de desempate.
Retorno esperado:
id_produto
quantidade_vendida
total_vendido
pedidos
clientes
2
12
220
3
2

Requisitos

Utilize apenas as tabelas e dados presentes no arquivo schema.sql.
Certifique-se de que os nomes das colunas no resultado sejam exatamente os especificados e retornados nos desafios.
Valide suas respostas utilizando o compilador online SQL Fiddle.
Boa sorte!
