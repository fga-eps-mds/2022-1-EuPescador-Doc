# Análise de risco

## Histórico de versão
| Data | Versão | Modificação | Autor |
| :--: | :----: | :---------: | :---: |
| 08/07/2022 | 1.0 | Criação do documento | Ailamar Alves |
| 13/07/2022 | 1.1 | Atualização das tabelas | Ailamar Alves |
| 18/07/2022 | 1.2 | Atualização lista de riscos | Ailamar Alves |

## Introdução

Segundo o guia PMBOK, risco é definido como “evento ou condição incerta que, se ocorrer, terá um efeito positivo ou negativo sobre pelo menos um objetivo do projeto”. 

Sendo assim, esse documento apresenta o plano de gerenciamento de risco com os eventos ou condições do projeto EuPescador. Em outras palavras, trata-se das decisões relacionadas em como abordar e executar as atividades no projeto. 

## Objetivo

A análise de riscos tem como objetivo abordar os riscos do projeto, monitorar e definir como controlar imprevistos ao longo do prazo de desenvolvimento. Esse planejamento aborda fatores  ambientais  da  organização, ativos de processos organizacionais, definição  do  escopo do projeto, entre outros fatores.

## Estrutura Analítica de Riscos

A Estrutura Analítica de Riscos (EAR) é uma estrutura pela qual você agrupa riscos e organiza-os em categorias. Cada categoria é então dividida em níveis, sendo que cada nível detalha a fonte de riscos para seu projeto. Ou seja, a EAR é uma estrutura hierárquica de possíveis fontes de risco. 

Essa estrutura possibilita a identificação das dependências de risco, quebrando cada risco em níveis. É dividido em 4 categorias:

- **Externo:** são aqueles que não estão no controle dos líderes da organização, como cliente, mercado, ambiente, fornecedores, etc.
- **Gerenciamento:** àqueles que afetam os negócios com uma previsão tecnológica, financeira ou cronológica.
- **Organizacional:** advém da falta de organização da empresa, dos recursos e infraestrutura.
- **Técnico:** inclui atrasos decorrentes de defeitos de software e hardware ou a falha de um serviço ou de uma plataforma.

## Análise Quantitativa de Riscos

A matriz de **probabilidade** e **impacto**  é uma tabela que reúne uma série de informações sobre os potenciais riscos do negócio. 

Nela são reunidas todas as ameaças e oportunidades, distribuídas de acordo com a probabilidade de acontecimento e impacto causado. As informações são colocadas nos campos correspondentes classificadas de acordo com a sua prioridade. 

### Prioridade:

| Probabilidade x Impacto | Muito Baixa | Baixa | Média | Alta | Muito Alta |
|:-----------------------:| :---------: | :---: | :---: | :--: | :---------:|
| **Muito Baixa** | 1 | 2 | 3 | 4 | 5 | 
| **Baixa**       | 2 | 4 | 6 | 8 | **10** | 
| **Média**       | 3 | 6 | 9 | **12** | **15** | 
| **Alta**        | 4 | 8 | **12** | **16** | **20** | 
| **Muito Alta**  | 5 | 10 | **15** | **20** | **25** | 

## Identificação dos Riscos

| ID | Risco | Prob. | Impacto | Prevenção | Correção | EAR |
|:--:| :---- | :-----------: | :-----: | :-------: | :------: | :--:|
| R01 | Falta de conhecimento das tecnologias do projeto | 3 | 3 | Realizar treinamento com os membros da equipe | Disponibilizar documentação e instruções, fazer pareamentos | Organizacional | 
| **R02** | Dificuldade de interação entre a equipe | 3 | 4 | Seguir plano de comunicação, utilizar as ferramentas de interação instantâneas | Repensar ferramentas, ficar mais atento(a) aos avisos | Gerenciamento | 
| R03 | Atraso de tarefas relacionadas a tarefas futuras | 2 | 4 | Estar atento ao cronograma, organizar as tarefas | Prolongar a data, auxílio de outro integrante | Gerenciamento | 
| **R04** | Indisponibilidade do cliente ao decorrer do projeto | 5 | 5 | - | Evitar reagendar reuniões, manter o que foi combinado, estar atento à agenda do cliente | Externo | 
| **R05**| Indisponibilidade de algum integrante da equipe | 4 | 5 | Manter os horários de trabalho sempre disponíveis | Programar melhor as atividades individuais | Organizacional | 
| R06 | Indisponibilidade para as reuniões | 2 | 4 | Manter os horários de trabalho sempre disponíveis entre o grupo | Estar atento ao calendário de reuniões | Gerenciamento | 
| **R07** | Desistência de integrante da equipe no meio do projeto | 4 | 5 | Dividir as tarefas igualmente e não sobrecarregar os integrantes | Reorganizar a divisão de tarefas e cronograma | Organizacional | 
| **R08** | Atraso nos prazos previstos | 3 | 5 | Atentar-se às datas estipuladas | Reorganizar o cronograma | Gerenciamento | 
| R09 | Cronograma de atividades mal elaborado  | 2 | 4 | Elaborar backlog de forma coerente, dividir as tarefas de forma eficaz | Revizar o backlog | Gerenciamento | 
| R10 | Greve | 3 | 3 | - | - | Externo | 
| R11 | Qualidade do software | 3 | 3 | Manter o padrão de projeto ao longo do desenvolvimento, testes, usabilidade | Pareamentos, revisão do padrão de projeto |Técnico | 
| **R12** | Entendimento equivocado do que é esperado pelo cliente | 4 | 5 | Estar sempre dentro do que foi validado pelo cliente | Rever o escopo, documentações e planejamento inicial | Técnico | 
| R13 | Alteração de escopo | 2 | 4 | Fazer o planejamento inicial atento à complexidade do projeto | Definir o possível entregável dentro do prazo | Técnico | 
| R14 | Problemas com os equipamentos da equipe | 3 | 3 | - | Resolver o quando antes a situação, fazer pareamento | Técnico | 
| **R15** | Conflitos com demanda de outras matérias | 3 | 4 | Ter um planejamento dentro do cronograma de entrega das atividades acadêmicas | Definir prioridade e datas de entregas das matérias | Técnico | 
| R16 | Corona Vírus | 3 | 3 | Seguir as recomendações da OMS | Reorganizar tarefas | Técnico | 


## Referências

- Do Prado, Pedro Felipe & Vasques, Edmir & De Albuquerque, Joao. (2009). Análise de Riscos em Projetos de Software. 
- Seiji Isotani, Rafaela V. Rocha. Gestão de Riscos em Projetos de Software. Disponível em: <https://edisciplinas.usp.br/pluginfile.php/3385127/mod_resource/content/1/Aula10-GerenciaProjeto-Riscos.pdf>. Acesso em: jul, 2022.
- Perinity. A IMPORTÂNCIA DA MATRIZ DE PROBABILIDADE E IMPACTO NA GESTÃO DE RISCOS.Disponível em: <https://www.perinity.com.br/riscos/a-importancia-da-matriz-de-probabilidade-e-impacto-na-gestao-de-riscos/#:~:text=Entenda%20a%20matriz%20de%20probabilidade%20e%20impacto&text=Enquanto%20a%20probabilidade%20pode,que%20o%20mesmo%20deve%20receber.> Acesso em: jul, 2022.
