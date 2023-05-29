# Violência Doméstica na Colômbia

###### Aqui, você terá acesso a:
- Print do Dashboard feito em Power BI
- Arquivo notebook em Python que criei para tratar os dados, comentei tudo para melhor entendimento.
- Arquivo .pbix para caso queira interagir ou realizar alguma alteração
- Base de dados já tratada para caso queira navegar.

## Introdução
Acessando o Kaggle, consegui uma base de dados muito interessante: ela fala sobre a quantidade de ocorrências realizadas na Colômbia entre 2010 e Março de 2023 referentes a violência doméstica. Um assunto delicado, mas que abre precedente para muitos estudos.

## Conclusão
Foram mais de meio milhão de ocorrências, mais de um milhão de vítimas envolvidas... O que me leva a concluir que a violência dentro do lar atinge não somente marido e mulher, mas todos que ali convivem. 

Além disso:
- Temos quase 80% mais vítimas do que ocorrências, quase o dobro, como citado anteriormente.
- Cerca de 48% das armas foram contundentes: se há a intenção da agressão, até mesmo uma ferramenta serve como arma.
- Surpreendendo um total de 'zero pessoas': 76% das vítimas são mulheres. Em outras palavras, a cada 4 vítimas, 3 são mulheres.

A distribuição territorial seguiu a proporção da densidade populacional.

## Pontos a melhorar 
- Foi excelente usar Python, mas acredito que caso eu pudesse (ou soubesse) realizar scripts dentro do próprio Power BI, seria mais ágil.
- Eu poderia ter pensado em insights através de dados calculados em linguagem DAX.

## Passo a passo
- OBJETIVO: Realizar um estudo com os principais KPI's capazes de se retirar da base em questão afim de encontrar padrões ou fatores que possam estar influenciando na taxa de violência doméstica.

- EXTRAÇÃO: O banco de dados foi disponibilizado no Kaggle no formato .csv
A partir disso, resolvi realizar todo o tratamento em Python para fins didáticos, evidentemente eu poderia ter feito com outras ferramentas caso quisesse.
- TRANSFORMAÇÃO: Inseri o arquivo .csv dentro do Jupyter para fazer as devidas correções e ajustes nos mínimos detalhes, desde correção de idioma (muitos dados em espanhol) até formatação dos valores para evitar discrepância.

A seguir, um print do antes e depois do tratamento na base de dados:

![Aqui está o print](https://github.com/BitencourtVitor/bitencourtvitor/blob/main/Viol%C3%AAncia%20Dom%C3%A9stica%20na%20Col%C3%B4mbia/Antes_Depois%20do%20Tratamento.png)

A partir do arquivo já corrigido, transformei-o em uma tabela dentro do Excel.
- LOAD: Sabendo do que precisava ser apresentado e planejando como apresentar, criei o Dashboard no Figma tomando cuidado com paleta de cores, distribuição dos elementos visuais, etc.


![Aqui há um print do Dashboard](https://github.com/BitencourtVitor/bitencourtvitor/blob/main/Viol%C3%AAncia%20Dom%C3%A9stica%20na%20Col%C3%B4mbia/print_dashboard.png)
