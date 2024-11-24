# Verificação da Entrega 4 - "Modelagem Ágil"

## Introdução

Este documento aborda a verificação da Entrega 4, intitulada "Modelagem Ágil". Esta entrega inclui os artefatos de [Backlog](../../modelagem_agil/backlog.md), [Histórias de Usuário](../../modelagem_agil/historias_de_usuario/historias_de_usuario.md) e [NFR Framework](../../modelagem_agil/NFR%20Framework.md) elaborados pelo nosso grupo com base no aplicativo Firefox.

## Metodologia

Para realizar a análise dos documentos, utilizarei uma adaptação do método de "Inspeção" criado por Fagan no final da década de 1970 (MASTER2TEACH). No contexto desta disciplina, a Inspeção será composta por três das seis etapas propostas por Fagan. São elas:

1. **Planejamento**: Consiste em avaliar os artefatos e planejar as atividades de inspeção.
2. **Preparação**: Após a análise e compreensão dos artefatos, será elaborada uma lista de critérios (*checklist*) que orientará a avaliação de cada página.
3. **Inspeção**: Esta etapa envolve verificar se os artefatos atendem aos critérios estabelecidos nas *checklists*.

A fase de planejamento será realizada por meio de um estudo individual dos artefatos, pelo membro do grupo que irá produzir os *checklists* referentes à entrega ao qual foi designado. A segunda fase consiste em, de fato, produzir os *checklists* com base no que foi estudado durante a fase de planejamento e seguindo o modelo apresentado na **Tabela 1** abaixo. A última fase da inspeção será realizada por um integrante diferente daquele que produziu os *checklists*. Essa etapa consiste em verificar os artefatos e marcar o campo "Avaliação" da lista de critérios.

<center>

**Tabela 1**: Template para os checklists

| ID             | Descrição             | Referência                      | Avaliação                        |
| -------------- | --------------------- | ------------------------------- | -------------------------------- |
| ID do critério | Descrição do critério | Referência da qual foi retirado | Sim/Não/Incompleto/Não se aplica |

**Autor**: [Guilherme Westphall](https://github.com/west7)

</center>

## Objetos de Verificação

<center>

**Tabela 2**: Objetos de verificação

|                          | Versão | Data       | Descrição                             | Autor(es)                                                           | Revisor(es)     |
| ------------------------ | ------ | ---------- | ------------------------------------- | ------------------------------------------------------------------- | --------------- |
| **Backlog**              | 1.3    | 05/06/2024 | Correções                             | Leonardo Aguiar                                                     | Kauan Eiras     |
| **Histórias de usuário** | 2.2    | 05/06/2024 | Correções                             | Leonardo Aguiar, Guilherme Westphall, Lucas Martins, Kallyne Macedo | Kauan Eiras     |
| **NFR Framework**        | 2.2    | 29/06/2024 | Adiciona critérios de ajuste ao NFR05 | Guilherme Westphall                                                 | Leonardo Aguiar |

**Autor**: [Guilherme Westphall](https://github.com/west7)

</center>

## Checklists

Nesta seção, serão dispostos os checklists dos artefatos da Entrega 4 nas tabelas 3, 4 e 5. Durante a inspeção, o responsável deverá preencher o campo de avaliação da seguinte maneira: 

>- **Sim**, se o critério foi totalmente atendido. 
>- **Não**, se o critério não foi atendido. 
>- **Incompleto**, se o critério foi parcialmente atendido, explicando em qual parte o artefato falhou. 
>- **Não se aplica**, se o critério não pode ser verificado devido ao contexto do projeto. 

### Backlog

<center>

**Tabela 3**: Checklist do Backlog

| ID  | Descrição                                                                                                                                                                                                            | Referência                                                      | Avaliação     |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- | ------------- |
| 01  | Os itens do product backlog estão descritos, preferencialmente, no formato de histórias de usuário?                                                                                                                  | [Agile Product Managment, p. 53](../grupo_6/assets/B5.png)      | Sim           |
| 02  | Os itens do product backlog estão **detalhados adequadamente**, ou seja, os itens de maior prioridade estão refinados o suficiente (histórias de usuário), permitindo que possam ser "consumidos" na próxima sprint? | [Agile Product Managment, p. 48](../grupo_6/assets/B1.png)      | Sim           |
| 03  | Os itens do product backlog estão **estimados** em tempo e em custo?                                                                                                                                                 | [Agile Product Managment, p. 49](../grupo_6/assets/B2.png)      | Não se aplica |
| 04  | Os itens do product backlog são **emergentes**, ou seja, eles mudam de acordo com o tempo e são alterados frequentemente?                                                                                            | [Agile Product Managment, p. 49](../grupo_6/assets/B3.png)      | Não           |
| 05  | Os itens do product backlog estão **priorizados**?                                                                                                                                                                   | [Agile Product Managment, p. 49](../grupo_6/assets/B4.png)      | Sim           |
| 06  | Os itens de **alta prioridade** são encontrados no **topo da lista**?                                                                                                                                                | [Agile Product Managment, p. 49](../grupo_6/assets/B4.png)      | Sim           |
| 07  | O backlog está estruturado em **Temas** (grupo de itens relacioandos)?                                                                                                                                               | [Agile Product Managment, p. 53 e 54](../grupo_6/assets/B6.png) | Sim           |
| 08  | Os Temas do backlog estão subdivididos em **Épicos**?                                                                                                                                                                | [Agile Product Managment, p. 53 e 54](../grupo_6/assets/B6.png) | Sim           |
| 09  | Cada **Tema** contém, idealmente, **entre 2 e 5 Épicos**?                                                                                                                                                            | [Agile Product Managment, p. 53 e 54](../grupo_6/assets/B6.png) | Incompleto    |

**Autor da lista de verificação**: [Guilherme Westphall](https://github.com/west7), **Inspecionado por**: [Lucas Martins](https://github.com/martinsglucas)

</center>

#### Problemas encontrados

Os problemas encontrados no artefato de [Backlog](../../modelagem_agil/backlog.md) foram que os itens do product backlog não são emergentes (não foram alterados frequentemente). Além disso, o tema Personalização tem apenas um épico, o que não está de acordo com o critério de 2 a 5 épicos por tema.

### Histórias de usuário

<center>

**Tabela 4**: Checklist das Histórias de usuário

| ID  | Descrição                                                                                                                                                                                                                  | Referência                                                                                                               | Avaliação  |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------- |
| 01  | As histórias de usuário são **independetes**?                                                                                                                                                                              | [User Stories Applied: For Agile Software Development, p. 17](../grupo_6/assets/U1.png)                                  | Sim        |
| 02  | As histórias de usuário são **negociáveis**, ou seja, elas não representam um contrato ou um requisito obrigatório para o software. Elas podem e devem ser discutidas e ajustadas juntamente com o cliente posteriormente? | [User Stories Applied: For Agile Software Development, p. 18](../grupo_6/assets/U2.png)                                  | Sim        |
| 03  | As histórias de usuário **agregam valor para o cliente ou usuário**? Ou seja, elas estão escritas de maneira que o cliente/usuário possa entender os benefícios que serão agregados de maneira aparente?                   | [User Stories Applied: For Agile Software Development, p. 20](../grupo_6/assets/U3.png)[ e 21](../grupo_6/assets/U4.png) | Sim        |
| 04  | As histórias de usuário são **estimáveis**, os desenvolvedores conseguem ter um entendimento de forma que elas possam estimar quanto tempo levará para transformar aquela história em código real?                         | [User Stories Applied: For Agile Software Development, p. 22](../grupo_6/assets/U5.png)                                  | Incompleto |
| 05  | As histórias de usuário são **pequenas**?                                                                                                                                                                                  | [User Stories Applied: For Agile Software Development, p. 23](../grupo_6/assets/U6.png)                                  | Sim        |
| 06  | As histórias de usuário são **testáveis**?                                                                                                                                                                                 | [User Stories Applied: For Agile Software Development, p. 23](../grupo_6/assets/U7.png)                                  | Sim        |
| 07  | As histórias de usuário **são fechadas**, ou seja elas possuem **critérios de aceitação** que indicam quando uma história foi completamente implementada?                                                                  | [User Stories Applied: For Agile Software Development, p. 76 e 77](../grupo_6/assets/U8.png)                             | Sim        |
| 08  | As histórias de usuário estão no formato: **"Como [quem], quero [o que] para [por quê]"**?                                                                                                                                 | [REtraining. Histórias de usuário.](../grupo_6/assets/U9.png)                                                            | Sim        |

**Autor da lista de verificação**: [Guilherme Westphall](https://github.com/west7), **Inspecionado por**: [Lucas Martins](https://github.com/martinsglucas)

</center>

#### Problemas encontrados

O único problema encontrado nas [Histórias de Usuário](../../modelagem_agil/historias_de_usuario/historias_de_usuario.md) foi que as histórias de usuário não são estimáveis, ou seja, os desenvolvedores não conseguem ter um entendimento de forma que possam estimar quanto tempo levará para transformar aquela história em código real.

### NFR Framework

<center>

**Tabela 5**: Checklist do NFR Framework

| ID  | Descrição                                                                                                                                                          | Referência                                      | Avaliação  |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------- | ---------- |
| 01  | O **SIG (Softgoal Interdependency Graph)** foi feito?                                                                                                              | [NFR4ES, p. 30 e 31](../grupo_6/assets/N10.png) | Sim        |
| 02  | No SIG, os **Softgoals NFR** representam os requisitos não funcionais?                                                                                             | [NFR4ES, p. 31](../grupo_6/assets/N1.png)       | Sim        |
| 03  | No SIG, os **Softgoals NFR** são representados por **nuvens claras**?                                                                                              | [NFR4ES, p. 31 e 32](../grupo_6/assets/N4.png)  | Incompleto |
| 04  | No SIG, os **Softgoals de operacionalização** representam soluções para satisfazerem os Softgoals de NFR?                                                          | [NFR4ES, p. 31](../grupo_6/assets/N2.png)       | Incompleto |
| 05  | No SIG, os **Softgoals de operacionalização** são representados por **nuvens com linhas mais grossas**?                                                            | [NFR4ES, p. 31 e 32](../grupo_6/assets/N4.png)  | Incompleto |
| 06  | No SIG, os **Softgoals de Afirmação** fornecem razões para decisões no desenvolvimento?                                                                            | [NFR4ES, p. 31](../grupo_6/assets/N3.png)       | Incompleto |
| 07  | No SIG, os **Softgoals de Afirmação** são representados por **nuvens com linhas tracejadas**?                                                                      | [NFR4ES, p. 31 e 32](../grupo_6/assets/N4.png)  | Sim        |
| 08  | No SIG, os softgoals são refinados até produzirem **softgoals mais especializados** (operacionalização)?                                                           | [NFR4ES, p. 32](../grupo_6/assets/N5.png)       | Sim        |
| 09  | No SIG, as **contribuições** foram corretamente representadas?                                                                                                     | [NFR4ES, p. 33 e 34](../grupo_6/assets/N6.png)  | Sim        |
| 10  | No SIG, os softgoals são **rotulados** de acordo com o **procedimento de avaliação**(propagação de impactos)?                                                      | [NFR4ES, p. 38](../grupo_6/assets/N7.png)       | Sim        |
| 11  | No NFR Framework, foram usados **cartões de especificação** para exemplificar os requisitos não funcionais?                                                        | [NFR4ES, p. 45](../grupo_6/assets/N8.png)       | Sim        |
| 12  | Os cartões de especificação possuem: **ID, Classificação, Descrição, Justificativa, Origem, Critérios de ajuste, Dependências, Prioridade, Conflitos e História**? | [NFR4ES, p. 45](../grupo_6/assets/N8.png)       | Incompleto |


**Autor da lista de verificação**: [Guilherme Westphall](https://github.com/west7), **Inspecionado por**: [Lucas Martins](https://github.com/martinsglucas)

</center>

#### Problemas encontrados

Os problemas encontrados no artefato de [NFR Framework](../../modelagem_agil/NFR%20Framework.md) foram que alguns softgoals NFR não foram representados por nuvens claras e alguns softgoals de operacionalização não foram representados por nuvens com linhas mais grossas, os softgoals de afirmação não fornecem razões para decisões no desenvolvimento, mas sim um detalhamento do que é esperado, e os softgoals de operacionalização não representam completamente soluções para satisfazerem os Softgoals de NFR. Por fim, alguns cartões de especificação não possuem os critérios de ajuste.


## Referências

1. MASTER2TEACH. Fagan Inspection Methodology - Benefits of Software Inspections. Disponível em: https://www.youtube.com/watch?v=v_Lz2l_XsTQ. Acesso em: 28 de Junho 2024.
1. PICHLER, Roman. Agile Product Management with Scrum: Creating Products that Customers Love. 1. ed. Addison-Wesley Professional, 2017.
1. COHN, Mike. User Stories Applied: For Agile Software Development. Addison-Wesley Professional, 2004.
1. REtraining. Histórias de usuário. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-historias-de-usuario. Acesso em: 29 de Junho de 2024.
1. SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 29 de Junho de 2024.
1. CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.


## Histórico de versões

| Versão | Data       | Descrição                                   | Autor                                             | Revisor                                           |
| ------ | ---------- | ------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| 1.0    | 28/06/2024 | Cria página                                 | [Guilherme Westphall](https://github.com/west7)   | [Lucas Martins](https://github.com/martinsglucas) |
| 1.1    | 28/06/2024 | Adiciona chesklist do backlog               | [Guilherme Westphall](https://github.com/west7)   | [Lucas Martins](https://github.com/martinsglucas) |
| 1.2    | 29/06/2024 | Adiciona chesklist das histórias de usuário | [Guilherme Westphall](https://github.com/west7)   | [Lucas Martins](https://github.com/martinsglucas) |
| 1.3    | 29/06/2024 | Adiciona chesklist do NFR Framework         | [Guilherme Westphall](https://github.com/west7)   | [Lucas Martins](https://github.com/martinsglucas) |
| 1.4    | 01/07/2024 | Adiciona inspeção dos artefatos             | [Lucas Martins](https://github.com/martinsglucas) |   [Guilherme Westphall](https://github.com/west7)                                               |