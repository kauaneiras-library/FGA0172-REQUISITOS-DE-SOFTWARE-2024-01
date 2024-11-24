# Cenários

## Introdução

Os cenários são uma ferramenta muito útil para compreender a interação entre o ambiente e o sistema. Eles são eficazes na elicitação e especificação do comportamento do software. A abordagem escolhida pelo grupo considera os cenários como descrições evolutivas de situações no ambiente, alinhada com uma linha de base de requisitos orientada ao cliente ou usuário. Esta abordagem modela os requisitos externos de um sistema de software e sua evolução, começando por descrever as situações do ambiente e as principais ações realizadas fora do sistema de software. Além disso, os cenários ajudam a esclarecer a relação entre requisitos funcionais e não funcionais (LEITE, 1997).

Os cenários facilitam a comunicação entre stakeholders, ajudando a visualizar como o sistema deve funcionar em situações reais (YOUNG, 2003). Eles são fundamentais para garantir a qualidade do software, pois identificam possíveis problemas e áreas de melhoria desde as fases iniciais do desenvolvimento (CHEMUTURI, 2010). Cenários bem definidos podem facilitar a análise de requisitos, proporcionando uma melhor compreensão das necessidades do usuário e do contexto de uso (BERENBACH et al., 2009). Casos de uso bem elaborados ajudam a identificar e preparar narrativas detalhadas do atual e futuro processo necessário para o desenvolvimento do projeto de software, incluindo a descrição completa de todos os processos, fluxo de eventos e atividades simultâneas (RETRAINING, 2024).

## Metodologia

A construção dos cenários foi realizada identificando as principais tarefas do aplicativo Firefox para Android e iOS. Essas tarefas foram selecionadas com base nos requisitos que foram priorizados pelo grupo utilizando as técnicas In or Out, Three Level Scale e MOSCOW. Os cenários escolhidos são os requisitos que obtiveram a maior prioridade nas três técnicas de priorização. Para essa tarefa, todos os membros da equipe foram designados, cada um responsável por descrever quatro cenários usando textos estruturados para melhor compreensão. A elaboração dos cenários seguiu as diretrizes propostas por Leite (1997), que sugere uma estrutura semi-estruturada para facilitar o entendimento e a validação dos requisitos. A Tabela 1 mostra o identificador do cenário, descrição e membro da equipe responsável.

<center>

**Tabela 1**: Cenários

| Identificador | Descrição | Membro de Equipe |
|---|---|---|
| CEN01 | Pesquisar e abrir sites | [Leonardo Aguiar](https://github.com/Leonardo0o0) | 
| CEN02 | Escolher idioma | [Kauan Eiras](https://github.com/kauaneiras) | 	
| CEN03 | Traduzir páginas | [Leonardo Aguiar](https://github.com/Leonardo0o0) |
| CEN04 | Sincronizar e salvar dados do usuário | [Leonardo Aguiar](https://github.com/Leonardo0o0)  |
| CEN05 | Trocar de conta sincronizada | [Leonardo Aguiar](https://github.com/Leonardo0o0)  |
| CEN06 | Bloquear anúncios dos sites| [Guilherme Westphall](https://github.com/west7) | 
| CEN07 | Buscar por textos na página | [Guilherme Westphall](https://github.com/west7) |
| CEN08 | Realizar pesquisa por voz | [Kallyne Macedo](https://github.com/kalipassos) |
| CEN09 | Ler textos da página para deficientes visuais | [Davi Pierre](https://github.com/DaviPierre) |
| CEN10 | Ativar modo para daltônicos | [Lucas Martins](https://github.com/martinsglucas) |
| CEN11 | Ativar controle parental	| [Kauan Eiras](https://github.com/kauaneiras) |
| CEN12 | Alterar fonte do navegador em tipo e tamanho | [Kauan Eiras](https://github.com/kauaneiras) |
| CEN13 | Proteger dados do usuário |[Kauan Eiras](https://github.com/kauaneiras) | 
| CEN14 | Limpar histórico de navegação, senhas salvas e cache | [Lucas Martins](https://github.com/martinsglucas) | 
| CEN15 | Escolher entre tema claro ou escuro | [Lucas Martins](https://github.com/martinsglucas) |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024

</center>

Cada cenário é descrito conforme a Tabela 2.

<center>

**Tabela 2**: Elementos de um cenário

| Elemento | Descrição |
| --- | --- |
| Título | O título do cenário |
| Objetivo | O objetivo a ser alcançado pela tarefa |
| Contexto | Descreve a localização geográfica e o estado inicial da tarefa |
| Recursos | Meios de apoio e dispositivos que necessitam estar disponíveis para o cenário |
| Atores | Pessoa que realiza a tarefa descrita no cenário |
| Episódios | Frases que descrevem como o cenário acontece e seu comportamento |
| Restrição | Características que o cenário deve seguir |
| Exceção | Situações que impedem a realização do cenário |

**Fonte**: LEITE, 1997

</center>

## Cenários


### CEN01: Pesquisar e abrir sites

Na Tabela 3 está determinado o cenário CEN01, que descreve a pesquisa e abertura de sites no aplicativo Firefox.

<center>

**Tabela 3**: CEN01

| Elemento | Descrição |
| --- | --- |
| Título | Pesquisar e abrir sites |
| Objetivo | Realizar uma pesquisa na internet através da barra de pesquisa |
| Contexto | Local: em casa,<br> Tempo: durante o dia realizado em 1 minuto,<br> Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos | Aparelho celular,<br> Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios | Usuário deseja realizar uma pesquisa sobre cachorros,<br> Usuário pega o celular, <br> Usuário abre o aplicativo do Firefox,<br> Usuário abre a barra de pesquisa,<br> Usuário digita o que deseja pesquisar,<br> Usuário aperta o botão para realizar a pesquisa,<br> O app Firefox mostra os resultados da pesquisa |
| Restrição | O aplicativo deve estar atualizado para evitar erros |
| Exceção | Queda de internet,<br> O aparelho celular não funcionar |

**Autor**: [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024

</center>

### CEN02: Escolher idioma

Na Tabela 4 está determinado o cenário CEN02, que descreve a escolha de idioma no aplicativo Firefox.

<center>

**Tabela 4**: CEN02

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Escolher idioma                                                                                    |
| Objetivo    | Permitir ao usuário alterar o idioma do aplicativo Firefox                                         |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 2 minutos<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos    | Aparelho celular<br>Acesso à internet                                                              |
| Atores      | Usuário do aplicativo Firefox                                                                      |
| Episódios   | <ul><li>Usuário deseja alterar o idioma do aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu de configurações</li><li>Usuário seleciona a opção "Idioma"</li><li>Usuário escolhe o idioma desejado na lista de idiomas disponíveis</li><li>Usuário confirma a seleção do idioma</li><li>O aplicativo Firefox atualiza a interface para o idioma escolhido</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros<br>O idioma escolhido deve estar disponível no aplicativo |
| Exceção     | <ul><li>Queda de internet</li><li>O aparelho celular não funcionar</li><li>O idioma escolhido não está disponível</li></ul>                        |

**Autor**: [Kauan Eiras](https://github.com/kauaneiras), 2024

</center>

### CEN03: Traduzir páginas

Na Tabela 5 está determinado o cenário CEN03, que descreve a tradução de páginas no aplicativo Firefox.

<center>

**Tabela 5**: CEN03

| Elemento | Descrição |
| --- | --- |
| Título | Traduzir páginas |
| Objetivo | Traduzir uma página que está em um idioma desconhecido para um idioma conhecido |
| Contexto | Local: em casa,<br> Tempo: durante a noite realizado em 1 minuto,<br> Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos | Aparelho celular,<br> Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios | Usuário deseja realizar uma pesquisa sobre gatos,<br> Usuário pega o celular, <br> Usuário abre o aplicativo do Firefox,<br> Usuário abre a barra de pesquisa,<br> Usuário digita o que deseja pesquisar,<br> Usuário aperta o botão para realizar a pesquisa,<br> O app Firefox mostra os resultados da pesquisa,<br> O Usuário entra em um dos links,<br> A página se encontra em um idioma desconhecido,<br> O Usuário abre o menu de opções,<br> O Usuário seleciona a opção "traduzir página",<br> O Usuário seleciona o idioma para o qual ele deseja que a página seja traduzida,<br> O app Firefox mostra a mesma página no idioma que foi selecionado a tradução |
| Restrição | O aplicativo deve estar atualizado para evitar erros,<br> O idioma estar elegível para ser traduzido |
| Exceção | Queda de internet,<br> O aparelho celular não funcionar |

**Autor**: [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024

</center>

### CEN04: Sincronizar e salvar dados do usuário

Na Tabela 6 está determinado o cenário CEN04, que descreve a

 sincronização e salvamento de dados do usuário no aplicativo Firefox.

<center>

**Tabela 6**: CEN04

| Elemento | Descrição |
| --- | --- |
| Título | Sincronizar e salvar dados do usuário |
| Objetivo | Sincronizar as configurações e dados salvos entre dois aparelhos diferentes que possuam o app Firefox |
| Contexto | Local: no escritório do trabalho,<br> Tempo: durante a tarde realizado em 5 minutos,<br> Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado em ambas as máquinas, possuir um dos aparelhos com câmera ou possuir um email válido |
| Recursos | Aparelho celular e/ou computador,<br> Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios | Usuário deseja sincronizar os dados do navegador do PC com o do celular,<br> Usuário pega o celular, <br> Usuário abre o aplicativo do Firefox,<br> Usuário abre o menu de opções,<br> Usuário clica na opção "sincronizar e salvar dados",<br> Usuário aperta o botão para sincronizar via QR Code,<br> Usuário abre o QR Code no PC, <br> Usuário aponta a câmera do celular para o QR Code no PC,<br> O app Firefox sincroniza os dados dos dispositivos |
| Restrição | O aplicativo deve estar atualizado para evitar erros |
| Exceção | Queda de internet,<br> O aparelho celular não funcionar,<br> O computador não funcionar |

**Autor**: [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024

</center>

### CEN05: Trocar de conta sincronizada

Na Tabela 7 está determinado o cenário CEN05, que descreve a troca de conta sincronizada no aplicativo Firefox.

<center>

**Tabela 7**: CEN05

| Elemento | Descrição |
| --- | --- |
| Título | Trocar de conta sincronizada |
| Objetivo | Ter ao mesmo tempo duas contas registradas no app do Firefox e conectadas que possam ser trocadas conforme necessário |
| Contexto | Local: na academia,<br> Tempo: durante a tarde realizado em 1 minuto,<br> Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos | Aparelho celular,<br> Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios | Usuário deseja entrar no perfil de trabalho para enviar um email,<br> Usuário pega o celular, <br> Usuário abre o aplicativo do Firefox,<br> Usuário vê que está no seu perfil pessoal,<br> Usuário deseja trocar para o perfil de trabalho,<br> Usuário abre o menu de opções,<br> O Usuário seleciona a opção "contas",<br> O app Firefox abre uma página com opções relacionadas à conta do usuário,<br> O Usuário seleciona a opção "trocar de conta",<br> O Usuário seleciona a conta que deseja entrar,<br> O app Firefox sincroniza com a conta escolhida,<br> O Usuário envia o email do trabalho |
| Restrição | O aplicativo deve estar atualizado para evitar erros |
| Exceção | Queda de internet,<br> O aparelho celular não funcionar |

**Autor**: [Leonardo Aguiar](https://github.com/Leonardo0o0), 2024

</center>

### CEN06: Bloquear anúncios de sites

Na Tabela 8 está determinado o cenário CEN06, que descreve o bloqueio de anúncios de sites no aplicativo Firefox.

<center>

**Tabela 8**: CEN06

| Elemento | Descrição |
|----------|-----------|
| Título | Bloquear anúncios de sites |
| Objetivo | Permitir que o usuário configure o navegador para bloquear anúncios em sites diversos, permitindo uma navegação mais rápida e limpa |
| Contexto | Local: em casa ou no trabalho<br>Tempo: durante o dia, realizado em 2 minutos<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos | Aparelho celular ou computador<br>Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios | <ul><li>Usuário está navegando em um site e é incomodado por muitos anúncios</li><li>Usuário decide bloquear os anúncios</li><li>Usuário pega o celular ou está no computador</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu de configurações</li><li>Usuário seleciona a opção "Bloqueio de anúncios"</li><li>Usuário ativa a opção para bloquear anúncios</li><li>Usuário personaliza as configurações de bloqueio, se desejar (ex.: bloquear todos os anúncios, permitir anúncios em sites específicos)</li><li>Usuário salva as configurações</li><li>O aplicativo Firefox aplica as configurações de bloqueio de anúncios</li></ul> |
| Restrição | O aplicativo deve estar atualizado para evitar erros<br>Usuário deve ter permissões administrativas no dispositivo |
| Exceção   | <ul><li>Queda de internet</li><li>O aparelho celular ou computador não funcionar</li><li>O aplicativo não aplicar corretamente as configurações de bloqueio</li><li>O site detectar e não permitir o bloqueio de anúncios</ul> |

**Autor**: [Guilherme Westphall](https://github.com/west7), 2024

</center>

### CEN07: Busca por texto em páginas

Na Tabela 9 está determinado o cenário CEN07, que descreve a busca por texto em páginas no aplicativo Firefox.

<center>

**Tabela 9**: CEN07

| Elemento | Descrição |
|----------|-----------|
| Título   | Busca por texto em páginas| 
| Objetivo | Permitir que o usuário encontre rapidamente palavras ou frases específicas em uma página web aberta no navegador |
| Contexto | Local: em casa ou no trabalho<br>Tempo: durante o dia, realizado em 1 minuto<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos | Aparelho celular ou computador<br>Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios |<ul><li>Usuário está lendo um artigo longo e precisa encontrar uma informação específica</li><li>Usuário decide usar a função de busca por texto</li><li>Usuário pega o celular ou está no computador</li><li>Usuário abre o aplicativo do Firefox e a página web desejada</li><li>Usuário abre o menu de opções do navegador</li><li>Usuário seleciona a opção "Buscar na página"</li><li>Usuário digita a palavra ou frase que deseja encontrar</li><li>O navegador destaca todas as ocorrências do texto buscado na página</li><li>Usuário navega pelas ocorrências encontradas até achar a informação desejada</li></ul> |
| Restrição | O aplicativo deve estar atualizado para evitar erros<br>A página deve estar totalmente carregada para uma busca precisa |
| Exceção | <ul><li>Queda de internet</li><li>O aparelho celular ou computador não funcionar</li><li>O aplicativo não encontrar o texto desejado devido a problemas de indexação</li></ul> | 

**Autor**: [Guilherme Westphall](https://github.com/west7), 2024

</center>

### CEN08: Realizar pesquisa por voz

Na Tabela 10 está determinado o cenário CEN08, que descreve a realização de uma pesquisa por voz no aplicativo Firefox.

<center>

**Tabela 10**: CEN08

| Elemento | Descrição |
| --- | --- |
| Título | Realizar pesquisa por voz |
| Objetivo | Conseguir realizar uma pesquisa no app através de ferramenta speech-to-text embutida no navegador |
| Contexto | Local: em casa,<br> Tempo: de manhã, realizado em 1 minuto,<br> Pré-condições: acesso à Internet, ter o aplicativo do Firefox instalado, ter um microfone funcional no aparelho |
| Recursos | Aparelho celular,<br> Acesso à internet |
| Atores | Usuário do aplicativo Firefox |
| Episódios | Usuário está cozinhando e precisa pesquisar uma receita,<br> Usuário pega o celular, <br> Usuário abre o aplicativo do Firefox,<br> Usuário está com a mão suja, então prefere usar a voz<br> Usuário abre a barra de pesquisa, <br> Usuário seleciona a opção de pesquisa por voz, <br> Usuário fala, no microfone, o que deseja pesquisar, <br> O app Firefox retorna uma página com resultados da busca, <br> Usuário consegue visualizar a informação que precisava,<br> Usuário volta a cozinhar<br> |
| Restrição | O aplicativo deve estar atualizado para evitar erros,<br>O microfone deve estar ativado<br> |
| Exceção | Queda de internet,<br> O aparelho celular não funcionar,<br> O aplicativo não entender a voz do usuário |

**Autor**: [Kallyne Macedo](https://github.com/kalipassos), 2024

</center>

### CEN09: Ler textos da página para deficientes visuais

Na Tabela 11 está determinado o cenário CEN09, que descreve leitura de uma página no ponto de vista de um deficiente visual.

<center>

**Tabela 11**: CEN09

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Ler textos da página para deficientes visuais      |
| Objetivo    | Ativar uma funcionalidade de acessibilidade para pessoas com deficiência visual |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 1 minuto<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos    | Aparelho celular<br>Acesso à internet                                                             |
| Atores      | Usuário do aplicativo Firefox portador de deficiência visual     |
| Episódios   | <ul><li>Usuário deseja ler uma página no aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário abre o menu</li><li>Usuário seleciona a opção "Configurações"</li><li>Usuário seleciona a opção "Acessibilidade"</li><li>Usuário desativa a opção de "Dimensionamento automático de fontes"</li><li>Usuário aumenta o tamanho da fonte até o tamanho desejado deslizando a barra "Tamanho das fontes"</li><li>Usuário liga a opção "Zoom em todos os sites"</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros |
| Exceção     | <ul><li>O aparelho celular não funcionar</li></ul> |

**Autor**: [Davi Pierre](https://github.com/DaviPierre), 2024

</center>

### CEN10: Ativar modo para daltônicos

Na Tabela 12 está determinado o cenário CEN10, que descreve a ativação do modo para daltônicos no aplicativo Firefox.

<center>

**Tabela 12**: CEN10

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Ativar modo para daltônicos                                               |
| Objetivo    | Ativar uma funcionalidade de acessibilidade para pessoas com daltonismo |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 1 minuto<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos    | Aparelho celular<br>Acesso à internet                                                             |
| Atores      | Usuário do aplicativo Firefox                                                                      |
| Episódios   | <ul><li>Usuário deseja ativar modo para daltônicos do aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu</li><li>Usuário seleciona a opção "Configurações"</li><li>Usuário seleciona a opção "Acessibilidade"</li><li>Usuário ativa a opção do modo</li><li>O aplicativo Firefox aplica o modo no aplicativo</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros |
| Exceção     | <ul><li>O aparelho celular não funcionar</li></ul> |

**Autor**: [Lucas Martins](https://github.com/martinsglucas), 2024

</center>

### CEN11: Ativar controle parental

Na Tabela 13 está determinado o cenário CEN11, que descreve a ativação do controle parental no aplicativo Firefox.

<center>

**Tabela 13**: CEN11


| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Ativar controle parental                                                                                  |
| Objetivo    | Permitir que os pais ou responsáveis configurem restrições no navegador para proteger os menores de conteúdo inapropriado |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 5 minutos<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado, ter permissões administrativas no dispositivo |
| Recursos    | Aparelho celular<br>Acesso à internet                                                              |
| Atores      | Usuário do aplicativo Firefox (pais ou responsáveis)                                               |
| Episódios   | <ul><li>Usuário deseja configurar controles parentais no aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu de configurações</li><li>Usuário seleciona a opção "Controle parental"</li><li>Usuário ativa a opção de controle parental</li><li>Usuário define um código de acesso ou senha para modificar as configurações de controle parental</li><li>Usuário configura as restrições desejadas (ex.: bloquear sites específicos, definir horários de uso, restringir conteúdo adulto)</li><li>Usuário salva as configurações</li><li>O aplicativo Firefox aplica as restrições configuradas</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros<br>O dispositivo deve ter suporte para controles parentais<br>Usuário deve ter permissões administrativas no dispositivo |
| Exceção     | <ul><li>Queda de internet</li><li>O aparelho celular não funcionar</li><li>O usuário não ter permissões administrativas no dispositivo</li></ul>                        |

**Autor**: [Kauan Eiras](https://github.com/kauaneiras), 2024

</center>

### CEN12: Alterar fonte do navegador em tipo e tamanho

Na Tabela 14 está determinado o cenário CEN12, que descreve a alteração da fonte do navegador em tipo e tamanho no aplicativo Firefox.

<center>

**Tabela 14**: CEN12

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Alterar fonte do navegador em tipo e tamanho                                                       |
| Objetivo    | Permitir que o usuário altere o tipo e o tamanho da fonte utilizada no navegador Firefox para melhorar a legibilidade e a personalização da interface |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 3 minutos<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos    | Aparelho celular<br>Acesso à internet                                                              |
| Atores      | Usuário do aplicativo Firefox                                                                      |
| Episódios   | <ul><li>Usuário deseja alterar o tipo e o tamanho da fonte no aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu de configurações</li><li>Usuário seleciona a opção "Aparência"</li><li>Usuário escolhe a sub-opção "Fonte"</li><li>Usuário seleciona o tipo de fonte desejado a partir de uma lista</li><li>Usuário ajusta o tamanho da fonte usando um controle deslizante ou opções de tamanho pré-definidas</li><li>Usuário visualiza uma prévia das alterações</li><li>Usuário confirma e salva as configurações</li><li>O aplicativo Firefox aplica as alterações de fonte na interface</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros<br>O tipo de fonte deve estar disponível no aplicativo |
| Exceção     | <ul><li>Queda de internet</li><li>O aparelho celular não funcionar</li><li>O tipo de fonte desejado não estar disponível</li></ul>                        |

**Autor**: [Kauan Eiras](https://github.com/kauaneiras), 2024

</center>

### CEN13: Proteger dados do usuário

Na Tabela 15 está determinado o cenário CEN13, que descreve a proteção dos dados do usuário no aplicativo Firefox.

<center>

**Tabela 15**: CEN13

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Proteger dados do usuário                                                                      |
| Objetivo    | Garantir a proteção das contas, senhas, cartões e informações pessoais do usuário contra acessos não autorizados e violações de privacidade |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 5 minutos<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado, ter permissões administrativas no dispositivo |
| Recursos    | Aparelho celular<br>Acesso à internet                                                              |
| Atores      | Usuário do aplicativo Firefox                                                                      |
| Episódios   | <ul><li>Usuário deseja configurar as opções de proteger dados no aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu de configurações</li><li>Usuário seleciona a opção "Proteger Dados"</li><li>Usuário revisa e ajusta as configurações de segurança, como ativar a proteção de contas, gerenciar senhas salvas, e ativar a verificação em duas etapas</li><li>Usuário define uma senha mestra ou utiliza autenticação biométrica para proteger o acesso às configurações de segurança</li><li>Usuário configura alertas de segurança para notificações de tentativas de acesso não autorizadas</li><li>Usuário salva as configurações</li><li>O aplicativo Firefox aplica as configurações de segurança e protege as contas, senhas, cartões e informações pessoais do usuário</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros<br>O dispositivo deve suportar autenticação biométrica (se utilizada) |
| Exceção     | <ul><li>Queda de internet</li><li>O aparelho celular não funcionar</li><li>Falta de suporte para autenticação biométrica no dispositivo</li></ul> |

**Autor**: [Kauan Eiras](https://github.com/kauaneiras), 2024

</center>

### CEN14: Limpar histórico de navegação, senhas salvas e cache

Na Tabela 16 está determinado o cenário CEN14, que descreve a limpeza do histórico de navegação, senhas salvas e cache no aplicativo Firefox.

<center>

**Tabela 16**: CEN14

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Limpar histórico de navegação, senhas salvas e cache                                               |
| Objetivo    | Apagar as informações de sites acessados, de senhas e liberar memória |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 1 minuto<br>Pré-condições: acesso à internet, ter o aplicativo do Firefox instalado |
| Recursos    | Aparelho celular<br>Acesso à internet                                                              |
| Atores      | Usuário do aplicativo Firefox                                                                      |
| Episódios   | <ul><li>Usuário deseja limpar dados de navegação do aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu</li><li>Usuário seleciona a opção "Histórico"</li><li>Usuário tem acesso às páginas acessadas anteriormente</li><li>Usuário seleciona ícone da lixeira</li><li>Usuário decide entre apagar da última hora, hoje e ontem ou tudo</li><li>O aplicativo Firefox aplica a limpeza do histórico</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros |
| Exceção     | <ul><li>Queda de internet</li><li>O aparelho celular não funcionar</li></ul> |

**Autor**: [Lucas Martins](https://github.com/martinglucas), 2024

</center>

### CEN15: Escolher entre tema claro ou escuro


Na Tabela 17 está determinado o cenário CEN15, que descreve a escolha entre tema claro ou escuro no aplicativo Firefox.

<center>

**Tabela 17**: CEN15

| Elemento    | Descrição                                                                                          |
| --- | --- |
| Título      | Escolher entre tema claro ou escuro                                               |
| Objetivo    | Escolher entre as duas opções de visualização da interface gráfica do aplicativo |
| Contexto    | Local: em casa<br>Tempo: durante o dia, realizado em 1 minuto<br>Pré-condições: ter o aplicativo do Firefox instalado |
| Recursos    | Aparelho celular                                                             |
| Atores      | Usuário do aplicativo Firefox                                                                      |
| Episódios   | <ul><li>Usuário deseja entre tema claro e escuro do aplicativo Firefox</li><li>Usuário pega o celular</li><li>Usuário abre o aplicativo do Firefox</li><li>Usuário navega até o menu</li><li>Usuário seleciona a opção "Configurações"</li><li>Usuário seleciona a opção "Personalizar"</li><li>Usuário tem acesso à definição de tema do aplicativo</li><li>Usuário escolhe entre claro, escuro ou acompanhar tema do dispositivo</li><li>O aplicativo Firefox aplica o tema no aplicativo</li></ul> |
| Restrição   | O aplicativo deve estar atualizado para evitar erros |
| Exceção     | <ul><li>O aparelho celular não funcionar</li></ul> |

**Autor**: [Lucas Martins](https://github.com/martinsglucas), 2024

</center>

## Referências

1. LEITE, Júlio C. S. P.; et al. **Modelos de requisitos e cenários: uma abordagem centrada no usuário**. PUC-Rio. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 27 jun. 2024.
2. YOUNG, Ralph. **Requirements Engineering Handbook**. Norwood, US: Artech House Books, 2003.
3. CHEMUTURI, Murali. **Mastering Software Quality Assurance: Best Practices, Tools and Technique for Software Developers**. Ft. Lauderdale, US: J. Ross Publishing Inc., 2010.
4. BERENBACH, Brian; PAULISH, Daniel; KAZMEIER, Juergen; RUDORFER, Arnold. **Software & Systems Requirements Engineering: In Practice**. Disponível em: <http://livrodeengenhariaderequisitos.blogspot.com.br/>. Acesso em: 2017.
5. RETRAINING. Técnicas de Elicitação de Requisitos - Cenários. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios. Acesso em: 27 jun. 2024.

## Histórico de Versões 

| Versão |    Data    | Descrição                                                 |                      Autor                        |                     Revisor                     |
| :----: | :--------: | --------------------------------------------------------- | :-----------------------------------------------: | :---------------------------------------------: |
|  1.0   | 15/05/2024 | Introdução e Metodologia                                  | [Kauan Eiras](https://github.com/kauaneiras)      | [Kallyne Macedo](https://github.com/kalipassos) |
|  1.1   | 16/05/2024 | Correções e criação da tabela 3                           | [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Kallyne Macedo](https://github.com/kalipassos) |
|  1.2   | 18/05/2024 | Correções e criação das tabelas 5, 6 e 7                  | [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Kallyne Macedo](https://github.com/kalipassos) |
|  1.3   | 19/05/2024 | Correção dos cenários e criação das tabelas 4, 14, 15, 16 | [Kauan Eiras](https://github.com/kauaneiras)      | [Kallyne Macedo](https://github.com/kalipassos) |
|  1.4   | 19/05/2024 | Criação tabela - CEN08                                    | [Kallyne Macedo](https://github.com/kalipassos)   | [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.5   | 19/05/2024 | Criação dos cenários CEN06 e CEN07                        | [Guilherme Westphall](https://github.com/west7)   | [Kallyne Macedo](https://github.com/kalipassos) |
|  1.6   | 20/05/2024 | Criação dos cenários CEN10, CEN14 e CEN15                 | [Lucas Martins](https://github.com/martinsglucas) | [Kauan Eiras](https://github.com/kauaneiras)    |
|  1.7   | 20/05/2024 | Criação do cenário CN09                                   | [Davi Pierre](https://github.com/DaviPierre)      |  [Guilherme Westphall](https://github.com/west7)                                              |
|  1.8   | 20/05/2024 | Organização geral de numeração                            | [Davi Pierre](https://github.com/DaviPierre)      |  [Guilherme Westphall](https://github.com/west7)                                              |
|  1.9   | 02/06/2024 | Correção das fontes | [Lucas Martins](https://github.com/martinsglucas) | [Kallyne Macedo](https://github.com/kalipassos) |
|  2.0   | 27/06/2024 | Correção das fontes | [Kauan Eiras](https://github.com/kauaneiras) | [Kallyne Macedo](https://github.com/kalipassos) |
