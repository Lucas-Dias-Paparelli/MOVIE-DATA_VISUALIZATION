Português

Projeto: Análise Gráfica de Dados Cinematográficos

Introdução

Neste segundo projeto, aprofundei minha análise nos dados cinematográficos, utilizando a tabela previamente criada no SQL. Explorei diferentes visualizações gráficas para destacar aspectos significativos do conjunto de dados.

Visualizações Principais

Top 5 Filmes com Maior Bilheteria (Gráfico de Barras):
Destaca os cinco filmes que mais arrecadaram em termos de bilheteria.

Estúdios com Maior Número de Filmes (Gráfico de Barras Horizontal):
Apresenta os sete estúdios com a maior produção de filmes, proporcionando uma visão clara da distribuição.

Filmes de Maior Arrecadação Anual (Gráfico Lineplot):
Mostra a arrecadação anual dos filmes ao longo do tempo, identificando tendências e destaques.

Distribuição das Receitas por Ano (Gráfico de Pizza):
Destaca os anos que tiveram a maior arrecadação total, proporcionando uma visão geral do desempenho ao longo do tempo.

Estruturação dos Dados e Utilização de Bibliotecas
Adicionei o símbolo "$" às colunas numéricas para facilitar a visualização.
Criei a tabela profit para calcular o lucro de cada filme.
Utilizei a biblioteca Pandas para manipulação eficiente dos dados.
Desenvolvi o segundo gráfico com base no DataFrame group, que contém informações sobre a quantidade de filmes por estúdio.
Análise Temporal e Formatação Avançada
Para o terceiro gráfico (Lineplot), utilizei o DataFrame df_line_film com colunas como YEAR, PROFIT_YEAR, TOP_FILM_YEAR e BOX_OFFICE.
Realizei uma formatação avançada dos números para melhor legibilidade, indicando bilhões (B) e milhões (M).
Bibliotecas Utilizadas
Pandas: Manipulação e análise de dados.
Matplotlib: Visualizações gráficas.
Seaborn: Aprimoramento estético das visualizações.


Contribuições e Feedback

Se você deseja contribuir ou fornecer feedback, fique à vontade para abrir issues ou pull requests. Sua participação é bem-vinda!

---------------------------------------------------------------------------------------


English

Project: Cinematic Data Visual Analysis

Introduction

In this second project, I delved deeper into the cinematic data, utilizing the previously created SQL table. I explored various graphical visualizations to highlight significant aspects of the dataset.

Key Visualizations

Top 5 Highest Grossing Films (Bar Chart):
Highlights the top five films in terms of box office revenue.

Studios with Highest Number of Films (Horizontal Bar Chart):
Presents the seven studios with the highest film production, providing a clear distribution overview.

Annual Box Office Revenue of Top Films (Lineplot):
Shows the annual revenue of films over time, identifying trends and highlights.

Distribution of Revenues by Year (Pie Chart):
Highlights the years with the highest total revenue, providing an overall view of performance over time.

Data Structuring and Library Usage
Added the "$" symbol to numeric columns for enhanced visualization.
Created the profit table to calculate the profit of each film.
Utilized the Pandas library for efficient data manipulation.
Developed the second graph based on the group DataFrame, containing information about the quantity of films per studio.
Temporal Analysis and Advanced Formatting
For the third graph (Lineplot), I used the df_line_film DataFrame with columns such as YEAR, PROFIT_YEAR, TOP_FILM_YEAR, and BOX_OFFICE.
Implemented advanced formatting of numbers for better readability, indicating billions (B) and millions (M).
Libraries Used
Pandas: Data manipulation and analysis.
Matplotlib: Graphical visualizations.
Seaborn: Aesthetic enhancement of visualizations.

Contributions and Feedback

If you wish to contribute or provide feedback, feel free to open issues or pull requests. Your participation is welcomed!
