<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0%3A05070D%2C70%3A0B1F3A%2C100%3A2878C8&height=130&section=header&text=Cau%C3%AA%20Teles&fontSize=46&fontColor=E6EDF7&fontAlignY=32&desc=ADS%20%C2%B7%20Desenvolvimento%20e%20Dados&descSize=24&descAlignY=72&animation=false" alt="Banner em degradê azul-escuro com o nome Cauê Teles e o foco em desenvolvimento de software e análise de dados"/>

</div>

# Cauê Teles

**Estudante de Análise e Desenvolvimento de Sistemas no Senac São Paulo (unidade Nações Unidas) · Objetivo: estágio em desenvolvimento de software e análise de dados · Primeira oportunidade profissional em TI**

[Início](#cauê-teles) · [Sobre](#sobre-mim) · [Formação](#formação) · [Tecnologias](#tecnologias-e-competências) · [Projetos](#projetos-em-destaque) · [Outros](#outros-repositórios) · [Contato](#contato)

---

## Sobre mim

Estudante de ADS no Senac São Paulo (unidade Nações Unidas). Foco principal em **desenvolvimento de software** e **análise de dados**; suporte técnico, infraestrutura, hardware e redes aparecem apenas como formação complementar.

Projetos acadêmicos e independentes: escopo, tecnologias e ressalvas em cada card e nos repositórios linkados.

---

## Formação

- **Análise e Desenvolvimento de Sistemas** — Senac São Paulo (unidade Nações Unidas; em andamento).
- **Formação complementar:** Operador de Computador e Front-End · Assistente de Manutenção de Computadores e Redes.

---

## Tecnologias e competências

### Aplicadas em projetos publicados

- <img src="https://cdn.simpleicons.org/openjdk/4DA6FF" width="16" alt=""> **Java** — aplicação de console do Hermes e port do SCC Fabric (Java 21 e Fabric).
- <img src="https://cdn.simpleicons.org/python/4DA6FF" width="16" alt=""> **Python** — notebook de análise exploratória e exercícios de estudo.
- **Pandas**, **Matplotlib** e **Seaborn** — limpeza, estatísticas e visualizações no projeto de análise de dados.
- <img src="https://cdn.simpleicons.org/gradle/4DA6FF" width="16" alt=""> **Gradle** — build do projeto SCC Fabric.
- <img src="https://cdn.simpleicons.org/github/4DA6FF" width="16" alt=""> **Git e GitHub** — histórico público, commits e publicação dos repositórios.

### Conhecimentos acadêmicos e formação complementar

- **SQL**, <img src="https://cdn.simpleicons.org/mysql/4DA6FF" width="16" alt=""> **MySQL** e **Oracle Database** — estudos de consultas.
- <img src="https://cdn.simpleicons.org/html5/4DA6FF" width="16" alt=""> **HTML5** e <img src="https://cdn.simpleicons.org/css/4DA6FF" width="16" alt=""> **CSS3** — formação complementar em Front-End.
- **Hardware**, **manutenção de computadores** e **redes** — formação complementar.

### Em aprendizado

- <img src="https://cdn.simpleicons.org/javascript/4DA6FF" width="16" alt=""> **JavaScript** — em estudo; a demonstração web do Hermes é de outro integrante.

---

## Projetos em destaque

### [SCC Fabric](https://github.com/teles-hub/SCC-Fabric-Portfolio)

![Java 21](https://img.shields.io/badge/Java-21-4DA6FF?style=flat-square&logo=openjdk&logoColor=E6EDF7&labelColor=0B1F3A) [![status do build no GitHub Actions](https://img.shields.io/github/actions/workflow/status/teles-hub/SCC-Fabric-Portfolio/build.yml?branch=main&style=flat-square&label=build&labelColor=0B1F3A&logo=github&logoColor=E6EDF7)](https://github.com/teles-hub/SCC-Fabric-Portfolio/actions/workflows/build.yml)

Port não oficial do mod *Super Cool Calculator* para Minecraft 1.21.1/Fabric, em Java 21. O port foca nos sistemas não combatentes do original: armazenamento, cabos e redes, terminais e análise de receitas.

- **Stack:** Java 21 · Fabric · Gradle · perfil de compatibilidade opcional com Cobblemon 1.8.4 / Cobbleverse 1.8.0 (Campfire Pot).
- **Situação:** em desenvolvimento; build verificado no CI e 13 assinaturas da API binária do Cobblemon 1.8.4 verificadas automaticamente no `check` do Gradle, **sem validação em jogo**.
- **Créditos:** mod original de [XxRonaldxX](https://github.com/xXxRonaldxXx/SuperCoolCalculator) ([MIT](https://github.com/teles-hub/SCC-Fabric-Portfolio/blob/main/LICENSE)); port independente por **Cauê Teles**.

---

### [Análise de Dados com Python](https://github.com/teles-hub/Analise-de-Dados-com-Python)

![Python](https://img.shields.io/badge/Python-4DA6FF?style=flat-square&logo=python&logoColor=E6EDF7&labelColor=0B1F3A) [![Colab: notebook](https://img.shields.io/badge/Colab-notebook-2878C8?style=flat-square&logo=googlecolab&logoColor=E6EDF7&labelColor=05070D)](https://colab.research.google.com/github/teles-hub/Analise-de-Dados-com-Python/blob/main/analise_animes_crunchyroll.ipynb)

Análise exploratória de notas e votos de animes da Crunchyroll. Resultados registrados nas saídas do notebook: **1.235 de 1.255** títulos com pelo menos um voto; média **4,15** e mediana **4,36** entre esses títulos.

<img src="https://raw.githubusercontent.com/teles-hub/Analise-de-Dados-com-Python/main/images/histograma-notas.png" alt="Histograma da distribuição das notas dos animes da Crunchyroll, com curva KDE, após a exclusão dos títulos sem votos" width="420" />

- **Stack:** Python · Pandas · Matplotlib · Seaborn · kagglehub · Colab.
- **Situação:** projeto de autoria de Cauê Teles, executável no Google Colab; revisão com apoio do Claude.
- **Limitação:** números e gráfico extraídos de saídas salvas; notebook não reexecutado nesta revisão. Base [Crunchyroll Anime Ratings](https://www.kaggle.com/datasets/filipefilardi/crunchyroll-anime-ratings), de **filipefilardi**, no Kaggle.

---

### [Projeto Hermes](https://github.com/teles-hub/Proposta-Pi)

![Java: console](https://img.shields.io/badge/Java-console-4DA6FF?style=flat-square&logo=openjdk&logoColor=E6EDF7&labelColor=0B1F3A) ![Status: Acadêmico](https://img.shields.io/badge/Status-Acad%C3%AAmico-4DA6FF?style=flat-square&labelColor=0B1F3A)

Projeto Integrador de ADS: sistema de vendas em Java de console com catálogo, carrinho, estoque, cálculo de tributos e persistência em arquivos. A interface web é uma demonstração separada, sem conexão com o núcleo Java.

- **Stack:** Java (console) · HTML5 · CSS3 · JavaScript (demo web) · Python (teste de regressão).
- **Situação:** projeto acadêmico encerrado; o [teste de regressão](https://github.com/teles-hub/Proposta-Pi/blob/main/tests/test_projeto_pi.py) verifica os cálculos e a gravação de arquivos.
- **Créditos:** **Cauê Teles** — aplicação Java; **Gabriel Roque** — interface web; **Yuri Vasconcellos** e **Murilo H. P.** — pesquisa de mercado e alíquotas; orientação do **Prof. Marcus Gália**.

---

## Outros repositórios

Repositórios de estudo e apoio:

- [Algoritmos e Programação](https://github.com/teles-hub/Algoritmos-e-Programa-o) — estudos acadêmicos em Java (62 arquivos `.java` de exercícios e atividades).
- [Aprendendo em casa](https://github.com/teles-hub/Aprendendo-em-casa) — estudos independentes de Java e Python (18 arquivos Java e 4 Python).
- [Tic-em-Trilhas](https://github.com/teles-hub/Tic-em-Trilhas) — trilhas de exercícios em Java e Python; repositório de estudo.
- [dio-lab-open-source](https://github.com/teles-hub/dio-lab-open-source) — fork de estudo da DIO; não é projeto autoral (PR de perfil aberto, não mergeado).

<details>
<summary>Atividade pública no GitHub</summary>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=teles-hub&card_width=340&hide_rank=true&show_icons=true&theme=github_dark&title_color=4DA6FF&icon_color=4DA6FF&text_color=E6EDF7&bg_color=0B1F3A&border_color=2878C8&hide_border=false" alt="Cartão de atividade pública de Cauê Teles no GitHub"/>

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=teles-hub&layout=compact&langs_count=5&card_width=340&theme=github_dark&title_color=4DA6FF&text_color=E6EDF7&bg_color=0B1F3A&border_color=2878C8&hide_border=false" alt="Linguagens mais usadas nos repositórios públicos de Cauê Teles"/>

</div>

Cards do GitHub Readme Stats, com dados dinâmicos. Se não carregarem, a atividade pública pode ser conferida no [perfil](https://github.com/teles-hub) e nos [repositórios](https://github.com/teles-hub?tab=repositories).

</details>

---

## Contato

<div align="center">

[![GitHub: teles-hub](https://img.shields.io/badge/GitHub-teles--hub-2878C8?style=for-the-badge&logo=github&logoColor=E6EDF7&labelColor=05070D)](https://github.com/teles-hub)
[![LinkedIn: Cauê Teles](https://img.shields.io/badge/LinkedIn-Cau%C3%AA%20Teles-4DA6FF?style=for-the-badge&logo=linkedin&logoColor=05070D&labelColor=05070D)](https://www.linkedin.com/in/cau%C3%AA-teles-b498b4428/)
[![Email: teles.cauers@gmail.com](https://img.shields.io/badge/Email-teles.cauers%40gmail.com-4DA6FF?style=for-the-badge&logo=gmail&logoColor=E6EDF7&labelColor=05070D)](mailto:teles.cauers@gmail.com)

</div>

São Paulo/SP.
