# Elicitação de Requisitos: Observação

## Introdução

A técnica de observação, também chamada de análise social, envolve um usuário e um mediador com o objetivo de identificar funcionalidades do software observando o uso do aplicativo. Esta técnica fornece insights valiosos sobre as interações dos usuários, ajudando a definir requisitos mais precisos. É especialmente útil em ambientes complexos ou quando os usuários têm dificuldade em expressar suas necessidades (VAZQUEZ; SIMÕES, 2016).

## Justificativa

Por ser uma técnica etnográfica, que estuda o comportamento e os hábitos do usuário, a escolha da observação direta como método de elicitação de requisitos é justificada pela capacidade de coletar requisitos que poderiam não ser identificados por meio de outras técnicas. A observação ajuda a coletar requisitos implícitos que uma entrevista não consegue revelar e é particularmente útil quando os usuários estão muito ocupados para serem envolvidos em entrevistas (UFSC, 2023).

## Metodologia

No contexto do navegador Firefox, no dia 14 de abril de 2024, foi realizada uma reunião no Teams entre Guilherme Westphall e Kauan Eiras, respectivamente mediador e usuário, para elicitar os requisitos do aplicativo.

Esta técnica pode ser aplicada de duas formas:

- **Ativa**: O usuário pode ser questionado durante o processo de observação.
- **Passiva**: O observador não interage com o usuário enquanto observa sua rotina.

A observação utilizada para a elicitação de requisitos das Tabelas 2 e 3 foi a Observação direta ativa. Os requisitos foram elicitados com base na observação no qual o usuário utilizou o aplicativo. Na forma ativa, o observador conduziu o usuário por meio de perguntas durante o uso do aplicativo. Ao contrário de outros métodos de coleta de dados, como questionários ou entrevistas, a observação direta ativa permite capturar informações em tempo real, sem depender da memória ou interpretação posterior dos usuários. Isso proporciona uma visão mais precisa e detalhada do uso do navegador, revelando insights valiosos que podem orientar melhorias no design, na usabilidade e na experiência do usuário (VIANNA et al., 2011).

<center> 

### Tabela 1: Participantes

| Nome      | Função     |
| --------- | ---------- |
| Guilherme | Observador |
| Kauan     | Usuário    |

**Autores:** [Guilherme Westphall](https://github.com/west7) e [Kauan Eiras](https://github.com/kauaneiras), 2024.

</center>

## Requisitos elicitados

> Legenda para tabelas 2 e 3:
>
- **RFx**: Requisito funcional nº x
- **RNFx**: Requisito não funcional nº x
- **OBSx**: Requisito nº x elicitado pela técnica de observação

<center> 

### Tabela 2: Requisitos Funcionais

| Tipo | Descrição                                                                     | ID    | Implementado |
| ---- | ----------------------------------------------------------------------------- | ----- | ------------ |
| RF01 | O aplicativo deve possuir uma barra de pesquisa                               | OBS01 | Sim          |
| RF02 | O aplicativo deve ter opção de navegação anônima                              | OBS02 | Sim          |
| RF03 | Deve possuir opção de visualizar todas as guias                               | OBS03 | Sim          |
| RF04 | Deve possuir opção de favoritar sites                                         | OBS04 | Sim          |
| RF05 | Deve possuir histórico de navegação                                           | OBS05 | Sim          |
| RF06 | Deve possuir histórico de downloads                                           | OBS06 | Sim          |
| RF07 | Deve ser possível instalar extensões de uso                                   | OBS07 | Sim          |
| RF08 | Deve possuir opção de sincronizar dados e salvar                              | OBS08 | Sim          |
| RF09 | Deve ser possível visualizar em formato desktop                               | OBS09 | Sim          |
| RF10 | Deve ser possível criar atalhos na tela inicial do dispositivo                | OBS10 | Sim          |
| RF11 | Deve ser possível visualizar sites visitados recentemente                     | OBS11 | Sim          |
| RF12 | O navegador deve oferecer sugestões personalizadas de pesquisa                | OBS12 | Sim          |
| RF13 | Deve ser possível personalizar a tela inicial do navegador                    | OBS13 | Sim          |
| RF14 | Deve ser possível mudar o idioma                                              | OBS14 | Sim          |
| RF15 | Deve ser possível mudar entre tema claro e escuro                             | OBS15 | Sim          |
| RF16 | A escolha de tema deve acompanhar a escolha do dispositivo                    | OBS16 | Sim          |
| RF17 | Deve ser possível personalizar local da barra de pesquisa                     | OBS17 | Sim          |
| RF18 | Deve possuir atalhos de gestos                                                | OBS18 | Sim          |
| RF19 | Deve ser possível alterar tamanho da fonte                                    | OBS19 | Sim          |
| RF20 | Deve ser possível trocar de conta                                             | OBS20 | Sim          |
| RF21 | Deve ser possível alterar senha                                               | OBS21 | Sim          |
| RF22 | Deve ser possível limpar histórico de navegação                               | OBS22 | Sim          |
| RF23 | Deve ser possível limpar dados do usuário                                     | OBS23 | Sim          |
| RF24 | Deve ser possível habilitar e bloquear notificações                           | OBS24 | Sim          |
| RF25 | Deve ser possível alterar tema entre claro e escuro na tela inicial           | OBS25 | Não          |
| RF26 | Deve ser possível alterar fonte do navegador                                  | OBS26 | Não          |
| RF27 | O navegador deve incluir opção de bloquear anúncios                           | OBS27 | Não          |
| RF28 | O navegador deve incluir opção de busca na página                             | OBS28 | Sim          |
| RF29 | A barra de pesquisa deve incluir opção de pesquisa por voz                    | OBS29 | Sim          |
| RF30 | O navegador deve possuir opção de leitura da paǵina para deficientes visuais  | OBS30 | Não          |
| RF31 | Deve possuir opção de buscar imagens, vídeos, notícias, mapas, lojas e livros | OBS31 | Sim          |
| RF32 | Deve possuir opção de controle parental                                       | OBS32 | Não          |
| RF33 | Deve oferecer opção de impressão                                              | OBS33 | Sim          |
| RF34 | Deve conter opção de traduzir páginas                                         | OBS34 | Não          |

**Autores:** [Guilherme Westphall](https://github.com/west7) e [Kauan Eiras](https://github.com/kauaneiras), 2024.

### Tabela 3: Requisitos não funcionais 

| Tipo  | Descrição                                                         | ID    | Implementado |
| ----- | ----------------------------------------------------------------- | ----- | ------------ |
| RFN01 | O navegador deve ser rápido                                       | OBS35 | Sim          |
| RFN02 | O navegador deve proteger os dados do usuário durante a navegação | OBS36 | Sim          |
| RNF03 | O navegador deve proteger contra rastreamento de dados            | OBS37 | Sim          |

**Autores:** [Guilherme Westphall](https://github.com/west7) e [Kauan Eiras](https://github.com/kauaneiras), 2024.

</center>

## Link da gravação

<center> Vídeo 1: Técnica de Observação <br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/fOiNribFwbU?si=DXiJ6krCd1celE9W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Autores:** [Guilherme Westphall](https://github.com/west7) e [Kauan Eiras](https://github.com/kauaneiras), 2024.

</center>

## Referências
 1. **VAZQUEZ, C. E., & SIMÕES, G. S. (2016).** Engenharia de requisitos: software orientado ao negócio. Brasport.
 2. **Universidade Federal de Santa Catarina (UFSC).** (2023). Pesquisa sobre técnicas de elicitação de requisitos. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-observacao-direta. Acesso em: 14 abr. 2024.
 3. **VIANNA, M., VIANNA, Y., ADLER, I. K., LUCENA, B., & RUSSO, B. (2011).** Design Thinking: Inovação em Negócios. MJV Tecnologia Ltda.

## Histórico de versões

| Versão | Data       | Descrição                                    | Autor                                           | Revisor                                         |
| ------ | ---------- | -------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| 1.0    | 14/04/2024 | Criação do documento                         | [Guilherme Westphall](https://github.com/west7) | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.1    | 14/04/2024 | Adição da introdução e metodologia           | [Guilherme Westphall](https://github.com/west7) | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.2    | 14/04/2024 | Adição das tabelas                           | [Guilherme Westphall](https://github.com/west7) | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.3    | 14/04/2024 | Adição do link de gravação e bibliografia    | [Guilherme Westphall](https://github.com/west7) | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.4    | 15/04/2024 | Adição de justificativa e correções de forma | [Kallyne Macedo](https://github.com/kalipassos) | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.5    | 30/05/2024 | Correções                                    | [Kauan Eiras](https://github.com/kauaneiras)    | [Guilherme Westphall](https://github.com/west7) |
