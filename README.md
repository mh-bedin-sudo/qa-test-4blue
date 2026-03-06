# Teste Técnico QA - 4Blue

Este repositório contém os resultados do teste técnico proposto pela empresa 4Blue, com foco na análise funcional da aplicação, identificação de defeitos e documentação dos testes realizados.

## Abordagem de teste

Foi realizada uma exploração funcional da aplicação com foco nos seguintes pontos:

* validação de campos
* fluxo de autenticação
* mensagens de erro e feedback ao usuário
* comportamento das telas

A exploração teve como objetivo identificar falhas de funcionalidade, inconsistências de validação e possíveis problemas na experiência do usuário.

## Resultados

Durante a análise da aplicação foram elaborados:

* 15 casos de teste
* 11 bugs identificados

Os defeitos foram classificados considerando dois critérios:

* severidade: impacto técnico do problema no sistema
* prioridade: urgência de correção considerando o impacto para o negócio

## Arquivos

A planilha disponibilizada contém:

* casos de teste
* resultados da execução dos testes
* relatório de bugs identificados durante a exploração

## Ferramentas utilizadas

* teste exploratório
* Google Sheets para documentação dos testes
* GitHub para versionamento e compartilhamento do material
* Mozilla Firefox como navegador utilizado nos testes
* sistema operacional Linux Mint 22.3 XFCE 64-bit

## Visualização online

Também foi disponibilizado um link para visualização da planilha diretamente no Google Sheets:

https://docs.google.com/spreadsheets/d/1Gy_BH3SNANR7-RahhIR_kmjETXp-vM0g8jjueulVI_I/edit?usp=sharing

## Priorização de correção

Entre os defeitos identificados, dois apresentaram maior criticidade e deveriam ser priorizados para correção.

Bug-06 – criação de conta duplicada permitida.

Esse defeito possui severidade crítica, pois permite a duplicidade de registros de usuários. Esse comportamento pode gerar inconsistências na base de dados e possíveis problemas no processo de autenticação e gerenciamento de contas.

Bug-09 – criação de conta permitida sem preenchimento de campos.

Esse problema também possui severidade crítica, pois permite a criação de registros inválidos no sistema, comprometendo a integridade dos dados e a confiabilidade da base de usuários.

## Sugestões de melhoria

Durante a análise também foram identificadas algumas oportunidades de melhoria na aplicação:

* padronizar os títulos dos campos utilizando letra maiúscula apenas na primeira palavra, tanto na tela de login quanto na tela de criação de conta
* melhorar as mensagens de alerta e feedback para torná-las mais claras ao usuário
* tornar obrigatórios os campos da tela de cadastro de conta
* inserir máscara de formatação no campo de telefone
* incluir um identificador único (por exemplo um documento) para evitar duplicidade no cadastro de contas
