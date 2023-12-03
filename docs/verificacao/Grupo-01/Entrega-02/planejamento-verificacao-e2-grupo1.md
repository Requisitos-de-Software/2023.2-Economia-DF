# Planejamento Verificação e Validação - Entrega 2

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

## Cronograma

A verificação será executada no período de 26/11/2023 a 30/11/2023, as atividades desenvolvidas nesse processo estão na Tabela 2.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Cronograma do planejamento da verificação dos artefatos </p></font>

<table>
<thead>
    <tr>
        <th>Data</th>
        <th>Descrição</th>
        <th>Responsável</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Planejamento da verificação</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a> e
        <a href="https://github.com/Lucas13032003">Lucas Victor</a> </td>
    </tr>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Verificação do artefato "100$"</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
        <td align="center">27/11/2023</td>
        <td>Verificação do artefato "Grupo de Foco"</td>
        <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
        <td align="center">27/11/2023</td>
        <td>Verificação do artefato "Brainstorming"</td>
        <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Verificação do artefato "First Thing First"</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Verificação do artefato "In or Out"</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
        <td align="center">27/11/2023</td>
        <td>Verificação do artefato "Introspecção"</td>
        <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Verificação do artefato "Observação"</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
        <td align="center">27/11/2023</td>
        <td>Verificação do artefato "Perfil de Usuário"</td>
        <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
        <td align="center">27/11/2023</td>
        <td>Verificação do artefato "Personas"</td>
        <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
        <td align="center">27/11/2023</td>
        <td>Verificação do artefato "Questionário"</td>
        <td align="center"><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Verificação do artefato "Requisitos Elicitados"</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
        <td align="center">26/11/2023</td>
        <td>Verificação do artefato "Requisitos Priorizados"</td>
        <td align="center"><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
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
    <tr align="center">
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>O artefato possui histórico de versão padronizado com pelo menos data, descrição, autores e revisores?</td>
      <td align="center">-</td>
      <td align="center">-</td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-1.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>As referências bibliográficas seguem a ordem de chamada do texto? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-1.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td>Todas as referências bibliográficas são chamadas no texto? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-1.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">5</td>
      <td>O artefato possui introdução? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-2.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td>Todas as tabelas possuem legendas e fontes padronizadas? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-4.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">7</td>
      <td>Todas as tabelas são referenciadas no texto? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-5.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">8</td>
      <td>Todas as figuras possuem legendas e fontes padronizadas e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.</td>
     <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-4.png?raw=true"></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Checklist de 100$

Na Tabela 4, estão listados os critérios que devem ser verificados no artefato [100$](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-priorizacao/100%24.md) do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Checklist para o artefato 100$</p></font>

<table>
  <thead>
    <tr>
      <th align="center">ID</th>
      <th align="center">Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>A prorização foi realizada em conjunto com um usuário real?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>O usuário que participou se enquadrava no perfil de usuário estabelecido?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>Os requisitos priorizados foram previamente elicitados?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td>Os requisitos priorizados passaram por algum processo de validação?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">5</td>
      <td>Os requisitos piorizados tinham ID identificando de qual técnica de elicitação eles eram provenientes?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td>Utilizou-se $100 para serem distribuidos entre os requisitos a fim de prioriza-los?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">7</td>
      <td>O processo de priorização levou em consideração a dependêcia entre requisitos?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">8</td>
      <td>Os requisitos foram, posteriormente, separados por nível de prioridade?</td>
      <td></td>
      <td></td>
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Checklist Grupo de Foco

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
      <td>Os objetivos do Grupo de Foco foram claramente definidos?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>A metodologia do Grupo de Foco foi adequada para traçar o perfil do usuário?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td>A agenda da reunião do Grupo de Foco foi comunicada antecipadamente e de forma clara?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Os membros do Grupo de Foco foram bem recrutados, representando adequadamente o público-alvo?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>5</td>
      <td>O roteiro da entrevista utilizado no Grupo de Foco abordou questões relevantes para a elaboração do perfil do usuário?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>6</td>
      <td>A condução da reunião foi imparcial e permitiu a expressão livre das opiniões dos participantes?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td>A documentação do Grupo de Foco, incluindo gravações, está completa e organizada?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td>As informações fornecidas pelos participantes do Grupo de Foco foram significativas e agregaram valor?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>9</td>
      <td>O documento final do Grupo de Foco reflete de maneira precisa as conclusões e sugestões dos participantes?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td>O link da gravação foi compartilhado de maneira acessível e compreensível?</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

### Checklist de Brainstorming


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
      <td>Os objetivos do Brainstorming foram claramente definidos?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Os participantes do Brainstorming foram selecionados considerando sua relevância para o tema?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td>A sessão de Brainstorming foi bem facilitada para encorajar a participação ativa?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Todas as ideias foram registradas sem julgamento durante a sessão de Brainstorming?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Foram exploradas diversas perspectivas e abordagens durante o Brainstorming?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>6</td>
      <td>A quantidade de tempo dedicada ao Brainstorming foi apropriada para a complexidade do problema?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td>O registro das ideias do Brainstorming é claro e compreensível?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td>As ideias geradas no Brainstorming foram avaliadas de forma eficaz para seleção das melhores?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>9</td>
      <td>O documento final do Brainstorming reflete as ideias prioritárias e decisões tomadas?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td>O Brainstorming contribuiu de maneira efetiva para a resolução do problema ou geração de novas ideias?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>11</td>
      <td>Os participantes do Brainstorming expressaram satisfação com o processo?</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>


### Checklist de First Thing First

Na Tabela 4, estão listados os critérios que devem ser verificados no artefato [First Things First](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-priorizacao/first-thing-first.md) do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Checklist para o artefato First Thing First</p></font>

<table>
  <thead>
    <tr>
      <th align="center">ID</th>
      <th align="center">Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>A técnica que foi utilizada para priorização é descrita? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%201.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>Os requisitos estão ordenados em ordem de prioridade? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%202.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>A fórmula para o cálculo do valor está correta? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%203.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td>A tabela possui os pesos relativos e sua justificativa? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%204.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">5</td>
      <td>Os requisitos são únicos e não se repetem? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%205.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td>Os representantes dos desenvolvedores estão participando na classificação dos custos e riscos? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%206.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">7</td>
      <td>Os cálculos estão corretos? [3]</td>
      <td>SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/FTF%20-%203.png?raw=true"></td>
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Checklist de In our Out

Na Tabela 4, estão listados os critérios que devem ser verificados no artefato [In our Out](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-priorizacao/in%20our%20out.md) do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Checklist para o artefato In our Out</p></font>

<table>
  <thead>
    <tr>
      <th align="center">ID</th>
      <th align="center">Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>É identificado a gravação e os registros da atividade de priorização dos requisitos?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>Os requisitos priorizados estão identificados por IDs?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>Um cronograma (data e horário) e local para realização da priorização dos requisitos com o do cliente e/ou persona do projeto?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td>Todos os requisitos elicitados tiveram sua prioridade definida? </td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">5</td>
      <td>Há um grupo de stakeholds? </td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td>O grupo definiou o critério de ser in or out?</td>
      <td></td>
      <td></td>
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Checklist de Introspecção

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato inclui um cronograma detalhado (data e horário) e local para a realização da elicitação dos requisitos?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Há registro da atividade de elicitação dos requisitos?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Os requisitos elicitados foram categorizados entre funcionais e não-funcionais?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Foi explicitado o motivo da escolha da técnica de elicitação? (Observação: A técnica é explicada, mas não o motivo de sua escolha.)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Considerou-se que a técnica pode não refletir totalmente a visão do usuário, dado que é conduzida por membros da equipe do projeto?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>6</td>
      <td>Cada membro que participou apresentou uma explicação detalhada sobre como executou a técnica?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td>Os requisitos elicitados foram identificados por meio de IDs?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td>Para cada requisito funcional, foi indicado se foi implementado ou não.?</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

### Checklist de Observação

Na Tabela 4, estão listados os critérios que devem ser verificados no artefato [Observação](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md) do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Checklist para o artefato Observação</p></font>

<table>
  <thead>
    <tr>
      <th align="center">ID</th>
      <th align="center">Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>Os objetivos da observação são estabelecidos? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%201.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>Os participantes são selecionados a partir do perfil de usuários? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%202.1.png?raw=true"> <img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%202.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>Eles possuem responsabilidades e competências necessárias para a observação do seu trabalho? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%202.1.png?raw=true"> <img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%202.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td>São apresentadas as atividades a serem observadas? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%204.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">5</td>
      <td>É definida a postura do observador? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%205.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td>É informado aos observados que eles não serão criticados e nem sofreram penalizações? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%206.png?raw=true"></td>
    </tr>
    <tr>
      <td align="center">7</td>
      <td>A observação foi realizada com mais de uma pessoa? [4]</td>
      <td>VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.</td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/OBS%20-%207.png?raw=true"></td>
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>


### Checklist Perfil de Usuário


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Checklist para Perrfil de Usuário da Entrega 2</p></font>

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
      <td>Foram utilizados estudos, como entrevistas ou questionários, para coletar dados para o perfil de usuário?</td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Os dados coletados foram agrupados por faixas e grupos nos quais os usuários se encaixam?</td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Foi elaborado um perfil de usuários com base nos dados agregados?</td>
      <td></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Existe uma proporção calculada para os usuários em cada perfil identificado?</td>
      <td></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Os usuários foram categorizados em grupos considerando idade, experiência, atitudes e tarefas primárias?</td>
      <td></td>
    </tr>
    <tr>
      <td>6</td>
      <td>O perfil de usuário identifica características relevantes?</td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td>O perfil de usuário inclui informações sobre cargos ocupados pelos usuários?</td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td>O perfil de usuário inclui informações sobre as atitudes desempenhadas pelos usuários?</td>
      <td></td>
    </tr>
    <tr>
      <td>9</td>
      <td>O perfil de usuário abrange informações sobre a experiência dos usuários?</td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td>O perfil de usuário inclui detalhes sobre o nível de instrução dos usuários?</td>
      <td></td>
    </tr>
    <tr>
      <td>11</td>
      <td>O perfil de usuário descreve as atividades principais dos usuários?</td>
      <td></td>
    </tr>
    <tr>
      <td>12</td>
      <td>O perfil de usuário considera a faixa etária dos usuários?</td>
      <td></td>
    </tr>
    <tr>
      <td>13</td>
      <td>O perfil de usuário avalia a relação dos usuários com a tecnologia?</td>
      <td></td>
    </tr>
    <tr>
      <td>14</td>
      <td>O perfil de usuário considera a relação dos usuários com o domínio do produto?</td>
      <td></td>
    </tr>
    <tr>
      <td>15</td>
      <td>O perfil de usuário avalia a relação dos usuários com as principais tarefas realizadas?</td>
      <td></td>
    </tr>
    <tr>
      <td>16</td>
      <td>As características identificadas nos perfis foram priorizadas?</td>
      <td></td>
    </tr>
    <tr>
      <td>17</td>
      <td>Foi designada uma responsabilidade específica para a elaboração do questionário?</td>
      <td></td>
    </tr>
    <tr>
      <td>18</td>
      <td>Foi estabelecido um cronograma para a elaboração do questionário?</td>
      <td></td>
    </tr>
    <tr>
      <td>19</td>
      <td>Foi definido um prazo para o preenchimento do questionário?</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div>

### Checklist de Personas


<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>As metodologias do texto definem de forma condizente as formas e os métodos que o grupo realizou o artefato?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>É informado o motivo de se ter personas no projeto?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td>É mostrado como as personas serão usadas no projeto?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>4</td>
      <td>A persona foi definida usando o perfil de usuário?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>5</td>
      <td>A persona é um personagem fictício?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>6</td>
      <td>A persona primária representa o público-alvo?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td>A persona apresenta as características esperadas?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td>A persona possui citações para melhor entendimento do que ela precisa?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>9</td>
      <td>A persona é bem detalhada?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td>Foi definido um elenco de personas?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>11</td>
      <td>É informado o porquê da quantidade de personas?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>12</td>
      <td>No texto, é explicitado a metodologia utilizada para a criação das personas?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>13</td>
      <td>Todas as personas foram descritas de modo pessoal, técnico e profissional?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>14</td>
      <td>Foram descritas as motivações de cada persona?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>15</td>
      <td>Houve algum registro de gravação no processo de criação das personas?</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>

### Checklist de Questionário

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>Foi informado o motivo da escolha do questionário?</td>
      <td align="center"></td>
      <td align="center"></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>Antes da elaboração do questionário, foi feito um estudo para decidir as perguntas?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">3</td>
      <td>O questionário apresenta um termo de consentimento onde a pessoa permite a utilização das informações que ira fornecer?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">4</td>
      <td>O questionário apresenta mais perguntas fechadas do que perguntas abertas?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">5</td>
      <td>Os resultados foram tratados e apresentados?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">6</td>
      <td>O perfil de usuário apresenta os pontos principais requisitados?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">7</td>
      <td>É explicado no artefato como o questionário será utilizado?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">8</td>
      <td>As perguntas apresentam alguma ordem ou padrão estratégico?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">9</td>
      <td>Apresenta no texto os locais onde o questionário foi distribuído?	</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">10</td>
      <td>Apresenta no texto o prazo em que ficou aberto?</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
    <tr>
      <td align="center">11</td>
      <td>Houve o cuidado para não haver perguntas pessoais ou evasivas?	</td>
      <td align="center"></td>
      <td align="center"></td>  
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div>


### Checklist de Requisitos Elicitados

Na Tabela 4, estão listados os critérios que devem ser verificados no artefato [Requisitos Elicitados](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md) do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Checklist para o artefato Requisitos Elicitados</p></font>

<table>
  <thead>
    <tr align="center">
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>Existem uma introdução condizente com o conteúdo apresentado no artefato?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>Os requisitos foram diferenciados entre "Funcionais" e "Não Funcionais"?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>Nos requisitos elicitados, mostram como eles foram elicitados?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td>É mostrado se os requisitos já são implementados ou não?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">5</td>
      <td>Os requisitos elicitados estão classificados e organizados corretamente?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td>Todos os requisitos possuem uma rastreabilidade mínimo?</td>
      <td></td>
      <td></td>
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Checklist de Requisitos Priorizados

Na Tabela 4, estão listados os critérios que devem ser verificados no artefato [Requisitos Priorizados](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos_priorizados.md) do [Grupo 1](https://requisitos-de-software.github.io/2023.2-Economia-DF/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Checklist para o artefato Requisitos Priorizados</p></font>

<table>
  <thead>
    <tr>
      <th align="center">ID</th>
      <th align="center">Descrição</th>
      <th align="center">Fonte</th>
      <th align="center">Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td>Existem uma introdução condizente com o conteúdo apresentado no artefato?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td>No artefato, é mostrado as 3 técnicas de priorização que serão utilizadas pelo grupo?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td>Existe um link para cada técnica em si?</td>
      <td></td>
      <td></td>
    </tr>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

## Referências Bibliográficas

> [1] FAGAN, Michael E. Design and Code Inspections to Reduce Errors in Program Development. 1976.
>
> [2] Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 18 de novembro de 2023.
>
> [3] SERRANO, Milene. Requisitos - Aula 07. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: Requisitos - Aula 07. Acesso em: 29 de novembro de 2023.
>
> [4] VAZQUEZ, Carlos Eduardo. SIMÕES, Guilherme Siqueira. ENGENHARIA DE REQUISITOS - SOFTWARE ORIENTADO AO NEGÓCIO. Disponível em: Requisitos - Engenharia de Requisitos. Acesso em: 29 de novembro de 2023.

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
