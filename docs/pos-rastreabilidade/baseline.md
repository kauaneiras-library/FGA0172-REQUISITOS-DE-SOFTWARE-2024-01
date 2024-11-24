# Baseline

## Introdução

Neste documento, vamos apresentar de forma detalhada os requisitos do projeto. Para isso, utilizaremos uma tabela que abrange todas as versões dos requisitos. Cada linha da tabela trará uma descrição completa, começando desde a criação inicial dos requisitos até o estágio atual do projeto. O objetivo é fornecer uma visão clara e abrangente de como os requisitos evoluíram ao longo do tempo, documentando todas as mudanças e atualizações realizadas em cada fase do desenvolvimento.

## Metodologia

A baseline de requisitos refere-se ao grupo de requisitos documentados no [Software Requirements Specification (SRS)](./assets/ref-1.png). Esses requisitos são desenvolvidos ao longo das diversas etapas do processo de requisitos, incluindo elicitação, modelagem, verificação e validação. Eles servem como fundamento para o design e a implementação do software.

<!-- **Fonte**: [Referência 1](./assets/ref-1.png)<br>-->

Para a construção da baseline, os requisitos foram dividos igualmente entre o grupo da seguinte maneira:

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

**Autor**: [Guilherme Westphall](https://github.com/west7)

</center>

## Baseline dos requisitos

Nesta seção está apresentada a baseline dos requisitos, conforme a Tabela 1 a seguir. Esta tabela registra os requisitos, incluindo suas diferentes versões, com a versão mais atual destacada em negrito.

<center>

**Tabela 2**: Baseline de requisitos

<table border='0.5'>
    <tr>
        <th>Requisito</th>
        <th>Versão</th>
        <th>Descrição</th>
        <th>Implementado</th>
        <th>Alta-prioridade</th>
    </tr>
    <tr>
        <td rowspan="2">R1</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve possuir uma barra de pesquisa</b></td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O sistema deve conter uma ferramenta de pesquisa rápida</td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td rowspan="1">R2</td>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais"><b>1.0</b></a></td>
        <td><b>O aplicativo deve ter opção de navegação anônima</b></td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="3">R3</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></b></td>
        <td><b>O aplicativo deve possuir opção de visualizar e agrupar guias</b></td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Deve ser possível agrupar várias guias</td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve possuir opção de visualizar todas as guias</td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="1">R4</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.0</a></b></td>
        <td><b>O aplicativo deve possuir opção de favoritar sites</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="2">R5</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve possuir histórico de navegação</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td> Deve possuir histórico de navegação </td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="2">R6</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve possuir histórico de downloads</b></td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.0</a></td>
        <td>Deve possuir histórico de downloads</td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td rowspan="2">R7</td>
        <td><b><a href="">1.1</a></b></td>
        <td><b>O aplicativo deve possibilitar a instalação de extensões de uso</b></td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td><a href="">1.0</a></td>
        <td>Deve ser possível instalar extensões de uso</td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    </tr>
    <tr>
        <td rowspan="4">R8</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao"><b>1.4</b></a></b></td>
        <td><b>O aplicativo deve possuir opção de sincronizar e salvar dados inseridos</b></td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#requisitos-elicitados">1.3</a></td>
        <td>Deve possuir opção de sincronizar dados e salvar</td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.1</a></td>
        <td>Deve ser possível sincronizar senhas com outros dispositivos</td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.0</a></td>
        <td>Deve sincronizar os dados</td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td rowspan="2">R9</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve permitir visualização dos sites em formato desktop</b></td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve ser possível visualizar em formato desktop	</td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="1">R10</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.0</a></b></td>
        <td><b>O aplicativo deve permitir a criação de atalhos na tela inicial do dispositivo</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="1">R11</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.0</a></b></td>
        <td><b>O aplicativo deve oferecer sugestões personalizadas de pesquisa</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="3">R12</td>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></td>
        <td><b>O aplicativo deve permitir a personalização da tela inicial do navegador</b></td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.1</a></td>
        <td>Deve ser possível personalizar a tela inicial do navegador</td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.0</a></td>
        <td>O sistema deve fornecer uma personalização diversa</td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td rowspan="2">R13</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve suportar a mudança de idioma do sistema</b></td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
    <td>1.0</td>
        <td>Deve ser possível mudar o idioma</td>
        <td>  Sim </td>
        <td>  Sim </td></tr>
    <tr>
        <td rowspan="3">R14</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></b></td>
        <td><b>O aplicativo deve permitir a alternação entre tema claro e escuro</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.1</a></td>
        <td>Deve ser possível mudar entre tema claro e escuro</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/questionario/#resultado">1.0</a></td>
        <td>Temas mais agradáveis</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="2">R15</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve possuir suporte para atalhos de gestos</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve possuir atalhos de gestos</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="1">R16</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.0</a></b></td>
        <td><b>O aplicativo deve possibilitar a troca de conta do usuário </b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="2">R17</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve permitir a alteração da senha da conta do usuário</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve ser possível alterar senha</td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="2">R18</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve permitir ao usuário limpar seu histórico de navegação</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.0</a></td>
        <td>Deve ser possível limpar histórico de navegação</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="2">R19</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve permitir ao usuário limpar seus dados inseridos e de navegação</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve ser possível limpar dados do usuário</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="2">R20</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve permitir a habilitação e bloqueio de notificações</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.0</a></td>
        <td>Deve ser possível habilitar e bloquear notificações	</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="3">R21</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></b></td>
        <td><b>O aplicativo deve permitir alterar a fonte de texto em tipo e tamanho</b></td>
        <td> Não </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Deve ser possível alterar fonte do navegador</td>
        <td> Não </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O aplicativo deve permitir alterar a fonte de texto em tipo e tamanho</td>
        <td> Não </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="1">R22</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.0</a></b></td>
        <td><b>O aplicativo deve incluir opção de bloquear anúncios</b></td>
        <td>Não</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="2">R23</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve incluir opção de busca interna na página</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O navegador deve incluir opção de busca na página</td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="2">R24</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve incluir opção de pesquisa por voz</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.0</a></td>
        <td>A barra de pesquisa deve incluir opção de pesquisa por voz</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="3">R25</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></b></td>
        <td><b>O aplicativo deve possuir opção de leitura da página em voz alta</b></td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
    <td>1.1</td>
        <td>O navegador deve possuir opção de leitura da paǵina para deficientes visuais</td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
    <td>1.0</td>
        <td>Deve fornecer uma ferramenta de leitura avançada</td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td rowspan="3">R26</td>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao"><b>1.2</b></a></td>
        <td><b>O aplicativo deve possuir opção de controle parental de acesso das páginas</b></td>
        <td> Não </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.1</a></td>
        <td>Deve conter uma ferramenta de controle parental</td>
        <td> Não </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/observacao/#tabela-2-requisitos-funcionais">1.0</a></td>
        <td>Deve possuir opção de controle parental</td>
        <td> Não </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="2">R27</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve oferecer opção de impressão de páginas</b></td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve oferecer opção de impressão</td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="1">R28</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.0</a></b></td>
        <td><b>O aplicativo deve conter opção de traduzir o idioma das páginas</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="4">R29</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.3</a></b></td>
        <td><b>O aplicativo deve permitir sincronização de dados pessoais com a conta do Google</b></td>
        <td> Não </td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.2</td>
        <td>O sistema deve prover sincronização com a conta google</td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Sincronização de dados com conta Google	</td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Sincronização de dados com a conta do Google</td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="2">R30</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve oferecer opção de navegação através de rede privada virtual (VPN)</b></td>
        <td>Não</td>
        <td>Não</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/entrevista/#tabela-6-requisitos-elicitados-na-entrevista">1.0</a></td>
        <td>Rede privada virtual (VPN)</td>
        <td>Não</td>
        <td>Não</td>
    </tr>
    <tr>
    <td rowspan="2">R31</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>Capacidade de usar aplicações em outros navegadores</b></td>
        <td>  Sim </td>
        <td>  Sim </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O aplicativo deve simular, para desenvolvedores, suas aplicações em outros navegadores</td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td rowspan="3">R32</td>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/espec_requisitos/#especificacao-dos-requisitos_1"><b>1.2</b></a></td>
        <td><b>O sistema deve ser compatível com os sistemas operacionais IOS e Android</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></td>
        <td>O aplicativo deve ser compatível com vários sistemas operacionais</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.0</a></td>
        <td>O sistema deve ser compatível com várias plataformas</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="2">R33</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve conter uma ferramenta de correção ortográfica</b></td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Deve conter uma ferramenta de correção ortográfica</td>
        <td> Não </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="2">R34</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/especificacao-suplementar/#desempenho">1.1</a></b></td>
        <td><b>O Firefox deve consumir menos de 20% de CPU durante a navegação típica e menos de 50% durante operações intensivas</b></td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O aplicativo deve ser leve </td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td rowspan="3">R35</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></b></td>
        <td><b>O aplicativo deve permitir acesso rápido a sites acessados recentemente</b></td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Acesso à sites acessados recentemente</td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>Acesso rápido à sites acessados recentemente</td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td rowspan="2">R36</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></b></td>
        <td><b>O aplicativo deve apresentar um design arredondado</b></td>
        <td>Não</td>
        <td>Não</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/entrevista/#tabela-6-requisitos-elicitados-na-entrevista">1.0</a></td>
        <td>Temas mais arredondados</td>
        <td>Não</td>
        <td>Não</td>
    </tr>
    <tr>
    <td rowspan="4">R37</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.3</a></b></td>
        <td><b>O aplicativo deve possuir modo alternativo de cores para daltônicos</b></td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td>1.2</td>
        <td>Modo para daltônicos</td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Temas para dautônicos</td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O navegador deve incluir um modo de daltonismo </td>
        <td>  Sim </td>
        <td>  Não </td>
    </tr>
    <tr>
        <td rowspan="3">R38</td>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/especificacao-suplementar/#requisitos-de-interface"><b>1.2</b></a></td>
        <td><b>A interface do aplicativo deve apresentar  abas quadradas, animações suaves e uma Biblioteca que oferece acesso rápido a itens salvos, como favoritos, histórico, downloads, abas e capturas de tela</b></td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.1</a></td>
        <td>O aplicativo deve apresentar uma interface minimalista</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/entrevista/#tabela-6-requisitos-elicitados-na-entrevista">1.0</a></td>
        <td>Retirar excesso de funções que usuários não vão utilizar</td>
        <td> Sim </td>
        <td> Sim </td>
    </tr>
    <tr>
        <td rowspan="3">R39</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/especificacao-suplementar/#desempenho">1.2</a></b></td>
        <td><b>O sistema deve apresentar tempo de resposta inferior a 1 segundo ao realizar uma pesquisa</b></td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>O aplicativo deve ser rápido</td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O navegador deve responder rapidamente as pesquisas </td>
        <td> Sim </td>
        <td> Não </td>
    </tr>
    <tr>
        <td rowspan="2">R40</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/especificacao-suplementar/#desempenho">1.1</a></b></td>
        <td><b>O Firefox deve liberar memória quando as guias são fechadas ou não utilizadas, mantendo o consumo de memória abaixo de 500 MB durante a navegação típica (até 10 guias abertas) e não ultrapassar 2 GB em uso intenso (mais de 30 guias abertas)</b></td>
        <td>Sim</td>
        <td>Não</td>
    <tr>
        <td>1.0</td>
        <td>O aplicativo deve gerir bem a memória</td>
        <td>Sim</td>
        <td>Não</td>
    </tr>
    <tr>
        <td rowspan="7">R41</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/especificacao-suplementar/#confiabilidade">1.6</a></b></td>
        <td><b>O aplicativo deve apresentar proteção contra ataques maliciosos 24 horas por dia, 7 dias da semana, conforme comprovado por um sistema de segurança</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.5</td>
        <td>Ter segurança contra rastreamento, roubo de dados e ataques</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.4</td>
        <td>O navegador deve proteger contra rastreamento de dados</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.3</td>
        <td>O navegador deve prover uma navegação segura</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.2</td>
        <td>O sistema deve proteger os dados do usuário durante a navegação</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.1</td>
        <td>O aplicativo deve ser seguro</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td>1.0</td>
        <td>O navegador deve prover uma navegação segura</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td rowspan="4">R42</td>
        <td><b><a href="https://requisitos-de-software.github.io/2024.1-Firefox/modelagem/especificacao-suplementar/#requisitos-de-interface">1.3</a></b></td>
        <td><b>O usuário deve conseguir acessar qualquer parte do sistema em no máximo três cliques</b></td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/priorizacao/requisitos_priorizados/#resultado-da-priorizacao">1.2</a></td>
        <td>O aplicativo deve ser de fácil uso</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.1</a></td>
        <td>Sistema deve ser de fácil uso</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
    <tr>
        <td><a href="https://requisitos-de-software.github.io/2024.1-Firefox/elicitacao/tecnicas/brainstorming/#tabela-2-requisitos-elicitados">1.0</a></td>
        <td>O sistema deve ter uma interface intuitiva</td>
        <td>Sim</td>
        <td>Sim</td>
    </tr>
</table>


**Autor**: [Davi Pierre](https://github.com/DaviPierre), [Guilherme Westphall](https://github.com/west7), [Kallyne Macedo](https://github.com/kalipassos), [Leonardo Aguiar](https://github.com/Leonardo0o0), [Kauan Eiras](https://github.com/kauaneiras), [Lucas Martins](https://github.com/martinsglucas).

</center>

## Referências

1. SAYÃO, Miriam; LEITE, Julio Cesar. Monografias em Ciência da Computação n° 20/05. Acesso em 16 de junho de 2024.


## Histórico de versões

| Versão | Data       | Descrição                                             | Autor                                                                                                                                                                                                                                                                                              | Revisor                                         |
|--------|------------|-------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------|
| 1.0    | 13/06/2024 | Criação da página                                     | [Guilherme Westphall](https://github.com/west7)                                                                                                                                                                                                                                                    | [Davi Pierre](https://github.com/DaviPierre)    |
| 1.1    | 15/06/2024 | Cria tabela 1                                         | [Guilherme Westphall](https://github.com/west7)                                                                                                                                                                                                                                                    | [Davi Pierre](https://github.com/DaviPierre)    |
| 1.2    | 16/06/2024 | Adiciona o texto de introdução e da metodologia       | [Davi Pierre](https://github.com/DaviPierre)                                                                                                                                                                                                                                                       | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.3    | 16/06/2024 | Adiciona os requisitos 1 - 7 - 13 - 19 - 25 - 31 - 37 | [Davi Pierre](https://github.com/DaviPierre)                                                                                                                                                                                                                                                       | [Kauan Eiras](https://github.com/kauaneiras)    |
| 1.4    | 16/06/2024 | Adiciona mais requisitos                              | [Davi Pierre](https://github.com/DaviPierre), [Guilherme Westphall](https://github.com/west7), [Kallyne Macedo](https://github.com/kalipassos), [Leonardo Aguiar](https://github.com/Leonardo0o0), [Lucas Martins](https://github.com/martinsglucas)                                               | [Kallyne Macedo](https://github.com/kalipassos) |
| 1.5    | 19/06/2024 | Atualiza requisitos da baseline                       | [Davi Pierre](https://github.com/DaviPierre), [Guilherme Westphall](https://github.com/west7), [Kallyne Macedo](https://github.com/kalipassos), [Leonardo Aguiar](https://github.com/Leonardo0o0), [Kauan Eiras](https://github.com/kauaneiras), [Lucas Martins](https://github.com/martinsglucas) | [Davi Pierre](https://github.com/DaviPierre)    |
| 1.6    | 21/06/2024 | Adiciona tabela 1                                     | [Guilherme Westphall](https://github.com/west7)                                                                                                                                                                                                                                                    | [Kallyne Macedo](https://github.com/kalipassos) |