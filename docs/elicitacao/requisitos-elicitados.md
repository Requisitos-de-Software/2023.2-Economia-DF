# Requisitos Elicitados

## Introdução

O aplicativo Economia DF é um sistema que visa oferecer aos cidadãos do Distrito Federal uma plataforma conveniente e informativa para lidar com questões relacionadas à economia local e à gestão de seus créditos acumulados por meio do programa "Nota Legal". Para garantir que o aplicativo atenda às necessidades e expectativas dos usuários, foram definidos uma série de requisitos funcionais (RF) e requisitos não funcionais (RNF) durante o processo de elicitação de requisitos. Esses requisitos desempenham um papel fundamental na definição do escopo e na orientação do desenvolvimento do aplicativo. Os requisitos elicitados vieram das técnidas de elicitação: [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [Observação](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observação.md).

## Metodologia

A metodologia adotada envolveu a consolidação de todos os requisitos funcionais (RF) e requisitos não funcionais (RNF) obtidos por meio de diversas técnicas de elicitação em uma tabela estruturada. Nesta tabela, cada requisito é identificado por um ID exclusivo, categorizado como RF ou RNF para indicar seu tipo e acompanhado de um status de implementação. Além disso, a tabela também rastreia a origem de cada requisito, destacando se ele foi obtido por meio de técnicas como a [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [Observação](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observação.md).

Foram elicitados 51 requisitos através dessas técnicas citadas, tanto para o site Nota Legal da disciplina de Interação Humano-Computador quanto para o aplicativo Economia-DF da disciplina Requisistos de Software. Após a apresentação da entrega e o feedback do professor e do monitor, o grupo escolheu 30 requisitos para trabalhar no projeto. O critério utilizado foi escolher os requisitos funcionais e não-funcionais já implementados no aplicativo Economia-DF e alguns requisitos do Nota Legal não implementados no aplicativo em estudo. Na tabela 2 constam esses requisitos.

Essa abordagem de registro em tabela oferece uma visão organizada e estruturada dos requisitos do projeto, permitindo uma fácil referência e acompanhamento ao longo do ciclo de desenvolvimento. Ela promove a rastreabilidade, o que significa que é possível rastrear a origem de cada requisito, garantindo que todas as necessidades dos stakeholders sejam devidamente consideradas e atendidas no projeto.

A legenda para cada sigla é a seguinte:

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda para a tabela 2 de requisitos do Economia - DF. </p></font>

<table>
  <thead>
    <tr>
        <th>Tipo</th>
        <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>RF</td>
        <td>Requisito Funcional</td>
    </tr>
    <tr>
        <td>RNF</td>
        <td>Requisito Não-Funcional</td>
    </tr>
    <tr>
        <td>IS</td>
        <td>Requisito elicitado pela Introspecção</td>
    </tr>
    <tr>
        <td>BS</td>
        <td>Requisito elicitado pelo Brainstorming</td>
    </tr>
    <tr>
        <td>O</td>
        <td>Requisito elicitado pelo Observação</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>
</div >

## Tabela de requisitos elicitados

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos elicitados do aplicativo Economia - DF</p></font>
</div >

| ID    | Código | Descrição                                                                            | Implementado | Rastreabilidade |
| :---: | :----: | ------------------------------------------------------------------------------------ | :----------: | :-------------: |
| INT01 | RF     | O aplicativo deve possuir login com email e senha                                    | Sim          | O               |
| INT02 | RF     | O usuário poderá logar no aplicativo utilizando o gov.br                             | Sim          | O, BS           |
| INT03 | RF     | O usuário poderá alterar a senha de login                                            | Sim          | O, IS, BS       |
| INT04 | RF     | O usuário poderá se deslogar do aplicativo                                           | Sim          | O               |
| INT05 | RF     | O aplicativo deve listar as notas fiscais de compras realizadas no CPF do usuário    | Sim          | O, IS, BS       |
| INT06 | RF     | O usuário poderá pesquisar por uma nota fiscal                                       | Sim          | O               |
| INT07 | RF     | O usuário poderá visualizar as notas fiscais e suas informações                      | Sim          | O               |
| INT08 | RF     | O usuário poderá imprimir a DANFE de uma nota fiscal                                 | Sim          | O               |
| INT09 | RF     | O usuário poderá cadastrar um veículo                                                | Sim          | O               |
| INT10 | RF     | O aplicativo deverá listas os veículos cadastrados pelo usuário                      | Sim          | O               |
| INT11 | RF     | O aplicativo deverá mostrar os débitos pendentes do veículo cadastrados pelo usuário | Sim          | O               |
| INT12 | RF     | O usuário poderá emitir o DAR de um débito pendente                                  | Sim          | O               |
| INT13 | RF     | O usuário poderá cadastrar um imóvel                                                 | Sim          | O               |
| INT14 | RF     | O aplicativo deverá listar os imóveis cadastrados pelo usuário                       | Sim          | O               |
| INT15 | RF     | O aplicativo deverá mostrar os débitos pendentes do imóvel cadastrado pelo usuário   | Sim          | O               |
| INT16 | RF     | O aplicativo deverá mostrar os débitos pendentes de um parcelamento do usuário       | Sim          | O               |
| INT17 | RF     | O aplicativo deverá listar as dívidas ativas do usuário                              | Sim          | O               |
| INT18 | RF     | O usuário poderá imprimir o DAR de um débito pendente                                | Sim          | O               |
| INT19 | RF     | O aplicativo deverá listar os parcelamentos do usuário                               | Sim          | O               |
| INT20 | RF     | O aplicativo deverá ter um meio do usuário entrar em contato com o Economia DF       | Sim          | O               |
| INT21 | RF     | O aplicativo deverá ter um meio de fornecer ajuda ao usuário                         | Sim          | O               |
| INT22 | RF     | O aplicativo deverá mostrar o saldo do usuário no programa Nota Legal                | Não          | O, IS           |
| INT23 | RF     | O usuário poderá realizar a indicação do saldo do Nota Legal                         | Não          | O, IS, BS       |
| INT24 | RNF    | Garantir que ao fechar o aplicativo o usuário seja deslogado                         | Não          | BS              |
| INT25 | RF     | O aplicativo deve possuir login com CPF e senha                                      | Sim          | O, IS, BS       |
| INT26 | RF     | Possibilitar que o usuário aumente a fonte                                           | Não          | BS              |
| INT27 | RNF    | O usuário não deve conseguir colocar uma quantidade diferente de 7 caracteres ao cadastrar a placa de um veículo | Não | BS, O |
| INT28 | RNF    | O usuário não deve conseguir colocar uma quantidade diferente de 11 números ao cadastrar o renavan de um veículo | Não | BS, O |
| INT29 | RNF    | O usuário não deve conseguir colocar uma quantidade diferente de 8 números ao cadastrar a inscrição de um imóvel | Não | BS, O |
| INT30 | RF     | O usuário deve conseguir emitir a segunda via da dívida ativa                                                    | Não | BS, O |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>
</div >

## Histórico de Versões

| Versão | Data       | Descrição                                                                        | Autor                                              |                      Revisor                       |
| :----: | ---------- | -------------------------------------------------------------------------------- | -------------------------------------------------- | :------------------------------------------------: |
| `1.0`  | 29/09/2023 | Criação do documento e adição de tabela                                          | [Izabella Alves](https://github.com/izabellaalves) |   [Gabriel Zaranza](https://github.com/gzaranza)   |
| `1.1`  | 29/09/2023 | Adição da introdução, metodologia e inserindo rastreabilidade da tabela          | [Gabriel Rosa](https://github.com/gabrielrosa09)   | [Izabella Alves](https://github.com/izabellaalves) |
| `1.2`  | 22/10/2023 | Padronizando localização dos nomes das figuras/tabelas e das fontes nas legendas | [Zenilda Vieira](https://github.com/zenildavieira) |   [Gabriel Zaranza](https://github.com/GZaranza)   |
| `2.0`  | 29/10/2023 | Correção após a entrega 3 | [Zenilda Vieira](https://github.com/zenildavieira) e <br>   [Gabriel Zaranza](https://github.com/GZaranza)   |  [Izabella Alves](https://github.com/izabellaalves) | 
