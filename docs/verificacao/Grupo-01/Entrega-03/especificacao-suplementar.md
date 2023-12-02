# Verificação do artefato "Especificação Suplementar"

## Introdução

Este documento tem como objetivo relatar os resultados da verificação por inspeção do artefato "[Especificação Suplementar](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#historico-de-versoes)" elaborado pelo [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/) na disciplina de Requisitos de Software. Será analisado o documento feito pelos integrantes do grupo em sua última versão, 1.9, de 05/11/2023.

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
      <td>Não se aplica</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a> e <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

### Checklist Específico

Na tabela 2, encontram-se os resultados obtidos na verificação do checklist específico do artefato em estudo.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8:</b> Checklist para o artefato de Especificação Suplementar</p></font>

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
      <td>O artefato contém a especificação suplementar?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>2</td>
      <td>A especificação suplementar segue o modelo FURPS+? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>3</td>
      <td>O artefato possui um tópico de Funcionalidade? Ele contém requisitos testáveis? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>4</td>
      <td>O artefato possui um tópico de Usabilidade? Ele contém requisitos testáveis? [3]</td>
      <td>Incompleto</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Os requisitos apresentados facilitam as tarefas realizadas pelos usuários? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>6</td>
      <td>O artefato possui um tópico de Confiabilidade? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Os requisitos apresentados aumentam a confiabilidade do sistema? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>8</td>
      <td>O artefato especifica o Tempo Médio entre Falhas (MTBF)? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>9</td>
      <td>O artefato especifica o Tempo Médio para Reparo (MTTR)? [9]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Os requisitos relacionados à segurança são apresentados? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>11</td>
      <td>O artefato possui um tópico de Desempenho? Ele contém requisitos testáveis? [3] </td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>12</td>
      <td>Os requisitos sobre os tempos de respostas são apresentados com esses respectivos tempos especificados? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
    <tr>
      <td>13</td>
      <td>Os requisitos sobre a disponibilidade são apresentados? [3]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>14</td>
      <td>O artefato possui um tópico de Suportabilidade? Ele contém requisitos testáveis? [3]</td>
      <td>Incompleto</td>
    </tr>
    <tr>
      <td>15</td>
      <td>É apresentado os sistemas operacionais que o sistema funcionará? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>16</td>
      <td>O artefato possui um tópico de Restrições de Design? Ele contém requisitos testáveis? [4]</td>
      <td>Incompleto</td>
    </tr>
    <tr>
      <td>17</td>
      <td>As características físicas de onde o sistema funcionará são apresentadas? [4]</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>18</td>
      <td>O artefato especifica qual plataforma o aplicativo pode ser executado? [4]</td>
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

- **ID 04:** O artefato possui o tópico usabilidade, porém, alguns requisitos não estão quantificáveis, portanto, não são testáveis.
    - **Correção:** Os requisitos não quantificáveis foram reescritos para que se tornassem quantificáveis.

- **ID 14:** O artefato possui o tópico suportabilidade, porém, não apresenta requisitos, e sim, descreve o funcionamento do aplicativo.
    - **Correção:** Foi incluído no tópico de "suportabilidade" uma tabela com requisitos de suportabilidade.

- **ID 16:** O artefato possui o tópico restrições de design, porém, a apresentação dos requisitos é muito fraca e descontextualizada.
    - **Correção:** O tópico restrições de design foi reescrito para que os requisitos ficassem mais claros e objetivos.


## Resultados

Nesta seção, serão apresentados os resultados obtidos na verificação do artefato "[Especificação Suplementar](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#historico-de-versoes)" na forma de um gráfico de pizza, onde são apresentadas a quantidade de "sim", "não" e "não se aplica" obtidos na verificação.

### Checklist geral

No gráfico 1, é possível visualizar os resultados obtidos na verificação do artefato "[Especificação Suplementar](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#historico-de-versoes)" em relação ao checklist geral.

<div align="center">
  <p><b>Gráfico 1:</b> Resultados da verificação checklist geral.</p>

  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/4b83314700c4acdd7c72cc214a8d9c8f366a2bb2/docs/imagens/verifcacao-ce-uc.png?raw=true" style="width: 45%;">

<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

### Checklist específico

No gráfico 2, é possível visualizar os resultados obtidos na verificação do artefato "[Especificação Suplementar](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#historico-de-versoes)" em relação ao checklist específico.

<div align="center">
  <p><b>Gráfico 2:</b> Resultados da verificação do checklist específico.</p>

  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/e4e4d1a2ae5ad15fafd811b59ec8e07819619aa0/docs/imagens/verifcacao-ce-es.png?raw=true" style="width: 45%;">

<p><b>Fonte:</b> Izabella Alves, 2023.</p>

</div>

## Referências Bibliográficas

> [1] ALVES, Izabella; VIEIRA, Zenilda. [Planejamento da Verificação da Etapa 3 do Grupo 1](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/verificacao/Grupo-01/Entrega-03/planejamento-verificacao-e3-grupo1.md), GAMA, FGA, 2023. Acesso em: 22 de novembro de 2023.
> 
> [2] Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.
>
> [3] SERRANO, et al. Requisitos - Aula 13. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Acesso em 18 de novembro 2023.
>
> [4] WORLD WIDE WEB CONSORTIUM. WCAG 2.0: Web Content Accessibility Guidelines. Versão 2.0. World Wide Web Consortium, 2008. Disponível em: https://www.w3.org/WAI/WCAG21/quickref/. Acesso em: 18 de novembro de 2023.

## Bibliografia

> Economia-DF. [Especificação Suplementar](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#historico-de-versoes), FGA, GAMA, 2023. Acesso em: 22 de novembro de 2023.
> 

## Histórico de Versões

| Versão | Data   | Descrição     | Autor     |  Revisor        |
| :----: | ------ | ------------- | --------- | :-------------: |
| `1.0`  | 26/11/2023 | Criação do documento  | [Izabella Alves](https://github.com/izabellaalves) | [Zenilda Vieira](https://github.com/zenildavieira)|