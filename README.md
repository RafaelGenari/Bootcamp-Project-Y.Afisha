# Performance Analysis and Marketing Optimization for Y.Afisha

## Project Description
This project was developed in the TripleTen course and simulates an internship in the analytical department of the fictitious company Y.Afisha. The goal is to optimize marketing expenses by analyzing data to understand user behavior, purchasing patterns, customer value, and the time needed to recover costs.

## Data Description
- **Visits**: Website access logs (user ID, device, ad source, and session times).
- **Orders**: Orders placed (user ID, date, and revenue generated).
- **Costs**: Marketing expenses (ad source, date, and costs).

## Approach
- **Exploratory Data Analysis**: Understanding user behavior patterns.
- **LTV and ROI Calculation**: Determining customer value and expense efficiency.
- **Payback Calculation**: Estimating time to recover costs.

## Tools
- **Python**: Data analysis and visualization.
- **Pandas, Matplotlib, and Seaborn**: Data manipulation and graph creation.
- **Jupyter Notebook**: Organizing the analysis.

## Conclusion

### Products
- There is a consistent trend of declining access during weekends, with a significant peak in week 47.
- The average number of sessions per day is 987, with an average duration of 10 minutes.
- Retention rates are low, with only 6.5% of users returning in the following month.

### Sales
- On average, users make their first purchase 17 days after their first visit.
- Customer retention after the first purchase decreases significantly, with an average of only 115 users making repeat purchases in the following month.
- The LTV of older cohorts, such as June 2017, is higher due to longer customer lifespans and higher purchase frequencies.

### Marketing
- A total of 329,131.62 was spent on marketing, with **source_id 3** having the highest cost (141,321.63) and **source_id 9** the lowest (5,517.49).
- The average customer acquisition cost (CAC) is 4.80, with **source_id 3** being the most expensive (10.21) and **source_id 9** the least expensive (1.97).
- In all months analyzed, operational costs exceeded revenue, resulting in negative profitability.

### Recommendations
- Reduce the budget for **source_id 3** and reallocate funds to **source_id 4** and **source_id 5**, which show better performance.
- Consider increasing investments in **source_id 1** and **source_id 2**, as they demonstrate cost efficiency despite smaller user numbers.

===========================================================================

# Análise de Desempenho e Otimização de Marketing da Y.Afisha

## Descrição do Projeto
Este projeto foi desenvolvido no curso da TripleTen e simula um estágio no departamento analítico da empresa fictícia Y.Afisha. O objetivo é otimizar as despesas de marketing, analisando dados para entender o comportamento dos usuários, o momento de compra, o valor gerado por cliente e o tempo necessário para cobrir os custos.

## Descrição dos Dados
- **Visits**: Logs de acessos ao site (ID de usuário, dispositivo, origem do anúncio e horários de sessão).
- **Orders**: Pedidos realizados (ID de usuário, data e receita gerada).
- **Costs**: Custos de marketing (origem do anúncio, data e valores gastos).

## Abordagem
- **Análise Exploratória de Dados**: Compreender padrões de comportamento.
- **Cálculo do LTV e ROI**: Determinar o valor do cliente e a eficiência dos gastos.
- **Cálculo do Payback**: Estimar o tempo para cobrir os custos.

## Ferramentas
- **Python**: Análise e visualização de dados.
- **Pandas, Matplotlib e Seaborn**: Manipulação e criação de gráficos.
- **Jupyter Notebook**: Organização das análises.

## Conclusão

### Produtos
- Há uma tendência consistente de queda de acessos durante os finais de semana, com um pico significativo na semana 47.
- A média de sessões por dia é de 987, com uma duração média de 10 minutos.
- As taxas de retenção são baixas, com apenas 6,5% dos usuários retornando no mês seguinte.

### Vendas
- Em média, os usuários fazem sua primeira compra 17 dias após a primeira visita.
- A retenção de clientes após a primeira compra diminui significativamente, com uma média de apenas 115 usuários realizando compras repetidas no mês seguinte.
- O LTV de coortes mais antigas, como junho de 2017, é mais alto devido à maior longevidade e frequência de compras.

### Marketing
- Um total de 329.131,62 foi gasto em marketing, com o **source_id 3** apresentando o maior custo (141.321,63) e o **source_id 9** o menor (5.517,49).
- O custo médio de aquisição de cliente (CAC) é de 4,80, com o **source_id 3** sendo o mais caro (10,21) e o **source_id 9** o mais barato (1,97).
- Em todos os meses analisados, os custos operacionais superaram a receita, resultando em lucratividade negativa.

### Recomendações
- Reduzir o orçamento para o **source_id 3** e realocar os fundos para os **source_id 4** e **source_id 5**, que apresentam melhor desempenho.
- Considerar aumentar os investimentos nos **source_id 1** e **source_id 2**, já que demonstram eficiência de custo apesar do número menor de usuários.