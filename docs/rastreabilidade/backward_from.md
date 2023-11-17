# Backward-From

## Introdução

Esse documento aborda a aplicação do método de rastreabilidade backward-from. A rastreabilidade de requisitos desempenha um papel crucial no desenvolvimento de sistemas. Ela permite não apenas identificar e conectar requisitos durante a fase de desenvolvimento, mas também rastreá-los ao longo de todo o ciclo de vida do sistema. Isso se traduz em uma compreensão mais clara das origens e implicações de cada requisito, contribuindo para a garantia da qualidade, gestão eficiente de mudanças e alinhamento contínuo com as necessidades do cliente.

Quando aplicamos o método de rastreabilidade backward-from, estamos focados em estabelecer vínculos sólidos entre os requisitos e suas fontes. Isso significa que podemos rastrear um requisito específico até a sua origem, seja ela uma solicitação do cliente, um processo de negócio ou qualquer outra fonte relevante. Ao utilizar materiais como os [slides da aula 26](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) conduzida pela professora Milene Serrano e o livro [Requirements Engineering Fundamentals](https://aprender3.unb.br/pluginfile.php/2692881/mod_resource/content/2/Rastreabilidade.pdf) de Klaus Pohl e Chris Rupp, somos capazes de aprimorar essa abordagem, garantindo uma visão mais abrangente e estruturada da rastreabilidade de requisitos.

A implementação eficaz da rastreabilidade não apenas facilita o entendimento dos requisitos, mas também simplifica a validação e verificação dos sistemas, auxiliando na detecção precoce de possíveis problemas. Isso resulta em economia de tempo e recursos, além de promover a satisfação do cliente ao assegurar que o sistema atenda de maneira precisa e confiável às suas necessidades ao longo do tempo.

## Metodologia

A metodologia de rastreabilidade de requisitos proposta por Toranzo é um enfoque importante no desenvolvimento de software. Ela visa garantir que os requisitos sejam rastreáveis ao longo do ciclo de vida do projeto, desde a sua concepção até a entrega final do produto.

Na execução do método backward-from, utilizamos o meta-modelo proposto por Toranzo. Esse meta-modelo classifica os requisitos elicitados pelo grupo em níveis e elos. Com base nos slides 19 da [aula 26](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da professora Milene Serrano, os níveis são: 

- **_Ambiental_**: Essas informações provêm do ambiente e contexto nos quais a organização está inserida.
- **_Organizacional_**: São dados relacionados à própria organização.
- **_Gerencial_**: Engloba informações que auxiliam na gestão do projeto.
- **_Desenvolvimento_**: Refere-se às informações associadas aos diversos artefatos gerados durante o processo de desenvolvimento.

Com base nos slides 21 da [aula 26](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da professora Milene Serrano, os principais **elos de rastreabilidade** são os seguintes:

1. **Satisfação**: Indica que a classe de origem depende da satisfação proporcionada pela classe de destino.
2. **Recurso**: Reflete a dependência de recursos da classe de origem em relação à classe de destino.
3. **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre os artefatos.
4. **Representação**: Captura a forma como os requisitos são representados ou modelados em outras linguagens.
5. **Alocado**: Relaciona a classe de origem a uma classe de destino que representa um subsistema.
6. **Agregação**: Indica a "composição" de elementos.

Para auxiliar na criação do meta-modelo de Toranzo, foram elaboradas as **tabelas 1 e 2**, que dividem os requisitos a serem rastreados em funcionais (RF) e não-funcionais (RNF).

## Tabelas de requisitos funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos funcionais, que está sendo demonstrado na tabela 1 a seguir:

**Legendas:**

> - RF: Requisito Funcional
> - RNF: Requisito Não Funcional
> - BS: Brainstorm
> - ENT: Entrevista
> - INT: Instrospecção
> - IS: Introspecção
> - C: Cenários
> - E: Épico
> - F: Feature
> - HS: Histórias de Usuário
> - UC: Casos de Uso
> - L: Léxicos 

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Requisitos funcionais elicitados</p></font>


| ID    | Código | Descrição                                                                            | Implementado | Rastreabilidade |
| ----- | ------ | ------------------------------------------------------------------------------------ | ------------ | --------------- |
| INT01 | RF     | O aplicativo deve possuir login com email e senha                                    | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs01---efetuar-login-com-email-e-senha)               |
| INT02 | RF     | O usuário poderá logar no aplicativo utilizando o gov.br                             | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs01---efetuar-login-com-email-e-senha)           |
| INT03 | RF     | O usuário poderá alterar a senha de login                                            | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [IS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md)       |
| INT04 | RF     | O usuário poderá se deslogar do aplicativo                                           | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs04---efetuar-logout)               |
| INT05 | RF     | O aplicativo deve listar as notas fiscais de compras realizadas no CPF do usuário    | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [IS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs05---listar)       |
| INT06 | RF     | O usuário poderá pesquisar por uma nota fiscal                                       | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs06---pesquisar)               |
| INT07 | RF     | O usuário poderá visualizar as notas fiscais e suas informações                      | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs07---visualizar-detalhes)               |
| INT08 | RF     | O usuário poderá imprimir a DANFE de uma nota fiscal                                 | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs08---imprimir-danfe)               |
| INT09 | RF     | O usuário poderá cadastrar um veículo                                                | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar)               |
| INT10 | RF     | O aplicativo deverá listas os veículos cadastrados pelo usuário                      | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs10---consultar-d%C3%A9bitos-de-ipva)               |
| INT11 | RF     | O aplicativo deverá mostrar os débitos pendentes do veículo cadastrados pelo usuário | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs10---consultar-d%C3%A9bitos-de-ipva)               |
| INT12 | RF     | O usuário poderá emitir o DAR de um débito pendente                                  | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar)               |
| INT13 | RF     | O usuário poderá cadastrar um imóvel                                                 | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar)               |
| INT14 | RF     | O aplicativo deverá listar os imóveis cadastrados pelo usuário                       | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md)               |
| INT15 | RF     | O aplicativo deverá mostrar os débitos pendentes do imóvel cadastrado pelo usuário   | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos)               |
| INT16 | RF     | O aplicativo deverá mostrar os débitos pendentes de um parcelamento do usuário       | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md)               |
| INT17 | RF     | O aplicativo deverá listar as dívidas ativas do usuário                              | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos)               |
| INT18 | RF     | O usuário poderá imprimir o DAR de um débito pendente                                | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar)               |
| INT19 | RF     | O aplicativo deverá listar os parcelamentos do usuário                               | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md)               |
| INT20 | RF     | O aplicativo deverá ter um meio do usuário entrar em contato com o Economia DF       | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs15---enviar-email)               |
| INT21 | RF     | O aplicativo deverá ter um meio de fornecer ajuda ao usuário                         | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [HS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs16---visualizar-informa%C3%A7%C3%B5es-sobre-o-aplicativo)               |
| INT22 | RF     | O aplicativo deverá mostrar o saldo do usuário no programa Nota Legal                | Não          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [IS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md)           |
| INT23 | RF     | O usuário poderá realizar a indicação do saldo do Nota Legal                         | Não          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [IS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md)       |
| INT24 | RF     | O aplicativo deve possuir login com CPF e senha                                      | Sim          | [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md), [IS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md)       |
| INT25 | RF     | Possibilitar que o usuário aumente a fonte                                           | Não          | [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md)              |
| INT26 | RF     | O usuário deve conseguir emitir a segunda via da dívida ativa                                                    | Não | [BS](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md), [O](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md) |


<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> e <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a>, 2023</p></font>
</div>

## Tabelas de requisitos não-funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na tabela 2 a seguir:

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos não-funcionais elicitados</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Implementado</th>
      <th>Rastreabilidade</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>INT01</td>
      <td>Garantir que ao fechar o aplicativo o usuário seja deslogado</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md">BS</a></td>
    </tr>
    <tr>
      <td>INT02</td>
      <td>O usuário não deve conseguir colocar uma quantidade diferente de 7 caracteres ao cadastrar a placa de um veículo</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md">BS</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md">O</a></td>
    </tr>
    <tr>
      <td>INT03</td>
      <td>  O usuário não deve conseguir colocar uma quantidade diferente de 11 números ao cadastrar o renavan de um veículo</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md">BS</a> , <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md">O</a></td>
    </tr>
    <tr>
      <td>INT04</td>
      <td>O usuário não deve conseguir colocar uma quantidade diferente de 8 números ao cadastrar a inscrição de um imóvel </td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md">BS</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md">O</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> e <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a>, 2023</p></font>
</div>

## Elos

Neste segmento, abordaremos os vínculos dos requisitos identificados nas tabelas 1 e 2. De acordo com a metodologia mencionada, todos os requisitos serão categorizados com base no tipo de vínculo. No entanto, é importante observar que todos esses requisitos identificados pertencem à categoria de Desenvolvimento. Eles derivam de artefatos criados durante o processo de desenvolvimento do trabalho, sem qualquer relação com a organização ou a gestão do projeto. A partir desses requisitos, compilamos a tabela 3, que apresenta todos os vínculos (elos) envolvidos.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Elos de rastreabilidade.</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Rastreabilidade</th>
      <th>Implementado</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> e <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a>, 2023</p></font>
</div>

## Conclusão





## Bibliografia

> Requirements Engineering Fundamentals. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692881/mod_resource/content/2/Rastreabilidade.pdf>. Acesso em: 15 nov. 2023.

> Slides da Aula 26 da Professora Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 15 nov. 2023.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|15/11/2023|Criação do documento|[Gabriel Rosa](https://github.com/gabrielrosa09) e [Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|15/11/2023|Adição da introdução |[Gabriel Rosa](https://github.com/gabrielrosa09) e [Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.2`|15/11/2023|Adição das outras secções|[Gabriel Rosa](https://github.com/gabrielrosa09) e [Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.3`|15/11/2023|Adição dos Requisitos Funcionais|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira) e [Gabriel Rosa](https://github.com/gabrielrosa09)|[Lucas Ribeiro](https://github.com/lucassouzs)|
