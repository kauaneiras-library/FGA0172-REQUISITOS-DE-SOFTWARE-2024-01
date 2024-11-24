# Backward-from

## Introdução

Conforme SAYÃO e LEITE (2005), a rastreabilidade dos requisitos se refere à técnica que define seu relacionamento com a arquitetura do sistema, o que garante maior facilidade para os desenvolvedores identificarem o atendimento ou não do projeto aos requisitos elicitados. Dessa forma, a pós-rastreabilidade, trabalhada nessa etapa, atua no ciclo de vida dos requisitos de forma a ligá-los às implementações realizadas.
Assim, o artefato presente estabelece a rastreabilidade backward-from, que olha “para trás" ou "a partir de”, ou seja, busca ligar o requisito elicitado a fonte de onde ele deriva. 


## Metodologia

Para construir a matriz de rastreabilidade *backward-from* (SAYÃO e LEITE 2005), foi utilizada a [baseline](./baseline.md) de requisitos. A rastreabilidade de requisitos pode ser definida como a capacidade de acompanhar e descrever a vida de um requisito. No contexto da disciplina, iremos ligar os requisitos às técnicas de elicitação que os originaram, durante a etapa 2 do projeto.

A divisão dos requisitos para a construção da matriz foi a mesma definida anteriormente na baseline e pode ser encontrada na Tabela 1.

<center>

**Tabela 1**: Divisão dos requisitos

| Integrante          | Requisitos                        |
|---------------------|-----------------------------------|
| Davi Pierre         | R1, R7, R13, R19, R25, R31 e R37  |
| Guilherme Westphall | R2, R8, R14, R20, R26, R32 e R38  |
| Kallyne Macedo      | R3, R9, R15, R21, R27, R33 e R39  |
| Kauan Eiras         | R4, R10, R16, R22, R28, R34 e R40 |
| Leonardo Aguiar     | R5, R11, R17, R23, R29, R35 e R41 |
| Lucas Martins       | R6, R12, R18, R24, R30, R36 e R42 |

**Autor**: [Guilherme Westphall](https://github.com/west7), 2024.

</center>

## Backward-from dos requisitos

Nesta seção, está disposta a matriz de rastreabilidade *backward-from*, na Tabela 2 a seguir.

<center>

**Tabela 2**: Backward-from de requisitos


 | ID  | Tipo | Descrição                                                                                                                                                                                           | Técnicas                                                                                                                                                                                                                                                                                                   |
 |-----|------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
 | R1  | RF   | O aplicativo deve possuir uma barra de pesquisa                                                                                                                                                     | [OBS01](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS23](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R2  | RF   | O aplicativo deve ter opção de navegação anônima                                                                                                                                                    | [OBS02](../elicitacao/tecnicas/observacao.md#tabela-2-requisitos-funcionais)                                                                                                                                                                                                                               |
 | R3  | RF   | O aplicativo deve possuir opção de visualizar e agrupar guias                                                                                                                                       | [OBS03](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS13](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R4  | RF   | O aplicativo deve possuir opção de favoritar sites                                                                                                                                                  | [OBS04](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R5  | RF   | O aplicativo deve possuir histórico de navegação                                                                                                                                                    | [OBS05](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS24](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R6  | RF   | O aplicativo deve possuir histórico de downloads                                                                                                                                                    | [OBS06](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R7  | RF   | O aplicativo deve possibilitar a instalação de extensões de uso                                                                                                                                     | [OBS07](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS09](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R8  | RF   | O aplicativo deve possuir opção de  sincronizar e salvar dados inseridos                                                                                                                            | [OBS08](../elicitacao/tecnicas/observacao.md#tabela-2-requisitos-funcionais), [BRS03, BRS14](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [QST01](../elicitacao/tecnicas/questionario.md#resultado)                                                                            |
 | R9  | RF   | O aplicativo deve permitir visualização dos sites em formato desktop                                                                                                                                | [OBS09](../elicitacao/tecnicas/observacao.md#tabela-2-requisitos-funcionais)                                                                                                                                                                                                                               |
 | R10 | RF   | O aplicativo deve permitir a criação de atalhos na tela inicial do dispositivo                                                                                                                      | [OBS10](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [ENT10](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista)                                                                                                                                            |
 | R11 | RF   | O aplicativo deve oferecer sugestões personalizadas de pesquisa                                                                                                                                     | [OBS12](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS15](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R12 | RF   | O aplicativo deve permitir a personalização da tela inicial do navegador                                                                                                                            | [OBS13](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS22](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R13 | RF   | O aplicativo deve suportar a mudança de idioma do sistema                                                                                                                                           | [OBS14](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R14 | RF   | O aplicativo deve permitir a alternação entre tema claro e escuro                                                                                                                                   | [OBS15, OBS16](../elicitacao/tecnicas/observacao.md#tabela-2-requisitos-funcionais), [QST04](../elicitacao/tecnicas/questionario.md#resultado)                                                                                                                                                             |
 | R15 | RF   | O aplicativo deve possuir suporte para atalhos de gestos                                                                                                                                            | [OBS18](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R16 | RF   | O aplicativo deve possibilitar a troca de conta do usuário                                                                                                                                          | [OBS20](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R17 | RF   | O aplicativo deve permitir a alteração da senha da conta do usuário                                                                                                                                 | [OBS21](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R18 | RF   | O aplicativo deve permitir ao usuário limpar seu histórico de navegação                                                                                                                             | [OBS22](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R19 | RF   | O aplicativo deve permitir ao usuário limpar seus dados inseridos e de navegação                                                                                                                    | [OBS23](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R20 | RF   | O aplicativo deve permitir a habilitação e bloqueio de notificações                                                                                                                                 | [OBS24](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R21 | RF   | O aplicativo deve permitir alterar a fonte de texto em tipo e tamanho                                                                                                                               | [OBS26](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [OBS19](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                   |
 | R22 | RF   | O aplicativo deve incluir opção de bloquear anúncios                                                                                                                                                | [OBS27](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS08](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [QST02](../elicitacao/tecnicas/questionario.md#resultado)                                                                                            |
 | R23 | RF   | O aplicativo deve incluir opção de busca interna na página                                                                                                                                          | [OBS28](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R24 | RF   | O aplicativo deve incluir opção de pesquisa por voz                                                                                                                                                 | [OBS29](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R25 | RF   | O aplicativo deve possuir opção de leitura da página em voz alta                                                                                                                                    | [OBS30](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS11](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R26 | RF   | O aplicativo deve possuir opção de controle parental de acesso das páginas                                                                                                                          | [OBS32](../elicitacao/tecnicas/observacao.md#tabela-2-requisitos-funcionais), [BRS18](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                              |
 | R27 | RF   | O aplicativo deve oferecer opção de impressão de páginas                                                                                                                                            | [OBS33](../elicitacao/tecnicas/observacao.md#requisitos_elicitados)                                                                                                                                                                                                                                        |
 | R28 | RF   | O aplicativo deve conter opção de traduzir o idioma das páginas                                                                                                                                     | [OBS34](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS10](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                       |
 | R29 | RF   | O aplicativo deve permitir sincronização de dados pessoais com a conta do Google                                                                                                                    | [ENT01](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista), [BRS07](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [QST01](../elicitacao/tecnicas/questionario.md#resultado)                                                                     |
 | R30 | RF   | O aplicativo deve oferecer opção de navegação através de rede privada virtual (VPN)                                                                                                                 | [ENT03](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista)                                                                                                                                                                                                                 |
 | R31 | RF   | O aplicativo deve simular, para desenvolvedores, suas aplicações em outros navegadores                                                                                                              | [ENT08](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista)                                                                                                                                                                                                                 |
 | R32 | RF   | O aplicativo deve ser compatível com os sistemas IOS e Android                                                                                                                                      | [BRS05, BRS20](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                                                     |
 | R33 | RF   | O aplicativo deve conter uma ferramenta de correção ortográfica                                                                                                                                     | [BRS19](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                                                            |
 | R34 | RNF  | O aplicativo deve ser leve                                                                                                                                                                          | [ENT04](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista), [QST03](../elicitacao/tecnicas/questionario.md#resultado)                                                                                                                                                      |
 | R35 | RNF  | O aplicativo deve permitir acesso rápido a sites acessados recentemente                                                                                                                             | [ENT05](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista), [BRS24](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                |
 | R36 | RNF  | O aplicativo deve apresentar um design arredondado                                                                                                                                                  | [ENT06](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista)                                                                                                                                                                                                                 |
 | R37 | RNF  | O aplicativo deve possuir modo alternativo de cores para daltônicos                                                                                                                                 | [ENT07](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista), [BRS17](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                |
 | R38 | RNF  | A interface do aplicativo deve apresentar abas quadradas, animações suaves e uma Biblioteca que oferece acesso rápido a itens salvos, como favoritos, histórico, downloads, abas e capturas de tela | [ENT09](../elicitacao/tecnicas/entrevista.md#tabela-6-requisitos-elicitados-na-entrevista), [QST06](../elicitacao/tecnicas/questionario.md#tabela-3-requisitos-elicitados-na-entrevista)                                                                                                                   |
 | R39 | RNF  | O aplicativo deve ser rápido                                                                                                                                                                        | [BRS01](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                                                            |
 | R40 | RNF  | O aplicativo deve gerir bem a memória                                                                                                                                                               | [BRS02](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                                                            |
 | R41 | RNF  | O aplicativo deve apresentar proteção contra ataques maliciosos 24 horas por dia, 7 dias da semana, conforme comprovado por um sistema de segurança                                                 | [OBS36](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [OBS37](../elicitacao/tecnicas/observacao.md#requisitos_elicitados), [BRS16](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados), [BRS06](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados) |
 | R42 | RNF  | O usuário deve conseguir acessar qualquer parte do sistema em no máximo três cliques                                                                                                                | [BRS12, BRS21](../elicitacao/tecnicas/brainstorming.md#tabela-2-requisitos-elicitados)                                                                                                                                                                                                                     |


**Autor**: [Davi Pierre](https://github.com/DaviPierre), [Guilherme Westphall](https://github.com/west7), [Kallyne Macedo](https://github.com/kalipassos), [Leonardo Aguiar](https://github.com/Leonardo0o0), [Kauan Eiras](https://github.com/kauaneiras), [Lucas Martins](https://github.com/martinsglucas), 2024. 
</center>


> Legenda para tabela 2:
> 
> - CENx: Cenário nº x
> - UCx: Caso de uso nº x
> - Ex: Épico nº x
> - Tx: Tema nº x
> - USx: História de usuário nº x
> - NFRx: NFR nº x
> - Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade e +: Componentes da especificação suplementar
> - RF: Requisito Funcional
> - RNF: Requisito Não Funcional


## Referências

1. SAYÃO, Miriam; LEITE, Julio Cesar. Monografias em Ciência da Computação n° 20/05. Acesso em 16 de junho de 2024.



## Histórico de versões

| Versão | Data       | Descrição                                                                                                    | Autor                                                                                                                                                                                          | Revisor                                           |
|--------|------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|
| 1.0    | 16/06/2024 | Criação da tabela 2 e adição de requisitos 1, 2, 5, 7, 8, 11, 13, 14, 17, 19, 20, 23, 25, 29, 31, 35, 37, 41 | [Davi Pierre](https://github.com/DaviPierre), [Guilherme Westphall](https://github.com/west7), [Kauan Eiras](https://github.com/kauaneiras), [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Kallyne Macedo](https://github.com/kalipassos)   |
| 1.1    | 20/06/2024 | Corrige tabela                                                                                               | [Guilherme Westphall](https://github.com/west7)                                                                                                                                                | [Leonardo Aguiar](https://github.com/Leonardo0o0) |
| 1.2    | 21/06/2024 | Adiciona tabela 1  e Metodologia                                                                             | [Guilherme Westphall](https://github.com/west7)                                                                                                                                                | [Kallyne Macedo](https://github.com/kalipassos)   |
| 1.3    | 21/06/2024 | Adiciona versão atual do R42                                                                                 | [Lucas Martins](https://github.com/martinsglucas)                                                                                                                                              | [Kauan Eiras](https://github.com/kauaneiras)      |
| 1.4    | 23/06/2024 | Corrige links da tabela                                                                                      | [Leonardo Aguiar](https://github.com/Leonardo0o0)                                                                                                                                              | [Guilherme Westphall](https://github.com/west7)   |
| 1.5    | 21/06/2024 | Adiciona rastreabilidade dos requisitos R3, R9, R15, R21, R27, R33 e R39 a tabela 2 | [Kallyne Macedo](https://github.com/kalipassos) | [Leonardo Aguiar](https://github.com/Leonardo0o0)      |
| 1.6    | 21/06/2024 | Adiciona rastreabilidade dos requisitos R4, R10, R16, R22, R28, R34 e R40 a tabela 2 | [Kauan Eiras](https://github.com/kauaneiras) | [Leonardo Aguiar](https://github.com/Leonardo0o0)      |
| 1.7    | 21/06/2024 | Adiciona rastreabilidade dos requisitos R6, R12, R18, R24, R30, R36 e R42 a tabela 2 | [Lucas Martins](https://github.com/martinsglucas) | [Leonardo Aguiar](https://github.com/Leonardo0o0)      |
| 1.8    | 08/07/2024 | Adiciona tipo de requisito                                                                                   | [Kallyne Macedo](https://github.com/kalipassos)                                                                                                                                                | [Guilherme Westphall](https://github.com/west7)   |