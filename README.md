# ANÁLISE DO SISTEMA PORTUÁRIO E PROJEÇÃO DA PRODUTIVIDADE DOS SHIPLOADERS

> Este projeto visa otimizar a operação de terminais portuários através da análise de dados históricos e do desenvolvimento de modelos preditivos, trazendo insights críticos para a eficiência dos processos e competitividade dos portos.

<p align="center"> 
API 4° Semestre - Logística Noturno
</p> 
  
<p align="center">   
 <img src="https://img.shields.io/badge/Status%3A-ANDAMENTO-green"/>
 <a href="http://fatecsjc-prd.azurewebsites.net/"><img src="https://img.shields.io/badge/Instituição%3A-FATEC-red"/></a>
</p>

## Sumário

:small_blue_diamond: [Aprendizado por Projeto Integrado (API)](#aprendizado-por-projeto-integrado-api)  
:small_blue_diamond: [Equipe](#equipe)  
:small_blue_diamond: [Descrição do Projeto](#descrição-do-projeto)  
:small_blue_diamond: [Backlog do Produto](#backlog-do-produto)  
:small_blue_diamond: [Organização e Metodologia](#organização-e-metodologia)  
:small_blue_diamond: [Resultado e Produto](#resultado-e-produto)  
:small_blue_diamond: [Tecnologias Utilizadas](#tecnologias-utilizadas)  

## Aprendizado por Projeto Integrado (API) 
A Aprendizagem por Projetos Integrados (API) é uma metodologia de ensino em implantação na Fatec São José dos Campos, desenhada para aprimorar o aprendizado prático e desenvolver habilidades essenciais nos estudantes. Baseada nos princípios ágeis do framework **SCRUM**, a API foca na criação de um ambiente de aprendizado onde a **Proatividade**, **Autonomia**, **Colaboração** e **Entrega de Resultados** são estimulados e fortalecidos.

### Pilares da Metodologia API
A API é construída sobre três pilares fundamentais:
1. **Real Problem Based Learning (rPBL):** Adota o aprendizado baseado em problemas reais, onde os estudantes trabalham em projetos com situações concretas e desafiadoras, preparando-os para o mercado de trabalho.
2. **Validação Externa:** Valoriza a validação dos resultados por profissionais e especialistas externos, trazendo uma visão prática e crítica que auxilia os estudantes a alinhar o que aprendem com o que é realmente esperado na prática profissional.
3. **Mindset Ágil (Agile):** Utiliza práticas ágeis para a gestão e desenvolvimento dos projetos, incentivando um pensamento flexível, adaptável e orientado a resultados.

### Objetivos
A API busca criar uma experiência educacional dinâmica e envolvente, promovendo o desenvolvimento de habilidades fundamentais para o mercado de trabalho atual. Através do uso de SCRUM, os estudantes experimentam uma metodologia de trabalho colaborativa e iterativa, essencial para atender demandas complexas e em constante mudança.

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>

## Equipe

|            							| Aluno         | Função | LinkedIn & GitHub          		
| -------------------------------------------- | ---------------- | ---------------- |  ----------------
| <img src = "./imagens_git/photo-rebeca.png" width="60" >|__Rebeca Abreu__  | *Product Owner*  | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rebeca-fonseca-0615a1277) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/rebecafonsec4)
| <img src = "./imagens_git/photo-jess.png" width="60" >|__Jessica Tinoco__| *Scrum Master* | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jessica-tinoco-534589235/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/jehbernardo)
| <img src = "./imagens_git/photo-joao.png" width="60" >|__João Pedro__  | *Developer Team*  | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-pedro-cardoso-de-oliveira-a1a64a1a1) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoaoCardoli)
| <img src = "./imagens_git/photo-laine.png" width="60" >|__Elaine Gonçalves__  | *Developer Team* | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/elaine-gon%C3%A7alves-41111b253) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/ElaineGoncalves1)
| <img src = "./imagens_git/photo-joy.png" width="60" >|__Joyce Prudêncio__ | *Developer Team* | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joyce-prudencio) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JPrudencio)
| <img src = "./imagens_git/photo-avila.png" width="60" >|__Vitor Ávila__ | *Developer Team* | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/vitor-%C3%A1vila-16418339) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/vitor-avila-github/vitor-avila-github)
| <img src = "./imagens_git/photo-hugo.png" width="60" >|__Vitor Hugo__ | *Developer Team* | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/mwlite/in/vitor-hugo-caetano-das-merc%C3%AAs-195823137) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/vhsjc)
| <img src = "./imagens_git/photo-nicoli.png" width="60" >|__Nicolli Paparazo__ | *Developer Team* | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/nicolli-paparazo-b6a360261?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/nicollipaparazo)

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>

## Descrição do Projeto

<div id="top"></div>
<p align="center">
      <img src="./imagens_git/apresentacao_API4-imagens-3.jpg" width="100%" height="100%">
<p align="center">

> A Análise do Sistema Portuário e Projeção da Produtividade dos Shiploaders tem como objetivo investigar a produtividade de carregadores de navios (shiploaders) e fornecer uma ferramenta que auxilie na análise para tomada de decisões estratégicas

### Objetivo

- **Análise de Dados Históricos (2014-2023):** Compilar e limpar dados das operações de carga a granel.
- **Modelos Preditivos de Produtividade:** Criar modelos que possam prever a produtividade futura dos shiploaders.
- **Ranking de Eficiência:** Classificar os 10 principais portos com base na capacidade operacional e na taxa de movimentação.

### Funcionalidades

- **Visualização de Dados:** Painel em Business Intelligence (BI) para monitoramento de métricas de desempenho operacional.
- **Análise de Tendências:** Projeções da produtividade dos shiploaders ao longo do tempo.
- **Ranking de Eficiência:** Classificação dos portos utilizando Análise Envoltória de Dados (DEA) para identificar os mais eficientes.

### Indicadores de Desempenho (KPIs)

<div id="top"></div>
<p align="center">
      <img src="./imagens_git/apresentacao_API4-imagens-5.jpg" width="100%" height="100%">
<p align="center">

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>

## Backlog do Produto

Principais itens do backlog:

1. **Agregação de Dados Históricos:** Coleta e formatação dos dados operacionais dos portos de 2014 a 2023.
2. **Painel de Indicadores de Desempenho:** Desenvolvimento de uma interface para visualizar métricas como tempo de operação e produtividade.
3. **Modelo de Produtividade dos Shiploaders:** Análise das taxas de movimentação e criação de modelos preditivos.
4. **Ranking de Eficiência Portuária:** Análise e classificação dos 10 principais portos com base na eficiência.
5. **Compartilhamento do Código:** Publicação do código no Google Colab para transparência e reprodutibilidade.

### Requisitos Funcionais

1. **Agregação de Dados Históricos**
   - O sistema deve ser capaz de compilar dados operacionais dos portos de 2014 a 2023.
   - Deve realizar a limpeza e formatação dos dados para análise posterior.
2. **Painel de Indicadores de Desempenho (KPIs)**
   - O sistema deve apresentar um painel de visualização que exiba os principais indicadores, como produtividade dos shiploaders, tempo médio de operação, tempo de espera e taxa de ociosidade.
   - O painel deve permitir que o usuário selecione períodos específicos para análise detalhada.
3. **Modelo de Produtividade dos Shiploaders**
   - O sistema deve gerar projeções de produtividade dos shiploaders com base em dados históricos.
4. **Ranking de Eficiência Portuária**
   - O sistema deve classificar os 10 principais portos de acordo com eficiência operacional, utilizando Análise Envoltória de Dados (DEA).
5. **Compartilhamento do Código no Google Colab**
   - O código e as análises devem ser disponibilizados no Google Colab para fácil acesso e reprodutibilidade por outros usuários.

### Requisitos Não Funcionais

1. **Usabilidade**
   - O painel de visualização de KPIs deve ser intuitivo, permitindo que usuários com pouco conhecimento técnico interpretem facilmente as métricas exibidas.
   - O sistema deve seguir uma interface de design clara e de fácil navegação.
2. **Segurança**
   - A visualização dos dados deve ser restrita a usuários autorizados.
3. **Compatibilidade**
   - O sistema deve ser compatível com as principais ferramentas de visualização de dados (como Google Colab e BI Tools).
   - A interface e funcionalidades devem ser acessíveis em diferentes navegadores e sistemas operacionais.

> [!NOTE]
> **Entregáveis por Sprint**

| Período        | Entregável                                           |
|----------------|------------------------------------------------------|
| 27 Set – 18 Out | Série Histórica de Dados compilada e limpa (2014-2023) |
| 18 Out – 08 Nov | Protótipo do Painel em BI com principais métricas    |
| 08 Nov – 29 Nov | Modelo de Ranking de Eficiência usando DEA           |

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>

## Organização e Metodologia

### Metodologia Aplicada

<div id="top"></div>
<p align="center">
      <img src="./imagens_git/apresentacao_API4-imagens-4.jpg" width="100%" height="100%">
<p align="center">

> Este projeto foi realizado conforme a metodologia ágil, utilizando o software Jira para a organização e acompanhamento das tarefas de cada membro da equipe; durante cada sprint, uma série de atividades eram designadas, com data de início e data limite, possibilitando a análise do tempo gasto em cada uma delas, e, do desempenho dos integrantes.

### Cronograma e Sprints

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
|Kick Off | 02/09/2024 | Concluído|| 
|Sprint 1| 18/10/2024|Concluído |[Ver Relatório](https://github.com/LuxLogistic/Lux_Logistic_API4/blob/main/Task%20Oriented%20Documentation.docx) | 
|Sprint 2| 08/11/2024 |Concluído |[Ver Relatório](https://github.com/LuxLogistic/Lux_Logistic_API4/blob/main/Task%20Oriented%20Documentation.docx) | 
|Sprint 3| 29/11/2024 |Em andamento |[Ver Relatório](https://github.com/LuxLogistic/Lux_Logistic_API4/blob/main/Task%20Oriented%20Documentation.docx)  | 
|Feira de Soluções|12/12/2024 |Em breve || 

<details>
<summary>Sprint 01</summary>

>Backlog
<div id="top"></div>
<p align="center">
      <img src="./imagens_git/backlog-sprint1.png" width="70%" height="30%">
<p align="center">
  
>Burndown Chart
<div id="top"></div>
<p align="center">
      <img src="./imagens_git/burndown-sprint1.png"  width="80%" height="40%">
<p align="center">
 
</details>

<details>
<summary>Sprint 02</summary>

>Backlog
<div id="top"></div>
<p align="center">
      <img src="./imagens_git/backlog-sprint2.png" width="70%" height="30%">
<p align="center">
  
>Burndown Chart
<div id="top"></div>
<p align="center">
      <img src="./imagens_git/burndown-sprint2.png"  width="80%" height="40%">
<p align="center">
 
</details>

<details>
<summary>Sprint 03</summary>

>Backlog
<div id="top"></div>
<p align="center">
      <img src="./imagens_git/backlog-sprint3.png" width="70%" height="30%">
<p align="center">
  
>Burndown Chart
<div id="top"></div>
<p align="center">
      <img src="./imagens_git/burndown-sprint3.png"  width="80%" height="40%">
<p align="center">
 
</details>

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>

## Resultado e Produto

### MVP - Minimum Viable Product

<details> 
<summary> 1ª SPRINT </summary>
![Nome do Vídeo]()
</details>

<details>
<summary> 2ª SPRINT </summary>

[📹 Assista ao vídeo da 2ª Sprint](videos_mvp/mvp-sprint2c.mp4)

</details>

<details>
<summary> 3ª SPRINT </summary>
![Nome do Vídeo]()
</details>

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>

## Tecnologias Utilizadas

<p align="center">   
 <a href="https://www.atlassian.com/software/jira"><img src="./imagens_git/logo-jira.png" width="7%" height="7%"/></a>
 <a href="https://www.python.org/"><img src="./imagens_git/logo-python.png" width="8%" height="8%"/></a>
 <a href="https://jupyter.org/"><img src="./imagens_git/logo-googlecolab.png" width="8%" height="8%"/></a>
</p>
<p align="center">    
 <a href="https://powerbi.microsoft.com/pt-br/"><img src="./imagens_git/logo-powerbi.png" width="7%" height="7%"/></a>
 <a href="https://posit.co/download/rstudio-desktop/"><img src="./imagens_git/logo-rstudio.png" width="7%" height="7%"/></a>
 <a href="https://posit.co/download/rstudio-desktop/"><img src="./imagens_git/logo-slack.png" width="7%" height="7%"/></a>
</p>

<p align="right">(<a href="#sumário">voltar ao topo</a>)</p>
