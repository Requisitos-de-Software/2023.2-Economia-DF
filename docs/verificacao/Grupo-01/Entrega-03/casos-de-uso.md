# Verificação do artefato "Casos de Uso"

## Introdução

Este documento tem como objetivo relatar os resultados da verificação por inspeção do artefato "[Casos de Uso](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/)" elaborado pelo [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/) na disciplina de Requisitos de Software. Será analisado o documento feito pelos integrantes do grupo em sua última versão, 1.14, de 22/10/2023.

## Metodologia

A metodologia e o planejamento da verificação desse artefato foram definidos no documento de [Planejamento da Verificação da Etapa 3 do Grupo 1](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/verificacao/Grupo-01/Entrega-03/planejamento-verificacao-e3-grupo1.md) [1].

A abordagem adotada neste documento consiste em uma inspeção por meio de checklist. Cada elemento do checklist será analisado, e caso seja identificada alguma divergência, ela será devidamente documentada na seção destinada aos problemas encontrados. No total, serão empregados dois tipos de checklists: um de caráter abrangente, que foi destinado a todos os artefatos do planejamento da verificação, e outro específico, direcionado exclusivamente a esse artefato em foco.

## Apresentação dos dados

Os resultados obtidos são apresentados a seguir nas tabelas 1 e 2. Cada item verififcado foi respondido com "Sim", "Não", "Incompleto" ou "Não Se Aplica". Quando necessário, foram feitas observações no tópico Problemas Encontrados mais adiante.

### Checklist Geral

Na tabela 1, encontram-se os resultados obtidos na verificação do checklist geral do artefato em estudo.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Checklist para todos os artefatos da Entrega 3</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Avaliação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui histórico de versão padronizado com pelo menos data, descrição, autores e revisores?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>2</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica? [2] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>3</td>
      <td>As referências bibliográficas seguem a ordem de chamada do texto? [2]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Todas as referências bibliográficas são chamadas no texto? [2]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>5</td>
      <td>O artefato possui introdução? [2]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Todas as tabelas possuem legendas e fontes padronizadas? [2]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Todas as tabelas são referenciadas no texto? [2] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Todas as figuras possuem legendas e fontes padronizadas e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>9</td>
      <td>Todas as figuras são referenciadas no texto e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td>Sim</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a> e <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

### Checklist Específico

Na tabela 2, encontram-se os resultados obtidos na verificação do checklist específico do artefato em estudo.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Checklist para o artefato de Casos de Uso</p></font>


<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Avaliação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui um diagrama de casos de uso?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>2</td>
      <td>O artefato cita a técnica utilizada para elaboração do diagrama de caso de uso do projeto?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>3</td>
      <td>O diagrama de caso de uso possui os atores principais e atores secundários? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>4</td>
      <td>O ator principal está do lado esquerdo do sistema no diagrama de caso de uso? [5]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Os atores estão fora da caixa de limite do sistema no diagrama de caso de uso? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>8</td>
      <td>No diagrama de Caso de Uso há pontos de extensão corretamente representados? [5]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>9</td>
      <td>As elipses do diagrama representam ações com o uso de verbos no infinitivo e não substantivos? [4] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>10</td>
      <td>No diagrama há relacionamentos de extend, include e generalization? [4] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>11</td>
      <td>O nome do ator principal condiz com o usuário associado a ele?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>12</td>
      <td>Quando o ator é um software ou um hardware, há a tag << system >>? [5]</td>
      <td>Não se aplica</td>
    </tr>
    <tr>
      <td>13</td>
      <td>O artefato possui a especificação de cada caso de uso?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>14</td>
      <td>Cada caso de uso é uma funcionalidade completa (requisito funcional) que fornece um resultado observável e de valor para os atores ou stakeholders? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>15</td>
      <td>A especificação dos casos de uso consistem no detalhamento de execução dos casos de uso?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>16</td>
      <td>Os elementos de atores, sistema e metas estão presentes nos casos de uso? [4] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>17</td>
      <td>A especificação de cada caso de uso possui: nome, descrição, atores, pré-condição, pós-condição? [6] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>18</td>
      <td>Existem fluxos como: principal, alternativo e de exceção? [4] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>19</td>
      <td>Cada especificação de caso uso tem somente um fluxo principal que representa como o usuário usaria a funcionalidade de forma primária? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>20</td>
      <td>Os fluxos alternativos são possibilidades de caminhos alternativos ao fluxo principal? [4] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>21</td>
      <td>Os fluxos de exceção demonstram como o sistema reagirá na presença de situações incomuns ou anormais? [4] </td>
      <td>Sim</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a> e <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

## Problemas encontrados


### Checklist geral

Nenhum problema encontrado no checklist geral.

### Checklist Específico

Nenhum problema encontrado no checklist específico.

## Resultados

Nesta seção, serão apresentados os resultados obtidos na verificação do artefato "[Casos de Uso](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/)" na forma de um gráfico de pizza, onde são apresentadas a quantidade de "sim", "não" e "não se aplica" obtidos na verificação.

### Checklist geral

No gráfico 1, é possível visualizar os resultados obtidos na verificação do artefato "[Casos de Uso](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/)" em relação ao checklist geral.

<div align="center">
  <p><b>Gráfico 1:</b> Resultados da verificação checklist geral.</p>

  <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-NotaLegal/edaeec4238fa1a5e61228479cda753242f031de7/docs/imagens/verifcacao-ce-storyboard.png" style="width: 45%;">

<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

### Checklist específico

No gráfico 2, é possível visualizar os resultados obtidos na verificação do artefato "[Casos de Uso](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/)" em relação ao checklist específico.

<div align="center">
  <p><b>Gráfico 2:</b> Resultados da verificação do checklist específico.</p>

  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/4b83314700c4acdd7c72cc214a8d9c8f366a2bb2/docs/imagens/verifcacao-ce-uc.png" style="width: 45%;">

<p><b>Fonte:</b> Izabella Alves, 2023.</p>

</div>

## Referências Bibliográficas

> [1] ALVES, Izabella; VIEIRA, Zenilda. [Planejamento da Verificação da Etapa 3 do Grupo 1](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/verificacao/Grupo-01/Entrega-03/planejamento-verificacao-e3-grupo1.md), GAMA, FGA, 2023. Acesso em: 22 de novembro de 2023.
> 
> [2] Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.
>
> [3] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> [4] SERRANO, Maurício. SERRANO, Milene. Slide “Requisitos - Aula 13”. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Acesso em: 18 de novembro de 2023.
>
> [5] Lucid Software Português. Tutorial de Caso de Uso UML [Recurso eletrônico: vídeo], 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 18 de novembro 2023.
>
> [6] REINEHR, Sheila. Engenharia de requisitos. Porto Alegre: Grupo A, 2020. E-book. ISBN 9786556900674. Disponível em: https://integrada.minhabiblioteca.com.br/#/books/9786556900674/. Acesso em: 18 novembro 2023.

## Bibliografia

> Economia-DF. [Casos de Uso](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/), FGA, GAMA, 2023. Acesso em: 22 de novembro de 2023.
> 

## Histórico de Versões

| Versão | Data   | Descrição     | Autor     |  Revisor        |
| :----: | ------ | ------------- | --------- | :-------------: |
| `1.0`  | 26/11/2023 | Criação do documento  | [Izabella Alves](https://github.com/izabellaalves) | [Zenilda Vieira](https://github.com/zenildavieira)|