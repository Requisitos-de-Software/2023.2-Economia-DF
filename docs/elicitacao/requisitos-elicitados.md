# Requisitos Elicitados

## Introdução

O aplicativo Economia DF é um sistema que visa oferecer aos cidadãos do Distrito Federal uma plataforma conveniente e informativa para lidar com questões relacionadas à economia local e à gestão de seus créditos acumulados por meio do programa "Nota Legal". Para garantir que o aplicativo atenda às necessidades e expectativas dos usuários, foram definidos uma série de requisitos funcionais (RF) e requisitos não funcionais (RNF) durante o processo de elicitação de requisitos. Esses requisitos desempenham um papel fundamental na definição do escopo e na orientação do desenvolvimento do aplicativo. Os requisitos elicitados vieram das técnidas de elicitação: [Introspecção](/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [Brainstorming](/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [Observação](/docs/elicitacao/tecnicas-elicitacao/observação.md).

## Metodologia

A metodologia adotada envolveu a consolidação de todos os requisitos funcionais (RF) e requisitos não funcionais (RNF) obtidos por meio de diversas técnicas de elicitação em uma tabela estruturada. Nesta tabela, cada requisito é identificado por um ID exclusivo, categorizado como RF ou RNF para indicar seu tipo e acompanhado de um status de implementação. Além disso, a tabela também rastreia a origem de cada requisito, destacando se ele foi obtido por meio de técnicas como a [Introspecção](/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [Brainstorming](/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [Observação](/docs/elicitacao/tecnicas-elicitacao/observação.md).

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

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023.</p></font>
</div >

## Tabela de requisitos elicitados

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos elicitados do aplicativo Economia - DF.</p></font>
</div >

| ID   | Código | Descrição                                                                                      | Implementado | Rastreabilidade |
|------|--------|------------------------------------------------------------------------------------------------|--------------| ------ |
| INT01| RF     | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |Sim| IS, BS |
| INT02| RF     | Deve ser possível acessar os dados diretamente da secretaria de estado de economia do distrito federal | Sim | IS |
| INT03| RF     | O aplicativo deve permitir a recuperação de senha por meio de um processo seguro e validado. | Sim | IS, BS |
| INT04| RF     | Os usuários devem poder acessar e visualizar informações sobre créditos acumulados. | Não | IS |
| INT05| RF     | O aplicativo deve possibilitar a consulta do histórico de notas fiscais associadas à conta do usuário. | Sim | IS, BS, O |
| INT06| RF     | Permitir que os usuários consultem estabelecimentos comerciais parceiros do programa Nota Legal. | Não | IS |
| INT07| RF     | Os usuários devem poder resgatar os créditos acumulados de forma clara e fácil. | Não | IS |
| INT08| RF     | Deve ser possível visualizar promoções e descontos oferecidos em estabelecimentos participantes. | Sim | IS |
| INT09| RF     | O aplicativo deve ter uma interface intuitiva, fácil de navegar e que proporcione uma boa experiência ao usuário. | Sim | IS, BS,  |
| INT10| RF     | Deve ser oferecido suporte para diferentes tamanhos de tela e dispositivos móveis. | Não | IS, BS |
| INT11| RF     | Deve ser disponibilizada uma forma de entrar em contato com a Secretária de Estado de Economia no caso de algum problema específico do usuário | Sim | IS  |
| INT12| RNF    | Garantir a segurança das informações dos usuários durante a transmissão e armazenamento de dados. | Sim | IS, BS |
| INT13| RNF    | Assegurar conformidade com regulamentações de proteção de dados vigentes no Brasil. | Sim | IS, BS |
| INT14| RNF    | Garantir uma resposta rápida e eficiente, minimizando o tempo de carregamento das páginas. | Não | IS, BS |
| INT15| RNF    | Manter a disponibilidade do aplicativo, minimizando tempo de inatividade para garantir uma experiência contínua. | Não | IS, BS |
| INT16| RNF    | Garantir uma interface de usuário amigável, facilitando a interação e a compreensão das funcionalidades do aplicativo. | Sim | IS, BS |
| INT17| RNF    | Certificar-se de que o aplicativo é compatível com uma ampla variedade de dispositivos móveis e sistemas operacionais. | Não | IS |
| INT18| RNF    | Garantir que o aplicativo seja otimizado para diferentes navegadores web. | Não | IS, BS |
| INT19| RNF    | Garantir que ao fechar o aplicativo o usuário seja deslogado | Não | BS  |
| INT20| RF  | Garantir que o usuário consiga realizar login com a conta do GOV | Não | BS |
| INT21| RF  | Possuir informações sobre desbloqueio de valores bloqueados | Não | BS |
| INT22| RF  | Possui informações sobre o percentual de concessão de cŕedito de acordo com o tipo de estabelecimento que emitiu a nota fiscal | Não | BS  |
| INT23| RF  | Possibilitar que o usuário aumente a fonte | Não | BS |  
| INT24| RF  | Possuir um modo escuro e um modo claro | Não | BS |
| INT25| RF  | Salvar os dados bancários da conta usada na indicação | Não | BS |
| INT26| RF  | Deve ser possível encontrar o recibo da indicação | Não | BS  |
| INT27| RNF  | O usuário não deve conseguir colocar uma quantidade diferente de 7 caracteres ao cadastrar a placa de um veículo | Não | BS, O |
| INT28| RNF  | O usuário não deve conseguir colocar uma quantidade diferente de 11 números ao cadastrar o renavan de um veículo | Não | BS, O |
|INT29| RNF  | O usuário não deve conseguir colocar uma quantidade diferente de 8 números ao cadastrar a inscrição de um imóvel | Não | BS, O |
|INT30| RF  | O usuário deve conseguir emitir a segunda via da dívida ativa | Não | BS, O  |

<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023.</p></font>
</div >

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|29/09/2023|Criação do documento e adição de tabela|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.1`|29/09/2023|Adição da introdução, metodologia e inserindo rastreabilidade da tabela|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.2`|22/10/2023|Padronizando localização dos nomes das figuras/tabelas e das fontes nas legendas|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Zaranza](https://github.com/GZaranza)|
