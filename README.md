## Projeto: ETL de Vendas

### Objetivo
Realizar a extração de dados de vendas da API DummyJSON, tratar e transformar os dados utilizando Pandas e NumPy, e exportar o resultado final para um arquivo CSV. Também foram geradas visualizações para análise dos dados.

### Ferramentas Utilizadas
- Visual Studio Code
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Requests
- Matplotlib

### Processo ETL
- **Extração:** Dados extraídos da API DummyJSON (`/carts`) via biblioteca `requests`, com tratamento de erro HTTP implementado.
- **Transformação:** 
  - Normalização de carrinhos e produtos em formato tabular.
  - Cálculo de colunas como `Total_Item`, `Classificacao_Venda` e `Mes_Venda`.
  - Conversão e tratamento de tipos de dados.
- **Carga:** 
  - Exportação do dataset tratado para um arquivo CSV em `dados_tratados/vendas_dummyjson.csv`.
  - Organização automática de diretórios para exportação.

### Visualizações
Foram gerados gráficos com foco em insights de negócio e apresentação visual:

- **Receita Total por Mês**: gráfico de barras ordenado.
- **Top 5 Produtos Mais Vendidos**: gráfico de barras horizontais.

As imagens foram salvas em `/graficos/`, podendo ser usadas em dashboards, relatórios ou apresentações.

### Resultados e Aprendizados
- Foram obtidos insights como receita total por mês e produto mais vendido.
- Análise da performance mensal de vendas.
- Identificação dos produtos mais vendidos.
- Aplicação de boas práticas em projetos de dados com Python (estruturação ETL, modularização, salvamento de imagens).
