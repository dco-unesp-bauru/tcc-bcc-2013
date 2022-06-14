---
layout: posts
title:  "Simplificação de malhas visando representações em multirresolução"
date:   2013-12-01 16:16:36 -0600
categories: trabalho
autornick: FernandoVLF
autor: "Fernando Vinicius Lima Fernandes"
orientador: "Prof. Dr. Antonio Carlos Sementille. Coorientador: Prof. Adj. João Fernando Marar"
---
A representação de objetos reais em ambientes virtuais tem aplicações em diversas áreas, como cartografia, realidade misturada e engenharia reversa. A geração de tais objetos pode ser realizada a partir de ferramentas CAD (Computer Aided Design), ou por meio de técnicas de reconstrução de superfícies. Quanto mais simples o modelo 3D, mais fácil é processá-lo e armazená-lo. Porém, tais métodos podem gerar elementos virtuais muito detalhados, que podem trazer problemas no processamento desta malha resultante, devido ao grande número de arestas e polígonos que devem ser tratados na visualização. Desta forma, podem ser aplicados algoritmos de simplificação, de forma a eliminar polígonos da malha resultante, sem prejudicar a topologia da mesma, gerando uma malha mais leve e sem certos detalhes que podem ser irrelevantes ao usuário. Portanto, este projeto teve como objetivos o estudo, a implementação e testes comparativos de algoritmos de simplificação de malhas geradas por um pipeline de reconstrução baseado em nuvens de pontos.. Este trabalho efetua a realização da etapa de simplificação, como complemento ao pipeline já desenvolvido por (ONO et al., 2012), que desenvolveu a reconstrução a partir de nuvem de pontos capturadas pelo Microsoft Kinect, utilizando-se do algoritmo de Poisson.
