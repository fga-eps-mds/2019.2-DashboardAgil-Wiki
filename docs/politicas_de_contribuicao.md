## Políticas

Contribua conosco! Basta clonar o repositório e seguir as seguintes políticas de contribuição do repositório:

- Commit
- Pull request
- Issue
- Branch

### 1. Commit

Devem ser escritos em inglês na forma infinitiva contendo uma breve decrição do que foi modificado.

```
$ git commit -m "this is an example"
```

Caso o commit tenha sido feito em cooperação com alguem, deve ser feita a co-autoria:

```
$ git commit -m "this is an example
>
>
Co-authored-by: name <name@example.com>
Co-authored-by: another-name <another-name@example.com>"
```

### 2. Pull request

Devem obedecer o template de pull request:

---

#### Nome do Pull Request

O nome do pull request deve ser constituído por número da issue relacionada e seu nome.

```
#X nome da issue
```

#### Conteúdo do Pull Request

O conteúdo do pull request deve ser constituído de uma lista contendo as principais modificações feitas.

```
Nesse pull request foi feito:

História #25
Issue #32
Correção de bugs
```

#### Critério de aceitação

Ex:
- [x] Testes criados.
- [x] testes passando.
- [x] build passando.

---

### 3. Issue

Deve obedecer o template feature request para uma nova funcionalidade, ou bug report caso ocorra um bug e deve ter o máximo de indicadores do que se trata.

Feature request:

---

#### Nome da *issue*

O nome da *issue* deve conter uma breve descrição sobre a funcionalidade a ser desenvolvida e deve ser escrita no infinitivo.

Nessa issue será realizado:
- tarefa 1
- tarefa 2
- tarefa 3

Critérios de aceitação:
- [ ] critério 1
- [ ] critério 2
- [ ] critério 3

---

Bug report:

---

#### Nome da *issue*

O nome da *issue* deve conter uma breve descrição sobre o problema a ser resolvido e deve ser escrito no infinitivo.

Nessa issue será realizado para resolver o bug:
- tarefa 1
- tarefa 2
- tarefa 3

Critérios de aceitação:
- [ ] critério 1
- [ ] critério 2
- [ ] critério 3

---

### 4. Branch

- Deve começar com o numero da issue que ela procura solucionar;

- Os espaços entre palavras devem ser substituídos por hífen;

- O nome deve remeter ao nome da issue que ela procura solucionar e em inglês.

```
30-branch-name-example
```






