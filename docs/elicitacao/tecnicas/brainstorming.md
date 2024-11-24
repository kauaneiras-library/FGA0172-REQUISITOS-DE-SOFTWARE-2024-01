# Elicitação de Requisitos: Brainstorming

## Introdução

Conforme pesquisa levantada pela UFSC, o brainstorming pode ser classificado como uma técnica de elicitação de requisitos em que cada participante tem a oportunidade de expor suas concepções de forma aberta, com o objetivo de desenvolvimento de um novo sistema. Nessa técnica, os participantes podem ter origens acadêmicas e profissionais distintas e compartilham suas ideias, que são direcionadas para a resolução de um problema específico, em um intervalo de tempo determinado. Dessa forma, a abordagem possibilita que os stakeholders ampliem suas perspectivas acerca do problema em questão (UFSC, 2023).

Alan Cooper (1999) sugere realizar sessões de brainstorming considerando um “computador mágico”, que não possui qualquer restrição. Ele acredita que esse exercício ajuda a fazer a distinção entre objetivos e tarefas. A elaboração de um perfil de usuário também é fundamental nesse processo, como destacado por Barbosa e Silva (2021), onde se identificam características de interesse e se conduz um estudo para coletar dados dos usuários.

O Design Thinking, conforme apresentado por Vianna et al. (2011), promove a geração de um grande número de ideias em um curto espaço de tempo. No processo de ideação, o brainstorming possibilita uma abordagem rica para gerar ideias em cima de questões relevantes que nasceram durante as fases de imersão e análise. Para que um brainstorming tenha sucesso, é necessário estar atento a preceitos como qualidade pela quantidade e evitar julgamentos precipitados das ideias.

## Justificativa

No contexto da elicitação de requisitos, o brainstorming tem como principal vantagem sua capacidade de estimular a criatividade, promovendo a geração de ideias diversas através da expressão livre dos pensamentos (Vianna et al., 2011). Assim, a técnica traz variedade, profundidade e inovação para as informações coletadas e, consequentemente, auxilia na resolução de conflitos oriundos da elicitação.

## Metodologia

A metodologia adotada neste estudo foi baseada na combinação de técnicas de elicitação de requisitos e práticas de Design Thinking. Para o brainstorming, foi estabelecido um número mínimo de seis participantes para garantir uma diversidade adequada de perspectivas e ideias, conforme recomendado na literatura (Vianna et al., 2011). As sessões foram estruturadas da seguinte maneira:

1. **Preparação:**
   - Seleção de participantes.
   - Definição do problema específico a ser resolvido.

2. **Sessão de Brainstorming:**
   - Condução da sessão por um moderador, garantindo que todos os participantes tenham a oportunidade de contribuir e que a sessão permaneça focada.

3. **Análise e Síntese:**
   - Coleta e agrupamento das ideias geradas durante a sessão.
   - Elaboração de perfis de usuário a partir dos dados coletados, conforme metodologia de Barbosa e Silva (2021).

4. **Avaliação:**
   - Discussão das ideias geradas e seleção das mais viáveis e inovadoras.
   - Revisão e refinamento dos requisitos identificados.

<center>

### Tabela 1: Participantes

| Nome                                              | Função   |
| ------------------------------------------------- | -------- |
| [Guilherme Westphall](https://github.com/west7)   | Mediador |
| [Lucas Martins](https://github.com/martinsglucas) | Mediador |
| Guilherme Dutra                                   | Usuário  |
| Hugo Queiroz                                      | Usuário  |

**Autor:** [Guilherme Westphall](https://github.com/west7)
</center>

## Desenvolvimento

### Pergunta 1 - Quais as funcionalidades essenciais para o navegador Firefox?
- Velocidade de resposta
- Sincronização de dados
- Boa gestão de memória
- Criação de vários perfis
- Proteção de dados
- Compatibilidade
- Assertividade

### Pergunta 2 - O que te faria usar o Firefox?
- Sincronização com a conta Google
- Bom bloqueador de anúncios
- Possibilidade de vários perfis de usuário
- Mais extensões
- Tradução de páginas
- Ferramenta de leitura de páginas

### Pergunta 3 - O que você mais gosta no seu navegador atual?
- Facilidade de uso
- Separação de perfis
- Agrupamento de guias
- Sincronização de senhas com o dispositivo 
- Bloqueador de anúncios   
- Sugestão de notícias
- Navegação segura

### Pergunta 4 - De que forma o Firefox pode ser mais acessível?
- Ferramenta de leitura avançada
- Modo daltonismo
- Controle parental
- Correção ortográfica

### Pergunta 5 - O que pode ser melhorado no Firefox?
- Padronização entre plataformas

### Pergunta 6 - Você considera a interface do Firefox intuitivo?
- Todos responderam "sim"

### Pergunta 7 - O que você considera positivo no Firefox?
- Variedade de personalização da tela inicial
- Pesquisa direta
- Acesso fácil a guias recém visitadas
- Criação de atalhos

> Legenda para tabela 2:
>
> - **RFx**: Requisito funcional nº x
> - **RNFx**: Requisito não funcional nº x
> - **BRSx**: Requisito nº x elicitado pela técnica de brainstorming

<center>

### Tabela 2: Requisitos elicitados

| Tipo  | Descrição                                                       | ID    | Implementado |
| ----- | --------------------------------------------------------------- | ----- | ------------ |
| RNF01 | O navegador deve responder rapidamente as pesquisas             | BRS01 | Sim          |
| RNF02 | O sistema deve gerir bem a memória                              | BRS02 | Sim          |
| RF01  | Deve sincronizar os dados                                       | BRS03 | Sim          |
| RF02  | Deve ser possível criar vários perfis                           | BRS04 | Não          |
| RF03  | O sistema deve ser compatível com várias plataformas            | BRS05 | Sim          |
| RNF03 | O sistema deve proteger os dados do usuário durante a navegação | BRS06 | Sim          |
| RF04  | O sistema deve prover sincronização com a conta google          | BRS07 | Não          |
| RF05  | O navegador deve conter um bloqueador de anúncios               | BRS08 | Não          |
| RF06  | Deve ser possível instalar várias extensões                     | BRS09 | Sim          |
| RF07  | Deve fornecer uma ferramenta de tradução de páginas             | BRS10 | Não          |
| RF08  | Deve fornecer uma ferramenta de leitura avançada                | BRS11 | Não          |
| RNF04 | Sistema deve ser de fácil uso                                   | BRS12 | Sim          |
| RF09  | Deve ser possível agrupar várias guias                          | BRS13 | Não          |
| RF10  | Deve ser possível sincronizar senhas com outros dispositivos    | BRS14 | Não          |
| RF11  | O navegador deve conter uma página de sugestão de notícias      | BRS15 | Não          |
| RNF05 | O navegador deve prover uma navegação segura                    | BRS16 | Não          |
| RF12  | O navegador deve incluir um modo de daltonismo                  | BRS17 | Não          |
| RF13  | Deve conter uma ferramenta de controle parental                 | BRS18 | Não          |
| RF14  | Deve conter uma ferramenta de correção ortográfica              | BRS19 | Não          |
| RNF06 | O sistema deve ser padronizado entra plataformas                | BRS20 | Não          |
| RNF07 | O sistema deve ter uma interface intuitiva                      | BRS21 | Sim          |
| RF15  | O sistema deve fornecer uma personalização diversa              | BRS22 | Sim          |
| RF16  | O sistema deve conter uma ferramenta de pesquisa rápida         | BRS23 | Sim          |
| RF17  | Deve conter uma lista de páginas recém visitadas                | BRS24 | Sim          |
| RF18  | Deve ser possível a criação de atalhos                          | BRS25 | Sim          |

**Autores:** [Guilherme Westphall](https://github.com/west7) e [Lucas Martins](https://github.com/martinsglucas), 2024

</center>

## Link da gravação

<center>

**Vídeo 1**: Gravação da reunião de Brainstorming

<iframe width="560" height="315" src="https://www.youtube.com/embed/narh2r5dhUg?si=fdIlbsQ10JuP6_GD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Autores:** [Guilherme Westphall](https://github.com/west7) e [Lucas Martins](https://github.com/martinsglucas), 2024
</center>

## Referências

1. **COOPER, Alan.** The Inmates Are Running the Asylum: Why High-Tech Products Drive Us Crazy and How to Restore the Sanity. Indianapolis: Sams, 1999.

2. **BARBOSA, Simone; SILVA, Bruno.** Interação Humano-Computador e Experiência do Usuário. 3 de maio de 2021.

3. **VIANNA, Maurício; VIANNA, Ysmar; ADLER, Isabel K.; LUCENA, Brenda; RUSSO, Beatriz.** Design Thinking: Inovação em Negócios. MJV Tecnologia Ltda, 2011.

4. **Universidade Federal de Santa Catarina (UFSC).** *Pesquisa sobre técnicas de elicitação de requisitos*, 2023. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-observacao-direta. Acesso em: 14 abr. 2024.

## Histórico de Versões 


| Versão |    Data    | Descrição                                        |                      Autor                      |                      Revisor                      |
| :----: | :--------: | ------------------------------------------------ | :---------------------------------------------: | :-----------------------------------------------: |
|  1.0   | 14/04/2024 | Descrição do método de Elicitação: Brainstorming | [Kallyne Macedo](https://github.com/kalipassos) |   [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.1   | 16/04/2024 | Adição das perguntas                             | [Guilherme Westphall](https://github.com/west7) |   [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.2   | 16/04/2024 | Adiciona tabela 1 e 2                            | [Guilherme Westphall](https://github.com/west7) |   [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.3   | 17/04/2024 | Adiciona link da gravação                        | [Guilherme Westphall](https://github.com/west7) | [Lucas Martins](https://github.com/martinsglucas) |
|  1.4   | 20/04/2024 | Troca do link para link do Youtube               |  [Kauan Eiras](https://github.com/kauaneiras)   |  [Guilherme Westphall](https://github.com/west7)  |
|  1.5   | 30/05/2024 | Correção da formatação                           |  [Kauan Eiras](https://github.com/kauaneiras)   |  [Guilherme Westphall](https://github.com/west7)  |

