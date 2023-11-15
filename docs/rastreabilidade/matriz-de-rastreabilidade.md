# Matriz de Rastreabilidade

## Introdução

Uma Matriz de Rastreabilidade de Requisitos é uma tabela que estabelece uma correspondência entre os requisitos e outros artefatos do projeto, como casos de teste, códigos fonte, documentos de design, entre outros. Ela cria uma trilha que permite rastrear a origem, evolução e implementação de cada requisito, fornecendo uma visão clara das inter-relações entre eles.

A complexidade inerente aos projetos de software, aliada à necessidade de mudanças constantes, destaca a importância de se ter um controle eficaz sobre os requisitos desde sua concepção até a implementação e entrega do produto final. A matriz de rastreabilidade proporciona uma visão estruturada e organizada dessas relações, facilitando a compreensão, monitoramento e gestão de todo o conjunto de requisitos.

## Metodologia

A metodologia deste documento consiste na apresentação dos [requisitos elicitados](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md) e de toda a rastreabilidade que tem relação com determinado requisito de alguma forma, então, a partir de uma avaliação minunciosa de todos os documentos a Matriz de Rastreabilidade é montada com as seguintes colunas:

- ID: ID do requisito analisado.
- CÓDIGO: Código para determinar se o requisito é funcional (RF) ou não-funcional (RNF).
- Descrição: Descrição do artefato.
- Implementado: Indica se o requisito está ou não implementado no aplicativo.
- Pré-rastreabilidade: Origem do requisito.
- Artefatos: Quais artefatos fazem referência ao requisito em questão.
- Elos: Ligação entre requisitos e artefatos mapeados nos documentos [Backward From]() e [Forward From]().

## Legenda

| Legenda | Artefato                  |
| ------- | ------------------------- |
| E       | Épico                     |
| P       | Personas                  |
| US      | Histórias de usuário      |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| Q       | Questionário              |
| B       | Brainstorming             |
| ENT     | Entrevista                |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |


## Matriz de Rastreabilidade

Na tabela 1, é possível ver a Matriz de Rastreabilidade dos requisitos do Economia DF.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Matriz de Rastreabilidade de requisitos do Economia - DF. </p></font>
</div>

| ID    | Código | Descrição                                                          | Implementado | Pré-rastreabilidade | Artefatos                 | Elos                |
|-------|--------|--------------------------------------------------------------------|--------------|------------------|---------------------------|---------------------|
| INT01 | RF     | O aplicativo deve possuir login com email e senha                  | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT02 | RF     | O usuário poderá logar no aplicativo utilizando o gov.br          | Sim          | O, BS            | [Link para artefato]      | [Link para elo]     |
| INT03 | RF     | O usuário poderá alterar a senha de login                           | Sim          | O, IS, BS        | [Link para artefato]      | [Link para elo]     |
| INT04 | RF     | O usuário poderá se deslogar do aplicativo                         | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT05 | RF     | O aplicativo deve listar as notas fiscais de compras realizadas no CPF do usuário | Sim | O, IS, BS | [Link para artefato]      | [Link para elo]     |
| INT06 | RF     | O usuário poderá pesquisar por uma nota fiscal                      | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT07 | RF     | O usuário poderá visualizar as notas fiscais e suas informações    | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT08 | RF     | O usuário poderá imprimir a DANFE de uma nota fiscal               | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT09 | RF     | O usuário poderá cadastrar um veículo                               | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT10 | RF     | O aplicativo deverá listas os veículos cadastrados pelo usuário     | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT11 | RF     | O aplicativo deverá mostrar os débitos pendentes do veículo cadastrados pelo usuário | Sim | O         | [Link para artefato]      | [Link para elo]     |
| INT12 | RF     | O usuário poderá emitir o DAR de um débito pendente                  | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT13 | RF     | O usuário poderá cadastrar um imóvel                                | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT14 | RF     | O aplicativo deverá listar os imóveis cadastrados pelo usuário      | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT15 | RF     | O aplicativo deverá mostrar os débitos pendentes do imóvel cadastrado pelo usuário | Sim | O     | [Link para artefato]      | [Link para elo]     |
| INT16 | RF     | O aplicativo deverá mostrar os débitos pendentes de um parcelamento do usuário | Sim        | O                | [Link para artefato]      | [Link para elo]     |
| INT17 | RF     | O aplicativo deverá listar as dívidas ativas do usuário             | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT18 | RF     | O usuário poderá imprimir o DAR de um débito pendente               | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT19 | RF     | O aplicativo deverá listar os parcelamentos do usuário              | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT20 | RF     | O aplicativo deverá ter um meio do usuário entrar em contato com o Economia DF | Sim | O          | [Link para artefato]      | [Link para elo]     |
| INT21 | RF     | O aplicativo deverá ter um meio de fornecer ajuda ao usuário         | Sim          | O                | [Link para artefato]      | [Link para elo]     |
| INT22 | RF     | O aplicativo deverá mostrar o saldo do usuário no programa Nota Legal | Não        | O, IS            | [Link para artefato]      | [Link para elo]     |
| INT23 | RF     | O usuário poderá realizar a indicação do saldo do Nota Legal         | Não          | O, IS, BS        | [Link para artefato]      | [Link para elo]     |
| INT24 | RNF    | Garantir que ao fechar o aplicativo o usuário seja deslogado       | Não          | BS               | [Link para artefato]      | [Link para elo]     |
| INT25 | RF     | O aplicativo deve possuir login com CPF e senha                    | Sim          | O, IS, BS        | [Link para artefato]      | [Link para elo]     |
| INT26 | RF     | Possibilitar que o usuário aumente a fonte                          | Não          | BS               | [Link para artefato]      | [Link para elo]     |
| INT27 | RNF    | O usuário não deve conseguir colocar uma quantidade diferente de 7 caracteres ao cadastrar a placa de um veículo | Não | BS, O | [Link para artefato] | [Link para elo]     |
| INT28 | RNF    | O usuário não deve conseguir colocar uma quantidade diferente de 11 números ao cadastrar o renavan de um veículo | Não | BS, O | [Link para artefato] | [Link para elo]     |
| INT29 | RNF    | O usuário não deve conseguir colocar uma quantidade diferente de 8 números ao cadastrar a inscrição de um imóvel | Não | BS, O | [Link para artefato] | [Link para elo]     |
| INT30 | RF     | O usuário deve conseguir emitir a segunda via da dívida ativa       | Não          | BS, O            | [Link para artefato]      | [Link para elo]     |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> Izabella Alves, Lucas Ribeiro, Lucas Victor, 2023. </p></font>
</div>

## Referências Bibliográficas

## Bibliografia

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|15/11/2023|Criação do documento|[Izabella Alves](https://github.com/izabellaalves) |[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| 
|`1.0`|15/11/2023|Adição da legenda|[Lucas Víctor](https://github.com/Lucas13032003) |[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| 

