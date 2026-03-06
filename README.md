# Teste Técnico QA - 4Blue

Este repositório contém os resultados do teste técnico proposto pela 4Blue.

## Abordagem de teste

Foi realizada exploração funcional da aplicação com foco em:

- Validação de campos
- Fluxo de autenticação
- Mensagens de erro
- Comportamento das telas

## Resultados

Foram criados:

- 15 Casos de Teste
- 11 Bugs identificados

Os defeitos foram classificados considerando impacto no sistema (Severidade) e urgência de correção (Prioridade).

## Arquivos

Planilha contendo:

- Casos de Teste
- Resultados da execução
- Relatório de Bugs encontrados


## Ferramentas utilizadas

- Teste exploratório
- Google Sheets (documentação de testes)
- GitHub (versionamento e compartilhamento)
- Mozilla Firefox (Navegador)
- Sistema Operacional (Linux Mint 22.3 - Xfce 64-bit)


## Visualização online

Também foi disponibilizado um link para visualização da planilha no Google Sheets:https://docs.google.com/spreadsheets/d/1Gy_BH3SNANR7-RahhIR_kmjETXp-vM0g8jjueulVI_I/edit?usp=sharing


## Priorização de Correção

Os dois defeitos que eu priorizaria para correção seriam:

1. Bug-06- Criação de conta duplicada é permitida.
   Este defeito possui severidade crítica, pois permite a duplicidade de registros de usuários, o que pode gerar inconsistências na base de dados e possíveis problemas no processo de autenticação..

2. Bug-09- Criação de conta é permitida sem preencher nenhum campo.
   Este problema também possui severidade crítica, pois permite a criação de registros inválidos no sistema, comprometendo a integridade dos dados.


   
## Sugestões finais:

como sugestões de melhorias é possível incluir: alterar o título dos campos deixando caixa alta apenas a primeira letra(tanto na tela de login, quanto na tela de criação de conta), mostrar mensagens de alerta e feeedback mais intuitivas ao usuário final. Inserir nos campos da tela de cadastro de conta, quais deles são obrigatórios e máscara de formatação no campo telefone, incluir um documento como identificador único para o cadastro da conta. 
