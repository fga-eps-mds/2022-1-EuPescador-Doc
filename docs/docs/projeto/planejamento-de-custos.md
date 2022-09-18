---
layout: default
title:  Planejamento de Custos
parent: Projeto
---


# Planejamento de Custos

## Histórico de versão

| Data | Versão | Modificação | Autor |
| :--: | :----: | :---------: | :---: |
| 28/07/2022 | 1.0 | Criação do documento | [Lucas Ganda](https://github.com/lucasgandac) e [Wictor Girardi](https://github.com/wictorgirardi) |
| 18/08/2022 | 1.1 | Atualização de valores de custo | [João Gabriel Antunes](https://github.com/flyerjohn) |
| 13/08/2022 | 1.2 | Adição dos valores na planilha | [Ailamar Alves ](https://github.com/ailamaralves) |

## Introdução

Este documento tem como finalidade fazer uma estimativa de custo e orçamento, para mostrar o valor que seria gasto durante o desenvolvimento deste projeto caso o mesmo tivesse sido desenvolvido fora do ambiente acadêmico da Universidade de Brasília que não possuísse um viés social.


## Recursos Utilizados

Para fins de cálculo, utilizaremos como base apenas gastos com Pessoas e Infraestrutura, gastos como Equipamento E Capacitação não serão calculados por motivos de os equipamentos usados foram os pessoas e a capacitação foi utilizando fontes gratuitas e open-source. 

## Pessoal

Como base para a estimativa, usamos o seguinte [artigo](https://jornal.unesp.br/2022/06/08/cobranca-de-mensalidade-nao-e-a-solucao-para-o-financiamento-da-universidade-publica/#:~:text=Em%20universidades%20federais%2C%20a%20m%C3%A9dia,%C3%A9%20de%20aproximadamente%20R%24%2027.850.) que colocou a média do custo médio anual de R$ 40.900,00 por estudante de universidade federal. Dessa forma, dividindo o custo médio pelo números de semana, 40.900/52, é obtido o valor de R$ 786,53 semanal por estudante. Entretanto como o time de MDS/EPS possui 11 membros, o custo semanal da equipe fica **R$ 8.651,83**.

## Infraestrutura 

Neste aspectos consideramos custo com energia e internet, custos com servidores não estão sendo considerados pois estamos usando o Heroku. 
Para energia elétrica, utilizando como base as [estatísticas](https://g1.globo.com/df/distrito-federal/noticia/2020/12/01/conta-de-luz-fica-mais-cara-no-df-apos-reajuste-da-aneel.ghtml), colocando R$ 0,06 o preço do kWh e uma média de 4 horas de trabalho semanal, (preço energia por hora * número de horas * número de participantes) fica 0.06 * 4 * 11 = **2,64 semanal**.

Para internet, consideramos a média de plano de R$ 100, dando R$ 25,00 semanal por integrante, logo 25 * 11 resultando em uma média de custo de **R$275,00**.

## Cálculo de Custo


<iframe src="https://docs.google.com/spreadsheets/d/1NEDSJ8m48VIcClozW3Aam5xZQifeUAKimmtsKTeqvuA/edit#gid=837937832" height="1000px" width="1000px" ></iframe>

Somando os cálculos, obtemos um custo estimado das sprints semanais de **R$ 8.929,47**. Dessa forma, o custo estimado total do projeto ao fim das sprints é de **R$ 142.871,52.**


## Referências
- A cobrança de mensalidades nas universidades públicas. Disponível em: <https://jornal.usp.br/artigos/a-cobranca-de-mensalidades-nas-universidades-publicas/>. Acesso em jul, 2022.
- Conta de luz fica mais cara no DF após reajuste da Aneel. Disponível em: <https://g1.globo.com/df/distrito-federal/noticia/2020/12/01/conta-de-luz-fica-mais-cara-no-df-apos-reajuste-da-aneel.ghtml>. Acesso em jul, 2022.
- Cobrança de mensalidade não é a solução para o financiamento da universidade pública. Disponível em: <https://jornal.unesp.br/2022/06/08/cobranca-de-mensalidade-nao-e-a-solucao-para-o-financiamento-da-universidade-publica/#:~:text=Em%20universidades%20federais%2C%20a%20m%C3%A9dia,%C3%A9%20de%20aproximadamente%20R%24%2027.850>. Acesso em set, 2022.


