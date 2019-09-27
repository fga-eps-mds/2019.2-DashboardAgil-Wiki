---
title: doc_visao
---

# Visão
Versão 1.2

## Histórico de revisão


Data | Versão | Descrição | Autor
----: | :------: | --------- | -----
20/09/19 | 1.0 | Iniciando documento de visão, template | Ailamar Alves, Matheus Amaral
20/09/19 | 1.1 | Adição dos tópicos 1 e 2 | Ailamar Alves, Matheus Amaral
26/09/19 | 1.2 | Adição dos tópicos 3.2, 3.3, 3.5, 3.8 | Ailamar Alves
26/09/19 | 1.3 | Adição dos tópicos 2.2, 3.1 | Matheus Amaral

## Índice

1. Introdução </p>
	1.1 Propósito </p>
	1.2 Escopo </p>
	1.3 Definições, acrônimos e abreviações </p>
	1.4 Referências </p> 
	1.5 Visão geral </p>
2. Posicionamento </p>
	2.1 Oportunidade de Negócios </p>
	2.2 Instrução do problema </p>
	2.3 Instrução de Posição do produto </p>
3. Descrições da parte interessada e do usuário </p>
	3.1 Demografia de mercado </p>
	3.2 Resumo da parte interessada </p>
	3.3 Resumo do usuário </p>
	3.4 Ambiente do usuário </p>
	3.5 Perfis das partes interessadas </p>
	3.6 Perfis do usuário </p>
	3.7 Principais Necessidades da parte interessada ou do usuário </p>
	3.8 Alternativa e concorrência </p>
4. Visão geral do produto </p>
	4.1 Perspectiva do produto </p>
	4.2 Resumo das capacidades </p>
	4.3 Suposições e dependências </p>
	4.4 Custo e precificação </p>
	4.5 Licenciamento e Instalação </p>
5. Recursos do produto </p>
6. Restrições </p>
7. Faixas de qualidade </p>
8. Precedência e prioridade </p>
9. Outros requisitos do produto </p>
10. Requisitos de documentação </p>
11. Apêndice </p>

---

## 1. Introdução 

### 1.1 Propósito 

Este documento tem como objetivo apresentar uma visão geral sobre o desenvolvimento do Dashboard Ágil DashOwl e seu contexto de aplicação para o usuário do Github.
 
### 1.2 Escopo 
	
Para a criação do dashboard, apoś analisar versões já existentes que possuem aplicações parecidas, foi estudado como poderia ser feito melhorias, devido a falta de certas funcionalidades que seriam interessantes para o cliente.
Espera-se que, com este produto os usuários que utilizam a plataforma GitHub ao entrar em certo repositório tenham a opção de ver graficamente de acordo com a metodologia ágil um breve histórico do que foi feito e/ou está sendo feito atualmente no projeto.	
 
### 1.3 Definições, acrônimos e abreviações

Sigla   | Descrição
:----  | ---
API     | Interface de Programação de Aplicações
GitHub  | Plataforma de hospedagem de código-fonte
ZenHub  | Plataforma de gerenciamento ágil de projetos no GitHub
Agile  | Metodologia ágil

### 1.4 Referências

1. Template Documento de visão.  Disponível em: <>.  Acesso em 20/09.
 
2. IBM Knowledge Center - Documento de Visão: A estrutura de tópicos do documento de visão. Disponível em: <https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_4.0.6/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.html>. Acesso em 20/09.
 
3.

### 1.5 Visão geral

Este documento possui um breve resumo do que espera-se do produto, descrevendo sucintamente as funcionalidades e suas finalidades, sendo organizado em tópicos abordando desde as partes mais interessadas, interação com usuário, mercado, entre outros.

---

## 2. Posicionamento
### 2.1 Oportunidade de Negócios

O Agile vem sendo muito utilizado no desenvolvimento de software. além disso, um projeto do GitHub traz muitas informações difusas, ou sem nenhuma imediatez. Com isso, surge a necessidade de uma ferramenta com o toda a informação relevante sobre o projeto, juntamente de uma interface gráfica amigável para o usuário.
 
### 2.2 Instrução do Problema 


| | |
---- | :------ 
**O problema seria** | Dificuldade de encontrar dados sobre um projeto Github com uma interpretação Agile.
**Afeta** | Usuários do GitHub e possíveis novos colaboradores de um projeto no GitHub.
**Cujo impacto é** | Dificuldade em saber se tem de fato atividade em algum projeto.
**Uma boa solução seria** | Automatizar e dar uma interface amigável à pesquisa de dados, dando imediatez nesse processo.


### 2.3 Instrução de Posição do Produto 

| | |
---- | :------ 
**Para** | Usuários da plataforma GitHub.
**Que** | Têm interesse em analisar o histórico de atividades dos repositórios que estão trabalhando e/ou pretendem cooperar.
**O DashOwl** | É uma extensão do GitHub.
**Que** | Filtra em forma de gráficos os dados mais relevantes dos arquivos de acordo com a metodologia agile.
**Diferente de** | Programas já existentes que são focados na organização e gerenciamento.
**Nosso produto** | Proporciona uma facilidade na tomada de decisão em relação a contribuir ou não com o repositório em questão.

## 3 Descrições da Parte Interessada e do Usuário
### 3.1 Demografia de mercado

O Github é o maior site de controle de versão, tendo aproximadamente 100 milhões de repositórios hospedados. Em um universo de desenvolvimento de software dessa magnitude é muito útil se pensar em uma interface que em mostre todos os dados de relevância de um projeto já interpretados em forma de gráfico, facilitando a vida, dentro dos quase 40 milhões de contribuidores do Github, de todos que trabalham com Agile ou buscam indicadores de um bom projeto para contribuir. 

### 3.2 Resumo da Parte Interessada

Nome | Representa | Função
:---- | :------ | :--------- 
Equipe de desenvolvimento | Estudantes da disciplina Métodos de Desenvolvimento de Software. | Gerenciar e desenvolver o software dentro das datas definidas.
Joenio Costa e Carla Rocha | Professores da disciplina Desenvolvimento de Software. | Avaliar o andamento do projeto e a entrega final.

### 3.3 Resumo do Usuário

Nome | Representa | Função
:--- | :--------- | :------
Usuário do GitHUb | Pessoas que tem o interesse em visualizar o histórico de atividades de determinado repositório do GitHub. | Utilizar a plataforma DashOwl.

### 3.4 Ambiente do Usuário

### 3.5 Perfis das Partes Interessadas

| | |
---- | :------ 
**Representantes** | Damarcones dos Santos, Ailamar Alves, Matheus Amaral, Kalebe Lopes, João Victor de Oliveira, Murilo Schiler
**Descrição** | Desenvolvedores e gestores do projeto.
**Tipo** | Estudantes da Universidade de Brasília - FGA/Gama, matriculados na disciplina Desenvolvimento de Software.
**Responsabilidades** | Conseguir desenvolver e gerenciar o projeto de forma que seja possível a entrega com todos os requisitos prontos dentro do prazo.
**Critérios de sucesso** | Garantir ao final do período um produto de qualidade e funcionando dentro do esperado pelo cliente.
**Envolvimento** | Alto
**Comentarios / Problemas** | -

### Perfis do Usuário

| | |
---- | :------ 
**Representantes** | 
**Descrição** | 
**Tipo** | 
**Responsabilidades** | 
**Critérios de sucesso** | 
**Envolvimento** |








