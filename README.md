# <Previsão de Precipitação para as Regiões Hidrográficas do Estado do Ceará>

As precipitações sobre o Estado do Ceará são caracterizadas
por elevada variabilidade espacial e temporal. Antecipar 
informações a respeito da distribuição e volume 
desta variável se torna fundamental para o gerenciamento de
risco de eventos de seca e cheia por parte dos
setores de Recursos Hídricos e Agrícola do Estado.
Neste sentido, este projeto se propõe a conceber um sistema
de previsão mensal de precipitação para as Regiões Hidrográficas do Ceará.

## Objetivos e resultados chave

 - Realizar uma análise exploratória de dados Meteoceanográficos
    - Idênticas e extrair variáveis meteorológicas e oceânicas que possam
      influenciar o processo de formação das precipitações.
    - Organizar os valores de cada variável por ponto de grade (latitude e longitude) e Região Hidrográfica,
      em uma série temporal.
    - Identificar a distribuição e o volume da precipitação, bem como as variáveis que possam explicar
      o seu comportamento.
    
 - Realizar a comparação entre os modelos de Aprendizado de Máquina 
    - Realizar a normalização das variáveis.
    - Identificar modelos preditivos e métricas de verificação dos modelos.
    - Idênticar o modelo com melhor desempenho na previsão de precipitação.

## Conteúdo

No contexto deste projeto, os seguintes notebook foram gerados:

 1 - pre-processing.ipynb
 Este notebook realiza a leitura dos dados
 de precipitação, reanálise atmosférica e
 dados oceânicos e os organiza considerando
 posição, o tempo (mês e ano) e o valor de cada variável.

 2 - EDA.ipynd
 Este notebook realiza a Análise Exploratória de Dados,
 a qual descreve a distribuição mensal dos dados de precipitação
 e apresenta a coordenação e o scatter plot entre as variáveis.

## Utilização 

## Desenvolvedores
 - [Diógenes Fontenele](https://github.com/diogenes-fontenele)
 - [Fabrício Teixeira](https://github.com/fabzfta)
 - [Ana Furtado](https://github.com/mabiapines)
