# Graficos-Interativos
## Resumo
  O arquivo Indicadores.html tem como objetivo construir gráficos interativos com os indicadore epidemiológicos disponíveis no repositório Indicadores-Epidemiológicos. Tendo o portal do projeto como fim para amostragem dos dados, o código é estruturado em html e o acesso aos dados e exibição dos gráficos em javascript, de forma a exibir gráficos dinâmicos e com dados atualizados dos indicadores por semana epidemiológica. Os indicadores são: Mortes Acumuladas, Casos Acumulados, Novas Mortes por semana, Novos Casos por semana, Letalidade, Mortalidade, Prevalência, Incidência de Casos, Incidência de Mortes, Fator de Crescimento de Casos e Fator de Crescimento de Mortes.
## Pré-Requisitos
  O código é estrurado em html e javascrpt, utilizando as bibliotecas Plotly, NumJS, MathJax e Bootstrap.
## Fonte/ Base de Dados Trabalhada:
  Os dados exibidos são retirados do arquivo Indicadores.csv no repositório Indicadores-Epidemiológicos em "https://github.com/CDA-EPCWeb/Indicadores-Epidemiologicos".
## Passo a passo:
  A implementação e execução do código parte essencialmente da estruturação em html e da leitura do csv e impressão dos gráficos. Primeiramente utiliza-se da modelagem do bootstrap para organizar a exibição do gráfico assim como a seleção do indicador e das anotações sobre o indicador. Além disso, é desenvolvido um script para fazer a leitura dos dados do csv e plotagem dos gráficos, fazendo alterações para cada indicador, legendas e estilizações quanto à visualização. 
## Resultado:
  O resultado é uma seção selecionável com os gráficos de linhas associando indicadores à semanas epidemiológicas para cada região do Brasil e o Brasil como um todo, também exibindo anexado uma breve descrição do indicador selecionado. Alguns exemplos são os seguintes:
  ![image](https://user-images.githubusercontent.com/57276191/109440353-c5b57100-7a10-11eb-9313-c34d469bfd2d.png)
  ![image](https://user-images.githubusercontent.com/57276191/109440596-96533400-7a11-11eb-8fd9-4c25781bb058.png)
## Acesso:
  Acesse o gráfico no portal do projeto em "http://covid.dcc.ufmg.br/linhas/web/".
## Membros:
  Daniel Ferreira, Marcelo Ganem, Rafael Santos
