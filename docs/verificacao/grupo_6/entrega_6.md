# Verificação da Entrega 6 - "Pós-rastreabilidade"

## Introdução

Este documento aborda a verificação da Entrega 6, intitulada "Pós-rastreabilidade". Esta entrega inclui os artefatos [Elos](../../pos-rastreabilidade/elos.md), matriz de rastreabilidade [Forward-From](../../pos-rastreabilidade/forwardfrom.md) e matriz de rastreabilidade [Backward-From](../../pos-rastreabilidade/backwardfrom.md) elaborados pelo nosso grupo com base no aplicativo Firefox.

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

|          | Versão | Data       | Descrição                                              | Autor(es)                                       | Revisor(es) |
| -------- | ------ | ---------- | ------------------------------------------------------ | ----------------------------------------------- | ----------- |
| **Elos** | 1.3    | 24/06/2024 | Adiciona elos referentes aos requisitos R26, R32 e R38 | [Guilherme Westphall](https://github.com/west7) |

**Autor**: [Guilherme Westphall](https://github.com/west7)

</center>

## Checklists

Nesta seção, serão dispostos os checklists dos artefatos da Entrega 4 nas tabelas 3, 4 e 5. Durante a inspeção, o responsável deverá preencher o campo de avaliação da seguinte maneira: 

>- **Sim**, se o critério foi totalmente atendido. 
>- **Não**, se o critério não foi atendido. 
>- **Incompleto**, se o critério foi parcialmente atendido, explicando em qual parte o artefato falhou. 
>- **Não se aplica**, se o critério não pode ser verificado devido ao contexto do projeto. 

### Elos

<center>

**Tabela 3**: Checklist dos Elos

| ID  | Descrição                                                                                                                  | Referência                                      | Avaliação |
| --- | -------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | --------- |
| 01  | Os elos do nível de **desenvolvimento** representam as relações entre os requisitos e os artefatos gerados a partir deles? | [SAYÃO e LEITE p. 9](../grupo_6/assets/E1.png)  | Sim       |
| 02  | Os elos de **satisfação** indicam que a classe de origem têm de satisfação com a classe de destino?                        | [SAYÃO e LEITE p. 9](../grupo_6/assets/E2.png)  | Sim       |
| 03  | Os elos de **recurso** indicam que classe origem tem dependência de recurso com a classe destino?                          | [SAYÃO e LEITE p. 9](../grupo_6/assets/E2.png)  | Sim       |
| 04  | Os elos de **responsabilidade** registram a participação, responsabilidade e ação de pessoas sobre artefatos?              | [SAYÃO e LEITE p. 10](../grupo_6/assets/E2.png) | Sim       |
| 05  | Os elos de **representação** capturam a representação ou modelagem dos requisitos em outras linguagens?                    | [SAYÃO e LEITE p. 10](../grupo_6/assets/E2.png) | Sim       |
| 06  | Os elos de **alocado** indicam que a classe origem é um subsistema da classe de destino?                                   | [SAYÃO e LEITE p. 10](../grupo_6/assets/E2.png) | Sim       |
| 07  | Os elos de **agregação** indicam a composição de elementos?                                                                | [SAYÃO e LEITE p. 10](../grupo_6/assets/E2.png) | Sim       |
| 08  | Na construção dos elos estão descritos: **Categoria, Elementos rastreáveis e o Elo**?                                      | [SERRANO p. 22](../grupo_6/assets/E3.png)       | Sim       |
| 09  | Os elos são construídos da seguinte maneira: "[Elemento 1] relação [Elemento 2]"?                                          | [SERRANO p. 22](../grupo_6/assets/E3.png)       | Sim       |

**Autor da lista de verificação**: [Guilherme Westphall](https://github.com/west7), **Inspecionado por**: [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

#### Problemas encontrados

Não foram encontrados problemas no artefato [Elos](https://requisitos-de-software.github.io/2024.1-Firefox/pos-rastreabilidade/elos/) de acordo com a checklist feita para realizar a verificação.


### Forward-From

<center>

**Tabela 4**: Checklist da matriz de Forward-from

| ID  | Descrição                                                                                            | Referência                                                                 | Avaliação |
| --- | ---------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- |
| 01  | A matriz de rastreabilidade **forward-from** liga os requisitos aos artefatos produzidos?            | [SAYÃO e LEITE p. 4](../grupo_6/assets/FF1.png)                            | Sim       |
| 02  | As **linhas da matriz** de rastreabilidade contém os **requisitos** (artefatos iniciais)?            | [Requirements engineering fundamentals, p. 126](../grupo_6/assets/FF2.png) | Sim       |
| 03  | As **colunas da matriz** de rastreabilidade contém os **artefatos subsequentes do desenvolvimento**? | [Requirements engineering fundamentals, p. 124](../grupo_6/assets/FF5.png) | Sim       |
| 04  | Cada **requisito** da matriz possui um **identificador único**?                                      | [Visure solutions](../grupo_6/assets/FF3.png)                              | Sim       |
| 05  | Cada **requisito** da matriz possui o seu **tipo** descrito?                                         | [Visure solutions](../grupo_6/assets/FF3.png)                              | Não       |
| 06  | Cada **requisito** da matriz contém sua **descrição**?                                               | [Visure solutions](../grupo_6/assets/FF3.png)                              | Sim       |
| 07  | Existem **hyperlinks** entre os requisitos e os artefatos?                                           | [Visure solutions](../grupo_6/assets/FF3.png)                              | Sim       |

**Autor da lista de verificação**: [Guilherme Westphall](https://github.com/west7), **Inspecionado por**: [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

#### Problemas encontrados

De acordo com a checklist de verificação foi encontrado apenas um probelma no artefato [Foward-From](https://requisitos-de-software.github.io/2024.1-Firefox/pos-rastreabilidade/forwardfrom/) sendo ele a falta de tipo dos requisitos.


### Backward-from


<center>

**Tabela 5**: Checklist da matriz de Backward-from

| ID  | Descrição                                                                                                    | Referência                                                                 | Avaliação |
| --- | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | --------- |
| 01  | A matriz de rastreabilidade **backward-from** liga os requisitos as suas fontes (técnicas de elicitação)?    | [SAYÃO e LEITE p. 4](../grupo_6/assets/FF1.png)                            | Sim       |
| 02  | As **linhas da matriz** de rastreabilidade contém os **requisitos** (artefatos iniciais)?                    | [Requirements engineering fundamentals, p. 126](../grupo_6/assets/FF2.png) | Sim       |
| 03  | As **colunas da matriz** de rastreabilidade contém os **artefatos que serviram de base para os requisitos**? | [Requirements engineering fundamentals, p. 124](../grupo_6/assets/FF4.png) | Sim       |
| 04  | Cada **requisito** da matriz possui um **identificador único**?                                              | [Visure solutions](../grupo_6/assets/FF3.png)                              | Sim       |
| 05  | Cada **requisito** da matriz possui o seu **tipo** descrito?                                                 | [Visure solutions](../grupo_6/assets/FF3.png)                              | Não       |
| 06  | Cada **requisito** da matriz contém sua **descrição**?                                                       | [Visure solutions](../grupo_6/assets/FF3.png)                              | Sim       |
| 07  | Existem **hyperlinks** entre os requisitos e os artefatos?                                                   | [Visure solutions](../grupo_6/assets/FF3.png)                              | Sim       |

**Autor da lista de verificação**: [Guilherme Westphall](https://github.com/west7), **Inspecionado por**: [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

#### Problemas encontrados

De acordo com a checklist de verificação foi encontrado apenas um probelma no artefato [Backward-From](https://requisitos-de-software.github.io/2024.1-Firefox/pos-rastreabilidade/backwardfrom/) sendo ele a falta de tipo dos requisitos.


## Referências

1. SAYÃO, Miriam; LEITE, Julio Cesar. Monografias em Ciência da Computação n° 20/05.
2. SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 26. 2019. Slides de aula.
3. POHL, Klaus. Requirements engineering fundamentals: a study guide for the certified professional for requirements engineering exam-foundation level-IREB compliant. Rocky Nook, Inc., 2016.
4. VISURE SOLUTIONS. What is Requirements Traceability. Visure Solutions, 2024. Disponível em: https://visuresolutions.com/what-is-requirements-traceability/. Acesso em: 01 jul. 2024.

## Histórico de versões

| Versão | Data       | Descrição                                                   | Autor                                           | Revisor                                      |
| ------ | ---------- | ----------------------------------------------------------- | ----------------------------------------------- | -------------------------------------------- |
| 1.0    | 01/07/2024 | Cria página                                                 | [Guilherme Westphall](https://github.com/west7) | [Davi Pierre](https://github.com/DaviPierre) |
| 1.1    | 01/07/2024 | Adiciona chesklist dos Elos                                 | [Guilherme Westphall](https://github.com/west7) | [Davi Pierre](https://github.com/DaviPierre) |
| 1.2    | 01/06/2024 | Adiciona chesklist do Forward-from                          | [Guilherme Westphall](https://github.com/west7) | [Davi Pierre](https://github.com/DaviPierre) |
| 1.3    | 01/06/2024 | Adiciona chesklist do Backward-from                         | [Guilherme Westphall](https://github.com/west7) | [Davi Pierre](https://github.com/DaviPierre) |
| 1.4    | 02/06/2024 | Verificação dos artefatos Foward-From, Backward-from e Elos | [Davi Pierre](https://github.com/DaviPierre)    |    [Guilherme Westphall](https://github.com/west7)                                          |
