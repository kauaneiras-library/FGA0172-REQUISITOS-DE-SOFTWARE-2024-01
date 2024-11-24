# Backlog 

## Introdução 

O backlog do produto é uma lista priorizada que contém todas as funcionalidades que devem fazer parte do produto. O conteúdo do mesmo é definido pelo Product Owner, que cria e mantém o backlog do produto durante toda a produção e evolução do software. Portanto, o backlog do produto não precisa estar completo no início do projeto, uma vez que ele cresce e muda à medida que se aprende mais sobre o produto e seus usuários (SCHWABER; SUTHERLAND, 2020).

## Metodologia 

A estrutura do backlog do produto que foi utilizada envolve a subdivisão em tema, épicos e histórias de usuário. Dessa forma, a organização do backlog do produto foi pensada da seguinte maneira: os temas foram definidos com base nos requisitos levantados e priorizados anteriormente e divididos em épicos, que são as partes que constituem os temas e guiam as histórias de usuário, que são ainda menores e mais específicas (PICHLER, 2017).

## Modelo 

<div align="center">
    <font size="3"><p style="text-align: center"><b>Tabela 1:</b> Modelo de Backlog</p></font>
</div>
<center>

| Tema | Épicos | Histórias de Usuário       | Prioridade         | Status                                          | 
| ------ | ---------- | ----------------- | ----------------------------------------------- | ------- |
| T01    | E01 | US01 | Alta | Implementado 

</center>

<div align="center"
    <font size="3"><p style="text-align: center"><b>Autor: </b><a href="https://github.com/kalipassos">Kallyne Macedo</a>, 2024</p></font>
</div>

## Backlog

### Temas

Atráves da análise dos requisitos elicitados e priorizados para o projeto, foi possível definir três principais temas. 

#### T01. Navegação 
O tema de Navegação engloba os épicos e histórias de usuário voltadas para o acesso e para a pesquisa, tanto em sites quanto no próprio navegador. 

#### T02. Personalização    
O tema de Personalização engloba os épicos e histórias de usuários que intendem adequar a aplicação às preferências e necessidades do usuário. 

#### T03. Dados 
O tema de Dados engloba os épicos e histórias de usuário que tratam da gestão e armazenamento de dados do usuário na aplicação. 


### Épicos

#### T01. Navegação 

##### E01. Acesso à sites

O épico de acesso à sites engloba as funcionalidades responsáveis pela navegação em páginas na Internet. 

"Eu, como usuário, desejo utilizar o navegador para visitar sites na Web".

##### E02. Pesquisa

O épico de pesquisa engloba as funcionalidades que envolvem a realização de pesquisas através do navegador.

"Eu, como usuário, desejo realizar pesquisas pelo navegador".

#### T02. Personalização 

##### E03. Acessibilidade

O épico de acessibilidade engloba as funcionalidades que permitem o usuário moldar o sistema de forma com que seu uso se torne prático e possível dentro de suas limitações. 

"Eu, como usuário, desejo que o aplicativo seja acessível para deficientes visuais".

##### E03.1*. Preferências 

O épico de preferências engloba as funcionalidades que permitem o usuário moldar o sistema de forma que atenda aos seus gostos pessoais e traga uma experiência de uso mais individual e agradável para o usuário.

"Eu, como usuário, desejo ter uma experiência de uso mais agradável as minhas preferências".

#### T03. Dados

##### E04. Performance

O épico de performance engloba as funcionalidades que envolvem a otimização e funcionamento do sistema conforme o esperado pelo usuário.

"Eu, como usuário, desejo que a aplicação tenha uma gestão de memória eficiente". 

##### E05. Tradução

O épico de tradução engloba as funcionalidades que envolvem a troca de idioma da aplicação.

"Eu, como usuário, desejo que as páginas que acesso possam ser traduzidas para o Português".

##### E06. Rastreabilidade

O épico de rastreabilidade engloba as funcionalidades que envolvem o histórico de dados e as informações de navegação do usuário.

"Eu, como usuário, desejo ter um histórico que contenha as últimas páginas que acessei".

##### E07. Segurança

O épico de segurança engloba as funcionalidades que protegem o usuário de danos.

"Eu, como usuário, desejo que o aplicativo me proteja contra ataques maliciosos".

<div align="center">
    <font size="3"><p style="text-align: center"><b>Tabela 1:</b> Backlog do Produto</p></font>
</div>

<center>

| Tema | Épicos | Histórias de Usuário       | Prioridade         | Status                                          | 
| ------ | ---------- | ----------------- | ----------------------------------------------- | ------- |
| T01    | E01 | [US01](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us01-acessar-site) - Acessar site | Alta | Implementado |
| T01    | E01 | [US02](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us02-acessar-site-formato-desktop) - Acessar site formato desktop | Alta | Implementado |
| T01   | E01 | [US03](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us03-favoritar-sites) - Favoritar sites | Alta | Implementado |
| T01    | E02 | [US04](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us04-pesquisar-no-navegador) - Pesquisar no navegador | Alta | Implementado |
| T01    | E02 | [US05](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us05-pesquisar-por-voz) - Pesquisar por voz | Alta | Não implementado |
| T02    | E03 | [US06](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us06-iniciar-leitura-de-paginas) - Iniciar leitura de páginas | Alta | Implementado |
| T02    | E03 | [US07](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us07-controlar-acesso-a-sites-controle-parental) - Controlar acesso à sites (controle parental) | Alta | Não implementado |
| T02    | E03 | [US08](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us08-alterar-fonte-do-navegador) - Alterar fonte do navegador | Alta | Implementado |
| T02    | E03 | [US09](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us09-controlar-por-atalho-de-gestos) - Controlar por atalho de gestos | Alta | Implementado |
| T02    | E03 | [US10](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us10-alterar-entre-o-tema-claro-e-escuro) - Alterar entre o tema claro e escuro | Alta | Implementado |
| T03    | E04 | [US11](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us11-gerir-memoria) - Gerir memória | Alta | Implementado |
| T03    | E05 | [US12](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us12-mudar-idioma) - Mudar idioma | Alta | Implementado |
| T03    | E05 | [US13](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us13-traduzir-pagina) - Traduzir página | Alta | Implementado |
| T03    | E06 | [US14](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us14-sincronizar-dados) - Sincronizar dados | Alta | Implementado |
| T03    | E06 | [US15](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us15-acessar-historico-de-navegacao) - Acessar histórico de navegação | Alta | Implementado |
| T03    | E06 | [US16](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us16---acessar-historico-de-downloads) - Acessar histórico de downloads | Alta | Implementado |
| T03    | E06 | [US17](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us17-limpar-historico) - Limpar histórico | Alta | Implementado |
| T03    | E06 | [US18](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us18-limpar-dados-de-usuario) - Limpar dados de usuário | Alta | Implementado |
| T03    | E07 | [US19](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us19-trocar-de-conta) - Trocar de conta | Alta | Implementado |
| T03    | E07 | [US20](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us20-alterar-senha) - Alterar senha | Alta | Implementado |
| T03    | E07 | [US21](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us21-ter-seguranca-contra-rastreamento-roubo-de-dados-e-ataques) - Ter segurança contra rastreamento, roubo de dados e ataques | Alta | Implementado |
| T03    | E06 | [US22](../modelagem_agil/historias_de_usuario/historias_de_usuario.md#us22-bloquear-anuncios) - Bloquear anúncios | Alta | Implementado |



</center>

<div align="center"
    <font size="3"><p style="text-align: center"><b>Autor: </b><a href="https://github.com/kalipassos">Kallyne Macedo</a>, <a href="https://github.com/Leonardo0o">Leonardo Aguiar</a>,2024</p></font>
</div>


## Referências 

1. **LuizTools**. Product Backlog - Introdução. YouTube, 21 de março de 2020. Disponível em: <https://www.youtube.com/watch?v=z4ubaBwjCsU>. Acesso em 24 de Maio de 2024.
2. **SCHWABER, Ken**; SUTHERLAND, Jeff. The Scrum Guide. The Definitive Guide to Scrum: The Rules of the Game. 2020. Disponível em: <https://scrumguides.org/scrum-guide.html>. Acesso em: 24 de Maio de 2024.
3. **PICHLER, Roman**. Agile Product Management with Scrum: Creating Products that Customers Love. 1. ed. Addison-Wesley Professional, 2017.

## Histórico de versões

| Versão | Data       | Descrição         | Autor                                           | Revisor |
| ------ | ---------- | ----------------- | ----------------------------------------------- | ------- |
| 1.0    | 25/05/2024 | Criação da página | [Kallyne Macedo](https://github.com/kalipassos), [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Lucas Martins](https://github.com/martinsglucas)     |
| 1.1    | 27/05/2024 | Atualizações gerais do Backlog com as US08 -> US12 | [Davi Pierre](https://github.com/DaviPierre) | [Kallyne Macedo](https://github.com/kalipassos) |
| 1.2    | 27/05/2024 | Correções gerais | [Kallyne Macedo](https://github.com/kalipassos), [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Davi Pierre](https://github.com/DaviPierre)    |
| 1.3 | 05/06/2024 | Correções | [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Kauan Eiras](https://github.com/kauaneiras) |
