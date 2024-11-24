# Especificação Suplementar

## Introdução

A Especificação Suplementar corresponde a um documento em linguagem natural que busca descrever os requisitos de um sistema que não foram elicitados pelos casos de uso. Este documento é complementar à modelagem de casos de uso e é crucial no processo de desenvolvimento de software, pois captura requisitos não funcionais e outros aspectos essenciais que não são facilmente definidos pela modelagem (MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES, 2024). O objetivo principal da Especificação Suplementar é garantir que todos os requisitos do sistema sejam abrangidos, proporcionando uma visão completa e detalhada que, junto com os casos de uso, define todos os requisitos do sistema. Este documento é essencial para assegurar a qualidade do software e a satisfação do usuário.

## Metodologia

A metodologia base utilizada para a produção da Especificação Suplementar é a FURPS+, que aborda Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, além de outros aspectos (PRESSMAN, 2014). Dessa forma, o documento foi estruturado de forma a permitir que cada subtópico da Especificação Suplementar represente um aspecto da FURPS+.

## Especificação Suplementar

### Funcionalidade

Os requisitos funcionais estão especificados nos [cenários](cenarios.md) e [casos de uso](casos_de_uso/casos_de_uso.md).

### Usabilidade

Usabilidade, segundo Nielsen (1994), é a qualidade que avalia a facilidade de uso de uma interface. Ele propõe 10 heurísticas que, quando seguidas, promovem uma melhor usabilidade, permitindo que os usuários realizem suas tarefas de forma eficiente, eficaz e satisfatória (NIELSEN, 1994).

Na tabela 1, são apresentados os requisitos identificados em relação à usabilidade:

<center>

**Tabela 1**: Requisitos de Usabilidade.

|  ID   |                                                                                 Descrição                                                                                  |
| :---: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  US1  |                                                              Deve ser possível visualizar em formato desktop                                                               |
|  US2  |                  Deve disponibilizar formas de facilitar seu uso principal, como criar atalhos, sugestões personalizadas de pesquisa e pesquisa por voz.                   |
|  US3  | Deve disponibilizar formas de se adaptar ao usuário, incluindo acessibilidade, personalizar a tela inicial do navegador, mudar o idioma e mudar entre tema claro e escuro. |
|  US4  |                                                  O aplicativo deve fornecer feedback imediato após cada ação do usuário.                                                   |
|  US5  |                                               O aplicativo deve permitir que os usuários desfaçam ações sempre que possível.                                               |

**Autor:**  [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024.

</center>

### Confiabilidade

O aspecto da confiabilidade refere-se à habilidade de um produto em executar uma função específica sob condições determinadas, por um período de tempo definido ou por uma quantidade específica de operações. As principais subcategorias que compõem a confiabilidade podem ser definidas como: disponibilidade, precisão e recuperabilidade (PRESSMAN, 2014).

Na tabela 2, são apresentados os requisitos identificados em relação à confiabilidade.

<center>

**Tabela 2**: Requisitos de Confiabilidade

|  ID   |                                                                                                    Descrição                                                                                                     |   Subcategoria   |
| :---: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------: |
| RC01  | O aplicativo deve ter um Tempo Médio Entre Falhas (MTBF) de no mínimo 1000 horas de uso, e um Tempo Médio para Reparo (MTTR) de no máximo 1 hora, conforme medido por ferramentas de monitoramento de desempenho | Disponibilidade  |
| RC02  |                               O aplicativo deve apresentar proteção contra ataques maliciosos 24 horas por dia, 7 dias da semana, conforme comprovado por um sistema de segurança                                | Disponibilidade  |
| RC03  |                                                                 O backup dos dados deve ser realizado automaticamente pelo menos uma vez por dia                                                                 | Recuperabilidade |
| RC04  |                                         O aplicativo deve carregar as páginas Web com 99.9% de precisão, exibindo os elementos adequadamente, conforme diretrizes do W3C                                         |     Precisão     |
| RC05  |                                                                     O aplicativo deve ser atualizado sem interromper a navegação do usuário                                                                      | Disponibilidade  |
| RC06  |                                                      O aplicativo deve ser capaz de restaurar a sessão do usuário em menos de 1 minuto, caso falhe ou trave                                                      | Recuperabilidade |
| RC07  |                                                 O navegador deve ser compatível com pelo menos 90% das páginas web, comprovado através de uma amostra de sites.                                                  |     Precisão     |

**Autor:**  [Kallyne Macedo](https://github.com/kalipassos), 2024
</center>

### Desempenho

Os requisitos de desempenho especificam as expectativas e limites relacionados à eficiência e capacidade de resposta de um sistema ou aplicativo. Eles são críticos para garantir que o software funcione de maneira eficaz sob várias condições de uso e carga (PRESSMAN, 2014).

Na tabela 3, são apresentados os requisitos identificados em relação ao desempenho.

<center>

**Tabela 3**: Requisitos de Desempenho

| Identificador |                                                                                                                                  Descrição                                                                                                                                   |
| :-----------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     DES01     |                                                                                          O sistema deve apresentar tempo de resposta inferior a 1 segundo ao realizar uma pesquisa                                                                                           |
|     DES02     |                                                  O navegador deve ser capaz de iniciar e estar pronto para uso em menos de 3 segundos em dispositivos móveis com pelo menos 4 GB de RAM e processador quad-core de 1.8 GHz                                                   |
|     DES03     |                                          As páginas web devem começar a ser renderizadas em menos de 1 segundo e estar totalmente carregadas em menos de 3 segundos em conexões de internet de alta velocidade (pelo menos 50 Mbps)                                          |
|     DES04     |                                                                          O sistema deve ser capaz de armazenar em cache páginas web visitadas para acelerar o carregamento de páginas subsequentes                                                                           |
|     DES05     | O Firefox deve consumir menos de 20% de CPU durante a navegação típica (definida como navegação em sites populares como redes sociais, notícias, e-commerce) e menos de 50% durante operações intensivas (definidas como execução de vídeos em alta definição, jogos online) |
|     DES06     |               O Firefox deve liberar memória quando as guias são fechadas ou não utilizadas, mantendo o consumo de memória abaixo de 500 MB durante a navegação típica (até 10 guias abertas) e não ultrapassar 2 GB em uso intenso (mais de 30 guias abertas)               |

**Autor:**  [Lucas Martins](https://github.com/martinsglucas), 2024

</center>

### Suportabilidade

A Suportabilidade de Software é a capacidade de suportar um sistema de software durante toda a sua vida útil. Isso implica satisfazer todas as necessidades ou requisitos necessários, bem como a provisão de equipamentos, infraestrutura de suporte, software adicional, instalações, mão de obra ou qualquer outro recurso necessário para manter o software operacional e capaz de cumprir sua função (MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES, 2024).

A empresa que gerencia o software possui uma [página de suporte online](https://support.mozilla.org/pt-BR/). Além disso, realiza atualizações regulares, com uma frequência de quatro semanas, além de uma atualização anual mais abrangente. As atualizações abordam novas funcionalidades e corrigem erros identificados em seus respectivos períodos. No caso do aplicativo Firefox, ele oferece suporte para sistemas operacionais iOS 13.0 e superior, e Android 5.0 e acima.

Na tabela 4, são apresentados os requisitos identificados em relação à suportabilidade:

<center>

**Tabela 4**: Requisitos de Suportabilidade.

|  ID   |                                                                                      Descrição                                                                                       |
| :---: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| SUP01 |                O aplicativo deve prover suporte técnico em casos de erros de execução e bugs através de sistema de tickets/reclamações com SLA inicial de até um dia                 |
| SUP02 |             O sistema deve ser extensível para permitir a adição de novas funcionalidades e acompanhar as mudanças, com validação pela aplicação de um framework modular             |
| SUP03 |                                         O aplicativo deve ter sua documentação sempre atualizada, com cobertura de pelo menos 90% do sistema                                         |
| SUP04 | O sistema deve ser projetado para facilitar a realização de testes automatizados durante o desenvolvimento e a manutenção, validado através de pelo menos 80% de cobertura de testes |
| SUP05 | O sistema deve contar com rastreabilidade, incluindo mecanismos para registrar e acompanhar mudanças e correções ao longo do tempo, com controle de versão e registros de alterações |

**Autor:**  [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024.

</center>

### +: Restrições de Design

As restrições de design tratam das limitações e diretrizes que o projeto deve seguir.

Na tabela 5, são apresentados os requisitos identificados em relação às restrições de design.

<center>

**Tabela 5**: Requisitos de Restrições de Design

|  ID   |                                              Descrição                                               |
| :---: | :--------------------------------------------------------------------------------------------------: |
| RD01  | O aplicativo deve ser compatível com as diretrizes de design do sistema operacional (Android ou iOS) |
| RD02  |        O design do aplicativo deve ser responsivo e adaptável ao tamanho do dispositivo móvel        |
| RD03  |                  O aplicativo deve seguir diretrizes de acessibilidade da WCAG 2.1                   |

**Autor:**  [Kallyne Macedo](https://github.com/kalipassos), 2024
</center>

### +: Requisitos de Implementação

Requisitos de implementação detalham as restrições e condições para a construção, codificação e integração de um sistema ou aplicativo. Eles são orientados para o desenvolvimento técnico e influenciam a forma como o software é desenvolvido, estruturado e mantido (PRESSMAN, 2014).

Na tabela 6, são apresentados os requisitos em relação à implementação.

<center>

**Tabela 6**: Requisitos de Implementação

| Identificador |                                                               Descrição                                                               |
| :-----------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
|     IMP01     | O código-fonte deve seguir os padrões de codificação definidos pela Mozilla, como aqueles especificados no Mozilla Coding Style Guide |
|     IMP02     |     O sistema deve ser desenvolvido de forma modular, permitindo a reutilização de componentes em diferentes partes do navegador      |
|     IMP03     |          A documentação técnica do sistema, incluindo diagramas de arquitetura e manuais de API, deve ser mantida atualizada          |
|     IMP04     |          Cobertura de testes deve ser mantida acima de 80%, com testes automatizados para todas as funcionalidades críticas           |
|     IMP05     |     O código deve ser escrito de maneira a ser portátil, facilitando a execução do navegador em diferentes sistemas operacionais      |

**Autor:**  [Lucas Martins](https://github.com/martinsglucas), 2024

</center>

### +: Requisitos de Interface

Os requisitos de interface no contexto do modelo FURPS+ estão relacionados à qualidade de usabilidade e interface do usuário de um sistema de software (NIELSEN, 1994).

Na tabela 7, foram listados na tabela os Requisitos Não Funcionais (RNF) relacionados a interface.

<center>

**Tabela 7**: Requisitos de Interface

| Identificador | Descrição                                                                                                                                                                           |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| INT01         | Os elementos da interface devem ser organizados conforme as diretrizes do Acorn Design                                                                                              |
| INT02         | O usuário deve conseguir acessar qualquer parte do sistema em no máximo três cliques, validado através de testes de usabilidade com aprovação de 90%                                |
| INT03         | Mensagens de erro devem ser exibidas em tons de vermelho entre #ffdfe7 e #810220, devendo ocupar pelo menos 15% da tela visível                                                     |
| INT04         | Um novo usuário deve conseguir concluir uma tarefa simples, como abrir uma nova guia, sem consultar a documentação,  validado através de testes de usabilidade com aprovação de 90% |
| INT05         | A interface deve ser testada com um leitor de tela para garantir que todas as informações sejam acessíveis, conforme as diretrizes de acessibilidade WCAG 2.1.                      |
| INT06         | O usuário deve conseguir alterar a cor de fundo da interface nas configurações, validado através de testes de usabilidade com aprovação de 90%                                      |
| INT07         | A interface deve carregar em menos de dois segundos em uma conexão de internet padrão, validado através de testes de desempenho.                                                    |

**Autor:**  [Kallyne Macedo](https://github.com/kalipassos), 2024

</center>

### +: Requisitos Físicos

Requisitos físicos: refere-se ao hardware onde o sistema vai ser alocado, como será exibido, além da interface usuário-sistema através do hardware. Desse modo, foi levantado que o app Firefox possui as seguintes restrições (SUPORTE, Mozilla, 2024):

* No caso de sistemas iOS, o aparelho deverá estar na versão 13.0 ou superior. <br>
* No caso de sistemas Android, o aparelho deverá estar na versão 5.0 ou superior. <br>
* O aparelho deverá possuir acesso à internet para ter todas as funcionalidades do software disponíveis.

**Autor:**  [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024.

## Referências

1. MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES. Especificação de Caso de Uso. Disponível em: https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Caso%20Uso_81686821.html?nodeId=afc37190. Acesso em: 27 jun. 2024.
   
2. PRESSMAN, Roger S. Software Engineering: A Practitioner's Approach. 7. ed. New York: McGraw-Hill, 2014.

3. NIELSEN, Jakob. 10 Usability Heuristics for User Interface Design. NN/g Nielsen Norman Group, 24 abr. 1994. Atualizado em 30 jan. 2024. Disponível em: https://www.nngroup.com/articles/ten-usability-heuristics/. Acesso em: 27 jun. 2024.

4. SUPORTE, Mozilla; Gerir atualizações do Firefox, 2024. Disponível em: <https://support.mozilla.org/pt-PT/kb/gerir-atualizacoes-do-firefox>. Acesso em: 20 de maio de 2024.

5. ALVES, Izabella; ZARANZA, Gabriel. Especificação Suplementar. Repositório do Grupo Economia-DF da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#historico-de-versoes. Acesso em: 17 de maio de 2024.

## Histórico de Versões 

| Versão |    Data    | Descrição                                         |                       Autor                       |                      Revisor                      |
| :----: | :--------: | ------------------------------------------------- | :-----------------------------------------------: | :-----------------------------------------------: |
|  1.0   | 19/05/2024 | Introdução e Metodologia                          |  [Kallyne Macedo](https://github.com/kalipassos)  | [Lucas Martins](https://github.com/martinsglucas) |
|  1.1   | 20/05/2024 | Usabilidade, Suportabilidade e Requisitos Físicos | [Leonardo Aguiar](https://github.com/Leonardo0o0) |   [Davi Pierre](https://github.com/DaviPierre)    |
|  1.2   | 20/05/2024 | Desempenho e Requisitos de Implementação          | [Lucas Martins](https://github.com/martinsglucas) |   [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.3   | 20/05/2024 | Confiabilidade, Restrições de Design e Interface  |  [Kallyne Macedo](https://github.com/kalipassos)  |   [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.4   | 27/05/2024 | Melhor especificação para o Desempenho            | [Lucas Martins](https://github.com/martinsglucas) | [Leonardo Aguiar](https://github.com/Leonardo0o0) |
|  1.5   | 05/06/2024 | Reescrita da especificação de forma testável      |  [Kallyne Macedo](https://github.com/kalipassos)  | [Leonardo Aguiar](https://github.com/Leonardo0o0) |
|  1.6   | 27/06/2024 | Referenciação Bibliográfica                       |   [Kauan Eiras](https://github.com/kauaneiras)    | [Leonardo Aguiar](https://github.com/Leonardo0o0) |
