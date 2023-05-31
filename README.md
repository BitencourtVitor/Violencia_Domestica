# Violência Doméstica na Colômbia

###### Aqui, você terá acesso a:
- Arquivo .ipynb usado para tratamento dos dados;
- Arquivo .pbix para caso queira interagir;
- Base de dados já tratada;
- Print do Dashboard feito em Power BI

## Introdução
Acessando o Kaggle, foi obtida uma base de dados muito interessante sobre a quantidade de ocorrências realizadas na Colômbia entre 2010 e Março de 2023 referentes a violência doméstica.  
Um assunto delicado, mas que abre precedente para muitos estudos.

## Conclusão
Foram mais de meio milhão de ocorrências, mais de um milhão de vítimas envolvidas, logo, os indícios levam a concluir que a violência dentro do lar atinge não somente marido e mulher, mas todos que ali convivem. 

Percentualmente:
- Quase 80% mais vítimas do que ocorrências.
- Cerca de 48% das armas foram contundentes, para quem quer agredir, qualquer objeto serve como arma.  
(Por exemplo: martelos, barra de ferro, pedras, etc.)
- A cada 4 vítimas, 3 são mulheres. Um percentual de aproximadamente 76% das vítimas.

A distribuição territorial seguiu a proporção da densidade populacional.

## Pontos a melhorar 
- Foi excelente usar Python, mas realizar scripts em Power BI poderia ser mais ágil.
- Buscar insights através de dados calculados em linguagem DAX poderia agregar ao estudo.

## Passo a passo
- OBJETIVO: Realizar um estudo com os principais KPI's capazes de se retirar da base em questão afim de encontrar padrões ou fatores que possam estar influenciando na taxa de violência doméstica.

- EXTRAÇÃO: O banco de dados foi disponibilizado no Kaggle no formato .csv .
- TRANSFORMAÇÃO: Inserção do arquivo .csv dentro do Jupyter para tratamento.

A seguir, um print do antes e depois do tratamento na base de dados:

![Aqui está o print](https://github.com/BitencourtVitor/Violencia_Domestica/blob/main/images/Antes_Depois%20do%20Tratamento.png)

###### Observação: alguns dados como departamento e município precisaram passar por uma adaptação na sua acentuação. ATLÃNTICO (incorreto) passou a ser Atlántico (correto), por exemplo. Isso foi possível graças ao encoding UTF-8 durante o tratamento.

- LOAD: Diante da proposta do projeto, foi criado um Dashboard no Figma.

Prestando atenção na parte inferior do painel é possível notar que a distribuição visual segue a proporção de cores da bandeira da Colômbia no sentido vertical (amarelo, azul e vermelho).

![Aqui há um print do Dashboard](https://github.com/BitencourtVitor/Violencia_Domestica/blob/main/images/print_dashboard.png)
