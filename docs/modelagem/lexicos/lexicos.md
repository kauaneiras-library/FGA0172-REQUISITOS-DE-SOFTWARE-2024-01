# Léxicos

## Introdução

Na engenharia de requisitos, léxicos são documentos que contêm um conjunto de palavras e vocabulário específico relacionado ao domínio do sistema que está sendo desenvolvido. Eles servem como referência para garantir que todos os membros do time tenham uma compreensão comum e consistente dos termos utilizados no projeto, além de ajudarem a definir a linguagem utilizada para a definição dos requisitos do software (ZOWGHI; COULIN, 2003).

## Metodologia

Neste artefato, iremos identificar os léxicos referentes ao navegador Firefox. A metodologia para a identificação dos léxicos envolve a coleta dos termos utilizados no domínio do sistema, seguida da definição clara e concisa de cada termo. Esta prática é fundamental para assegurar que todos os participantes do projeto compartilhem uma compreensão comum dos termos usados (ZOWGHI; COULIN, 2003).

Os léxicos serão baseados nos [requisitos elicitados na entrega 2](../../elicitacao/tecnicas/requisitos_elicitados.md) e na utilização do aplicativo. A seguir, na Tabela 1, temos um modelo de como será feita a definição dos léxicos, seguindo um template estruturado que inclui os elementos: termo, tipo, noção, impacto e autor.

**Tabela 1: Template para os léxicos**

| Termo | Tipo | Noção | Impacto | Autor |
|-------|------|-------|---------|-------|
| Nome associado ao léxico | Objeto/Verbo/Estado | Significado do símbolo, com descrição quase que de "dicionário" | Descrição do efeito/uso/decorrência do símbolo na aplicação | Indivíduo que realizou a descrição |

<center>

**Tabela 1**: Template para os léxicos

| Termo                    | Tipo                | Noção                                                           | Impacto                                                     | Autor                              |
| ------------------------ | ------------------- | --------------------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------- |
| Nome associado ao léxico | Objeto/Verbo/Estado | Significado do símbolo, com descrição quase que de "dicionário" | Descrição do efeito/uso/decorrência do símbolo na aplicação | Indivíduo que realizou a descrição |

**Fonte**: SERRANO, 2019.

</center>

Existem 3 tipos de léxicos que são os seguintes: Objeto, verbo e estado. Na tabela 2 estão listadas as regras por tipo de como devem ser definidos os léxicos.

<center>

**Tabela 2**: Regras por tipo

| Tipo   | Noção                                                              | Impacto                                                                                                   |
| ------ | ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| Objeto | Definir o objeto e listar outros objetos com os quais se relaciona | Ações que podem ser aplicadas ao objeto                                                                   |
| Verbo  | Quem realiza, quando acontece e quais procedimentos são envolvidos | Quais são os reflexos da ação no ambiente (outras ações que podem/devem ocorrer) e os estados decorrentes |
| Estado | Significado e quais ações levaram até esse estado                  | Identificar outros estados e ações que devem ocorrer a partir deste                                       |

**Fonte**: SERRANO, 2019

</center>

## Objetos

Os léxicos do tipo objeto são uma abordagem na engenharia de requisitos que se concentra na identificação e descrição detalhada dos objetos relevantes dentro do domínio do problema ou do sistema em desenvolvimento. Nesse contexto, um "objeto" pode se referir a qualquer entidade, conceito ou componente significativo no domínio do sistema. Na tabela 3, a seguir, é possível encontrar os léxicos deste tipo.


<center>

**Tabela 3**:  Léxicos do tipo Objeto

| Termo | Tipo   | Noção                                                                                                                                                                                              | Impacto                                                                                                                                                                                 | Autor                                           |
| ----- | ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| <a id="abas">Abas</a> | Objeto | <a href="#abas">Abas</a> são funcionalidades de <a href="#navegador">navegadores</a> que permitem abrir e gerenciar múltiplas <a href="#pw">páginas web</a> dentro de uma única janela. | O uso de <a href="#abas">abas</a> aumenta a produtividade e facilita a navegação entre diferentes <a href="#site">sites</a> sem a necessidade de abrir várias janelas do <a href="#navegador">navegador</a>. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="anuncios">Anúncios</a> | Objeto | <a href="#anuncios">Anúncios</a> são conteúdos promocionais exibidos em <a href="#pw">páginas web</a> com o objetivo de divulgar produtos, serviços ou marcas. | Os <a href="#anuncios">anúncios</a> são uma fonte de receita para muitos <a href="#site">sites</a> e podem ser personalizados com base no comportamento e nas preferências do <a href="#usuario">usuário</a>, mas também podem ser intrusivos e afetar a experiência de navegação. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="bloqueadordeanuncios">Bloqueador de anúncios</a> | Objeto | Um <a href="#bloqueadordeanuncios">bloqueador de anúncios</a> é uma ferramenta que impede que anúncios online sejam exibidos nas <a href="#pw">páginas web</a> durante a navegação. | O <a href="#bloqueadordeanuncios">bloqueador de anúncios</a> melhora a experiência do <a href="#usuario">usuário</a> ao reduzir distrações e aumentar a velocidade de carregamento das <a href="#pw">páginas</a>. No entanto, pode impactar as receitas de sites que dependem de publicidade. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="cache">Cache</a> | Objeto | O <a href="#cache">cache</a> é uma área de armazenamento temporário que guarda cópias de <a href="#pw">páginas web</a>, imagens e outros recursos para acelerar o carregamento futuro dessas páginas. | O uso do <a href="#cache">cache</a> melhora a eficiência do <a href="#navegador">navegador</a>, reduzindo o tempo de carregamento das <a href="#pw">páginas web</a> e economizando largura de banda. No entanto, pode exigir limpeza periódica para liberar espaço e evitar problemas de exibição. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="cookies">Cookies</a> | Objeto | <a href="#cookies">Cookies</a> são pequenos arquivos de dados armazenados no dispositivo do <a href="#usuario">usuário</a> pelo <a href="#site">site</a> que está sendo visitado, usados para lembrar informações sobre o <a href="#usuario">usuário</a> e suas preferências. | <a href="#cookies">Cookies</a> são utilizados para melhorar a experiência do <a href="#usuario">usuário</a>, armazenando preferências e dados de sessão. No entanto, também podem levantar questões de <a href="#privacidade">privacidade</a> quando usados para rastreamento. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="download">Download</a> | Objeto | <a href="#download">Download</a> é o processo de transferir dados de um <a href="#servidor">servidor</a> para o dispositivo do <a href="#usuario">usuário</a>. | A capacidade de realizar <a href="#download">downloads</a> permite que os <a href="#usuario">usuários</a> obtenham arquivos, programas e mídias, aumentando a funcionalidade e utilidade do <a href="#navegador">navegador</a>. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="extensao">Extensão</a>  | Objeto | Uma <a href="#extensao">extensão</a> é um complemento que pode ser instalado em um <a href="#navegador">navegador</a> para adicionar funcionalidades extras ou modificar o comportamento padrão do navegador. | As <a href="#extensao">extensões</a> permitem personalizar e expandir as capacidades do <a href="#navegador">navegador</a>, oferecendo recursos como bloqueio de anúncios, gerenciadores de senhas, tradutores, entre outros. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="favoritos">Favoritos</a> | Objeto | <a href="#favoritos">Favoritos</a>, também conhecidos como bookmarks, são links salvos pelos <a href="#usuario">usuários</a> para facilitar o acesso a <a href="#pw">páginas web</a> específicas no futuro. | Os <a href="#favoritos">favoritos</a> permitem que os <a href="#usuario">usuários</a> guardem e organizem links de <a href="#pw">páginas web</a> importantes, melhorando a eficiência da navegação. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="historico">Histórico</a> | Objeto | O <a href="#historico">histórico</a> de navegação é um registro das <a href="#pw">páginas web</a> que um <a href="#usuario">usuário</a> visitou em um <a href="#navegador">navegador</a>. | O <a href="#historico">histórico</a> permite que os <a href="#usuario">usuários</a> revisitem <a href="#pw">páginas</a> previamente acessadas, facilitando a recuperação de informações. Contudo, pode levantar preocupações de <a href="#privacidade">privacidade</a> se acessado por terceiros. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="internauta">Internauta</a>| Objeto  | Um <a href="#internauta">internauta</a> é um <a href="#usuario">usuário</a> da <a href="#internet">inetrnet</a> que <a href="#navegar">navega</a> por <a href="#pw">páginas da web</a>, participa de redes sociais, consome conteúdo digital, envia e-mails, e realiza atividades <a href="#online">online</a>. Esse termo engloba qualquer pessoa que utiliza a <a href="#internet">internet</a>, seja para lazer, trabalho, estudo ou comunicação. Os <a href="#internauta">inetrnautas</a> interagem com diversas plataformas e serviços <a href="#online">online</a>, contribuindo para a vastidão e dinamismo do mundo digital. | Os <a href="#internauta">inetrnautas</a> impactam significativamente os <a href="#site">sites</a> da <a href="#internet">internet</a>. Eles geram <a href="#trafego">tráfego</a>, influenciam algoritmos de <a href="#busca">busca</a>, contribuem com feedback e conteúdo, e determinam tendências. Suas interações e preferências moldam a relevância e o sucesso dos <a href="#site">sites</a>. Além disso, seus dados de navegação são analisados para melhorar a experiência do <a href="#usuario">usuário</a> e direcionar publicidade, impulsionando a economia digital. | [Davi Pierre](https://github.com/DaviPierre) |
|<a id="internet">Internet</a>| Objeto | A <a href="#internet">internet</a> é uma rede global de computadores que permite a comunicação e o compartilhamento de informações em escala mundial, transformando a sociedade e promovendo a conectividade global. | A <a href="#internet">internet</a> transformou <a href="#site">sites</a> em ferramentas essenciais para comunicação, comércio e interação. Ela amplia o alcance, oferece visibilidade global, facilita o acesso a informações e serviços, e permite interações em tempo real. | [Davi Pierre](https://github.com/DaviPierre) |
| <a id="link">Link</a> | Objeto | Um <a href="#link">link</a> é um elemento presente em <a href="#pw">página web</a> que permite aos <a href="#usuario">usuários</a> navegar entre diferentes recursos na <a href="#internet">internet</a>, como outras <a href="#pw">páginas web</a>, documentos, imagens, vídeos, entre outros. Ele é representado por texto, imagem ou outro elemento visual clicável que, quando ativado, direciona o <a href="#usuario">usuário</a> para o destino associado. | <a href="#link">Links</a> podems ser <a href="#click">clicados</a> e são usados para otimizar os mecanismos de <a href="#busca">busca</a>, redirecionando os <a href="#usuario">usuários</a> para outros recursos. | [Guilherme Westphall](https://github.com/west7)|
|<a id="navegador">Navegador</a>| Objeto | Um <a href="#navegador">navegador</a> é um aplicativo usado para acessar e visualizar <a href="#pw">páginas web</a>. Ele interpreta o código HTML, CSS e JavaScript das <a href="#pw">páginas</a> para exibir conteúdo visualmente atraente aos <a href="#usuario">usuários</a>. Além disso, permite <a href="#navegar">navegar</a> entre diferentes <a href="#site">sites</a>, gerenciar favoritos e oferece recursos como abas e modo de navegação privada. | O <a href="#navegador">navegador</a> afeta a experiência do <a href="#usuario">usuário</a>, a acessibilidade e o deseminternepenho do <a href="#site">site</a>. Compatibilidade, segurança e recursos adicionais influenciam a usabilidade e a eficácia do <a href="#site">site</a>, podendo afetar o alcance e a satisfação dos <a href="#usuario">usuários</a>. | [Davi Pierre](https://github.com/DaviPierre) |
| <a id="pw">Página web</a> | Objeto |  Uma <a href="#pw">página web</a> é uma única página digital composta por conteúdo, como texto, imagens, vídeos e elementos interativos, que é acessível por meio de um <a href="#navegador">navegador</a> da web. Geralmente, uma <a href="#pw">página web</a> é identificada por um <a href="#url">URL</a> único e pode conter informações sobre um tópico específico, serviço, produto ou qualquer outro conteúdo relevante para os <a href="#usuario">usuários</a> da <a href="#internet">internet</a>. | Os <a href="#usuario">usuários</a> visualizam o conteúdo da página que pode ser texto, imagens, vídeos, entre outros e interagem com elementos da página.| [Guilherme Westphall](https://github.com/west7) |
| <a id="popups">Pop-ups</a> | Objeto | <a href="#popups">Pop-ups</a> são janelas ou elementos de interface que aparecem sobre a <a href="#pw">página web</a> principal, frequentemente usadas para exibir anúncios ou informações adicionais. | <a href="#popups">Pop-ups</a> podem ser intrusivos e prejudicar a experiência de navegação. Muitos <a href="#navegador">navegadores</a>, incluindo o Firefox, incluem bloqueadores de pop-ups para melhorar a usabilidade. | [Kauan  Eiras](https://github.com/kauaneiras) |
| <a id="privacidade">Privacidade</a> | Objeto | <a href="#privacidade">Privacidade</a> refere-se à capacidade de um indivíduo ou grupo de se proteger contra invasões à sua vida pessoal, especialmente na <a href="#internet">internet</a>. | A <a href="#privacidade">privacidade</a> é fundamental para proteger dados pessoais e evitar rastreamento não autorizado. <a href="#navegador">Navegadores</a> como o Firefox oferecem recursos para aumentar a privacidade, como bloqueio de rastreadores e navegação anônima. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="proxy">Proxy</a> | Objeto | Um <a href="#proxy">proxy</a> é um servidor intermediário que atua entre o <a href="#usuario">usuário</a> e a <a href="#internet">internet</a>, encaminhando solicitações e respostas. | O uso de um <a href="#proxy">proxy</a> pode melhorar a <a href="#seguranca">segurança</a> e a <a href="#privacidade">privacidade</a>, além de permitir o acesso a conteúdos restritos ou bloqueados geograficamente. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="seguranca">Segurança</a> | Objeto | <a href="#seguranca">Segurança</a> na web refere-se às medidas tomadas para proteger os <a href="#usuario">usuários</a>, dados e sistemas contra ameaças e ataques cibernéticos. | A <a href="#seguranca">segurança</a> no <a href="#navegador">navegador</a> é essencial para proteger informações sensíveis, evitar fraudes e garantir uma navegação segura. O Firefox implementa diversas proteções como detecção de sites maliciosos e proteção contra phishing. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="servidor">Servidor</a>| Objeto | Um <a href="#servidor">servidor</a> é um computador ou software que hospeda e disponibiliza <a href="#pw">páginas da web</a> para acesso via <a href="#internet">internet</a>. Ele recebe solicitações de clientes (<a href="#navegador">navegadores</a>) e envia as <a href="#pw">páginas</a> correspondentes, geralmente utilizando o protocolo HTTP. | Um <a href="#servidor">servidor</a> influencia diretamente a disponibilidade, desempenho e segurança de um <a href="#site">site</a>. Sua configuração, capacidade de lidar com tráfego e tempo de resposta afetam a experiência do <a href="#usuario">usuário</a>, a eficácia do <a href="#site">site</a> e sua visibilidade na <a href="#internet">internet</a>. | [Davi Pierre](https://github.com/DaviPierre) |                                                      
| <a id="site">Site</a>  | Objeto | Entidade virtual que representa uma coleção de <a href="#pw">páginas web</a>, geralmente acessíveis através de um <a href="#navegador">navegador web</a>. Cada site possui um <a href="#url">URL</a> único que serve com um endereço na <a href="#internet">internet</a>. | Os <a href="#usuario">usuários</a> podem <a href="#navegar">navegar</a> por um <a href="#site">site</a> através de <a href="#link">links</a> internos, botões e menus de navegação. Também podem <a href="#busca">pesquisar</a> por informações relevantes dentro do <a href="#site">site</a>. | [Guilherme Westphall](https://github.com/west7) |
| <a id="tema">Tema</a> | Objeto | Um <a href="#tema">tema</a> é um pacote de personalização que altera a aparência visual do <a href="#navegador">navegador</a>, incluindo cores, imagens de fundo e ícones. | <a href="#tema">Temas</a> permitem que os <a href="#usuario">usuários</a> personalizem a interface do <a href="#navegador">navegador</a> de acordo com suas preferências estéticas, melhorando a experiência de uso. | [Kauan Eiras](https://github.com/kauaneiras) |
| <a id="trafego">Tráfego</a> | Objeto | <a href="#trafego">Tráfego</a> é a quantidade de dados transmitidos entre um <a href="#servidor">servidor</a> e os <a href="#usuarios">usuários</a> que acessam um <a href="#site">site</a> ou aplicação online. É uma medida do volume de visitantes, <a href="#pw">páginas</a> visualizadas e interações, crucial para entender o desempenho e a popularidade de um <a href="#site">site</a>. | O <a href="#trafego">trafego</a> afeta a visibilidade, desempenho e rentabilidade de um <a href="#site">site</a>. Altos volumes podem sobrecarregar <a href="#servidores">servidores</a>, impactar a velocidade de carregamento e gerar custos adicionais. No entanto, <a href="#trafego">tráfego</a> qualificado pode impulsionar a popularidade, aumentar a receita e melhorar o ranking nos mecanismos de <a href="#busca">busca</a>. | [Davi Pierre](https://github.com/DaviPierre) |
| <a id="url">URL</a> | Objeto | Um <a href="#url">URL</a> (Uniform Resource Locator) é uma sequência de caracteres que especifica o endereço único de um recurso na <a href="#internet">internet</a>, como uma <a href="#pw">página web</a>, uma imagem, um arquivo de áudio, entre outros. Ele fornece a localização precisa do recurso na rede e é utilizado pelos <a href="navegador">navegadores</a> da web para acessar e exibir o conteúdo desejado. | Os <a href="#url">URLs</a> podem ser compartilhadas entre os <a href="#usuario">usuários</a> para acessar recursos específicos, podem ser digitados/colados/sugeridos na barra de pesquisa de um <a href="#navegador">navegador</a> e usados em <a href="#link">links</a>. | [Guilherme Westphall](https://github.com/west7) |
|<a id="usuario">Usuário</a>| Objeto  | Um usuário é qualquer pessoa que interage com o <a href="#site">site </a> para alcançar um objetivo específico, e sua experiência e feedback são fundamentais para o desenvolvimento e melhoria contínua desses sistemas e produtos. | Os  <a href="#usuario">usuários</a> fornecem feedback para melhorar a usabilidade, influenciando o desempenho e ajudando a identificar vulnerabilidades de segurança. Eles geram conteúdo, moldam a personalização e direcionam a evolução do  <a href="#site">site</a>. Além disso, suas interações influenciam estratégias de marketing, crescimento e monetização, orientando o desenvolvimento contínuo e a adaptação do  <a href="#site">site</a> ao mercado.| [Davi Pierre](https://github.com/DaviPierre) |


**Autores**: [Guilherme Westphall](https://github.com/west7), [Kauan Eiras](https://github.com/kauaneiras) e [Davi Pierre](https://github.com/DaviPierre)

</center>

## Verbo
Os léxicos do tipo verbo representam uma abordagem na engenharia de requisitos que se foca nas ações realizadas pelos usuários ou sistemas dentro do contexto de um problema ou sistema em desenvolvimento. Nesse contexto, um "verbo" refere-se a uma operação, atividade ou procedimento que pode ser executado para alcançar um determinado objetivo ou realizar uma tarefa específica. Estão listados na tabela 4 abaixo.

<center>

**Tabela 4**: Léxicos do tipo Verbo

| Termo | Tipo   | Noção                                                                                                                                                                                              | Impacto                                                                                                                                                                                 | Autor                                           |
| ----- | ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| <a id="atualizar">Atualizar</a> | Verbo | <a href="#atualizar">Atualizar</a> é a ação de recarregar uma <a href="#pw">página web</a> ou aplicação para exibir a versão mais recente do conteúdo ou aplicar novas configurações e correções. | Ao <a href="#atualizar">atualizar</a> páginas ou sistemas, o <a href="#usuario">usuário</a> garante acesso às informações mais recentes e corrige possíveis erros ou inconsistências, melhorando a experiência de navegação. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="baixar">Baixar</a> | Verbo | <a href="#baixar">Baixar</a> é a ação de transferir arquivos ou dados da <a href="#internet">internet</a> para o dispositivo local do <a href="#usuario">usuário</a>. | Ao <a href="#baixar">baixar</a> arquivos, os <a href="#usuario">usuários</a> podem acessar conteúdos offline, mas também correm o risco de baixar malware ou arquivos indesejados, exigindo medidas de segurança adequadas. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="bloquear">Bloquear</a> | Verbo | <a href="#bloquear">Bloquear</a> é a ação de impedir que certos conteúdos ou funcionalidades sejam exibidos ou executados no <a href="#navegador">navegador</a>, como pop-ups, scripts ou <a href="#anuncios">anúncios</a>. | <a href="#bloquear">Bloquear</a> conteúdos indesejados melhora a experiência do <a href="#usuario">usuário</a> ao reduzir distrações e possíveis ameaças à segurança. No entanto, pode também impedir a visualização de conteúdos desejados. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="busca">Buscar/Pesquisar</a>| Verbo | <a href="#buscar">Buscar/pesquisar</a> é o processo de procurar informações ou recursos específicos usando um mecanismo de busca. Os usuários inserem palavras-chave ou frases para encontrar conteúdo relevante em <a href="#pw">páginas da web</a>, ajudando a obter respostas, descobrir produtos, serviços ou se informar sobre determinados tópicos. | A <a id="busca">busca/pesquisa</a> direciona o <a id="trafego">trafego</a> qualificado para um <a id="site">site</a>, aumentando a visibilidade e a relevância. <a id="site">Sites</a> otimizados para mecanismos de busca (SEO) podem atrair mais <a id="usuarios">usuários</a>, melhorar a classificação nos resultados e aumentar a taxa de conversão. | [Davi Pierre](https://github.com/DaviPierre) |
| <a id="click">Clicar</a>| Verbo | <a href="#click">Clicar</a> é a ação de pressionar o botão do mouse ou tocar na tela de um dispositivo para selecionar ou interagir com um elemento, como um <a href="#link">link</a>, botão ou imagem, direcionando o <a href="#usuario">usuário</a> para outra <a href="#pw">página da web</a>, recurso ou ação específica. | <a href="#click">Clicar</a> em <a href="#link">links</a> ou botões direciona os <a href="#usuario">usuários</a> para diferentes áreas de um <a href="#site">site</a>, influenciando a <a href="#navegar">navegação</a>, a interação e a conversão. Um design intuitivo e call-to-actions eficazes podem aumentar o engajamento, a permanência no <a href="#site">site</a> e a taxa de conversão. | [Davi Pierre](https://github.com/DaviPierre) |
| <a id="configurar">Configurar</a> | Verbo | <a href="#configurar">Configurar</a> é a ação de ajustar as preferências e as opções do <a href="#navegador">navegador</a> ou de uma aplicação para personalizar a experiência do <a href="#usuario">usuário</a>. | <a href="#configurar">Configurar</a> o sistema permite que os <a href="#usuario">usuários</a> personalizem seu ambiente de navegação, melhorando a eficiência, a segurança e a satisfação geral com o <a href="#navegador">navegador</a>. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="limpar">Limpar Histórico</a> | Verbo | <a href="#limpar">Limpar histórico</a> é a ação de apagar o registro de navegação, incluindo sites visitados, buscas realizadas e cookies armazenados, para proteger a privacidade do <a href="#usuario">usuário</a>. | <a href="#limpar">Limpar histórico</a> ajuda a proteger a privacidade do <a href="#usuario">usuário</a>, removendo rastros de atividades online e liberando espaço no armazenamento do <a href="#navegador">navegador</a>. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="navegar">Navegar</a> | Verbo | Ação realizada pelos <a href="#usuario">usuários</a> através de, principalmente, <a href="#navegador">navegadores</a> com o objetivo de explorar e interagir com diferentes partes do sistema. Esta ação ocorre quando os <a href="#usuario">usuários</a> buscam informações específicas, <a href="#navegar">navegam</a> por menus, <a href="#click">clicam</a> em <a href="#link">links</a> ou executam outras operações de <a href="#busca">busca</a> e interação. | Ao <a id="navegar">navegar</a> na <a href="#internet">internet</a>, os  <a href="#usuario">usuários</a> são expostos à diversas informações que podem levá-los a encontrar a informação que desejam ou não, levando a uma nova <a href="#busca">pesquisa</a> caso não encontrem ou levando ao <a href="#encerramento">encerramento</a> da aplicação em caso positivo. | [Guilherme Westphall](https://github.com/west7) |
| <a id="personalizar">Personalizar</a> | Verbo | <a href="#personalizar">Personalizar</a> é a ação de ajustar as configurações de aparência, funcionalidades e comportamento do <a href="#navegador">navegador</a> para atender às preferências individuais do <a href="#usuario">usuário</a>. | A capacidade de <a href="#personalizar">personalizar</a> o <a href="#navegador">navegador</a> permite que os <a href="#usuario">usuários</a> melhorem sua experiência de navegação, tornando-a mais intuitiva, eficiente e agradável. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="proteger">Proteger</a> | Verbo | <a href="#proteger">Proteger</a> é a ação de implementar medidas de segurança para salvaguardar dados pessoais, históricos de navegação e outras informações sensíveis contra acesso não autorizado ou ataques. | Ao <a href="#proteger">proteger</a> seus dados, os <a href="#usuario">usuários</a> garantem a privacidade e a integridade de suas informações, prevenindo roubo de identidade, fraudes e outras ameaças cibernéticas. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="salvar">Salvar</a> | Verbo | <a href="#salvar">Salvar</a> é a ação de armazenar informações ou dados de forma permanente ou temporária para uso futuro, como favoritos, histórico de navegação, senhas ou configurações de <a href="#navegador">navegador</a>. | Ao <a href="#salvar">salvar</a> dados, o <a href="#usuario">usuário</a> pode acessar rapidamente informações importantes e personalizar sua experiência de navegação. A segurança dos dados salvos é crucial para proteger a privacidade. | [Kauan Eiras](https://github.com/kauaneiras) | |
| <a id="sincronizar">Sincronizar</a> | Verbo | <a href="#sincronizar">Sincronizar</a> é o processo de manter os dados do <a href="#usuario">usuário</a> atualizados e consistentes em múltiplos dispositivos, como favoritos, histórico, senhas e abas abertas. | A capacidade de <a href="#sincronizar">sincronizar</a> dados oferece uma experiência de navegação contínua e conveniente, permitindo que os <a href="#usuario">usuários</a> acessem suas informações em qualquer dispositivo. | [Kauan Eiras](https://github.com/kauaneiras) |

**Autores**: [Guilherme Westphall](https://github.com/west7), [Kauan Eiras](https://github.com/kauaneiras) e [Davi Pierre](https://github.com/DaviPierre)

</center>

## Estado

Os léxicos do tipo Estado representam diferentes estados que um sistema pode assumir ao longo do tempo ou em resposta a determinadas condições ou eventos. Nesse contexto, um "estado" refere-se a uma condição ou situação específica em que o sistema se encontra em um determinado momento, refletindo diferentes configurações, modos de operação ou contextos de uso. Podem ser encontrados na tabela 5.

<center>

**Tabela 5**: Léxicos do tipo Estado

| Termo | Tipo   | Noção                                                                                                                                                                                              | Impacto                                                                                                                                                                                 | Autor                                           |
| ----- | ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
|<a id="carregando">Carregando</a>| Estado | O estado de <a href="#carregando">carregando</a> ocorre quando o Firefox está carregando conteúdo, como <a href="#pw">páginas web</a>, imagens ou outros recursos. | Enquanto está <a href="#carregando">carregando</a>, a experiência do <a href="#usuario">usuário</a> pode ser afetada pela velocidade da conexão e pelo desempenho do servidor. Otimizações são necessárias para minimizar o tempo de carregamento. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="conectado">Conectado</a>| Estado | O estado <a href="#conectado">conectado</a> indica que o Firefox está ativamente ligado à <a href="#internet">internet</a> e pode acessar e carregar recursos online. | Quando <a href="#conectado">conectado</a>, o <a href="#navegador">navegador</a> permite acesso completo a todos os recursos online, facilitando a navegação e a interação do <a href="#usuario">usuário</a> com a web. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="erro">Erro</a>| Estado | O estado de <a href="#erro">erro</a> ocorre quando o Firefox encontra um problema que impede o funcionamento normal do <a href="#navegador">navegador</a> ou de <a href="#pw">páginas web</a>. | Um <a href="#erro">erro</a> pode comprometer a experiência do <a href="#usuario">usuário</a>, necessitando de soluções rápidas e eficazes para restaurar a funcionalidade completa do sistema. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="privado">Modo de navegação privada</a>| Estado | O <a href="#privado">modo de navegação privada</a> permite que o <a href="#usuario">usuário</a> navegue na <a href="#internet">internet</a> sem armazenar histórico, cookies ou outros dados de navegação. | O <a href="#privado">modo de navegação privada</a> é útil para proteger a <a href="#privacidade">privacidade</a> do <a href="#usuario">usuário</a>, evitando que dados de navegação sejam salvos e rastreados. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="offline">Offline</a>| Estado | O estado <a href="#offline">offline</a> indica que o Firefox não está conectado à <a href="#internet">internet</a>. | Em modo <a href="#offline">offline</a>, o <a href="#navegador">navegador</a> pode acessar apenas conteúdo previamente armazenado em cache. Esse estado pode ser crítico para a continuidade do trabalho do <a href="#usuario">usuário</a> sem conexão. | [Kauan Eiras](https://github.com/kauaneiras) |
|<a id="online">Online</a>| Estado  | Estar <a href="#online">online</a> significa que o <a href="#usuario">usuário</a> está conectado à <a href="#internet">internet</a> e ativo em uma plataforma digital. Este estado permite a interação em tempo real com conteúdos, serviços e outros <a href="#usuario">usuários</a>. | O estado <a href="#online">online</a> é essencial para atividades como <a href="#navegar">navegação</a>, envio de mensagens instantâneas, participação em redes sociais, compras <a href="#online">online</a> e uso de aplicativos e serviços baseados na web. | [Davi Pierre](https://github.com/DaviPierre) |


**Autores**: [Guilherme Westphall](https://github.com/west7), [Kauan Eiras](https://github.com/kauaneiras) e [Davi Pierre](https://github.com/DaviPierre)


</center>

## Referências

1. **SERRANO, Milene.** Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf). Acesso em: 09/05/2024.
2. **Zowghi, D.; Coulin, C.** - Requirements Elicitation: A Survey of Techniques, Aproaches and Tools. Acesso em: 01/07/2024.

## Histórico de versões

| Versão | Data       | Descrição         | Autor                                           | Revisor |
| ------ | ---------- | ----------------- | ----------------------------------------------- | ------- |
| 1.0    | 09/05/2024 | Criação da página | [Guilherme Westphall](https://github.com/west7) | [Davi Pierre](https://github.com/DaviPierre)      |
| 1.1 | 14/05/2024 | Adição Tabelas 4 e 5 | [Guilherme Westphall](https://github.com/west7) | [Kauan Eiras](https://github.com/kauaneiras) |
| 1.2 | 17/05/2024 | Adição de Itens nas Tabelas 3 e 4| [Davi Pierre](https://github.com/DaviPierre) | [Kauan Eiras](https://github.com/kauaneiras) |
| 1.3 | 17/05/2024 | Adição de Itens nas Tabelas 3, 4 e 5| [Kauan Eiras](https://github.com/kauaneiras) | [Lucas Martins](https://github.com/martinsglucas) |
| 1.4 | 05/06/2024 | Adição de Itens nas Tabelas 3 e 5| [Davi Pierre](https://github.com/DaviPierre) | [Kauan Eiras](https://github.com/kauaneiras) |
| 1.5 | 01/07/2024 | Correção da Introdução e Metodologia| [Davi Pierre](https://github.com/DaviPierre) | [Kauan Eiras](https://github.com/kauaneiras) |
| 1.6 | 07/07/2024 | Ordenação alfabética dos léxicos | [Guilherme Westphall](https://github.com/west7) | [Davi Pierre](https://github.com/DaviPierre) | 