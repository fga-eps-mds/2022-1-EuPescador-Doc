---
layout: default
title: Post Mortem
parent: Produto
---


# Post Mortem

## Histórico de versão

| Data | Versão | Modificação | Autor |
| :--: | :----: | :---------: | :---: |
| 17/09/2022 | 1.0 | Criação do documento | Lucas Ganda |

## Pontos Fortes

* Evolução da comunicação da equipe
* Melhora da organização da equipe
* Evolução de conhecimento da equipe de MDS
* Conhecimento prévio das tecnologia por parte da equipe de MDS
* Entrega funcional da aplicação
* Entrega de quase todos os requisitos levantados inicialmente


## Pontos Fracos

* Falta de organização da equipe
* Demora para equipe começar a produzir
* Pouco foco no desenvolvimento por parte de alguns EPS
* Arquitetura do aplicativo dificultou o desenvolvimento
* Alguns membros de MDS saíram da disciplina
* Disciplina possui alta cargo

## Recomendaçoes 

* Tentar seguir ao máximo todos os processos do ágil, para ter controle do que está acontecendo
* Manter comunicação constante
* Incentivar proatividade por parte dos MDS
* Manter toda a equipe engajada
* Migrar arquitetura e serviços
* Organizar bem oi tempo

### Pontos Críticos

Em termos de possíveis recomendações e melhorias, separamos dois pontos que detectamos como crítico e caso o tema seja mantido em algum futuro semestre, sugerimos fortemente que sejam abordados.

* Retirada do Expo

Expo é uma ferramenta utilizada no desenvolvimento mobile com React Native que tem como objetivo facilitar acesso a APIs, a geração de build, entre outras features.

Sugerimos fortemente o trabalho de remoção do Expo e suas dependencias no projeto, seja para continuar com react-native puro ou migrar para outra linguagem mobile como Flutter ou Kotlin. A existência do Expo nesse projeto apenas atrapalhou o desenvolvimento em diversos termos, seja dificuldade para gerar builds ou utilizar alguns serviços terceiros.

Dessa forma, no entendimento da equipe de EPS a retirada do expo é altamente indicada para facilitar o desenvolvimento, garantir a qualidade, manutenibilidade, entre outros aspectos.

* Mudança do armazenamento de imagens

Da forma como a arquitetura está estruturada atualmente,  as requisições carregam os arquivos de imagem, tornando-as demoradas e pesadas.

Em relação a isso trazemos a possível sugestão de utilizar buckets de armazenamento como é o caso do Amazon S3. Dessa forma, as requisições trariam apenas os links paras imagens e não as imagens propriamente ditas, tornando as requisições muito mais leves e aumentando a perfomance da aplicação.


## Referências Bibliográficas

Ludum. Fga-eps-mds.github.io. Disponível em: <https://fga-eps-mds.github.io/2019.1-Ludum/#/post-mortem>. Acesso em: 18  set.  2022.
