# Verificação da Entrega 3 - "Modelagem"

## Introdução

Este documento tem como objetivo relatar os resultados da verificação por inspeção dos artefatos Especificação Suplementar, Casos de Uso, Cenários e Léxicos elaborado pelo grupo 06 da disciplina de Requisitos de Software no semestre 2024/01 da Universidade de Brasília (UnB). A análise foi realizada nas versões disponíveis do trabalho durante a data de 09/06/2024. Os artefatos serão avaliados pelos discentes [Kallyne Macedo](https://github.com/kalipassos) e [Kauan de Torres Eiras](https://github.com/kauaneiras). A tabela 1 apresenta os objetos de verificação.

## Metodologia

Para realizar a análise dos documentos, foi utilizado uma adaptação do método de "Inspeção" criado por Fagan no final da década de 1970 (MASTER2TEACH). No contexto desta disciplina, a Inspeção será composta por três das seis etapas propostas por Fagan. São elas:

1. **Planejamento**: Consiste em avaliar os artefatos e planejar as atividades de inspeção.
2. **Preparação**: Após a análise e compreensão dos artefatos, será elaborada uma lista de critérios (*checklist*) que orientará a avaliação de cada página.
3. **Inspeção**: Esta etapa envolve verificar se os artefatos atendem aos critérios estabelecidos nas *checklists*.

A fase de planejamento será realizada por meio de um estudo individual dos artefatos, pelo membro do grupo que irá produzir os *checklists* referentes à entrega ao qual foi designado. A segunda fase consiste em, de fato, produzir os *checklists* com base no que foi estudado durante a fase de planejamento e seguindo o modelo apresentado na **Tabela 1** abaixo. A última fase da inspeção será realizada por um integrante diferente daquele que produziu os *checklists*. Essa etapa consiste em verificar os artefatos e marcar o campo "Avaliação" da lista de critérios.

<center>

**Tabela 1**: Template para os checklists

| ID             | Descrição             | Referência                      | Avaliação                        |
| -------------- | --------------------- | ------------------------------- | -------------------------------- |
| ID do critério | Descrição do critério | Referência da qual foi retirado | Sim/Não/Incompleto/Não se aplica |

**Autor**: [Guilherme Westphall](https://github.com/west7), 2024

</center>

<center>

**Tabela 2**: Objetos de verificação

|                               | Versão | Data       | Descrição                         | Autor(es)                                    | Revisor(es)                                       |
| ----------------------------- | ------ | ---------- | --------------------------------- | -------------------------------------------- | ------------------------------------------------- |
| **Casos de Uso**              | 2.0    | 27/06/2024 | Adições bibliográficas            | [Kauan Eiras](https://github.com/kauaneiras) | [Kallyne Macedo](https://github.com/kalipassos)   |
| **Cenários**                  | 2.0    | 27/06/2024 | Correção das fontes               | [Kauan Eiras](https://github.com/kauaneiras) | [Kallyne Macedo](https://github.com/kalipassos)   |
| **Especificação Suplementar** | 1.6    | 27/06/2024 | Referenciação Bibliográfica       | [Kauan Eiras](https://github.com/kauaneiras) | [Leonardo Aguiar](https://github.com/Leonardo0o0) |
| **Léxicos**                   | 1.4    | 05/06/2024 | Adição de Itens nas Tabelas 3 e 5 | [Davi Pierre](https://github.com/DaviPierre) | [Kauan Eiras](https://github.com/kauaneiras)      |

**Autor**: [Kauan Eiras](https://github.com/kauaneiras), 2024

</center>

## Checklists

Nesta seção, serão dispostos os checklists dos artefatos da Entrega 4 nas tabelas 3, 4 e 5. Durante a inspeção, o responsável deverá preencher o campo de avaliação da seguinte maneira: 

>- **Sim**, se o critério foi totalmente atendido. 
>- **Não**, se o critério não foi atendido. 
>- **Incompleto**, se o critério foi parcialmente atendido, explicando em qual parte o artefato falhou. 
>- **Não se aplica**, se o critério não pode ser verificado devido ao contexto do projeto. 

### Especificação Suplementar

<center>

**Tabela 3**: Checklist da Especificação Suplementar

| ID  | Descrição                                                                                                                                                | Referência                                                      | Avaliação |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- | --------- |
| 01  | A Especificação Suplementar aborda todos os aspectos do FURPS+ (Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade)?               | [PRESSMAN, 2014, p. 511-513](../grupo_6/assets/PRESS511512.png) | Sim       |
| 02  | Os requisitos de usabilidade incluem critérios de acessibilidade?                                                                                        | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 03  | Os requisitos de usabilidade especificam a necessidade de feedback imediato para ações do usuário?                                                       | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 04  | O documento aborda a necessidade de permitir que os usuários desfaçam ações?                                                                             | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 05  | Os requisitos de confiabilidade incluem a realização automática de backups diários dos dados?                                                            | [PRESSMAN, 2014, p. 513](../grupo_6/assets/PRESS513.png)        | Sim       |
| 06  | O documento especifica que o aplicativo deve ser atualizado sem interromper a navegação do usuário?                                                      | [PRESSMAN, 2014, p. 513](../grupo_6/assets/PRESS513.png)        | Sim       |
| 07  | A Especificação Suplementar menciona a capacidade do sistema de restaurar a sessão do usuário rapidamente após uma falha?                                | [PRESSMAN, 2014, p. 513](../grupo_6/assets/PRESS513.png)        | Sim       |
| 08  | O documento garante que o navegador é compatível com a maioria das páginas web?                                                                          | [PRESSMAN, 2014, p. 513](../grupo_6/assets/PRESS513.png)        | Sim       |
| 09  | Os requisitos de desempenho especificam tempos de resposta aceitáveis para diferentes operações do sistema?                                              | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 10  | A Especificação Suplementar inclui limites para o uso de recursos como CPU e memória?                                                                    | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 11  | Os requisitos de suportabilidade incluem a necessidade de documentação atualizada e suporte técnico?                                                     | [ANUGRAH; PUTRA, 2018, p. 2](../grupo_6/assets/ANUGRAH2.png)    | Sim       |
| 12  | Os requisitos de segurança incluem proteção contra ataques maliciosos?                                                                                   | [PRESSMAN, 2014, p. 511](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 13  | O documento aborda a necessidade de testes automatizados e critérios de aceitação para garantir a qualidade do software?                                 | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |
| 14  | A Especificação Suplementar inclui métricas e métodos para monitorar e avaliar continuamente o desempenho e a qualidade do sistema após a implementação? | [PRESSMAN, 2014, p. 512](../grupo_6/assets/PRESS511512.png)     | Sim       |

**Autor da lista de verificação**: [Kauan Eiras](https://github.com/kauaneiras), **Inspecionado por**: [Leonardo Aguiar](https://github.com/Leonardo0o0) 

</center>

### Léxicos

<center>

**Tabela 4**: Checklist dos Léxicos

| ID  | Pergunta                                                                                        | Referência                                                  | Avaliação |
| --- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | --------- |
| 01  | O artefato inclui uma definição clara de léxicos e sua importância na engenharia de requisitos? | [ZOWGHI; COULIN, 2003, p. 7](../grupo_6/assets/Zowghi7.png) | Sim       |
| 02  | O template para a definição dos léxicos está devidamente apresentado e explicado?               | [SERRANO, p. 17](../grupo_6/assets/Aula10p17.png)           | Sim       |
| 03  | Cada léxico inclui todos os elementos do template: termo, tipo, noção, impacto e autor?         | [SERRANO, p. 17](../grupo_6/assets/Aula10p17.png)           | Sim       |
| 04  | Os termos definidos são relevantes e abrangem todos os aspectos do sistema?                     | [ZOWGHI; COULIN, 2003, p. 8](../grupo_6/assets/Zowghi8.png) | Sim       |
| 05  | Os tipos de léxicos (objeto, verbo, estado) estão devidamente identificados e diferenciados?    | [SERRANO, p. 17](../grupo_6/assets/Aula10p17.png)           | Sim       |
| 06  | Os impactos descritos são detalhados e refletem corretamente o efeito dos termos no sistema?    | [ZOWGHI; COULIN, 2003, p. 8](../grupo_6/assets/Zowghi8.png) | Sim       |
| 07  | O artefato menciona os autores da criação dos léxicos?                                          | [SERRANO, p. 25](../grupo_6/assets/Aula10p25.png)           | Sim       |
| 08  | Os léxicos estão conectados entre si através de hyperlinks?                                     | [SERRANO, p. 20](../grupo_6/assets/Aula10p20.png)           | Sim       |

**Autor da lista de verificação**: [Kauan Eiras](https://github.com/kauaneiras), **Inspecionado por**: [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024

</center>

### Diagrama de Casos de Uso

<center> 

**Tabela 5.1**: Checklist do Diagrama de Casos de Uso

| ID  | Pergunta                                                                                                     | Referência                                           | Avaliação  |
| --- | ------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- | ---------- |
| 01  | No documento, é apresentado um diagrama de casos de uso que representa a interação do usuário com o sistema? | [LUCID Chart](../grupo_6/assets/image.png)           | Sim        |
| 02  | O diagrama de casos de uso segue a notação UML?                                                              | [SERRANO, p. 12](../grupo_6/assets/image-1.png)      | Sim        |
| 03  | No diagrama, há a determinação de atores, sistema e ações?                                                   | [SERRANO, p. 12](../grupo_6/assets/image-2.png)      | Sim        |
| 04  | No diagrama, o ator principal fora do limite do sistema?                                                     | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-17.png) | Sim        |
| 05  | No diagrama, há a definição de atores primários e atores secundários?                                        | [LUCID Chart](../grupo_6/assets/image-3.png)         | Incompleto |
| 06  | No diagrama, o nome e/ou a especificação dos atores é significativa?                                         | [SERRANO, p. 13](../grupo_6/assets/image-4.png)      | Sim        |
| 07  | No diagrama, a sinalização << system >> indica um software ou hardware?                                      | [SERRANO, p. 13](../grupo_6/assets/image-13.png)     | Sim        |
| 08  | No diagrama, há pontos de extensão, inclusão e/ou generalização?                                             | [SERRANO, p. 23](../grupo_6/assets/image-14.png)     | Sim        |
| 09  | No diagrama, os pontos de extensão, inclusão ou generalização são aplicados corretamente?                    | [SERRANO, p. 23](../grupo_6/assets/image-14.png)     | Sim        |
| 10  | No diagrama, os casos de uso levantados representam requisitos?                                              | [SERRANO, p. 8](../grupo_6/assets/image-6.png)       | Sim        |


**Autor da lista de verificação**: [Kallyne Macedo](https://github.com/kalipassos), **Inspecionado por**:  [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

#### Problemas encontrados

De acordo com a checklist de verificação foi encontrado apenas um probelma no artefato [Casos de uso](https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/casos_de_uso/casos_de_uso/) sendo ele a falta de um ator secundário.



### Caso de uso - Realizar Pesquisa na Web

<center> 

**Tabela 5.2**: Checklist da Especificação do Caso de Uso - Realizar Pesquisa na Web

| ID  | Pergunta                                                                                                      | Referência                                           | Avaliação |
| --- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | --------- |
| 01  | Na especificação, os casos de uso levantados representam corretamente as funcionalidades e suas interações    | [MCTIC - CGSI, p. 4](../grupo_6/assets/image-7.png)  | Sim       |
| 02  | Na especificação, há a definição correta das pré e pós-condições dos casos de uso?                            | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-5.png)  | Sim       |
| 03  | Na especificação, há a definição correta dos atores dos casos de uso e de seu escopo?                         | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-8.png)  | Sim       |
| 04  | Na especificação, há a definição de apenas um fluxo principal para cada caso de uso?                          | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-9.png)  | Sim       |
| 05  | Na especificação, os fluxos alternativos são factívelmente alternativos ao principal?                         | [MCTIC - CGSI, p. 6](../grupo_6/assets/image-11.png) | Sim       |
| 06  | Na especificação, os fluxos de exceção representam a reação do sistema a erros ou situações fora do esperado? | [MCTIC - CGSI, p. 7](../grupo_6/assets/image-12.png) | Sim       |
| 07  | Na especificação, a validação do diagrama de casos de uso foi realizada com um usuário?                       | [SERRANO, p. 19](../grupo_6/assets/image-15.png)     | Não       |
| 08  | Na especificação, na validação do diagrama, há a especificação da técnica utilizada?                          | [SERRANO, p. 19](../grupo_6/assets/image-16.png)     | Sim       |

**Autor**: [Kallyne Macedo](https://github.com/kalipassos), **Verificado por**:  [Guilherme Westphall](https://github.com/west)

</center>

#### Problemas encontrados 

O único problema encontrado na especificação do Caso de uso [Realizar Pesquisa na Web](../../modelagem/casos_de_uso/casos_de_uso.md#realizar-pesquisa-na-web) foi no item **07**, não houve a participação do usuário na validação dos casos de uso, e sim de uma **Persona**.


### Caso de uso - Bloquear anúncios

<center>

**Tabela 5.3**: Checklist da Especificação do Caso de Uso - Bloquear anúncios

| ID  | Pergunta                                                                                                      | Referência                                           | Avaliação |
| --- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | --------- |
| 01  | Na especificação, os casos de uso levantados representam corretamente as funcionalidades e suas interações    | [MCTIC - CGSI, p. 4](../grupo_6/assets/image-7.png)  | Sim       |
| 02  | Na especificação, há a definição correta das pré e pós-condições dos casos de uso?                            | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-5.png)  | Sim       |
| 03  | Na especificação, há a definição correta dos atores dos casos de uso e de seu escopo?                         | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-8.png)  | Sim       |
| 04  | Na especificação, há a definição de apenas um fluxo principal para cada caso de uso?                          | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-9.png)  | Sim       |
| 05  | Na especificação, os fluxos alternativos são factívelmente alternativos ao principal?                         | [MCTIC - CGSI, p. 6](../grupo_6/assets/image-11.png) | Sim       |
| 06  | Na especificação, os fluxos de exceção representam a reação do sistema a erros ou situações fora do esperado? | [MCTIC - CGSI, p. 7](../grupo_6/assets/image-12.png) | Sim       |
| 07  | Na especificação, a validação do diagrama de casos de uso foi realizada com um usuário?                       | [SERRANO, p. 19](../grupo_6/assets/image-15.png)     | Não       |
| 08  | Na especificação, na validação do diagrama, há a especificação da técnica utilizada?                          | [SERRANO, p. 19](../grupo_6/assets/image-16.png)     | Sim       |

**Autor da lista de verificação**: [Kallyne Macedo](https://github.com/kalipassos), **Inspecionado por**:  [Leonardo Aguiar](https://github.com/Leonardo0o0)

</center>


### Caso de uso - Acessar histórico

<center> 

**Tabela 5.4**: Checklist da Especificação do Caso de Uso - Acessar histórico

| ID  | Pergunta                                                                                                      | Referência                                           | Avaliação |
| --- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | --------- |
| 01  | Na especificação, os casos de uso levantados representam corretamente as funcionalidades e suas interações    | [MCTIC - CGSI, p. 4](../grupo_6/assets/image-7.png)  | Sim       |
| 02  | Na especificação, há a definição correta das pré e pós-condições dos casos de uso?                            | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-5.png)  | Sim       |
| 03  | Na especificação, há a definição correta dos atores dos casos de uso e de seu escopo?                         | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-8.png)  | Sim       |
| 04  | Na especificação, há a definição de apenas um fluxo principal para cada caso de uso?                          | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-9.png)  | Sim       |
| 05  | Na especificação, os fluxos alternativos são factívelmente alternativos ao principal?                         | [MCTIC - CGSI, p. 6](../grupo_6/assets/image-11.png) | Sim       |
| 06  | Na especificação, os fluxos de exceção representam a reação do sistema a erros ou situações fora do esperado? | [MCTIC - CGSI, p. 7](../grupo_6/assets/image-12.png) | Sim       |
| 07  | Na especificação, a validação do diagrama de casos de uso foi realizada com um usuário?                       | [SERRANO, p. 19](../grupo_6/assets/image-15.png)     | Não       |
| 08  | Na especificação, na validação do diagrama, há a especificação da técnica utilizada?                          | [SERRANO, p. 19](../grupo_6/assets/image-16.png)     | Sim       |

**Autor da lista de verificação**: [Kallyne Macedo](https://github.com/kalipassos), **Inspecionado por**:  [Lucas Martins](https://github.com/martinsglucas), 2024

</center>

### Caso de uso - Mudar o Idioma

<center> 

**Tabela 5.5**: Checklist da Especificação do Caso de Uso - Mudar o Idioma

| ID  | Pergunta                                                                                                      | Referência                                           | Avaliação |
| --- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | --------- |
| 01  | Na especificação, os casos de uso levantados representam corretamente as funcionalidades e suas interações    | [MCTIC - CGSI, p. 4](../grupo_6/assets/image-7.png)  | Sim       |
| 02  | Na especificação, há a definição correta das pré e pós-condições dos casos de uso?                            | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-5.png)  | Sim       |
| 03  | Na especificação, há a definição correta dos atores dos casos de uso e de seu escopo?                         | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-8.png)  | Sim       |
| 04  | Na especificação, há a definição de apenas um fluxo principal para cada caso de uso?                          | [MCTIC - CGSI, p. 5](../grupo_6/assets/image-9.png)  | Sim       |
| 05  | Na especificação, os fluxos alternativos são factívelmente alternativos ao principal?                         | [MCTIC - CGSI, p. 6](../grupo_6/assets/image-11.png) | Sim       |
| 06  | Na especificação, os fluxos de exceção representam a reação do sistema a erros ou situações fora do esperado? | [MCTIC - CGSI, p. 7](../grupo_6/assets/image-12.png) | Sim       |
| 07  | Na especificação, a validação do diagrama de casos de uso foi realizada com um usuário?                       | [SERRANO, p. 19](../grupo_6/assets/image-15.png)     | Não       |
| 08  | Na especificação, na validação do diagrama, há a especificação da técnica utilizada?                          | [SERRANO, p. 19](../grupo_6/assets/image-16.png)     | Sim       |

**Autor da lista de verificação**: [Kallyne Macedo](https://github.com/kalipassos), **Inspecionado por**:  [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

#### Problemas encontrados

Não foram encontrados problemas no artefato [Casos de uso - Mudar Idioma](https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/casos_de_uso/casos_de_uso/) de acordo com o checklist de verificação.

### Cenários

<center> 

**Tabela 5**: Checklist dos Cenários 

| ID  | Pergunta                                                                                                                         | Referência                                                    | Avaliação  |
| --- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | ---------- |
| 01  | Cada cenário possui um título claro e fácil de entender, objetivo, contexto, atores, recursos, restrições, exceções e episódios? | [BARBOSA, SILVA, 2021, p. 172](../grupo_6/assets/imageC5.png) | Sim        |
| 02  | Os cenários são testáveis?                                                                                                       | [BARBOSA, SILVA, 2021, p. 172](../grupo_6/assets/imageC1.png) | Incompleto |
| 03  | Existem cenários que conjuntamente se complementam?                                                                              | [LEITE, p.52-53](../grupo_6/assets/imageC7.png)               | Não        |
| 04  | Os cenários descrevem interações realistas e significativas com o sistema?                                                       | [BARBOSA, SILVA, 2021, p. 173](../grupo_6/assets/imageC3.png) | Sim        |
| 05  | Os atores são apropriados e relevantes para o contexto dos cenários?                                                             | [BARBOSA, SILVA, 2021, p. 172](../grupo_6/assets/imageC2.png) | Sim        |
| 06  | Há um episódio/evento relacionado a cada um dos cenários?                                                                        | [BARBOSA, SILVA, 2021, p. 172](../grupo_6/assets/imageC5.png)  | Sim        |
| 07  | Há uma referência clara aos léxicos nos cenários?                                                                                | [LEITE, p. 50](../grupo_6/assets/imageC4.png)                 | Não        |
| 08  | O artefato menciona as técnicas utilizadas para desenvolver os cenários?                                                         | [LEITE, p.48-49](../grupo_6/assets/imageC6.png)               | Sim        |
| 09  | A introdução ou metodologia trazem referências que justifiquem a forma que o trabalho foi desenvolvido?                          | [LEITE, p.48-49](../grupo_6/assets/imageC6.png)               | Sim        |

**Autor da lista de verificação**: [Kallyne Macedo](https://github.com/kalipassos), **Inspecionado por**:  [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

#### Problemas encontrados

Foram encontrados alguns problemas no artefato [Cenários](https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/cenarios/) sendo eles os cenários não serem todos testáveis, pois "Proteger os dados de usuário" não é testável, não existem cenários que se completam conjuntamente, pois todos os cenários são individuais e não tem uma conexão clára com os léxicos em nenhum dos requisitos.

## Referências

1. PRESSMAN, Roger S. *Software Engineering: A Practitioner's Approach*. 7. ed. New York: McGraw-Hill, 2014.
2. MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES. *Especificação de Caso de Uso*. Disponível em: https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Caso%20Uso_81686821.html?nodeId=afc37190. Acesso em: 27 jun. 2024.
3. ANUGRAH, Septriyan; PUTRA, Andri Eka. *Analisis Kualitas ISO 25010 Aplikasi Artificial Intelligence Troubleshooting Komputer dengan FURPS*. Universitas Negeri Padang; SMK N 1 Ampek Angkek, 2018. Disponível em: <URL>. Acesso em: 27 jun. 2024.
4. ZOWGHI, D.; COULIN, C. *Requirements Elicitation: A Survey of Techniques, Approaches and Tools*. Acesso em: 28 jun. 2024. 
5. SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 10. Acesso em: 09 jun. 2024.
6. SERRANO, Milene. Requisitos - Aula 11. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 40, color. Disponível em: Requisitos - Aula 11. Acesso em: 27 jun. 2024.
7. LEITE, Júlio C. S. P.; et al. Modelos de requisitos e cenários: uma abordagem centrada no usuário. PUC-Rio. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf. Acesso em: 27 jun. 2024.
8. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em: 27 jun. 2024.


 
## Histórico de versões

| Versão | Data       | Descrição                                                                       | Autor                                             | Revisor                                         |
| ------ | ---------- | ------------------------------------------------------------------------------- | ------------------------------------------------- | ----------------------------------------------- |
| 1.0    | 01/07/2024 | Cria página                                                                     | [Kauan Eiras](https://github.com/kauaneiras)      | [Kallyne Macedo](https://github.com/kalipassos) |
| 1.1    | 01/07/2024 | Especificação Suplementar                                                       | [Kauan Eiras](https://github.com/kauaneiras)      | [Kallyne Macedo](https://github.com/kalipassos) |
| 1.2    | 01/07/2024 | Checklists cenário e casos de uso                                               | [Kallyne Macedo](https://github.com/kalipassos)   | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.3    | 01/07/2024 | verificação Especificação Suplementar e Léxicos e caso de uso bloquear anuncios | [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Kallyne Macedo](https://github.com/kalipassos) |
| 1.4    | 01/07/2024 | Adiciona inspeção do Caso de Uso - Realizar pesquisa na web                     | [Guilherme Westphall](https://github.com/west)    | [Kallyne Macedo](https://github.com/kalipassos) |
| 1.4    | 02/07/2024 | Verifica tabela 5 de cenários e adiciona tabela 5.5 Casos de Uso - Mudar Idioma | [Davi Pierre](https://github.com/DaviPierre)      |  [Kallyne Macedo](https://github.com/kalipassos)     |