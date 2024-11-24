# Verificação dos artefatos da entrega 3.

## Introdução

Este documento tem como objetivo relatar os resultados da verificação por inspeção dos artefatos [Especificação Suplementar](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/specSuplementar/), [Casos de Uso](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/useCase/), [Cenários](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/cenarios/) e [Léxicos](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/lexicos/) elaborado pelo [grupo 07](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS) da disciplina de Requisitos de Software no semestre 2024/01 da Universidade de Brasília (UnB). A análise foi realizada nas versões disponíveis do trabalho durante a data de 09/06/2024. Os artefatos serão avaliados pelos discentes [Kallyne Macedo](https://github.com/kalipassos) e [Kauan de Torres Eiras](https://github.com/kauaneiras). A tabela 1 apresenta os objetos de verificação.

<center>

**Tabela 1**: Objetos de verificação

|                               | Versão | Data       | Descrição                                                                  | Autor(es)                                              | Data de revisão | Revisor(es)   |
|-------------------------------|--------|------------|----------------------------------------------------------------------------|--------------------------------------------------------|-----------------|---------------|
| **Especificação Suplementar** | 1.2    | 19/05/2024 | Arrumando Hiperlinks e ajustes na tabela de backlog.                       | Johnny Lopes                                           | 19/05/2024      | Paulo Borba   |
| **Casos de Uso**              | 1.3    | 19/05/2024 | Adição dos SIGs de operacionalização, afirmação e seleção de alternativas. | José Filipi & Vitor Feijó & Johnny Lopes & Paulo Borba | 19/05/2024      | Amanda Campos |
| **Cenários**                  | 1.3    | 19/05/2024 | Adição da validação e priorização do cliente e ajustes.                    | Paulo Borba                                            | 19/05/2024      | Johnny Lopes  |
| **Léxicos**                   | 1.4    | 19/05/2024 | Adição de novos léxicos                                                    | Amanda Campos, Bianca Castro e Paulo Borba             | 19/05/2024      | Johnny Lopes  |

**Autor:** [Kauan Eiras](https://github.com/kauaneiras), 2024

</center>

## Metodologia
Para realizar a análise dos documentos, será utilizado uma adaptação do método de "Inspeção" criado por Fagan no final da década de 1970. No contexto desta disciplina, a Inspeção será composta por 3 das 6 etapas propostas por Fagan. São elas:

1. **Planejamento**: Consiste em avaliar os artefatos e planejar as atividades de inspeção.
2. **Preparação**: Após a análise e compreensão dos artefatos, será elaborada uma lista de critérios (checklist) que orientará a avaliação de cada página.
3. **Inspeção**: Esta etapa envolve verificar se os artefatos atendem aos critérios estabelecidos nas checklists.

### Especificação Suplementar
=== "Preparação do checklist"

    <center>

    **Tabela 2**: Preparação do checklist da Especificação Suplementar

    | ID | Pergunta                                                                                                                                                          |
    |----|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | 01 | O artefato contém o histórico de versão padronizado?                                                                                                              |
    | 02 | Os autores e revisores estão identificados para cada artefato?                                                                                                    |
    | 03 | O artefato possui um texto de introdução?                                                                                                                         |
    | 04 | As tabelas/imagens possuem fonte/autor?                                                                                                                           |
    | 05 | O artefato possui referências/bibliografia corretamente citadas?                                                                                                  |
    | 06 | O artefato contém a metodologia/método utilizado?                                                                                                                 |
    | 07 | Todos os textos seguem a norma padrão da língua portuguesa?                                                                                                       |
    | 08 | O documento tem em sua metodologia o modelo FURPS+?                                                                                                               |
    | 09 | O documento possui o tópico de Funcionalidade?                                                                                                                    |
    | 10 | O documento apresenta pelo menos dois tópicos + (Restrição de Design, Requisitos de Implementação, de Interface ou Físicos)?                                      |
    | 11 | No tópico Funcionalidade, há a descrição ou redirecionamento para os requisitos funcionais?                                                                       |
    | 12 | O documento possui o tópico de Usabilidade?                                                                                                                       |
    | 13 | No tópico Usabilidade, há a especificação de requisitos que  facilite a realização das tarefas pelo usuário?                                                      |
    | 14 | O documento possui o tópico de Confiabilidade?                                                                                                                    |
    | 15 | No tópico Confiabilidade, há a especificação do Tempo Médio entre Falhas (MTBF) e o Tempo Médio para Reparo (MTTR)?                                               |
    | 16 | No tópico Confiabilidade, há a especificação de requisitos que aumentam a confiabilidade considerando questões como disponibilidade, precisão e recuperabilidade? |
    | 17 | O documento possui o tópico de Desempenho?                                                                                                                        |
    | 18 | No tópico Desempenho, há a especificação do tempo de resposta de uma transação e da taxa de transferência?                                                        |
    | 19 | No tópico Desempenho, há a especificação de requisitos que especificam a capacidade do sistema?                                                                   |
    | 20 | O documento possui o tópico de Suportabilidade?                                                                                                                   |
    | 21 | No tópico Suportabilidade, há a especificação de sistema operacional ou plataforma de execução do sistema?                                                        |
    | 22 | No artefato, há a especificação física de funcionamento do sistema?                                                                                               |
    | 23 | No artefato, há a especificação de requisitos e restrições de design do sistema?                                                                                  |
    | 24 | No artefato, há a especificação de requisitos e restrições de construção do sistema?                                                                              |
    | 25 | No artefato, há a especificação de requisitos e restrições de interface?                                                                                          |
    | 26 | Os requisitos definidos no artefato são todos testáveis?                                                                                                          |

    **Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

    </center>

=== "Inspeção"

    <center>

    **Tabela 3**: Inspeção da Especificação Suplementar
    
    | ID | Pergunta                                                                                                                                                          | Resposta |
    |----|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
    | 01 | O artefato contém o histórico de versão padronizado?                                                                                                              |   Sim    |
    | 02 | Os autores e revisores estão identificados para cada artefato?                                                                                                    |   Sim    |
    | 03 | O artefato possui um texto de introdução?                                                                                                                         |   Sim    |
    | 04 | As tabelas/imagens possuem fonte/autor?                                                                                                                           |   Sim    |
    | 05 | O artefato possui referências/bibliografia corretamente citadas?                                                                                                  |   Sim    |
    | 06 | O artefato contém a metodologia/método utilizado?                                                                                                                 |   Sim    |
    | 07 | Todos os textos estão na norma padrão?                                                                                                                            |   Sim    |
    | 08 | O documento tem em sua metodologia o modelo FURPS+?                                                                                                               |   Sim    |
    | 09 | O documento possui o tópico de Funcionalidade?                                                                                                                    |   Sim    |
    | 10 | O documento apresenta pelo menos dois tópicos + (Restrição de Design, Requisitos de Implementação, de Interface ou Físicos)?                                      |   Sim    |
    | 11 | No tópico Funcionalidade, há a descrição ou redirecionamento para os requisitos funcionais?                                                                       |   Sim    |
    | 12 | O documento possui o tópico de Usabilidade?                                                                                                                       |   Sim    |
    | 13 | No tópico Usabilidade, há a especificação de requisitos que  facilite a realização das tarefas pelo usuário?                                                      |   Sim    |
    | 14 | O documento possui o tópico de Confiabilidade?                                                                                                                    |   Sim    |
    | 15 | No tópico Confiabilidade, há a especificação do Tempo Médio entre Falhas (MTBF) e o Tempo Médio para Reparo (MTTR)?                                               |   Sim    |
    | 16 | No tópico Confiabilidade, há a especificação de requisitos que aumentam a confiabilidade considerando questões como disponibilidade, precisão e recuperabilidade? |   Sim    |
    | 17 | O documento possui o tópico de Desempenho?                                                                                                                        |   Sim    |
    | 18 | No tópico Desempenho, há a especificação do tempo de resposta de uma transação e da taxa de transferência?                                                        |   Sim    |
    | 19 | No tópico Desempenho, há a especificação de requisitos que especificam a capacidade do sistema?                                                                   |   Sim    |
    | 20 | O documento possui o tópico de Suportabilidade?                                                                                                                   |   Sim    |
    | 21 | No tópico Suportabilidade, há a especificação de sistema operacional ou plataforma de execução do sistema?                                                        |   Sim    |
    | 22 | No artefato, há a especificação física de funcionamento do sistema?                                                                                               |   Sim    |
    | 23 | No artefato, há a especificação de requisitos e restrições de design do sistema?                                                                                  |   Sim    |
    | 24 | No artefato, há a especificação de requisitos e restrições de construção do sistema?                                                                              |   Sim    |
    | 25 | No artefato, há a especificação de requisitos e restrições de interface?                                                                                          |   Sim    |
    | 26 | Os requisitos definidos no artefato são todos testáveis?                                                                                                          |   Sim    |

    **Autor**: [Kauan de Torres Eiras](https://github.com/kauaneiras), 2024

    </center>

### Casos de Uso
=== "Preparação do checklist"

    <center>

    **Tabela 4**: Preparação do checklist dos Casos de Uso

    | ID | Pergunta                                                                                                          |
    |----|-------------------------------------------------------------------------------------------------------------------|
    | 01 | O artefato contém o histórico de versão padronizado?                                                              |
    | 02 | Os autores e revisores estão identificados para cada artefato?                                                    |
    | 03 | O artefato possui um texto de introdução?                                                                         |
    | 04 | As tabelas/imagens possuem fonte/autor?                                                                           |
    | 05 | O artefato possui referências/bibliografia corretamente citadas?                                                  |
    | 06 | O artefato contém a metodologia/método utilizado?                                                                 |
    | 07 | Todos os textos seguem a norma padrão da língua portuguesa?                                                       |
    | 08 | No documento, é apresentado um diagrama de casos de uso que representa a interação do usuário com o sistema?      |
    | 08 | No documento, há a especificação de local e data da confecção do diagrama?                                        |
    | 09 | O diagrama de casos de uso segue a notação UML?                                                                   |
    | 10 | No diagrama, há a especificação de atores, sistema e metas?                                                       |
    | 11 | No diagrama, o ator principal está do lado esquerdo e fora do limite do sistema?                                  |
    | 12 | No diagrama, há a definição de atores principais e atores secundários?                                            |
    | 13 | No diagrama, o nome dos atores é significativo?                                                                   |
    | 14 | No diagrama, a sinalização << system >> indica um software ou hardware?                                           |
    | 15 | No diagrama, há pontos de extensão, inclusão e generalização?                                                     |
    | 16 | No diagrama, os pontos de extensão, inclusão ou generalização são aplicados corretamente?                         |
    | 17 | Os casos de uso levantados representam requisitos funcionais?                                                     |
    | 18 | Os casos de uso levantados representam corretamente as funcionalidades e suas interações                          |
    | 19 | No documento, há a especificação completa (nome, descrição, atores, fluxos, pré e pós condição) dos casos de uso? |
    | 20 | No documento, há a especificação de apenas um fluxo principal para cada caso de uso?                              |
    | 21 | Os fluxos alternativos são factívelmente alternativos ao principal?                                               |
    | 22 | Os fluxos de exceção representam a reação do sistema a erros ou situações fora do esperado?                       |
    | 23 | A validação do diagrama de casos de uso foi realizada com usuário ou persona?                                     |
    | 24 | Na validação do diagrama, há a especificação da técnica utilizada?                                                |

    **Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

    </center>

=== "Inspeção"

    <center>

    **Tabela 5**: Inspeção dos Casos de Uso

    | ID | Pergunta                                                                                                          | Resposta |
    |----|-------------------------------------------------------------------------------------------------------------------|----------|
    | 01 | O artefato contém o histórico de versão padronizado?                                                              |    Sim   |
    | 02 | Os autores e revisores estão identificados para cada artefato?                                                    |    Sim   |
    | 03 | O artefato possui um texto de introdução?                                                                         |    Sim   |
    | 04 | As tabelas/imagens possuem fonte/autor?                                                                           |    Sim   |
    | 05 | O artefato possui referências/bibliografia corretamente citadas?                                                  |    Sim   |
    | 06 | O artefato contém a metodologia/método utilizado?                                                                 |    Sim   |
    | 07 | Todos os textos seguem a norma padrão da língua portuguesa?                                                       |    Sim   |
    | 08 | No documento, é apresentado um diagrama de casos de uso que representa a interação do usuário com o sistema?      |    Sim   |
    | 08 | Na validação do diagrama, há a especificação da técnica utilizada, especificação de local e data?                 |    Sim   |
    | 09 | O diagrama de casos de uso segue a notação UML?                                                                   |    Sim   |
    | 10 | No diagrama, há a especificação de atores, sistema e metas?                                                       |    Sim   |
    | 11 | No diagrama, o ator principal está do lado esquerdo e fora do limite do sistema?                                  |    Sim   |
    | 12 | No diagrama, há a definição de atores principais e atores secundários?                                            |    Sim   |
    | 13 | No diagrama, o nome dos atores é significativo?                                                                   |    Não   |
    | 14 | No diagrama, a sinalização << system >> indica um software ou hardware?                                           |    Sim   |
    | 15 | No diagrama, há pontos de extensão, inclusão e generalização?                                                     |    Sim   |
    | 16 | No diagrama, os pontos de extensão, inclusão ou generalização são aplicados corretamente?                         |    Sim   |
    | 17 | Os casos de uso levantados representam requisitos funcionais?                                                     |    Sim   |
    | 18 | Os casos de uso levantados representam corretamente as funcionalidades e suas interações                          |    Sim   |
    | 19 | No documento, há a especificação completa (nome, descrição, atores, fluxos, pré e pós condição) dos casos de uso? |    Sim   |
    | 20 | No documento, há a especificação de apenas um fluxo principal para cada caso de uso?                              |Incompleto|
    | 21 | Os fluxos alternativos são factívelmente alternativos ao principal?                                               |    Sim   |
    | 22 | Os fluxos de exceção representam a reação do sistema a erros ou situações fora do esperado?                       |    Sim   |
    | 23 | A validação do diagrama de casos de uso foi realizada com usuário ou persona?                                     |    Sim   |

    **Autor**: [Kauan de Torres Eiras](https://github.com/kauaneiras), 2024

    </center>

#### Problemas encontrados

O artefato [Casos de Uso](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/useCase/) se aparentou claro e bem inscrito, porém, há alguns pontos que devem ser conferidos. Um desses pontos está no Diagrama de caso de usos, onde o ator "usuário" não tem um nome adequado, considerndo que "Usuário" pode ser todas as pessoas que utilizam o sistema, como o advogado e funcionários do INSS. É interessante buscar por um nome mais adequado que dê a entender que tal ator vai consultar extratos, solicitar benefinios e utilizar as funcionalidades oferecidas para quem tem um benefício ou solicitou. O outro ponto importante para conferir é a padronização das tabelas, onde algumas estão enumeradas e outras não. 

### Cenários
=== "Preparação do checklist"

    <center>

    **Tabela 4**: Preparação do checklist dos Cenários

    | ID | Pergunta                                                                                                                         |
    |----|----------------------------------------------------------------------------------------------------------------------------------|
    | 01 | O artefato inclui uma descrição detalhada dos cenários?                                                                          |
    | 02 | Cada cenário possui um título claro e fácil de entender, objetivo, contexto, atores, recursos, restrições, exceções e episódios? |
    | 03 | Os cenários são testáveis?                                                                                                       |
    | 04 | Os objetivos dos cenários são alinhados com seus respectivos títulos?                                                            |
    | 05 | Os cenários descrevem interações realistas e significativas com o sistema?                                                       |
    | 06 | Os atores são apropriados e relevantes para o contexto dos cenários?                                                             |
    | 07 | Há um episódio relacionado aos cenários?                                                                                         |
    | 08 | Há uma referência clara aos léxicos nos cenários?                                                                                |
    | 09 | O artefato menciona as técnicas utilizadas para desenvolver os cenários?                                                         |
    | 10 | O artefato identifica os participantes e seus papéis na criação dos cenários?                                                    |
    | 11 | O artefato inclui informações autores e data na criação dos cenários?                                                            |
    | 12 | A introdução ou metodologia trazem referências que justifiquem a forma que o trabalho foi desenvolvido?                          |
  

    **Autor**: [Kauan de Torres Eiras](https://github.com/kauaneiras), 2024

    </center>

=== "Inspeção"

    <center>

    **Tabela 5**: Inspeção dos Cenários

    | ID | Pergunta                                                                                                                         | Resposta |
    |----|----------------------------------------------------------------------------------------------------------------------------------|----------|
    | 01 | O artefato inclui uma descrição detalhada dos cenários?                                                                          | Sim      |
    | 02 | Cada cenário possui um título claro e fácil de entender, objetivo, contexto, atores, recursos, restrições, exceções e episódios? | Sim      |
    | 03 | Os cenários são testáveis?                                                                                                       | Sim      |
    | 04 | Os objetivos dos cenários são alinhados com seus respectivos títulos?                                                            | Sim      |
    | 05 | Os cenários descrevem interações realistas e significativas com o sistema?                                                       | Sim      |
    | 06 | Os atores são apropriados e relevantes para o contexto dos cenários?                                                             | Sim      |
    | 07 | Há um episódio relacionado aos cenários?                                                                                         | Sim      |
    | 08 | Há uma referência clara aos léxicos nos cenários?                                                                                | Não      |
    | 09 | O artefato menciona as técnicas utilizadas para desenvolver os cenários?                                                         | Sim      |
    | 10 | O artefato identifica os participantes e seus papéis na criação dos cenários?                                                    | Não      |
    | 11 | O artefato inclui informações autores e data na criação dos cenários?                                                            |Incompleto|
    | 12 | A introdução ou metodologia trazem referências que justifiquem a forma que o trabalho foi desenvolvido?                          | Sim      |

    **Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

    </center>

#### Problemas encontrados

Os principais problemas encontrados no artefato [Cenários](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/cenarios/), foram a ausência da conexão dos cenários com os [Léxicos](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/lexicos/), também desenvolvidos durante essa etapa de entrega e a falta da participação de usuários ou personas na criação dos cenários. Além disso, ao longo do artefato se nota a autoria de diversos membros do grupo na formulação dos cenários, entretanto, não há a representação dessa informação no histórico de versões do artefato. 

#### Video de verificação

<center>

**Vídeo 1**: Verificação - Cenários

<iframe width="560" height="315" src="https://www.youtube.com/embed/iL9eNKaJe5w?si=8ij-deodVpsa4lf8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

</center>

### Léxicos

=== "Preparação do checklist"

    <center>

    **Tabela 6**: Preparação do checklist dos Léxicos

    | ID | Pergunta                                                                                        |
    |----|-------------------------------------------------------------------------------------------------|
    | 01 | O artefato inclui uma definição clara de léxicos e sua importância na engenharia de requisitos? |
    | 02 | A metodologia para a identificação dos léxicos é claramente descrita?                           |
    | 03 | O template para a definição dos léxicos está devidamente apresentado e explicado?               |
    | 04 | Cada léxico inclui todos os elementos do template: termo, tipo, noção, impacto e autor?         |
    | 05 | Os termos definidos são relevantes e abrangem todos os aspectos do sistema?                     |
    | 06 | Os tipos de léxicos (objeto, verbo, estado) estão devidamente identificados e diferenciados?    |
    | 07 | As noções dos léxicos são claras e bem definidas?                                               |
    | 08 | Os impactos descritos são detalhados e refletem corretamente o efeito dos termos no sistema?    |
    | 09 | As referências utilizadas para a definição dos léxicos são citadas corretamente?                |
    | 10 | O artefato menciona os autores e a data da criação dos léxicos?                                 |
    | 11 | Os léxicos estão conectados entre si através de hyperlinks?                                     |

    **Autor**: [Kauan de Torres Eiras](https://github.com/kauaneiras)

    </center>

=== "Inspeção"

    <center>

    **Tabela 7**: Inspeção dos Léxicos

    | ID | Pergunta                                                                                        | Resposta   |
    |----|-------------------------------------------------------------------------------------------------|------------|
    | 01 | O artefato inclui uma definição clara de léxicos e sua importância na engenharia de requisitos? | Incompleto |
    | 02 | A metodologia para a identificação dos léxicos é claramente descrita?                           | Incompleto |
    | 03 | O template para a definição dos léxicos está devidamente apresentado e explicado?               | Sim        |
    | 04 | Cada léxico inclui todos os elementos do template: termo, tipo, noção, impacto e autor?         | Sim        |
    | 05 | Os termos definidos são relevantes e abrangem os aspectos do sistema?                           | Sim        |
    | 06 | Os tipos de léxicos (objeto, verbo, estado) estão devidamente identificados e diferenciados?    | Sim        |
    | 07 | As noções dos léxicos são claras e bem definidas?                                               | Incompleto |
    | 08 | Os impactos descritos são detalhados e refletem corretamente o efeito dos termos no sistema?    | Incompleto |
    | 09 | As referências utilizadas para a definição dos léxicos são citadas corretamente?                | Sim        |
    | 10 | O artefato menciona os autores e a data da criação dos léxicos?                                 | Sim        |
    | 11 | Os léxicos estão conectados entre si através de hyperlinks?                                     | Não        |


    **Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

    </center>


#### Problemas encontrados

Os principais problemas encontrados no artefato [Léxicos](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/lexicos/) foram a ausência da definição da importância do uso dos léxicos na engenharia de requisitos, da identificação da metodologia, com especificação que justifique o uso do modelo de dicionário de dados e da conexão dos léxicos entre si. Além disso, as noções e impactos de cada termo carecem de maior descrição para que se possa englobar corretamente o efeito de cada léxico no sistema. 

### Video de verificação

<center>

**Vídeo 2**: Verificação - Léxicos

<iframe width="560" height="315" src="https://www.youtube.com/embed/-IZNWhHzHcA?si=uzyy0R0gogMC4Ve8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

</center>

## Referências

1. MEU INSS. Brasília, DF, 2024. Disponível em: https://requisitos-de-software.github.io/2024.1-Meu-INSS/. Acesso em: 08 de junho de 2024.

2. MASTER2TEACH. Fagan Inspection Methodology - Benefits of Software Inspections. Disponível em: https://www.youtube.com/watch?v=v_Lz2l_XsTQ. Acesso em: 08 de junho de 2024.

3. LEITE, Julio; FRANCO, Ana. A Strategy for Conceptual Model Acquisition. Rio de Janeiro: PUC-Rio, 1992. 243-246 p. Acesso em: 09 de junho de 2024.

## Histórico de Versões

| Versão | Data       | Descrição                                               | Autor(es)                                              | Revisor(es)                                            |
|--------|------------|---------------------------------------------------------|--------------------------------------------------------|--------------------------------------------------------|
| 1.0    | 09/06/2024 | Introdução e Metodologia                                | [Kauan de Torres Eiras](https://github.com/kauaneiras) | [Kallyne Macedo](https://github.com/kalipassos)        |
| 1.1    | 09/06/2024 | Checklist para Cenários e Léxicos                       | [Kauan de Torres Eiras](https://github.com/kauaneiras) | [Kallyne Macedo](https://github.com/kalipassos)        |
| 1.2    | 09/06/2024 | Checklist para Casos de Uso e Especificação Suplementar | [Kallyne Macedo](https://github.com/kalipassos)        | [Kauan de Torres Eiras](https://github.com/kauaneiras) |
| 1.4    | 10/06/2024 | Verificação para Cenários e Léxicos                     | [Kallyne Macedo](https://github.com/kalipassos)        | [Kauan de Torres Eiras](https://github.com/kauaneiras) |
