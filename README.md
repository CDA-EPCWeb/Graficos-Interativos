# Graficos-Interativos
## Resumo
  O arquivo Indicadores.html tem como objetivo construir gráficos interativos com os indicadore epidemiológicos disponíveis no repositório Indicadores-Epidemiológicos. Tendo o portal do projeto como fim para amostragem dos dados, o código é estruturado em html e o acesso aos dados e exibição dos gráficos em javascript, de forma a exibir gráficos dinâmicos e com dados atualizados dos indicadores por semana epidemiológica.
## Pré-Requisitos
  O código é estrurado em html e javascrpt, utilizando as bibliotecas Plotly, NumJS, MathJax e Bootstrap.
## Fonte/ Base de Dados Trabalhada:
  Os dados exibidos são retirados do arquivo Indicadores.csv no repositório Indicadores-Epidemiológicos em "https://github.com/CDA-EPCWeb/Indicadores-Epidemiologicos".
## Passo a passo:
  A implementação e execução do código parte essencialmente da estruturação em html e da leitura do csv e impressão dos gráficos. Primeiramente utiliza-se da modelagem do bootstrap para organizar a exibição do gráfico assim como a seleção do indicador e das anotações sobre o indicador. Além disso, é desenvolvido um script para fazer a leitura dos dados do csv e plotagem dos gráficos, fazendo alterações para cada indicador, legendas e estilizações quanto à visualização. 
## Resultado:
  O resultado é uma seção selecionável com os gráficos de linhas associando indicadores à semanas epidemiológicas para cada região do Brasil e o Brasil como um todo, também exibindo anexado uma breve descrição do indicador selecionado. Alguns exemplos são os seguintes:
  ![image](https://user-images.githubusercontent.com/57276191/109439353-c21feb00-7a0c-11eb-8089-e1b9caf2c791.png)
  ![image](https://user-images.githubusercontent.com/57276191/109439387-dbc13280-7a0c-11eb-8813-2424d29ab229.png)
## Acesso:
  Acesse o gráfico no portal do projeto em "http://covid.dcc.ufmg.br/linhas/web/".
## Membros:
  Daniel Ferreira, Marcelo Ganem, Rafael Santos
