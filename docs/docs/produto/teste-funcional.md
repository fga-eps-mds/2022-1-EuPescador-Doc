---
layout: default
title: Testes de aceitação
parent: Produto
---

# Testes de aceitação

## Histórico de versão

| Data | Versão | Modificação | Autor |
| :--: | :----: | :---------: | :---: |
| 05/09/2022 | 1.0 | Criação do documento | [Ailamar Alves](https://github.com/ailamaralves) |
| 14/09/2022 | 1.1 | Adição Introdução e Objetivo | [Ailamar Alves](https://github.com/ailamaralves) e [João Gabriel Antunes](https://github.com/flyerjohn) |
| 08/08/2022 | 1.2 | Release 1 Mobile | Time EPS |
| 15/08/2022 | 1.3 | Release 3 Mobile | Time EPS |
| 05/09/2022 | 1.4 | Release 5 Mobile | Time EPS |

## Introdução

No teste de aceitação uma versão particular do software é testada para uso fora do ambiente de desenvolvimento. 
Esse teste busca verificar se o sistema atente aos requisitos do cliente. 

## Objetivo

É um processo sistemático que tem por objetivo identificar prováveis defeitos, verificando se o software realiza suas tarefas de 
forma correta ou se eventualmente faz o que não deveria fazer. Os testes foram realizados pelo *Product Owner* do projeto.

## Release 1 - Mobile

Ambiente: Sistema Operacional Android 

### Funcionalidades 

1. **Acessar a plataforma**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, a plataforma web está funcionando normalmente e mostrando a tela de inicio?**

**Resposta:** Não.  

*"Não aparece tela de início nem logon. Quando acesso o endereço ele entra direto na tela que contém o menu do lado esquerdo e fica com a tela em branco. 
O título aparece "Listagem de peixes" porém não carrega as espécies da listagem. O menu parece estar selecionado a opção "Mapa" e quando cliquei em "Listar" 
apareceu a listagem das espécies do aplicativo. Não há nenhuma tela para exibição e validação dos registros feitos pelos pescadores que é a função primordial da web."*

2. **Logar na plataforma**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, a validação do usuário está sendo feita e o usuário está conseguindo acessar a tela de dashboard do site?**

**Resposta:** Não. 

*"Não aparece tela de logar. No menu há uma opção "Cadastrar" que não há necessidade pois já foi falado em reunião que o pesquisador ou administrador não vai fazer registro pela
web essa não é a finalidade. é apenas controlar os registros criados pelos usuários."*

3. **Acessar a listagem de peixes**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, todos os dados de registro de um peixe estão aparecendo de forma clara e esperada?**

**Resposta:** Não. 

*"Poderia estar bem mais claro. A listagem de peixes aparece com números do lado (tamanho máximo) porém deveria estar escrito junto que é o tamanho que
o peixe atinge, o habitat que ele ocorre e o peso máximo registrado (kg). Sugeriria colocar antes algo como Tmax Habitat e Peso max para as pessoas entenderem."*

4. **Outras considerações**

**Existe alguma consideração final que deseja realizar sobre a experiência de uso?**

**Resposta:** *"É muito importante a tela de logon e principalmente, eu esperava que fosse já haver uma tela com os registros que os pescadores fizessem pois tentei 
deixar claro que da perspectiva do usuário é fundamental que esta versão web exiba adequadamente os registros criados pelos pescadores de todos os 117 tipos de peixes 
diferentes para que possamos validar esses dados de forma mais fácil que pelo app, como era antigamente."*

## Release 3 Mobile

Ambiente: Sistema Operacional Android 

### Funcionalidades 

1. **Visualizar registros**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, após cadastrar um peixe já é possível vê-lo no mapa mesmo sem ter sido revisado?**

**Resposta:** Não.  

*"Registros não estão aparecendo. Gerei registros online, aparece a mensagem registro criado com sucesso porém o mesmo não fica disponível para o usuário ver posteriormente"*

2. **Registro offline**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, após cadastrar um peixe no offline é possível vê-lo na aba de registros?**

**Resposta:** Não. 

*"Não conseguí gerar o registro offline. Quando clico em enviar depois de preencher os dados do novo registro a tela continua parada da mesma forma.
Fiquei online posteriormente entrei na tela registros e ela estava em branco"*

3. **Visualizar registros offline**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, após cadastrar um peixe no offline é possível vê-lo no mapa mesmo sem ter sido revisado ?**

**Resposta:** Não. 

*"Como descrito acima, não é possível criar registros offline tampouco visualizá-los."*

4. **Buffer no mapa**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, cada vez que eu  aba de mapas é aberta a localização dos peixes está diferente?**

**Resposta:** *"Conseguí visualizar o mapa e os pontos nos quais fiz alguns registros das espécies estão aparecendo para mim no mapa. O mapa portanto carrega 
corretamente e os registros feitos online ficam visíveis no mapa para o usuário, porém não ficam visíveis na listagem de registros. Seria interessante que quando 
selecionado um registro no mapa, houvesse além do tipo de peixe um link para visualizar o registro na listagem."*

5. **Outras considerações**

**Existe alguma consideração final que deseja realizar sobre a experiência de uso?**

**Resposta:** *"Na tela de adicionar a localização a um registro solicitei em reunião que vcs tirassem a palavra marítimas do texto que aparece. No lugar de "A 
localização enviada será utilizada pelas unidades ambientais responsáveis para mapear a posição das espécies MARÍTIMAS" utilizar apenas: "A localização enviada 
será utilizada para mapeamento das espécies.""*

## Release 5 Mobile

Ambiente: Sistema Operacional Android 

### Funcionalidades 

1. **Visualizar o novo fluxo de usuário durante registros de novos peixes**

**Critério de Aceitação: Este processo está ocorrendo como o esperado, ou seja, após clicar no botão "Criar Novo Registro", as opções de escolha entre conhece e não conhece o nome do peixe aparecem?**

**Resposta:** 

2. **Opção "Sim, conheço" (o nome do peixe encontrado)**

**Critério de Aceitação: O processo de selecionar esta opção está ocorrendo como o esperado, ou seja, após selecioná-la, a tela de registro proposta para esta opção aparece de acordo com o esperado?**

**Resposta:** 

3. **Opção "Não conheço" (o nome do peixe encontrado)**

**Critério de Aceitação: O processo de selecionar esta opção está ocorrendo como o esperado, ou seja, após selecioná-la, a tela de registro proposta para esta opção aparece de acordo com o esperado?**

**Resposta:**

## Release 1 - Web




## Referências
- Testes de aceitação: conhecendo e aplicando. Disponível em: <[http://www.unimep.br/~anbelgamo/SQA/2-QualidProduto.pdf](https://www.devmedia.com.br/testes-de-aceitacao-conhecendo-e-aplicando/26959)>. Acesso em: set, 2022.
- Testes de Software. Eduardo Figueiredo. Disponível em: <[https://pt.wikipedia.org/wiki/ISO/IEC_9126#:~:text=ISO%2FIEC%209126%20%C3%A9%20uma,das%20normas%20da%20fam%C3%ADlia%209000](https://homepages.dcc.ufmg.br/~figueiredo/disciplinas/aulas/testes-software_v01.pdf)>. Acesso em: set, 2022.
- Teste funcional. Disponível em: <[https://jkolb.com.br/wp-content/uploads/2014/02/NBR-ISO_IEC-9126-1.pdf](https://pt.wikipedia.org/wiki/Teste_funcional)>. Acesso em: set, 2022.
