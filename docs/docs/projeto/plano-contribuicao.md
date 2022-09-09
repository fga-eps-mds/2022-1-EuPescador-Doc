# Plano de Contribuição

Para contribuir com o projeto basta clonar o repositório e seguir as políticas listadas abaixo.

## 1. Commit

Devem ser escritos em português na forma infinitiva contendo uma breve descrição do que foi modificado referenciando a Issue trabalhada.

```
$ git commit -m "Esse é um exemplo"
```

Caso o commit tenha sido feito em cooperação com alguém, deve ser feita a co-autoria:

```
$ git commit -m "Esse é um exemplo
>
>
Co-authored-by: name <name@example.com>
Co-authored-by: another-name <another-name@example.com>"
```
---

## 2. Pull request

Devem obedecer o template de pull request:

- Nome do Pull Request

O nome do pull request deve ser constituído por número da issue relacionada e seu nome.

```
#X nome da issue
```

- Conteúdo do Pull Request

O conteúdo do pull request deve ser constituído de uma lista contendo as principais modificações feitas.

```
Nesse pull request foi feito:

História #25
Issue #32
Correção de bugs
```

- Critério de aceitação

Ex:
- [x] Testes criados.
- [x] testes passando.
- [x] build passando.

---

## 3. Issue

Deve obedecer o template para uma nova funcionalidade, ou bug report caso ocorra um bug e deve ter o máximo de indicadores do que se trata:

### Nome da issue ou operação

#### Descrição:
Pequena e objetiva descrição sobre a issue.

#### Tarefas
Seção para tarefas (tasks) para issues mais complexas ou sub-tarefas. 
- [ ] Implementação do Login.
- [ ] Implementação do Cadastro.
- [ ] Redefinir senha.
- [ ] Alguma outra tarefa.

#### Comentários ou Observações
Alguma informação necessária para melhor compreensão.

---

## 4. Branch

- O nome deve remeter ao nome da issue que ela procura solucionar e em inglês;

- Os espaços entre palavras devem ser substituídos por hífen;

```
branch-name-example
```






