+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "EFEITO DA NÃO NORMALIDADE E DA ESTIMAÇÃO DOS PARÂMETROS NO DESEMPENHO DE GRÁFICOS DE CONTROLE EM DELINEAMENTOS POR CONJUNTOS ORDENADOS"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "grafico-controle.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Estatística-Espacial", "Modelagem", "Adolescência"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/grafico-controle.jpg"
caption = "My caption :smile:"

+++

A amostragem por conjuntos ordenados (ACO) é um delineamento amostral apropriado em situações em que a avaliação da variável de interesse é dispendiosa (seja por aspectos financeiros ou operacionais), havendo, no entanto, a possibilidade de ranquear unidades amostrais de forma econômica e precisa. Nesse contexto, a ACO viabiliza a produção de estimativas mais precisas do que a Amostragem Aleatória Simples (AAS) mediante seleção de um menor número de unidades amostrais. 

Ao longo das últimas décadas, diversas extensões do delineamento original da ACO foram propostos, verificando-se, em diferentes contextos, a maior eficiência (conjugada a menores custos) dessa classe de delineamentos amostrais em relação à AAS e outros delineamentos amostrais mais convencionais. Um cenário em que a ACO é particularmente indicada é no Controle Estatístico de Processos (CEP), área na qual a demanda por métodos estatísticos que proporcionem ganho de precisão e maior economia é bastante elevada. No entanto, a aplicação da ACO em CEP somente foi abordada recentemente, configurando uma área de pesquisa com grandes perspectivas. Assim, o presente projeto contempla a proposta e análise de métodos baseados em delineamentos amostrais por conjuntos ordenados no CEP. Dentre os principais temas a serem abordados, destacam-se a proposta e análise do desempenho de gráficos de controle adaptativos, a proposta de gráficos de controle robustos e a utilização de métodos de re-amostragem em diferentes problemas de Controle Estatístico de Qualidade (CEQ).

Os métodos propostos serão avaliados com base nos resultados de extensivos estudos por simulação. A ilustração dos métodos em conjuntos de dados reais permitirá visualizar suas respectivas aplicações. Adicionalmente, pretende-se implementar e disponibilizar rotinas computacionais que viabilizem a aplicação dos métodos e sirvam de suporte para estudos futuros. Todas as análises, bem como o desenvolvimento de um pacote com funções específicas, serão realizados usando o ambiente computacional estatístico R.