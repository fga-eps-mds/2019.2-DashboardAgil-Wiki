# Arquitetura
Versão 1.4 

## Histórico de revisão

Data | Versão | Descrição | Autor
----: | :------: | --------- | -----
26/09/19 | 1.0 | Iniciando documento, formatação | Ailamar Alves, Matheus Amaral
26/09/19 | 1.1 | Adição dos tópicos de 1 à 1.5 | Ailamar Alves, Matheus Amaral
29/09/19 | 1.2 | Adição dos tópicos 3.2, 7 | Matheus Amaral
29/09/19 | 1.3 | Adição dos tópicos 2 e 3.1 | João Victor
30/09/19 | 1.4 | Adição do tópico 1.4 | Ailamar Alves

## Índice

1. Introdução <br />
  1.1 Finalidade <br />
  1.2 Escopo <br />
  1.3 Definições, Acrônimos e Abreviações <br />
  1.4 Referências <br />
  1.5 Visão Geral <br />
2. Representação Arquitetural<br />
  2.1 Diagrama de Relações<br />
  2.2 Representação dos Microsserviços<br />
  2.3 Padrões<br />
  2.4 Tecnologias <br />
3. Metas e Restrições da Arquitetura <br />
  3.1 Restrições Tecnológicas <br />
  3.2 Requisitos Não Funcionais <br />
4. Visão de Casos de Usos<br />
    4.1 Atores de Casos de Usos <br />
    4.2 Visões de Casos de Usos <br />
    4.3 Descrições de Casos de Usos <br />
5. Visão Lógica <br />
  5.1. Visão Geral <br />
  5.2. Pacotes de Design Significativos do Ponto de Vista da Arquitetura <br />
    5.2.1 Diagrama de Pacotes <br />
    5.2.2 Diagrama de Classes <br />
6. Visão de Implementação <br />
7. Tamanho e Desempenho <br />

## 1. Introdução

### 1.1 Finalidade

Este documento tem o objetivo de fornecer uma visão arquitetural sobre o funcionamento de sistema do projeto DashOwl, transmitindo as decisões tomadas  nas etapas de criação e informando métodos utilizados para facilitar o entendimento de como atua o produto, como o caso de uso e tecnologias. 

### 1.2 Escopo

O documento descreve pontualmente a arquitetura de desenvolvimento do software DashOwl. Nele se engloba como e quais as tecnologias foram utilizadas. 
	
### 1.3 Definições, Acrônimos e Abreviações

Sigla   | Descrição
:----   | ---------
GitHub  | Plataforma de hospedagem de código-fonte
Dashboard | Painel visual que apresenta, de maneira centralizada, um conjunto informações: indicadores e suas métricas
API | Application Program Interface

### 1.4 Referências

1. MARIOTTI, Flávio Secchieri. Como documentar a arquitetura de software. Disponível em: http://www.linhadecodigo.com.br/artigo/3343/como-documentar-a-arquitetura-de-software.aspx . Acesso em: set/2019.

2. MUNIZ, Amanda; RIOS, Calebe; LIMA, Eduardo; DUARTE, Indiara; RIBEIRO, Luciana; TAIRA, Luís; GOUVEIA, Micaella; BUTERS, Samuel; PATROCINIO, Sofia. Documento de visão. Disponívem em: https://github.com/fga-eps-mds/2019.1-Gaia/blob/master/docs/projeto/DocArquitetura.md. Acesso em: set/2019.
 
3. KAMAL, Byron; CERQUEIRA, Eduardo; ALVES, Gabriel; ARAGÃO, Igor; VELUDO, Igor; MOTA, João; ARAUJO, Marcelo; ASSUNÇÃO, Matheus; SILVA, William. Documento de Visão. Disponível em: https://github.com/fga-eps-mds/2018.1-IncluCare_API/blob/master/docs/ARCHITECTURE_DOCUMENT.md. Acesso em: set/2019.
	
### 1.5 Visão Geral

Neste documento é apresentado um resumo com detalhes e esquemas do desenvolvimento do software de extensão DashOwl para o GitHub. Descrevendo as propostas e requisitos que foram necessárias, divididas nos principais tópicos que são a representação arquitetural, metas e restrições da arquitetura, visão de casos de uso e visão lógica.

---

## 2. Representação Arquitetural

### 2.1 Diagrama de Relações

![](./assets/imgs/Diagrama_arquitetura.png)
<br /> **Imagem 01 -** Representação da arquitetura através de um diagrama de relações

### 2.2 Representação dos Microsserviços

### 2.3 Padrões

O Django segue o padrão MVC que visa separar a aplicação em três partes:

* Model - Leitura e escrita de dados (interface com o banco de dados).
* View - Interface com o usuário e exibição de dados (HTML)
* Controller - Recebe e processa requisições, controla as models e views.

Porém, o Django usa uma terminologia um pouco diferente (MVT) na implementação do MVC:

* Model - mesma funcionalidade que a model no MVC
* View - gerencia a maior parte do processamento de dados, lógica e mensagens do aplicativo.
* Template -  é a camada que retorna a visão para o usuário do programa. Essa camada é composta por, HTML,CSS, javascript e etc. Geralmente linguagens focadas na apresentação do site para o usuário.

### 2.4 Tecnologias

#### 2.4.1 API do GitHub

O backend do DashOwl consumira a api do github em busca de dados sobre os repositórios. Esses dados serão processados, gerando as métricas necessárias para criação de gráficos e relatórios.

---

## 3. Metas e Restrições de Arquitetura

### 3.1 Restrições Tecnológicas

Para desenvolver o DashOwl serão utilizadas as seguintes tecnologias:

* Django - Framework de desenvolvimento para web que faz uso do padrão model-template-view
* Python - Linguagem utilizada no desenvolvimento backend da aplicação
* Docker - Tecnologia de fornecimento de contêineres, adicionando uma camada de abstração, automação e virtualização ao S.O
* JavaScript - Utilizado no desenvolvimento Web de forma dinâmica
* HTML/CSS - Utilizado no desenvolvimento Web de forma padrão e estruturado

### 3.2 Requisitos Não Funcionais

Requisito | Descrição
:----:  | ---
Integrações | A extensão deve ter integração com:<br /> - GitHub<br /> - ZenHub<br /> - Google Chrome
Comunicação | A extensão deve se comunicar com clareza e simplicidade com o usuário.

---

## 4. Visão de Casos de Uso

### 4.1 Atores de Casos de Uso

### 4.2 Visão dos Casos de Uso

### 4.3 Descrições dos Casos de Uso

---

## 5. Visão Lógica

### 5.1 Visão Geral

### 5.2 Pacotes de Design Significativos do Ponto de Vista da Arquitetura

#### 5.2.1 Diagrama de pacotes

#### 5.2.2 Diagrama de classe

##### 5.2.2.1 Diagrama de Classe do DashOwl

---

## 6. Visão de Implementação

---

## 7. Tamanho e Desempenho

O Github tem quase 100 milhões de repositórios, entre eles temos os que também utilizam o ZenHub. Tendo ciência da magnitude, o maior complicador é a ausência de banco de dados, economizando espaço, porém necessitando sempre fazer requisição nas APIs por uso.






