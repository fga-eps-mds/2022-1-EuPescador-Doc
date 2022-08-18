# Planejamento de Custos

## Histórico de versão
| Data | Versão | Modificação | Autor |
| :--: | :----: | :---------: | :---: |
| 28/07/2022 | 1.0 | Criação do documento | Lucas Ganda e Wictor Girardi |
| 18/08/2022 | 1.1 | Atualização de valores de custo | João Gabriel Antunes |

## Introdução

Este documento tem como finalidade fazer uma estimativa de custo e orçamento, para mostrar o valor que seria gasto durante o desenvolvimento deste projeto caso o mesmo tivesse sido desenvolvido fora de ambiente acadêmico da Universidade de Brasília que não possuísse um viés social.


## Recursos Utilizados

Para fins de cálculo, utilizaremos como base apenas gastos com Pessoas e Infraestrutura, gastos como Equipamento E Capacitação não serão calculados por motivos de os equipamentos usados foram os pessoas e a capacitação foi utilizando fontes gratuitas e open-source. 

## Pessoal

Como base para a estimativa, usamos o seguinte [artigo](https://jornal.usp.br/artigos/a-cobranca-de-mensalidades-nas-universidades-publicas/) que colocou a média do custo médio anual de R$ 80.500,00 por estudante de universidade federal. Dessa forma dividindo o custo médio pelo números de semana, 80.500/52, é obtido o valor de R$ 1.548,07 semanal por estudante. Entretanto como o time de MDS/EPS possui 13 membros, o custo semanal da equipe fica **R$ 20.125,00**.

## Infraestrutura 

Neste aspectos consideraremos custo com energia e internet, custos com servidores não estão sendo considerados pois estamos usando o Heroku. 
Para energia elétrica, utilizando como base as [estatísticas](https://g1.globo.com/df/distrito-federal/noticia/2020/12/01/conta-de-luz-fica-mais-cara-no-df-apos-reajuste-da-aneel.ghtml), colocando R$ 0,06 o preço do kWh e uma média de 3 horas de trabalho semanal, (preço energia por hora * número de horas * número de participantes) fica 0.06 * 4 * 13 = **3,12 semanal**.
Para internet, consideramos a média de plano de R$ 100, dando R$ 25,00 semanal por integrante, logo 25 * 13 resultando em uma média de custo de **R$325,00** 

## Cálculo de Custo

Somando os cálculos, obtemos um custo estimado semanal de R$ 20.450,00, entretanto como o projeto é dividido em sprints de 2 semanas, o custo da sprint fica em R$ 40.900,00

| Número das Sprints |  Custo por Sprint | Total | 
| :--: | :----: | :---------: | 
| 8 | R$ 40.900,00 | R$ 327.200,00|


Dessa forma, o custo estimado total do projeto ao fim das 8 sprints é de R$ 327.200,00
