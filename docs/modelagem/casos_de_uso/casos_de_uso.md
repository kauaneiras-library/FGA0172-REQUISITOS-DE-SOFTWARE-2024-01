# Casos de Uso

## Introdução

Casos de uso são ferramentas essenciais na engenharia de requisitos, pois descrevem interações entre um sistema e seus usuários, definindo os requisitos funcionais de forma clara. Eles ajudam a garantir uma compreensão comum dos objetivos do sistema entre todos os stakeholders (LARMAN, 2004). Além disso, melhoram a comunicação entre desenvolvedores e stakeholders, proporcionando uma descrição clara dos requisitos (COCKBURN, 2000). No contexto do Processo Unificado de Desenvolvimento de Software, casos de uso servem como base para todas as atividades de desenvolvimento, desde a análise de requisitos até o design e a implementação (JACOBSON et al., 1999). Um caso de uso representa uma possível utilização do sistema por um ator utilizando algum de seus serviços, narrando a interação entre o sistema e os atores envolvidos para atingir um ou mais objetivos. Ele cria um contrato entre os stakeholders de um sistema sobre seu comportamento, descrevendo o comportamento do sistema sob diversas condições enquanto responde a uma requisição de um ator primário, que pode ser uma pessoa, dispositivo físico, mecanismo ou subsistema (RETRAINING, 2024). Assim, casos de uso são fundamentais para garantir que o software desenvolvido atenda às expectativas e necessidades dos usuários finais.

## Metodologia

Na definição dos casos de uso, utilizaremos as personas definidas para entender melhor a atividade do usuário no navegador Firefox. O processo envolve identificar os atores, que neste caso será apenas o usuário (ator principal), o limite do sistema e a definição dos casos de uso que indicam o fluxo de ações dentro do sistema. Usaremos a ferramenta [Miro](https://miro.com/pt/) para a construção do diagrama. A legenda para o diagrama está presente na tabela 1.

<div align="center">
    <font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda para o diagrama</p></font>
</div>

| Símbolo                                    | Nome        | Função                                                    |
| ------------------------------------------ | ----------- | --------------------------------------------------------- |
| <img src="https://github.com/Requisitos-de-Software/2024.1-Firefox/blob/main/docs/modelagem/casos_de_uso/assets/boneco.png?raw=true" />    | Ator        | Representam os indivíduos que interagem com o sistema     |
| <img src="https://github.com/Requisitos-de-Software/2024.1-Firefox/blob/main/docs/modelagem/casos_de_uso/assets/elipse.png?raw=true" width=130 />    | Caso de uso | Representa as possíveis ações realizadas no sistema       |
| <img src="https://github.com/Requisitos-de-Software/2024.1-Firefox/blob/main/docs/modelagem/casos_de_uso/assets/flecha.png?raw=true" />    | Relações    | Indicam o fluxo de ações e as relações entre casos de uso |
| <img src="https://github.com/Requisitos-de-Software/2024.1-Firefox/blob/main/docs/modelagem/casos_de_uso/assets/retangulo.png?raw=true"/> | Sistema     | Representa a aplicação                                    |



<div align="center"
    <font size="3"><p style="text-align: center"><b>Autor: </b><a href="https://github.com/west7">Guilherme Westphall</a>, 2024</p></font>
</div>

## Diagrama de casos de uso

A figura 1 apresenta o diagrama de casos de uso confeccionado com base no App Firefox.

<div align="center">
    <font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama de casos de uso</p></font>
</div>

<center> <img src="https://github.com/Requisitos-de-Software/2024.1-Firefox/blob/main/docs/modelagem/casos_de_uso/assets/REQ%202024.1%20-%20G6%20-%20Frame%202.jpg?raw=true"/> </center>

<div align="center"
    <font size="3"><p style="text-align: center"><b>Autor: </b><a href="https://github.com/DaviPierre">Davi Pierre</a>, <a href="https://github.com/kalipassos">Kallyne Macedo</a>, 2024</p></font>
</div>

## Especificação de casos de uso

### Realizar pesquisa na Web 

Na tabela 2, abaixo, será disposta a especificação do caso de uso "Realizar pesquisa na web".


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Especificação - Realizar pesquisa na Web  </p></font>
</div>

|  | Realizar pesquisa na Web |
| -: | :- |
| **Descrição** | O internauta realiza uma pesquisa na web, o que envolve acessar a barra de pesquisa e depois acessar o site com resultados da pesquisa. |
| **Ator** | Internauta |
| **Frequência de Uso** | Alta |
| **Pré-condições** | Conexão à Internet, acesso ao navegador, acesso a um mecanismo de buscas (Google, Bing, DuckDuckGo, etc.) |
| **Fluxo principal** | - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa e navegação. Aciona caso de uso "Acessar barra de pesquisa". <br> - Internauta insere o que deseja pesquisar na Web e confirma. <br> - Internauta é redirecionado para a página com resultados da pesquisa. Aciona o caso de uso "Acessar página com resultados". <br> - Pesquisa realizada com sucesso. |
| **Fluxos alternativos** | <b> FA.1: Sugestões de pesquisa </b> <br> - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa e navegação. Aciona caso de uso "Acessar barra de pesquisa". <br> - O Internauta começa a digitar na barra de pesquisa. <br> - O Internauta recebe sugestões personalizadas baseadas em seu histórico. Aciona caso de uso "Receber sugestões personalizadas de pesquisa". <br> - Internauta seleciona uma sugestão e confirma. <br> - Internauta é redirecionado para a página com resultados da pesquisa. Aciona o caso de uso "Acessar página com resultados". <br> - Pesquisa realizada com sucesso. |
| **Fluxos de exceção** | FE.1: <b> Resultado não encontrado </b> <br> - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa e navegação. Aciona caso de uso "Acessar barra de pesquisa". <br> - Internauta insere o que deseja pesquisar na Web e confirma. <br> - Internauta não encontra resultados para sua pesquisa <br> - O Internauta pode tentar  repetir ou buscar com outros termos.  |
| **Pós-condições** |  O Internauta visualiza os resultados da pesquisa.  |
| **Data da Criação** | 16/05/2024 |
| **Rastreabilidade** | OBS01,  OBS12, BRS23, BRS15 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/kalipassos">Kallyne Macêdo</a>, 2024</p></font>
</div>

### Acessar histórico

Na tabela 3, abaixo, será disposta a especificação do caso de uso "Acessar histórico".


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Especificação - Acessar historico  </p></font>
</div>

|  | Acessar historico |
| -: | :- |
| **Descrição** | O Internauta acessa o historico, o que envolve acessar o menu lateral e selecionar a opção de histórico. |
| **Ator** | Internauta |
| **Frequência de Uso** | Média |
| **Pré-condições** | Conexão à Internet, possuir o aplicativo instalado em seu celular |
| **Fluxo principal** | - Internauta abre o app. <br> - Internauta seleciona o menu lateral. <br> - Internauta seleciona a opcao historico. Aciona caso de uso "Acessar historico de guias". <br> - Internauta é redirecionado para a página com o historico de guias. <br> - Acesso ao historico de guias realizado com sucesso. |
| **Fluxos alternativos** | <b> FA.1: Acesso ao historico de downloads </b> <br> - Internauta abre o app. <br> - Internauta seleciona o menu lateral. <br> - Internauta seleciona o botao de downloads. Aciona caso de uso "acessar historico de downloads" <br> - Internauta é redirecionado para a página com o historico de downloads. <br> - Acesso ao historico de downloads realizado com sucesso. <br> <b> FA.2: Limpar historico de guias </b> <br> - Internauta abre o app. <br> - Internauta seleciona o menu lateral. <br> - Internauta seleciona a opcao historico. Aciona caso de uso "Acessar historico de guias". <br> - Internauta é redirecionado para a página com o historico de guias. <br> - Internauta seleciona o botao de apagar historico. <br> - Internauta seleciona quanto apagar do historico. Acessa caso de uso "limpar historico". <br> - Internauta é redirecionado para a página com o historico de guias atualizado. <br> - Limpar historico de guias realizado com sucesso. <br> <b> FA.3: Limpar historico de downloads </b> <br> - Internauta abre o app. <br> - Internauta seleciona o menu lateral. <br> - Internauta seleciona o botao de downloads. Aciona caso de uso "acessar historico de downloads" <br> - Internauta é redirecionado para a página com o historico de downloads. <br> - Internauta seleciona o botao de apagar historico. <br> - Internauta seleciona quanto apagar do historico. Acessa caso de uso "limpar historico". <br> - Internauta é redirecionado para a página com o historico de downloads atualizado. <br> - Limpar historico de downloads realizado com sucesso. |
| **Fluxos de exceção** | - |
| **Pós-condições** |  O Internauta visualiza o historico.  |
| **Data da Criação** | 20/05/2024 |
| **Rastreabilidade** | OBS05, BRS24, OBS06, OBS22 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/Leonardo0o0">Leonardo Aguiar</a>, 2024</p></font>
</div>

### Bloquear anúncios
Na tabela 4, abaixo, será disposta a especificação do caso de uso "Bloquear anúncios".

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Especificação - Bloquear anúncios  </p></font>
</div>

|  | Bloquear anúncios |
| -: | :- |
| **Descrição** | O Internauta bloqueia anúncios enquanto navega, o que envolve acessar as configurações de bloqueio de anúncios no navegador. |
| **Ator** | Internauta |
| **Frequência de Uso** | Média |
| **Pré-condições** | Conexão à Internet, acesso ao navegador com recurso de bloqueio de anúncios disponível. |
| **Fluxo principal** | - Internauta abre o app. <br> - Internauta acessa o menu de configurações. <br> - Internauta seleciona a opção de bloqueio de anúncios. <br> - Internauta ativa a funcionalidade de bloqueio de anúncios. <br> - Bloqueio de anúncios realizado com sucesso. |
| **Fluxos alternativos** | <b> FA.1: Personalizar bloqueio de anúncios </b> <br> - Internauta abre o app. <br> - Internauta acessa o menu de configurações. <br> - Internauta seleciona a opção de bloqueio de anúncios. <br> - Internauta seleciona configurações avançadas de bloqueio de anúncios. <br> - Internauta personaliza os tipos de anúncios que deseja bloquear. <br> - Personalização de bloqueio de anúncios realizada com sucesso. |
| **Fluxos de exceção** | <b>FE.1: Erro ao ativar o bloqueio de anúncios </b> <br> - Internauta abre o app. <br> - Internauta acessa o menu de configurações. <br> - Internauta seleciona a opção de bloqueio de anúncios. <br> - Internauta tenta ativar a funcionalidade de bloqueio de anúncios, mas ocorre um erro. <br> - Internauta recebe uma mensagem de erro e pode tentar novamente mais tarde. <br><b>FE.2: O site identifica o bloqueador e não permite o uso</b> <br> - Internauta abre o app. <br> - Internauta acessa o menu de configurações. <br> - Internauta seleciona a opção de bloqueio de anúncios. <br> - Internauta ativa a funcionalidade de bloqueio de anúncios. <br> - Internauta acessa o site "x". <br> - O site "x" identifica o uso do bloqueador de anúncios. <br> - O site "x" barra o uso do bloqueador, não permitindo que o Internauta prossiga. <br> - Internauta precissa desligar o bloqueador.|
| **Pós-condições** | O Internauta navega na web sem anúncios indesejados. |
| **Data da Criação** | 20/05/2024 |
| **Rastreabilidade** | OBS27, BRS08, QST02 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/west7">Guilherme Westphall</a>, 2024</p></font>
</div>

### Mudar o Idioma
Na tabela 5, abaixo, será disposta a especificação do caso de uso "Mudar o Idioma".

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Especificação - Mudar o Idioma  </p></font>
</div>

|  | Mudar o Idioma |
| -: | :- |
| **Descrição** | O Internauta altera o idioma da interface do navegador, o que pode incluir a tradução de páginas web automaticamente. |
| **Ator** | Internauta |
| **Frequência de Uso** | Baixa |
| **Pré-condições** | Conexão à Internet, acesso ao navegador Firefox instalado no dispositivo do Internauta, disponibilidade de idiomas suportados pelo navegador. |
| **Fluxo principal** | - Internauta abre o app. <br> - Internauta acessa o menu de configurações. <br> - Internauta seleciona a opção de configuração de idioma. <br> - Internauta escolhe o idioma desejado da lista de idiomas suportados. <br> - Internauta confirma a mudança de idioma. <br> - Mudança de idioma realizada com sucesso. |
| **Fluxos alternativos** | <b> FA.1: Traduzir páginas automaticamente </b> <br> - Internauta habilita a tradução automática de páginas. <br> - Internauta seleciona a opção para traduzir páginas automaticamente ao acessar páginas em idiomas diferentes do configurado. <br> - O caso de uso "Traduzir páginas" é acionado. <br> - Páginas em idiomas diferentes são automaticamente traduzidas para o idioma configurado. |
| **Fluxos de exceção** | <b>FE.1: Erro na mudança de idioma</b> <br> - Internauta tenta confirmar a mudança de idioma. <br> - O sistema exibe uma mensagem de erro informando que a mudança de idioma falhou. <br> - Internauta fecha o aplicativo, abre o aplicativo novamente e tenta selecionar novamente o idioma desejado ou entra em contato com a empresa para informar o problema.|
| **Pós-condições** | O navegador exibe a interface no novo idioma escolhido pelo Internauta. |
| **Data da Criação** | 20/05/2024 |
| **Rastreabilidade** | OBS14 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/kauaneiras">Kauan Eiras</a>, 2024</p></font>
</div>

### Acessar site
Na tabela 6, abaixo, será disposta a especificação do caso de uso "Acessar site".

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Especificação - Acessar site  </p></font>
</div>

|  | Acessar site |
| -: | :- |
| **Descrição** | O Internauta encontra e acessa um site específico na internet |
| **Ator** | Internauta |
| **Frequência de Uso** | Média |
| **Pré-condições** | Conexão à Internet |
| **Fluxo principal** | - Internauta abre o app. <br> - Internauta acessa a barra de pesquisa. <br> - Internauta digita o nome do site a ser acessado. <br> - Internauta acesa o site. |
| **Fluxos alternativos** | <b> FA.1: Internauta deseja usar a ferramenta de pesquisa por voz </b> <br> - Internauta abre o app. <br> - Internauta acessa a barra de pesquisas. <br> - Internauta seleciona a ferramenta de pesquisa por voz. <br> - Internauta fala o nome do site que quer pesquisar. <br> - Internauta clica no link do site a ser acessado. <br> - Internauta acessa o site. <br> <b> FA.2: Internauta deseja usar a sugestão personalizada de pesquisa</b>  <br> - Internauta abre o app. <br> - Internauta acessa a barra de pesquisas. <br> - Internauta escreve algumas letras do site a ser acessado. <br> - Aplicativo mostra na tela sugestões personalizadas de pesquisa. <br> - Internauta clica na seleção personalizada de pesquisa adequada. <br> - Internauta acessa o site. <br> <b> FA.3: Internauta deseja usar um atalho de site favorito para acessar o site</b>  <br> - Internauta abre o app. <br> - Internauta clica no atalho do site favorito. <br> - Internauta acessa o site. <br> <b> FA.4: Internauta deseja acessar um site acessado recentemente</b>  <br> - Internauta abre o app. <br> - Internauta clica no atalho do site acessado recentimente. <br> - Internauta acessa o site. |
| **Fluxos de exceção** | <b>FE.1: Site fora do ar ou inexistente </b><br> - Internauta abre o app. <br> - Internauta acessa a barra de pesquisa. <br> - Internauta digita o nome do site a ser acessado. <br> - Site procurado pelo Internauta não existe ou está fora do ar. <br> - Internauta recebe a mensagem de error 404 <br> <b>FE.2: Aplicativo não consegue acessar a internet </b><br> - Internauta abre o app. <br> - Internauta acessa a barra de pesquisa. <br> - Internauta digita o nome do site a ser acessado. <br> - Aplicativo não tem acesso a internet. <br> - Internauta recebe a mensagem de erro "Sem internet|
| **Pós-condições** | O Internauta consegue acesar o site desejado. |
| **Data da Criação** | 20/05/2024 |
| **Rastreabilidade** | OBS01, BRS23, OBS12, BRS15, OBS29, OBS04, ENT05, BRS24 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/DaviPierre">Davi Pierre</a>, 2024</p></font>
</div>

### Acessar barra de pesquisa

Na tabela 7, abaixo, será disposta a especificação do caso de uso "Acessar barra de pesquisa".

<center>

<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Especificação - Acessar barra de pesquisa  </p></font>

|  | Acessar barra de pesquisa |
| -: | :- |
| *Descrição* | O Internauta acessa a barra de pesquisa, o que envolve digitar algo para pesquisar e confirmar. |
| *Ator* | Internauta |
| *Frequência de Uso* | Alta |
| *Pré-condições* | Conexão à Internet, acesso ao navegador |
| *Fluxo principal* | - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa. <br> - Internauta insere o que deseja pesquisar na Web e confirma. |
| *Fluxos alternativos* | <b> FA.1: Sugestões de pesquisa </b> <br> - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa. <br> - O Internauta começa a digitar na barra de pesquisa. <br> - O Internauta recebe sugestões personalizadas baseadas em seu histórico. Aciona caso de uso "Receber sugestões personalizadas de pesquisa". <br> - Internauta seleciona uma sugestão e confirma. <br> <b> FA.2: Realizar pesquisa por voz </b> <br> - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa. <br> - O Internauta clica no ícone de microfone. <br> - O Internauta pronuncia aquilo que ele deseja pesquisar. Aciona caso de uso "Realizar pesquisa por voz". |
| *Fluxos de exceção* | FE.1: <b> Barra de pesquisa com problema </b> <br> - Internauta abre o app. <br> - Internauta seleciona a barra de pesquisa.<br> - Internauta insere o que deseja pesquisar na Web, mas não consegue confirmar. <br> - O Internauta pode tentar repetir ou reiniciar o aplicativo.  |
| *Pós-condições* |  O Internauta confirma o que foi digitado para realizar a pesquisa.  |
| *Data da Criação* | 20/05/2024 |
| *Rastreabilidade* | OBS01, BRS23, OBS29 |

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/martinsglucas">Lucas Martins</a>, 2024</p></font>
</center>

## Referências

1. **Lucidchart.** Diagrama de caso de uso UML. Disponível em: <https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>. Acesso em: 16 de maio de 2024.
2. **Lucid Software Português.** Tutorial de Caso de Uso UML. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 16 de maio de 2024.
3. **LARMAN, C.** *Applying UML and Patterns: An Introduction to Object-Oriented Analysis and Design and Iterative Development*. 3. ed. New Jersey: Prentice Hall PTR, 2004.
4. **COCKBURN, A.** *Writing Effective Use Cases*. Boston: Addison-Wesley, 2000.
5. **JACOBSON, I.; BOOCH, G.; RUMBAUGH, J.** *The Unified Software Development Process*. Boston: Addison-Wesley, 1999.
6. **RETRAINING.** Técnicas de Elicitação de Requisitos - Casos de Uso. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-casos-de-uso. Acesso em: 27 jun. 2024.


## Histórico de versões

| Versão | Data       | Descrição         | Autor                                           | Revisor |
| ------ | ---------- | ----------------- | ----------------------------------------------- | ------- |
| 1.0    | 16/05/2024 | Criação da página | [Guilherme Westphall](https://github.com/west7) | [Kallyne Macedo](https://github.com/kalipassos)     |
| 1.1    | 18/05/2024 | Adição diagrama e caso de uso 1 | [Kallyne Macedo](https://github.com/kalipassos) |  [Davi Pierre](https://github.com/DaviPierre)    |
| 1.2    | 20/05/2024 | Caso de uso "Acessar historico" Tabela 3 | [Leonardo Aguiar](https://github.com/Leonardo0o0) |  [Kallyne Macedo](https://github.com/kalipassos)    |
| 1.3 | 20/05/2024 | Caso de uso "Bloquear anúncios" | [Guilherme Westphall](https://github.com/west7) | [Lucas Martins](https://github.com/martinsglucas)|
| 1.4 | 20/05/2024 | Caso de uso "Mudar o Idioma" | [Kauan Eiras](https://github.com/kauaneiras) | [Guilherme Westphall](https://github.com/west7)| 
| 1.5 | 20/05/2024 | Adiciona textos introdutórios | [Guilherme Westphall](https://github.com/west7) | [Kauan Eiras](https://github.com/kauaneiras)|
| 1.6 | 20/05/2024 | Adiciona casos de uso "Acessar site"| [Davi Pierre](https://github.com/DaviPierre)| [Kauan Eiras](https://github.com/kauaneiras) |
| 1.7 | 20/05/2024 | Adiciona caso de uso "Acessar barra de pesquisa" | [Lucas Martins](https://github.com/martinsglucas) | [Leonardo Aguiar](https://github.com/Leonardo0o0)| 
| 1.8 | 05/06/2024 | Atualização das legendas das tabelas e figuras /e atualizações dos textos | [Davi Pierre](https://github.com/DaviPierre) | [Kauan Eiras](https://github.com/kauaneiras)|
| 1.9 | 10/06/2024 | Atualização da tabela 1 e da imagem 1 e substituição de usuário por internauta nos textos de caso de uso| [Davi Pierre](https://github.com/DaviPierre) | [Kallyne Macedo](https://github.com/kalipassos) | 
| 2.0 | 27/06/2024 | Adições bibliográficas| [Kauan Eiras](https://github.com/kauaneiras) | [Kallyne Macedo](https://github.com/kalipassos) | 
