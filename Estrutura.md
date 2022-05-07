---
title: Estrutura do curso
author: Dirceu Reis, Francisco Eustáquio, Pedro Chaffe, Wilson Fernandes
date: 07/05/2022
---
-   [1 Estrutura do Curso](#1-estrutura-do-curso)
-   [2 Apresentação](#2-apresentação)
-   [3 Colaboradores](#3-colaboradores)
-   [4 Proposta de temas e respectiva
    itemização](#4-proposta-de-temas-e-respectiva-itemização)
    -   [4.1 Obtenção e manipulação de dados hidrológicos
        (Wilson?)](#41-obtenção-e-manipulação-de-dados-hidrológicos-wilson)
        -   [4.1.1 Acesso automático ao webservice da
            ANA](#411-acesso-automático-ao-webservice-da-ana)
        -   [4.1.2 Manipulação dos dados para facilitar análises no
            R](#412-manipulação-dos-dados-para-facilitar-análises-no-r)
        -   [4.1.3 Exemplo prático com dados de
            precipitação](#413-exemplo-prático-com-dados-de-precipitação)
    -   [4.2 Estimadores em hidrologia estatística
        (Dirceu)](#42-estimadores-em-hidrologia-estatística-dirceu)
        -   [4.2.1 Motivação](#421-motivação)
        -   [4.2.2 Relação entre os conceitos de população, amostra e
            estimador](#422-relação-entre-os-conceitos-de-população-amostra-e-estimador)
        -   [4.2.3 Desempenho de um estimador (e.g., viés, variância,
            erro médio
            quadrático)](#423-desempenho-de-um-estimador-eg-viés-variância-erro-médio-quadrático)
        -   [4.2.4 Métodos para obtenção de um
            estimador](#424-métodos-para-obtenção-de-um-estimador)
        -   [4.2.5 Fatores que afetam desempenho de um
            estimador](#425-fatores-que-afetam-desempenho-de-um-estimador)
        -   [4.2.6 Estimativa de incertezas em
            estimadores](#426-estimativa-de-incertezas-em-estimadores)
        -   [4.2.7 Exemplos de estimadores em
            hidrologia](#427-exemplos-de-estimadores-em-hidrologia)
    -   [4.3 Análise de frequência](#43-análise-de-frequência)
        -   [4.3.1 Motivação](#431-motivação)
        -   [4.3.2 Conceito de tempo de
            recorrência](#432-conceito-de-tempo-de-recorrência)
        -   [4.3.3 Ajuste de uma distribuição de probabilidades aos
            dados](#433-ajuste-de-uma-distribuição-de-probabilidades-aos-dados)
        -   [4.3.4 Estimador de quantis da variável de
            interesse](#434-estimador-de-quantis-da-variável-de-interesse)
        -   [4.3.5 Descrição das incertezas dos
            estimadores](#435-descrição-das-incertezas-dos-estimadores)
-   [5 Exemplos de cabo a rabo](#5-exemplos-de-cabo-a-rabo)
    -   [5.1 Exemplo para ajudar a compreender desempenho de diferentes
        estimadores](#51-exemplo-para-ajudar-a-compreender-desempenho-de-diferentes-estimadores)
        -   [5.1.1 Análise Monte Carlo para compreender diferença de
            desempenho entre
            métodos](#511-análise-monte-carlo-para-compreender-diferença-de-desempenho-entre-métodos)
        -   [5.1.2 Uso de mais de um estimador para a mesma
            característica da série num conjunto de estações (e.g.,
            correlação espacial, coeficente de assimteria,
            autocorrelação
            temporal)](#512-uso-de-mais-de-um-estimador-para-a-mesma-característica-da-série-num-conjunto-de-estações-eg-correlação-espacial-coeficente-de-assimteria-autocorrelação-temporal)
    -   [5.2 Exemplo de análise de frequência de cheias
        local](#52-exemplo-de-análise-de-frequência-de-cheias-local)
        -   [5.2.1 Obter e manipular
            informações](#521-obter-e-manipular-informações)
        -   [5.2.2 Escolha da distribuição de
            probabilidade](#522-escolha-da-distribuição-de-probabilidade)
        -   [5.2.3 Estimativa dos parâmetros da
            distribuição](#523-estimativa-dos-parâmetros-da-distribuição)
        -   [5.2.4 Construção da curva de
            frequência](#524-construção-da-curva-de-frequência)
        -   [5.2.5 Descrição das incertezas nos parâmetros e quantis de
            cheia](#525-descrição-das-incertezas-nos-parâmetros-e-quantis-de-cheia)
-   [6 Banco de dados que podem ser
    utilizados](#6-banco-de-dados-que-podem-ser-utilizados)
    -   [6.1 CAMELS-BR: hydrometeorological time series and landscape
        attributes for 897 catchments in
        Brazil](#61-camels-br-hydrometeorological-time-series-and-landscape-attributes-for-897-catchments-in-brazil)
    -   [6.2 CaBRA: Catchments attributes for Brazil (Almargo et
        al., 2021)](#62-cabra-catchments-attributes-for-brazil-almargo-et-al-2021)
-   [7 Cursos possíveis (demanda
    institucional)](#7-cursos-possíveis-demanda-institucional)
    -   [7.1 Agência Nacional de Água (conversa
        informal)](#71-agência-nacional-de-água-conversa-informal)


# Apresentação

Este documento é uma tentativa de itemização de assuntos a serem
tratados em um ou mais cursos a serem ofertados na área de hidrologia
estatística. Num primeiro momento, os colaboradores irão descrever, de
forma sucinta, tópicos da área sem muita preocupação com o tempo de
duração do curso. A ideia é ter ao final desse processo inicial um
conjunto de assuntos que serão posteriormente detalhados.

Sugiro que o colaborador identifique seu nome em parênteses ao lado do
título do item que pretende detalhar depois, como mostrado no item \*\*
Estimadores \*\*. Mesmo que outro colaborador já tenha iniciado uma
itemização de tema similar ao que você pretendia escrever, eu sugiro
escrever assim mesmo, a não ser que seja exatamente a mesma coisa. Nesse
caso, é melhor esperar pelo dia combinado para iniciarmos uma rodada de
discussão.

O prazo definido na úlitma reunião do 26/04 para finalizarmos a primeira
versão da itemização foi o dia 13/05/2022.

# Colaboradores

Por enquanto, esta iniciativa está sendo desenvolvida pelos seguintes
professores:

-   Dirceu Reis (UnB)
-   Fransciso Eustáquio (UFMG)
-   Pedro Chaffe (UFSC).
-   Wilson Fernandes (UFMG)

# 1 Proposta de temas e respectiva itemização

## 1.1 Obtenção e manipulação de dados hidrológicos (Wilson?)

Tomei a liberdade de sugerir o Wilson por motivos óbvios. Fiz uma
itemização inicial só para sair da inércia.

### 1.1.1 Acesso automático ao webservice da ANA

### 1.1.2 Manipulação dos dados para facilitar análises no R

### 1.1.3 Exemplo prático com dados de precipitação

## 1.2 Estimadores em hidrologia estatística (Dirceu)

### 1.2.1 Motivação

### 1.2.2 Relação entre os conceitos de população, amostra e estimador

### 1.2.3 Desempenho de um estimador (e.g., viés, variância, erro médio quadrático)

### 1.2.4 Métodos para obtenção de um estimador

### 1.2.5 Fatores que afetam desempenho de um estimador

### 1.2.6 Estimativa de incertezas em estimadores

### 1.2.7 Exemplos de estimadores em hidrologia

## 1.3 Análise de frequência

### 1.3.1 Motivação

Além de uma discussão geral sobre o uso de de análise de frequência em
diversos estudos na área de recursos hídricos, devemos apresentar, logo
no início, o problema que será resolvido ao longo do curso. Isso me
parece impotante para manter a motivação.

Em cada etapa de solução do problema será necessário discutir os temas
abaixo.

### 1.3.2 Conceito de tempo de recorrência

### 1.3.3 Ajuste de uma distribuição de probabilidades aos dados

### 1.3.4 Estimador de quantis da variável de interesse

### 1.3.5 Descrição das incertezas dos estimadores

# 2 Exemplos de cabo a rabo

Considerando que uma característica importante desse(s) curso(s) é o
**como fazer**, cada curso deverá ter pelo menos uma tarefa com um
produto final bem definido, que estou chamando aqui de **exemplo de cabo
a rabo**. Como nós estamos, neste momento, construindo uma itemização
mais geral, não especificamente ligada a u curso, sugiro que a gente
identifique alguns desses exemplos, imaginando sempre que cada exemplo
colocado aqui tera que ser executado num único curso.

## 2.1 Exemplo para ajudar a compreender desempenho de diferentes estimadores

### 2.1.1 Análise Monte Carlo para compreender diferença de desempenho entre métodos

### 2.1.2 Uso de mais de um estimador para a mesma característica da série num conjunto de estações (e.g., correlação espacial, coeficente de assimteria, autocorrelação temporal)

## 2.2 Exemplo de análise de frequência de cheias local

### 2.2.1 Obter e manipular informações

### 2.2.2 Escolha da distribuição de probabilidade

### 2.2.3 Estimativa dos parâmetros da distribuição

### 2.2.4 Construção da curva de frequência

### 2.2.5 Descrição das incertezas nos parâmetros e quantis de cheia

# 3 Banco de dados que podem ser utilizados

## 3.1 CAMELS-BR: hydrometeorological time series and landscape attributes for 897 catchments in Brazil

O banco de dados denominado
[CAMELS-BR](https://essd.copernicus.org/articles/12/2075/2020/) me
parece uma boa opção para algumas atividades de ensino. A primeira que
me vem à cabeça é a questão de regionalização hidrológica, já que o
banco contém diversas informações que podem servir de covariáveis na
construção de um modelo regional.

Chagas, V. B. P., Chaffe, P. L. B., Addor, N., Fan, F. M., Fleischmann,
A. S., Paiva, R. C. D., and Siqueira, V. A.: CAMELS-BR:
hydrometeorological time series and landscape attributes for 897
catchments in Brazil, Earth Syst. Sci. Data, 12, 2075–2096,
<https://doi.org/10.5194/essd-12-2075-2020>, 2020.

## 3.2 CaBRA: Catchments attributes for Brazil (Almargo et al., 2021)

O banco de dados denominado
[CaBRA](https://hess.copernicus.org/articles/25/3105/2021/) pode ser
também avaliado para uso nos cursos.

Almagro, A., Oliveira, P. T. S., Meira Neto, A. A., Roy, T., and Troch,
P.: CABra: a novel large-sample dataset for Brazilian catchments,
Hydrol. Earth Syst. Sci., 25, 3105–3135,
<https://doi.org/10.5194/hess-25-3105-2021>, 2021.

# 4 Cursos possíveis (demanda institucional)

## 4.1 Agência Nacional de Água (conversa informal)

A lista abaixo foi feita pelo Saulo Aires de Souza depois de uma
conversa informal que tive com ele.

-   Hidrologia estatística básica
-   Hidrologia estatística intermediária
-   Hidrologia estatística avançada
-   Regionalização de variáveis hidrológicas
    -   Vazões mínimas
    -   Vazões máximas
-   Séries temporais aplicadas à hidrologia
-   Sistemas de reservatórios
