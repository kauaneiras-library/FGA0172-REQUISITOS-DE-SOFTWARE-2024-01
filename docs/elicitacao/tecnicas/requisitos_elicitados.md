# Requisitos Elicitados

## Introdução

A seguinte tabela contém os requisitos elicitados a partir das técnicas utilizadas. Vale ressaltar que requisitos repetidos e requisitos muito similares foram agrupados em um única célula, para fins de simplificação, porém sempre mantendo a rastreabilidade.

> Legenda:
>
> - **RF**: Requisito funcional
> - **RNF**: Requisito não funcional
> - **BRSx**: Requisito nº x elicitado pela técnica de brainstorming
> - **OBSx**: Requisito nº x elicitado pela técnica de observação
> - **ENTx**: Requisito nº x elicitado pela técnica de entrevista
> - **QSTx**: Requisito nº x elicitado pela técnica de questionário
> - **Rx**: Identificador único do requisito nº x

## Elicitação

<center>

**Tabela 1**: Requisitos elicitados pelos usuários e sua rastreabilidade 
<!-- 
| Nº  | ID  | Tipo | Descrição                                                                              | Rastreabilidade            |
| --- | --- | ---- | -------------------------------------------------------------------------------------- | -------------------------- |
| 1   | R1  | RF   | O aplicativo deve possuir uma barra de pesquisa                                        | OBS01, BRS23               |
| 2   | R2  | RF   | O aplicativo deve ter opção de navegação anônima                                       | OBS02                      |
| 3   | R3  | RF   | O aplicativo deve possuir opção de visualizar e agrupar guias                          | OBS03, BRS13               |
| 4   | R4  | RF   | O aplicativo deve possuir opção de favoritar sites                                     | OBS04                      |
| 5   | R5  | RF   | O aplicativo deve possuir histórico de navegação                                       | OBS05, BRS24               |
| 6   | R6  | RF   | O aplicativo deve possuir histórico de downloads                                       | OBS06                      |
| 7   | R7  | RF   | O aplicativo deve ser possível instalar extensões de uso                               | OBS07, BRS09               |
| 8   | R8  | RF   | O aplicativo deve possuir opção de sincronizar e salvar dados inseridos                | OBS08, BRS03, QST01, BRS14 |
| 9   | R9  | RF   | O aplicativo deve permitir visualização dos sites em formato desktop                   | OBS09                      |
| 10  | R10 | RF   | O aplicativo deve permitir a criação de atalhos na tela inicial do dispositivo         | OBS10, ENT10               |
| 11  | R11 | RF   | O aplicativo deve oferecer sugestões personalizadas de pesquisa                        | OBS12, BRS15               |
| 12  | R12 | RF   | O aplicativo deve permitir a personalização da tela inicial do navegador               | OBS13, BRS22               |
| 13  | R13 | RF   | O aplicativo deve suportar a mudança de idioma do sistema                              | OBS14                      |
| 14  | R14 | RF   | O aplicativo deve permitir a alternação entre tema claro e escuro                      | OBS15, OBS16, ENT06, QST04 |
| 15  | R15 | RF   | O aplicativo deve possuir suporte para atalhos de gestos                               | OBS18                      |
| 16  |     | RF   | O aplicativo deve possibilitar a troca de conta do usuário                             | OBS20                      |
| 17  |     | RF   | O aplicativo deve permitir a alteração da senha da conta do usuário                    | OBS21                      |
| 18  |     | RF   | O aplicativo deve permitir ao usuário limpar seu histórico de navegação                | OBS22                      |
| 19  |     | RF   | O aplicativo deve permitir ao usuário limpar seus dados inseridos e de navegação       | OBS23                      |
| 20  |     | RF   | O aplicativo deve ser permitir a habilitação e bloqueio de notificações                | OBS24                      |
| 21  |     | RF   | O aplicativo deve permitir alterar a fonte de texto em tipo e tamanho                  | OBS26, OBS19               |
| 22  |     | RF   | O aplicativo deve incluir opção de bloquear anúncios                                   | OBS27, BRS08, QST02        |
| 23  |     | RF   | O aplicativo deve incluir opção de busca interna na página                             | OBS28                      |
| 24  |     | RF   | O aplicativo deve incluir opção de pesquisa por voz                                    | OBS29                      |
| 25  |     | RF   | O aplicativo deve possuir opção de leitura da página em voz alta                       | OBS30, BRS11               |
| 26  |     | RF   | O aplicativo deve possuir opção de controle parental de acesso das páginas             | OBS32, BRS18               |
| 27  |     | RF   | O aplicativo deve oferecer opção de impressão de páginas                               | OBS33                      |
| 28  |     | RF   | O aplicativo deve conter opção de traduzir o idioma das páginas                        | OBS34, BRS10               |
| 29  |     | RF   | O aplicativo deve permitir sincronização de dados pessoais com a conta do Google       | ENT01, BRS07, QST01        |
| 30  |     | RF   | O aplicativo deve oferecer opção de navegação através de rede privada virtual (VPN)    | ENT03                      |
| 31  |     | RF   | O aplicativo deve simular, para desenvolvedores, suas aplicações em outros navegadores | ENT08                      |
| 32  |     | RF   | O aplicativo deve ser compatível com vários sistemas operacionais                      | BRS05, BRS20               |
| 33  |     | RF   | O aplicativo deve conter uma ferramenta de correção ortográfica                        | BRS19                      |
| 34  |     | RNF  | O aplicativo deve ser leve                                                             | ENT04, QST03               |
| 35  |     | RNF  | O aplicativo deve permitir acesso rápido à sites acessados recentemente                | ENT05, BRS24               |
| 36  |     | RNF  | O aplicativo deve apresentar um design arredondado                                     | ENT06                      |
| 37  |     | RNF  | O aplicativo deve possuir modo alternativo de cores para daltônicos                    | ENT07, BRS17, QST04        |
| 38  |     | RNF  | O aplicativo deve apresentar uma interface minimalista                                 | ENT09, QST06               |
| 39  |     | RNF  | O aplicativo deve ser rápido                                                           | BRS01                      |
| 40  |     | RNF  | O aplicativo deve gerir bem a memória                                                  | BRS02                      |
| 41  |     | RNF  | O aplicativo deve ser seguro                                                           | OBS36, OBS37, BRS16, BRS06 |
| 42  |     | RNF  | O aplicativo deve ser de fácil uso                                                     | BRS12, QST07, BRS21        |
 -->

| Nº  | ID      | Tipo | Descrição                                                                              | Rastreabilidade                                                                                                                                                                                                                                                |
| --- | ------- | ---- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **R1**  | RF   | O aplicativo deve possuir uma barra de pesquisa                                        | [OBS01](../tecnicas/observacao.md#requisitos-elicitados), [BRS23](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 2   | **R2**  | RF   | O aplicativo deve ter opção de navegação anônima                                       | [OBS02](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 3   | **R3**  | RF   | O aplicativo deve possuir opção de visualizar e agrupar guias                          | [OBS03](../tecnicas/observacao.md#requisitos-elicitados), [BRS13](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 4   | **R4**  | RF   | O aplicativo deve possuir opção de favoritar sites                                     | [OBS04](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 5   | **R5**  | RF   | O aplicativo deve possuir histórico de navegação                                       | [OBS05](../tecnicas/observacao.md#requisitos-elicitados), [BRS24](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 6   | **R6**  | RF   | O aplicativo deve possuir histórico de downloads                                       | [OBS06](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 7   | **R7**  | RF   | O aplicativo deve ser possível instalar extensões de uso                               | [OBS07](../tecnicas/observacao.md#requisitos-elicitados), [BRS09](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 8   | **R8**  | RF   | O aplicativo deve possuir opção de sincronizar e salvar dados inseridos                | [OBS08](../tecnicas/observacao.md#requisitos-elicitados), [BRS03](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [QST01](../tecnicas/questionario.md#resultado), [BRS14](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)           |
| 9   | **R9**  | RF   | O aplicativo deve permitir visualização dos sites em formato desktop                   | [OBS09](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 10  | **R10** | RF   | O aplicativo deve permitir a criação de atalhos na tela inicial do dispositivo         | [OBS10](../tecnicas/observacao.md#requisitos-elicitados), [ENT10](../tecnicas/entrevista.md#resultado)                                                                                                                                                         |
| 11  | **R11** | RF   | O aplicativo deve oferecer sugestões personalizadas de pesquisa                        | [OBS12](../tecnicas/observacao.md#requisitos-elicitados), [BRS15](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 12  | **R12** | RF   | O aplicativo deve permitir a personalização da tela inicial do navegador               | [OBS13](../tecnicas/observacao.md#requisitos-elicitados), [BRS22](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 13  | **R13** | RF   | O aplicativo deve suportar a mudança de idioma do sistema                              | [OBS14](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 14  | **R14** | RF   | O aplicativo deve permitir a alternação entre tema claro e escuro                      | [OBS15](../tecnicas/observacao.md#requisitos-elicitados), [OBS16](../tecnicas/observacao.md#requisitos-elicitados), [QST04](../tecnicas/questionario.md#resultado)                                                                                             |
| 15  | **R15** | RF   | O aplicativo deve possuir suporte para atalhos de gestos                               | [OBS18](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 16  | **R16** | RF   | O aplicativo deve possibilitar a troca de conta do usuário                             | [OBS20](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 17  | **R17** | RF   | O aplicativo deve permitir a alteração da senha da conta do usuário                    | [OBS21](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 18  | **R18** | RF   | O aplicativo deve permitir ao usuário limpar seu histórico de navegação                | [OBS22](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 19  | **R19** | RF   | O aplicativo deve permitir ao usuário limpar seus dados inseridos e de navegação       | [OBS23](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 20  | **R20** | RF   | O aplicativo deve permitir a habilitação e bloqueio de notificações                    | [OBS24](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 21  | **R21** | RF   | O aplicativo deve permitir alterar a fonte de texto em tipo e tamanho                  | [OBS26](../tecnicas/observacao.md#requisitos-elicitados), [OBS19](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                             |
| 22  | **R22** | RF   | O aplicativo deve incluir opção de bloquear anúncios                                   | [OBS27](../tecnicas/observacao.md#requisitos-elicitados), [BRS08](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [QST02](../tecnicas/questionario.md#resultado)                                                                                 |
| 23  | **R23** | RF   | O aplicativo deve incluir opção de busca interna na página                             | [OBS28](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 24  | **R24** | RF   | O aplicativo deve incluir opção de pesquisa por voz                                    | [OBS29](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 25  | **R25** | RF   | O aplicativo deve possuir opção de leitura da página em voz alta                       | [OBS30](../tecnicas/observacao.md#requisitos-elicitados), [BRS11](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 26  | **R26** | RF   | O aplicativo deve possuir opção de controle parental de acesso das páginas             | [OBS32](../tecnicas/observacao.md#requisitos-elicitados), [BRS18](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 27  | **R27** | RF   | O aplicativo deve oferecer opção de impressão de páginas                               | [OBS33](../tecnicas/observacao.md#requisitos-elicitados)                                                                                                                                                                                                       |
| 28  | **R28** | RF   | O aplicativo deve conter opção de traduzir o idioma das páginas                        | [OBS34](../tecnicas/observacao.md#requisitos-elicitados), [BRS10](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                 |
| 29  | **R29** | RF   | O aplicativo deve permitir sincronização de dados pessoais com a conta do Google       | [ENT01](../tecnicas/entrevista.md#resultado), [BRS07](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [QST01](../tecnicas/questionario.md#resultado)                                                                                             |
| 30  | **R30** | RF   | O aplicativo deve oferecer opção de navegação através de rede privada virtual (VPN)    | [ENT03](../tecnicas/entrevista.md#resultado)                                                                                                                                                                                                                   |
| 31  | **R31** | RF   | O aplicativo deve simular, para desenvolvedores, suas aplicações em outros navegadores | [ENT08](../tecnicas/entrevista.md#resultado)                                                                                                                                                                                                                   |
| 32  | **R32** | RF   | O aplicativo deve ser compatível com vários sistemas operacionais                      | [BRS05](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [BRS20](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                     |
| 33  | **R33** | RF   | O aplicativo deve conter uma ferramenta de correção ortográfica                        | [BRS19](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                           |
| 34  | **R34** | RNF  | O aplicativo deve ser leve                                                             | [ENT04](../tecnicas/entrevista.md#resultado), [QST03](../tecnicas/questionario.md#resultado)                                                                                                                                                                   |
| 35  | **R35** | RNF  | O aplicativo deve permitir acesso rápido a sites acessados recentemente                | [ENT05](../tecnicas/entrevista.md#resultado), [BRS24](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                             |
| 36  | **R36** | RNF  | O aplicativo deve apresentar um design arredondado                                     | [ENT06](../tecnicas/entrevista.md#resultado)                                                                                                                                                                                                                   |
| 37  | **R37** | RNF  | O aplicativo deve possuir modo alternativo de cores para daltônicos                    | [ENT07](../tecnicas/entrevista.md#resultado), [BRS17](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                             |
| 38  | **R38** | RNF  | O aplicativo deve apresentar uma interface minimalista                                 | [ENT09](../tecnicas/entrevista.md#resultado), [QST06](../tecnicas/questionario.md#resultado)                                                                                                                                                                   |
| 39  | **R39** | RNF  | O aplicativo deve ser rápido                                                           | [BRS01](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                           |
| 40  | **R40** | RNF  | O aplicativo deve gerir bem a memória                                                  | [BRS02](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                           |
| 41  | **R41** | RNF  | O aplicativo deve ser seguro                                                           | [OBS36](../tecnicas/observacao.md#requisitos-elicitados), [OBS37](../tecnicas/observacao.md#requisitos-elicitados), [BRS16](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [BRS06](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados) |
| 42  | **R42** | RNF  | O aplicativo deve ser de fácil uso                                                     | [BRS12](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [BRS21](../tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                     |

**Autor:** [Guilherme Westphall](https://github.com/west7), 2024.
</center>

## Referências

1. GNACIO, Rafael C. Guia Facetado de Técnicas de Elicitação de Requisitos: Técnicas de Elicitação de Requisitos. Universidade Federal de Santa Catarina, 2018. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-brainstorming>. Acesso em 10 de abril de 2024.

2. VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de requisitos: software orientado ao negócio. 1. ed. [S. l.]: Brasport, 2016.

3. Universidade Federal de Santa Catarina. Guia de Retreinamento - Técnicas de Elicitação de Requisitos: Observação Direta. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-observacao-direta>. Acesso em: 14 de abril de 2024.

## Histórico de versões

| Versão | Data       | Descrição                                          | Autor                                             | Revisor                                         |
| ------ | ---------- | -------------------------------------------------- | ------------------------------------------------- | ----------------------------------------------- |
| 1.0    | 19/04/2024 | Cria página                                        | [Guilherme Westphall](https://github.com/west7)   | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.1    | 19/04/2024 | Adiciona tabela 1                                  | [Guilherme Westphall](https://github.com/west7)   | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.2    | 19/04/2024 | Adiciona bibliografia                              | [Lucas Gabriel](https://github.com/martinsglucas) | [Guilherme Westphall](https://github.com/west7) |
| 1.3    | 30/05/2024 | Correções                                          | [Kauan Eiras](https://github.com/kauaneiras)      | [Guilherme Westphall](https://github.com/west7) |
| 1.4    | 05/06/2024 | Reescrita dos requisitos                           | [Kallyne Macedo](https://github.com/kalipassos)   | [Guilherme Westphall](https://github.com/west7) |
| 1.5    | 15/06/2024 | Adiciona ID para cada um dos requisitos elicitados | [Guilherme Westphall](https://github.com/west7)   | [Kauan Eiras](https://github.com/kauaneiras)    |