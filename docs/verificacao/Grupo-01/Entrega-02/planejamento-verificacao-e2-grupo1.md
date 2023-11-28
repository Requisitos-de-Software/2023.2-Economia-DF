# Verificação e Validação - Entrega 2

## Introdução

A Verificação e Validação (V&V) são etapas cruciais no desenvolvimento de software, desempenhando um papel fundamental na garantia da qualidade e confiabilidade dos artefatos produzidos. Nesse contexto, a verificação refere-se à avaliação sistemática dos artefatos de software para assegurar sua conformidade com os requisitos e padrões especificados. Este documento visa realizar a verificação da entrega 2 realizada pelo [Grupo 1](https://github.com/Requisitos-de-Software/2023.2-Economia-DF.git) na disciplina de Requisitos de Software. O projeto em questão trata-se do desenvolvimento da verificação do aplicativo "Economia DF". Este processo de verificação visa garantir que a entrega 2 atenda aos padrões estabelecidos, assegurando a qualidade do produto em desenvolvimento. 

## Objetivos 

O propósito deste documento é realizar uma verificação minuciosa dos artefatos desenvolvidos pelo [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/) durante a etapa 2, que abrange o tema Modelagem de Requisitos. O objetivo é assegurar que esses artefatos estejam em plena conformidade com os requisitos estabelecidos na disciplina de Requisitos de Software, bem como em alinhamento com os padrões consagrados na literatura especializada nesse campo. Essa análise visa garantir a qualidade e a aderência às melhores práticas, contribuindo para o desenvolvimento de artefatos ainda melhores para o projeto.

## Metodologia

A metodologia que será utilizada na verificação dos artefatos do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/) é a de Inspeção, desenvolvida por Michael E. Fagan [1], que é uma abordagem estruturada para revisão de código e outros artefatos de software. Essa metodologia tem como objetivo identificar e corrigir defeitos de forma eficiente durante o processo de desenvolvimento. A inspeção por Fagan é conhecida por sua abordagem sistemática e rigorosa, enfocando a detecção precoce de erros para melhorar a qualidade do software.

Este método pode ser dividido em 5 etapas:

- **Preparação:** antes da reunião de inspeção, o autor do artefato (por exemplo, código-fonte) prepara um documento contendo o artefato a ser revisado, além de informações sobre seu contexto e propósito.

- **Inspeção Individual:** os participantes (inspetores) revisam o documento individualmente antes da reunião de inspeção. Cada inspetor concentra-se na identificação de erros, como bugs, inconsistências ou violações de padrões de codificação.

- **Reunião de Inspeção:** durante a reunião, os inspetores se reúnem com o autor para discutir os problemas identificados. O autor não participa ativamente da inspeção durante a fase individual, permitindo uma revisão mais imparcial.

- **Correção e Reinspeção:** o autor corrige os problemas identificados durante a reunião de inspeção. Em seguida, o artefato é reinspecionado para garantir que as correções foram efetuadas adequadamente.

- **Acompanhamento:** a metodologia de Fagan enfatiza a coleta de métricas e dados sobre o processo de inspeção. Isso inclui a contagem de defeitos encontrados, tempo gasto e eficácia geral do processo.

Nesta verificação, chegaremos até a etapa de Correção e Reinspeção, pois, após a verificação dos artefatos produzidos, os erros encontrados serão devidamente corrigidos.

## Participantes

Os integrantes do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/) responsáveis por fazer a verificação da Entrega 2 do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/) são [Lucas Ribeiro](https://github.com/lucassouzs) e [Lucas Victor](https://github.com/Lucas13032003). Estes participantes farão a verificação de todos os documentos produzidos na Entrega 2 e documentarão os resultados encontrados, que serão revisados pelo [Lucas Oliveira](https://github.com/), também integrante do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/). Além disso, os integrantes [Gabriel Zaranza](https://github.com/GZaranza) e [Gabriel Rosa](https://github.com/gabrielrosa09), também do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/), participarão da verificação como observadores, auxiliando na identificação de erros e na documentação dos resultados.

## Objetos de Verificação

A Tabela 1 apresenta os artefatos que serão inspecionados durante o processo de verificação da Entrega 2 do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/). Nela, estão listados os critérios que devem ser verificados em todos os artefatos, garantindo uma análise abrangente e eficiente.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Tabela de Artefatos </p></font>

<table>
  <thead>
      <tr align="center">
          <th>Artefato</th>
          <th>Versão</th>
          <th>Data</th>
          <th>Autor(es)</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td>100$</td>
          <td align="center">1.2</td>
          <td align="center">02/10/2023</td>
          <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
      </tr>
      <tr>
          <td>Grupo de Foco</td>
          <td align="center">1.1</td>
          <td align="center">02/10/2023</td>
          <td align="center"><a href="https://github.com/gabrielrosa09">Gabriel Rosa</a></td>
      </tr>
      <tr>
          <td>Brainstorming</td>
          <td align="center">1.3</td>
          <td align="center">08/11/2023</td>
          <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
      </tr>
      <tr>
          <td>First Thing First</td>
          <td align="center">1.1</td>
          <td align="center">02/10/2023</td>
          <td align="center"><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
      </tr>
          <tr>
          <td>In our Out</td>
          <td align="center">1.3</td>
          <td align="center">20/10/2023</td>
          <td align="center"><a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a></td>
      </tr>
      <tr>
          <td>Introspecção</td>
          <td align="center">1.0</td>
          <td align="center">21/10/2023</td>
          <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
      </tr>
      <tr>
          <td>Observação</td>
          <td align="center">1.5</td>
          <td align="center">29/10/2023</td>
          <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
      </tr>
      <tr>
          <td>Perfil de Usuário</td>
          <td align="center">1.3</td>
          <td align="center">30/09/2023</td>
          <td align="center"><a href="https://github.com/GZaranza">Gabriel Zaranza</a></td>
      </tr>
      <tr>
          <td>Personas</td>
          <td align="center">1.7</td>
          <td align="center">29/10/2023</td>
          <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
      </tr>
      <tr>
          <td>Questionário</td>
          <td align="center">1.1</td>
          <td align="center">12/11/2023</td>
          <td align="center"><a href="https://github.com/GZaranza">Gabriel Zaranza</a></td>
      </tr>
      <tr>
          <td>Requisitos Elicitados</td>
          <td align="center">2.0</td>
          <td align="center">29/10/2023</td>
          <td align="center"><a href="https://github.com/izabellaalves">Izabella Alves</a></td>
      </tr>
      <tr>
          <td>Requisitos Priorizados</td>
          <td align="center">1.1</td>
          <td align="center">01/10/2023</td>
          <td align="center"><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
      </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

## Checklists

Nesta etapa, será definido um checklist de verificação geral, que deve ser aplicado a todos os artefatos, e um checklist específico para cada artefato. As questões disponíveis no checklist devem ser respondidas com Sim, Não, Incompleto ou Não Se Aplica.

Além disso, as observações devem ser registradas após a tabela, indicando o ID respectivo que gerou a observação.

Os checklists criados se baseiam nos critérios estabelecidos na bibliografia recomendada, no Plano de Ensino da disciplina Requisitos de Software, bem como na observação dos projetos dos semestres anteriores e dos feedbacks dados pelos monitores e pelo Professor após as apresentações.

## Checklist Geral

Na Tabela 2, estão listados os critérios que devem ser verificados em todos os artefatos da Entrega 2 do Grupo 2.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Checklist para todos os artefatos da Entrega 3</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui histórico de versão padronizado com pelo menos data, descrição, autores e revisores?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-1.png"></td>
    </tr>
    <tr>
      <td>3</td>
      <td>As referências bibliográficas seguem a ordem de chamada do texto? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-1.png"></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Todas as referências bibliográficas são chamadas no texto? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-1.png"></td>
    </tr>
    <tr>
      <td>5</td>
      <td>O artefato possui introdução? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-2.png"></td>
    </tr>
    <tr>
      <td>6</td>
      <td>Todas as tabelas possuem legendas e fontes padronizadas? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-4.png"></td>
    </tr>
    <tr>
      <td>7</td>
      <td>Todas as tabelas são referenciadas no texto? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-5.png"></td>
    </tr>
    <tr>
      <td>8</td>
      <td>Todas as figuras possuem legendas e fontes padronizadas e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
     <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/28f4bf83826a500e0f301aecac8a1e1511aff0ff/docs/imagens/e3-4.png"></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>


## Bibliografia

>
> Bilheteria Digital. Planejamento da Verificação da Entrega 3 do Grupo 2. Grupo Bilheteria Digital da disciplina Requisitos de Software, disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega3/planejamento-verificacao-e3-grupo2/>. Acesso em: 09 de novembro de 2023.
>
> Artefato: Especificações Suplementares. Centro de Informática - UFPE. Disponível em: <https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>. Acesso em: 09 de novembro de 2023.
>

## Histórico de Versões

| Versão | Data   | Descrição     | Autor     |  Revisor        |
| :----: | ------ | ------------- | --------- | :-------------: |
| `1.0`  | 26/11/2023 | Criação do documento  | [Lucas Víctor](https://github.com/Lucas13032003)| [Lucas Oliveira](https://github.com/) |
| `1.1`  | 28/11/2023 | Ajustes do documento    | [Lucas Ribeiro](https://github.com/lucassouzs)| [Lucas Oliveira](https://github.com/) |
