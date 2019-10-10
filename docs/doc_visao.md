---
title: doc_visao
---

# Visão
Versão 1.8

## Histórico de revisão


Data | Versão | Descrição | Autor
----: | :------: | --------- | -----
20/09/19 | 1.0 | Iniciando documento de visão, template | Ailamar Alves, Matheus Amaral
20/09/19 | 1.1 | Adição dos tópicos 1 e 2 | Ailamar Alves, Matheus Amaral
26/09/19 | 1.2 | Adição dos tópicos 3.2, 3.3, 3.5, 3.8 | Ailamar Alves
26/09/19 | 1.3 | Adição dos tópicos 2.2, 3.1 | Matheus Amaral
27/09/19 | 1.4 | Adição dos tópicos 1.4, 2.3, 4.1 | Ailamar Alves
27/09/19 | 1.5 | Adição dos tópicos 3.4, 3.6, 4.3 | Damarcones dos Santos
27/09/19 | 1.6 | Adição dos tópicos 3.7, 4.2, 4,5 | Matheus Amaral, Ailamar Alves
30/09/19 | 1.7 | Adição dos tópicos 5, 6 | João Victor
30/09/19 | 1.8 | Adição dos tópicos 7, 8 | Kalebe 

## Índice

1. Introdução<br />
	1.1 Propósito<br />
	1.2 Escopo<br />
	1.3 Definições, acrônimos e abreviações<br />
	1.4 Referências<br />
	1.5 Visão geral<br />
2. Posicionamento<br />
	2.1 Oportunidade de Negócios<br />
	2.2 Instrução do problema<br />
	2.3 Instrução de Posição do produto<br />
3. Descrições da parte interessada e do usuário<br />
	3.1 Demografia de mercado<br />
	3.2 Resumo da parte interessada<br />
	3.3 Resumo do usuário<br />
	3.4 Ambiente do usuário<br />
	3.5 Perfis das partes interessadas<br />
	3.6 Perfis do usuário<br />
	3.7 Principais Necessidades da parte interessada ou do usuário<br />
	3.8 Alternativa e concorrência<br />
4. Visão geral do produto<br />
	4.1 Perspectiva do produto<br />
	4.2 Resumo das capacidades<br />
	4.3 Suposições e dependências<br />
	4.4 Licenciamento e Instalação<br />
5. Recursos do produto<br />
	5.1 Fornecer informações sobre o projeto<br/>
	5.2 Sistema de Ranking<br/>
6. Restrições<br />
	6.1 Restrições de implementação<br/>
	6.2 Restrições de design<br/>
	6.3 Restriçoes de uso<br/>
7. Faixas de qualidade<br />
8. Precedência e prioridade<br />
9. Outros requisitos do produto<br />
10. Requisitos de documentação<br />
11. Apêndice<br />

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

1. IBM Knowledge Center - Documento de Visão: A estrutura de tópicos do documento de visão. Disponível em: https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_4.0.6/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.html . Acesso em: set/2019.
 
2. MUNIZ, Amanda; RIOS, Calebe; LIMA, Eduardo; DUARTE, Indiara; RIBEIRO, Luciana; TAIRA, Luís; GOUVEIA, Micaella; BUTERS, Samuel; PATROCINIO, Sofia. Documento de visão. Disponívem em: https://github.com/fga-eps-mds/2019.1-Gaia/blob/master/docs/produto/DocVisao.md . Acesso em: set/2019.

3. KAMAL, Byron; CERQUEIRA, Eduardo; ALVES, Gabriel; ARAGÃO, Igor; VELUDO, Igor; MOTA, João; ARAUJO, Marcelo; ASSUNÇÃO, Matheus; SILVA, William. Documento de Visão. Disponível em: https://github.com/fga-eps-mds/2018.1-IncluCare_API/blob/master/docs/VISION_DOCUMENT.md#5-restri%C3%A7%C3%B5es . Acesso em: set/2019. 

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
**Nosso produto** | Proporciona uma solução gratuita, rápida e eficiente ao problema existente.

---

## 3 Descrições da Parte Interessada e do Usuário 
### 3.1 Demografia de mercado

O Github é o maior site de controle de versão, tendo aproximadamente 100 milhões de repositórios hospedados. Em um universo de desenvolvimento de software dessa magnitude é muito útil se pensar em uma interface que em mostre todos os dados de relevância de um projeto já interpretados em forma de gráfico, facilitando a vida, dentro dos quase 40 milhões de contribuidores do Github, de todos que trabalham com Agile ou buscam indicadores de um bom projeto para contribuir. 

### 3.2 Resumo da Parte Interessada

Nome | Representa | Função
:--- | :--------- | :--------- 
Equipe de desenvolvimento | Estudantes da disciplina Métodos de Desenvolvimento de Software. | Gerenciar e desenvolver o software dentro das datas definidas.
Joenio Costa e Carla Rocha | Professores da disciplina Métodos de Desenvolvimento de Software. | Avaliar o andamento do projeto e a entrega final.

### 3.3 Resumo do Usuário

Nome | Representa | Função
:--- | :--------- | :-----
Usuários do GitHub | Pessoas que tem o interesse em visualizar o histórico de atividades de determinado repositório do GitHub. | Utilizar a plataforma DashOwl.

### 3.4 Ambiente do Usuário

O projeto é uma extensão do GitHub no navegador, basta o usuário ter um navegador compatível e conexão com a internet para instalá-lo e poder acessá-lo.

### 3.5 Perfis das Partes Interessadas

| | |
---- | :------ 
**Representantes** | Damarcones dos Santos<br />Ailamar Alves<br />Matheus Amaral<br />Kalebe Lopes<br />João Victor de Oliveira<br />Murilo Schiler
**Descrição** | Desenvolvedores e gestores do projeto.
**Tipo** | Estudantes da Universidade de Brasília - FGA/Gama, matriculados na disciplina Métodos de Desenvolvimento de Software.
**Responsabilidades** | Conseguir desenvolver e gerenciar o projeto de forma que seja possível a entrega com todos os requisitos prontos dentro do prazo.
**Critérios de sucesso** | Garantir ao final do período um produto de qualidade e funcionando dentro do esperado pelo cliente.
**Envolvimento** | Alto
**Comentarios / Problemas** | -

### 3.6 Perfis do Usuário

| | |
---- | :------ 
**Representantes** | Usuários da plataforma GitHub.
**Descrição** | Interessados em acompanhar em tempo real o andamento das atividades dos repositórios.
**Tipo** | Desenvolvedores.
**Responsabilidades** | Pretensão de contribuir com o repositório de maneira a agregar e compartilhar conhecimento.
**Critérios de sucesso** | Identificar se o repositório continua a ser desenvolvido ou está “morto’.
**Envolvimento** | Alto.
**Comentarios / Problemas** | -

### 3.7 Principais Necessidades da Parte Interessada ou do Usuário

| | |
---- | :------ 
**Necessidade** | Ter uma visão panorâmica de um projeto seguindo o Agile.
**Prioridade** | Alta.
**Interesses** | Acabar com o processo de busca, dando imediatez à interpretação.
**Solução atual** | Navegar por todas as funcionalidades do GitHub manualmente.
**Solução proposta** | Uma extensão Web que seja capaz de pegar os dados  mais importantes para os gestores do Agile e devolvê-los com uma interface amigável. 

### 3.8 Alternativas e Concorrência

Atualmente já existe disponível no próprio GitHub uma sessão que indica graficamente o quantitativo de “commits” por dia feito por cada integrante do time em um repositório. Também existe a plataforma ZenHub que facilita no uso das funcionalidades do GitHub relacionadas com a organização e gerenciamento de projeto e também permite ver relatórios do Agile, entretanto essa extensão é mais focada em fazer interface com o GitHub do que transmitir visualmente interpretações Agile. 

---

## 4 Visão Geral do Produto
### 4.1 Perspectiva do Produto

O software será uma plataforma web para um dashboard ágil, em que os usuários poderão fazer o requerimento do produto instalando a extensão em seu navegador padrão. Com esta instalação o programa já estará disponível para uso.

### 4.2 Resumo das Capacidades

Benefício para o cliente | Recursos de suporte
:----------------------- | :------------------ 
Facilidade na tomada de decisão. | O acompanhamento do andamento do projeto é em real time, dando uma visão geral.
Facilidade em gerenciar um projeto seguindo o Agile. | A ferramenta suporta sistema de ranking por contribuição, Burndown, Velocity e dados periódicos sobre o desenvolvimento e sobre a gestão dos repositórios do projeto.

### 4.3 Suposições e Dependências

Incompatibilidade ou mal funcionamento em algum navegador ou sistema operacional específico, se necessário o documento será alterado para se encaixar com as especificações.

### 4.4 Licenciamento e Instalação

O DashOwl está sob a licença GNU General Public License v3.0 de softwares livres, que dá liberdade para todos que o adquirirem de modificar, distribuir, sublicenciar, vender, contribuir e concede um expressivo direito de patente para o software.

---

## 5 Recursos do Produto

### 5.1 Fornecer informações sobre o projeto, tais como:

* Porcentagem de issues abertas e/ou fechadas num período
* Período de issues abertas
* Total de pull requests abertos e/ou fechados por período

### 5.2 Sistema de ranking:

* Pontos por sprint
* Issues completas
* Pull requests
* Linhas de código

---

## 6 Restrições

### 6.1 Restrição de implementação

O software deverá ser desenvolvido usando o framework Django para a aplicação web e JavaScript para a extensão.

### 6.2 Restrição de design

O sistema devera ter uma interface amigável e de fácil usabilidade.

### 6.3 Restrição de uso

Para usar o DashOwl, o usuário deverá ter uma conexão com a internet e instalar a extensão no navegador google chrome.

---

## 7 Faixas de Qualidade

A extensão será disponibilizada na Chrome Web Store e funcionará com maior eficiência e estabilidade em dispositivos que utilizam o navegador Google Chrome como padrão, além de uma conexão estável com a internet.
 
---

## 8 Prioridade e Precedência

A prioridade da aplicação é acompanhar em tempo real os repositórios do GitHub. Além disso, a aplicação indicará graficamente as atividades feitas individualmente e pelo time com a intenção de facilitar a sua visualização e o seu monitoramento.

