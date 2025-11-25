1. Análise de Dados – Alura Store Brasil

Este repositório contém a análise completa das quatro lojas da Alura Store Brasil, realizada como parte do desafio de Data Science. O objetivo é avaliar o desempenho das lojas com base em métricas reais de vendas e recomendar qual delas deve ser vendida pelo proprietário, Sr. João.


2. Objetivo do Projeto

O Sr. João deseja vender uma das quatro lojas da rede para investir em um novo empreendimento.
Para apoiar essa decisão, realizamos uma análise completa envolvendo:

- Faturamento total
- Categorias mais e menos vendidas
- Avaliação média dos clientes
- Ranking de produtos
- Frete médio
- Visualizações comparativas
- Conclusão fundamentada


3. Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
  

🗂️ Estrutura do Repositório

├── README.md  # Documentação do projeto

├── AluraStoreBrasil.ipynb  # Notebook completo da análise

└── dados/  # Bases de dados (carregadas via URL no notebook)


4. Etapas da Análise

4.1. Importação e Preparação dos Dados

Os dados são carregados diretamente dos arquivos CSV disponibilizados pela Alura.
Etapas incluíram:

- Padronização das colunas
- Tratamento de valores nulos
- Criação de um dicionário para facilitar análises automáticas  

4.2. Análises Realizadas
   
4.2.1 Faturamento Total por Loja
- O faturamento foi calculado somando o valor de todas as vendas de cada loja.
4.2.2 Categorias mais e menos vendidas
- A contagem de categorias foi feita considerando que cada linha representa uma venda.
Também foi gerada uma pizza consolidada juntando as vendas das quatro lojas.
4.2.3 Avaliação Média das Lojas
4.2.4 Produtos mais e menos vendidos
- Foi gerado um ranking completo para cada loja, além de gráficos horizontais com o Top 5 produtos.
4.2.5 Frete Médio


5. Visualizações Incluídas

O notebook contém todos os seguintes gráficos:

- Gráfico de barras do faturamento total
- Pizza por loja e pizza consolidada
- Gráfico de barras da avaliação média
- Gráfico de barras do frete médio
- Gráfico horizontal do Top 5 produtos por loja

Todos os gráficos incluem valores numéricos para facilitar interpretação.


6. Conclusão Final

Com base nas análises combinadas — faturamento, avaliação média, categorias, produtos e frete — concluímos que:

🟦 ➡️ A loja recomendada para venda é a Loja 4.

Justificativas:

- Apresenta o menor faturamento total entre as quatro lojas.
- Possui avaliação média somente mediana, não se destacando positivamente.
- Seu desempenho geral fica atrás das demais lojas.
- Mesmo com o frete mais barato, isso não se traduz em volume de vendas significativo.
- É a loja com o conjunto mais fraco de métricas considerando toda a operação.
- Vender a Loja 4 permite ao Sr. João reduzir perdas operacionais e investir em oportunidades mais lucrativas.

7. Extra - Análise Geográfica

Além das análises principais, foi realizada uma investigação geográfica utilizando as colunas latitude (lat) e longitude (lon) das bases de dados. Essa etapa é opcional, mas adiciona profundidade ao projeto, permitindo observar padrões espaciais de vendas.

7.1 Objetivo da Análise Geográfica

- Mapear a distribuição das vendas por localização
- Identificar regiões com maior ou menor concentração de clientes
- Avaliar se alguma loja domina determinadas áreas geográficas
- Investigar se fatores geográficos influenciam:
    - Faturamento
    - Avaliações
    - Categorias vendidas

7.2 Dispersão Geográfica das Vendas

Foi criado um gráfico de dispersão utilizando Matplotlib, onde cada ponto representa uma venda real registrada nas bases de dados.
Esse gráfico permite visualizar:

- A amplitude territorial das vendas
- A concentração de vendas por região
- Sobreposição entre áreas atendidas pelas lojas

Em geral, observou-se uma forte concentração em determinados polos urbanos, o que indica maior densidade de clientes nessas regiões.

7.3 Heatmap de Densidade

Para aprofundar a análise espacial, foi gerado um Heatmap simples utilizando hist2d do Matplotlib.
O heatmap evidencia:

- Regiões com maior volume de vendas (cores quentes)
- Regiões com baixa atividade (cores frias)

Esse gráfico é especialmente útil para avaliar o potencial de mercado por zona geográfica.

7.4 Mapa Interativo

Para uma visualização ainda mais rica, foi incluída uma versão opcional usando a biblioteca Folium, que permite visualizar as vendas em um mapa interativo real.
Com esse recurso é possível:

- Navegar pelo mapa  
- Aproximar regiões específicas  
- Visualizar a distribuição exata das vendas  
- Comparar alcance geográfico entre lojas

7.5 Relação entre Localização e Desempenho

Além dos gráficos, foram realizados testes relacionando geografia com desempenho:

- Faturamento por região: verificou-se que determinadas áreas apresentam maior potencial comercial.  
- Avaliação por região: algumas regiões concentram avaliações melhores, sugerindo impacto cultural, logístico ou de concorrência.  
- Padrões por loja: identificou-se que cada loja tende a performar melhor em regiões específicas.
  

7.6 Conclusão da Análise Geográfica

A análise espacial adicionou valor ao projeto ao revelar padrões que não seriam percebidos somente com dados tradicionais. Embora seja uma etapa opcional, ela enriquece a compreensão do comportamento dos clientes e da atuação territorial das lojas, contribuindo para decisões estratégicas mais completas.



🚀 Como Executar o Projeto

1. Abra o arquivo AluraStoreBrasil.ipynb no Google Colab ou Jupyter Notebook
2. Execute as células na ordem apresentada
3. As bibliotecas serão importadas automaticamente
4. Os dados serão carregados via URL
5. As análises, tabelas e gráficos serão gerados automaticamente



🤝 Autor

Projeto desenvolvido como parte do desafio de Data Science da Alura.

Estudante: Eryck Barcelos









