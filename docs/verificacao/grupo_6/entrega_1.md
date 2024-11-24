# Verificação da Entrega 1 - "Pré-rastreabilidade"

## Introdução

Este documento aborda a verificação da Entrega 1, intitulada "Pré-rastreabilidade". Esta entrega inclui o artefato [Rich Picture](../../pre-rastreabilidade/rich-picture.md) elaborados pelo nosso grupo com base no aplicativo Firefox.

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

## Objetos de verificação

Nos dias que foi realizada a inspeção, 30 de junho de 2024 , os artefatos avaliados estavam nas seguintes versões demonstradas na tabela 2:

<center>

**Tabela 2**: Objetos de verificação

|                  | Versão | Data       | Descrição           | Autor(es)                                         | Revisor(es)                                  |
| ---------------- | ------ | ---------- | ------------------- | ------------------------------------------------- | -------------------------------------------- |
| **Rich Picture** | `1.1`  | 29/05/2024 | Correção da legenda | [Lucas Martins](https://github.com/martinsglucas) | [Davi Pierre](https://github.com/DaviPierre) |


**Autor**: [Davi Pierre](https://github.com/DaviPierre)

</center>

## Checklists

Nesta seção, serão dispostos os checklists dos artefatos da Entrega 2 nas tabelas 3, 4 e 5. Durante a inspeção, o responsável deverá preencher o campo de avaliação da seguinte maneira: 

>- **Sim**, se o critério foi totalmente atendido. 
>- **Não**, se o critério não foi atendido. 
>- **Incompleto**, se o critério foi parcialmente atendido, explicando em qual parte o artefato falhou. 
>- **Não se aplica**, se o critério não pode ser verificado devido ao contexto do projeto. 

### Rich Picture

A tabela 3 apresentao checklist do artefato "Rich Picture".


<center>

**Tabela 3**: Checklist do Rich Picture

| ID  | Descrição                                                                                                        | Referência                                                                                  | Avaliação |
| --- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | --------- |
| 01  | O Rich Picture está padronizado com simbologia dos Atores, Setas, Operações, Data Stores e Fronteira do Sistema? | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 02  | Os Atores tem legendas explicando o que representam?                                                             | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 03  | Toda Operação é executada por um Ator ou outra Operação?                                                         | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 04  | As Data Stores tem explicitamente qual tipo de dado será salvo nelas?                                            | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 05  | Apenas as operações estão interagindo com os Data Stores?                                                        | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 06  | As Setas tem legendas com a natureza do fluxo de dados?                                                          | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 07  | Os Atores estão fora da Fronteira do Sistema?                                                                    | [CTEC2402 Software Development Project página 4](../grupo_6/assets/R1.png)                  | Sim       |
| 08  | O Rich Picture é de fácil compreensão e descreve o sistema superficialmente?                                     | [Growing Wings on the Way: Systems Thinking for Messy Situations](../grupo_6/assets/R2.png) | Sim       |
| 09  | As preocupações, se presentes, estão presentes em bolhas de pensamento?                                          | [Growing Wings on the Way: Systems Thinking for Messy Situations](../grupo_6/assets/R2.png) | N/A       |
| 10  | A linguagem do Rich Picture está de simples compreensão do leitor?                                               | [Growing Wings on the Way: Systems Thinking for Messy Situations](../grupo_6/assets/R2.png) | Sim       |


**Autor da lista de verificação**: [Davi Pierre](https://github.com/DaviPierre), **Inspecionado por:** [Kallyne Macedo](https://github.com/kalipassos), 2024.

</center>


#### Problemas encontrados

Não foram localizados problemas específicos à diagramação do Rich Picture. A avaliação do item 09, entretanto, não se aplica, pois não foi utilizado o recurso da preocupação. Pode-se destacar, também, que no item 04, a legenda poderia ser mais descritiva do que se encontra atualmente no que tange os dados. 



## Referências

1. MASTER2TEACH. Fagan Inspection Methodology - Benefits of Software Inspections. Disponível em: https://www.youtube.com/watch?v=v_Lz2l_XsTQ. Acesso em: 3 jun. 2024.

2. REQUISITOS, Milane Serrano e Mauricio Serrano. Disponível em: https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 9 jun. 2024.

3. ENGENHARIA DE REQUISITOS, RE-training. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades. Acesso em: 9 jun. 2024.

4. Santos, V. G., Daher N., UTILIZAÇÃO DE STORYTELLING COMO FERRAMENTA DE AQUISIÇÃO DE REQUISITOS EM PROCESSO DE DESENVOLVIMENTO DE SOFTWARE APOIADOS EM MODELOS ÁGEIS: O USO APOIADO NO EXTREME PROGRAMMING, Belo Horizonte, 2008. 14 p., Artigo (Análise de Sistemas), e-tec UNI-BH. Disponível em: https://revistas.unibh.br/dtec/article/view/440. Acesso em: 9 jun. 2024.

5. WIEGERS, Karl E.; BEATTY, Joy. Software requirements. Pearson Education, 2013. Disponível em: <https://thuvienso.hoasen.edu.vn/bitstream/handle/123456789/9059/Contents.pdf?sequence=5&isAllowed=y>. Acesso em: 8 de junho de 2024.

6. POHL, Klaus. Requirements engineering fundamentals: a study guide for the certified professional for requirements engineering exam-foundation level-IREB compliant. Rocky Nook, Inc., 2016. Acesso em: 8 de junho de 2024.

7. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em: 8 de junho de 2024.

8. REQUISITOS DE SOFTWARE. Meu INSS. Disponível em: <https://requisitos-de-software.github.io/2024.1-Meu-INSS/>. Acesso em: 8 de junho de 2024.

9. VASQUEZ, Carlos. Engenharia de Requisitos: Software orientado ao negocio.

10. Personas 101, Digital.gov. Disponível em: https://digital.gov/2015/01/09/personas-101/. Acesso em: 30 jun. 2024.

11. Cooper, Alan. Reimaann, Robert. Cronin, David. About Face: the essentials of interaction design.

12. CTEC2402 Software Development Project. Disponível em: <https://www.scribd.com/document/227529428/Rich-Picture-Guidelines>. Acesso em: 02 de Junho de 2024.

13. Growing Wings on the Way: Systems Thinking for Messy Situations

## Histórico de versão

| Versão | Data       | Descição                                                            | Autor                                                                                         | Revisor                                           |
| ------ | ---------- | ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| 1.0    | 02/07/2024 | Criação da página, adição e inspeção da verificação do Rich Picture | [Davi Pierre](https://github.com/DaviPierre), [Kallyne Macedo](https://github.com/kalipassos) | [Lucas Martins](https://github.com/martinsglucas) |