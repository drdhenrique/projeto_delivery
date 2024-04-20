# Projeto de Análise com SQL/Python 

Nessa análise foi utilizado SQL, através da interface Python no VS Code (juntamente com a biblioteca DuckDB) para extrair informações de uma base de dados de deliveries disponível <a href = 'https://www.kaggle.com/datasets/nosbielcs/brazilian-delivery-center'> aqui</a>.

Os dados possuem um relacionamento ligeiramente complexo, como mostrado na imagem abaixo:
![Relacionamento entre os dados](https://github.com/drdhenrique/projeto_delivery/blob/main/database_relations.png)

## Perguntas de negócio

O objetivo desse projeto foi responder às quatro perguntas a seguir:

1. Numa ação de marketing, para atrair mais entregadores, vamos dar uma bonificação para os 20 entregadores que possuem maior distância percorrida ao todo. A bonificação vai variar de acordo com o tipo de profissional que ele é e o modelo que ele usa para se locomover (moto, bike, etc). Levante essas informações.
2. Além disso, o time de Pricing precisa ajustar os valores pagos aos entregadores. Para isso, eles precisam da distribuição da distância média percorrida pelos motoqueiros separada por estado, já que cada região terá seu preço.
3. Se a empresa tem um gasto fixo de 5 reais por entrega, recebe 15% do valor de cada entrega como receita e, do total do lucro, distribui 20% em forma de bônus para os 2 mil funcionários, quanto cada um irá receber no período contido no dataset?
4. Por fim, o CFO precisa de alguns indicadores de receita para apresentar para a diretoria executiva. Dentre esses indicadores, vocês precisarão levantar (1) a receita média e total separada por tipo (Food x Good), (2) A receita média e total por estado. Ou seja, são 4 tabelas ao todo.

Além dessas, também respondemos outros questionamentos interessantes sobre os dados, como por exemplo:

- Qual é a média de distância percorrida pelos entregadores em cada tipo de veículo?
- Qual é o hub com o maior número de entregas realizadas durante o mês de abril de 2021?
- Qual é o método de pagamento mais utilizado pelos clientes para fazer compras na plataforma?
- Qual é o total de receita gerada pela taxa de entrega durante o período de janeiro a abril de 2021?
- Qual é o canal de venda (channel_name) que gera o maior valor médio de pedido (order_amount)?
- Qual é o momento do dia em que mais pedidos são realizados na plataforma?

