# Forward from

## Introdução

Esse documento aborda a aplicação do método de rastreabilidade forward-from. A rastreabilidade de requisitos desempenha um papel crucial no desenvolvimento de sistemas. Ela permite não apenas identificar e conectar requisitos durante a fase de desenvolvimento, mas também rastreá-los ao longo de todo o ciclo de vida do sistema. Isso se traduz em uma compreensão mais clara das origens e implicações de cada requisito, contribuindo para a garantia da qualidade, gestão eficiente de mudanças e alinhamento contínuo com as necessidades do cliente. Quando aplicamos o método de rastreabilidade forward-from, estamos focados em estabelecer vínculos sólidos entre os requisitos e os desenhos do sistema e implementações [1].

## Metodologia

A metodologia a ser usada será a matriz de rastreabilidade com o uso de referências cruzadas [1], aplicada aos [requisitos elicitados](https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/) e os artefatos desenvolvidos após o processo de elicitação nas etapas [modelagem de requisitos](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/) e [ágil](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/). A relação entre um requisito e um tipo de artefato não é da ordem de um para um, por exemplo, um requisito pode estar presente em mais de um caso de uso. A tabela 1 representa a matriz de rastreabilidade em que as linhas representam os requisitos e cada coluna representa o artefato criado a partir do requisito.

Os requisitos podem estar ligados a épicos, temas, histórias do usuário, léxicos, casos de usos, cenários, especificação suplementar e NFR Framework. Esses artefatos serão representados nas colunas da matriz de rastreabilidade e são preenchidas com o id/nome do artefato.

Na execução da rastreabilidade dos elos, utilizamos o meta-modelo proposto por Toranzo. Esse meta-modelo classifica os requisitos elicitados pelo grupo em níveis e elos. Com base no slide 19 da [aula 26](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da professora Milene Serrano [2], os níveis são:

- **_Ambiental_**: Essas informações provêm do ambiente e contexto nos quais a organização está inserida.
- **_Organizacional_**: São dados relacionados à própria organização.
- **_Gerencial_**: Engloba informações que auxiliam na gestão do projeto.
- **_Desenvolvimento_**: Refere-se às informações associadas aos diversos artefatos gerados durante o processo de desenvolvimento.

Com base no slide 21 da [aula 26](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da professora Milene Serrano [2], os principais **elos de rastreabilidade** são os seguintes:

1. **Satisfação**: Indica que a classe de origem depende da satisfação proporcionada pela classe de destino.
2. **Recurso**: Reflete a dependência de recursos da classe de origem em relação à classe de destino.
3. **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre os artefatos.
4. **Representação**: Captura a forma como os requisitos são representados ou modelados em outras linguagens.
5. **Alocado**: Relaciona a classe de origem a uma classe de destino que representa um subsistema.
6. **Agregação**: Indica a "composição" de elementos.

Para auxiliar na criação do meta-modelo de Toranzo, foram elaboradas as tabelas 1 e 2 a seguir.

## Matriz de rastreabilidade Forward-From

A tabela 1 representa a matriz de rastreabilidade em que as linhas representam os requisitos e cada coluna representa o artefato criado a partir do requisito.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Matriz de rastreabilidade Forward-from</p></font>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Tipo</th>
      <th>Implementado</th>
      <th>Épico</th>
      <th>Tema</th>
      <th>História de<br>usuário</th>
      <th>Léxico</th>
      <th>Caso de<br>Uso</th>
      <th>Cenário</th>
      <th>Especificação<br>Suplementar</th>
      <th>NFR<br>Framework</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>INT01</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs01---efetuar-login-com-email-e-senha">HS01</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#r-confiabilidade-reliability">R</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr02---confiabilidade-reliability">NFR02</a></td>
    </tr>
    <tr>
      <td>INT02</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs02-hs02---efetuar-login-com-govbr">HS02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a>, 
      <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#r-confiabilidade-reliability">R</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr02---confiabilidade-reliability">NFR02</a></td>
    </tr>
    <tr>
      <td>INT03</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs03-hs03---recuperar-senha">HS03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr04---suporte">NFR04</a></td>
    </tr>
    <tr>
      <td>INT04</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs04---efetuar-logout">HS04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT05</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs05---listar">HS05</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfe">L07</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfce">L08</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#bpe">L09</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen04---consultar-notas-fiscais">CEN04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT06</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs06---pesquisar">HS06</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfe">L07</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfce">L08</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#bpe">L09</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#consultar">L12</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen04---consultar-notas-fiscais">CEN04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT07</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs07---visualizar-detalhes">HS07</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfe">L07</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfce">L08</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#bpe">L09</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#visualizar">L17</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc06-visualizar-nfc-e-detalhada">UC06</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen04---consultar-notas-fiscais">CEN04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT08</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs08---imprimir-danfe">HS08</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfe">L07</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#nfce">L08</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#bpe">L09</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#danfe">L11</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#danfe">L13</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc05-imprimir-danfe">UC05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen04---consultar-notas-fiscais">CEN04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT09</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#cadastrar">L14</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc12-cadastrar-ve%C3%ADculo">UC12</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT10</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#consultar">L12</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc11-consultar-ve%C3%ADculo">UC11</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT11</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs10---consultar-d%C3%A9bitos-de-ipva">HS10</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT12</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar">HS11</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>,
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#dar">L10</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#danfe">L13</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT13</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar">HS12</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#cadastrar">L14</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc10-cadastro-im%C3%B3vel">UC10</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen03---consultar-im%C3%B3veis">CEN03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT14</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar">HS12</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#consultar">L12</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc09-consultar-im%C3%B3vel">UC09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen03---consultar-im%C3%B3veis">CEN03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT15</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs13---consultar-d%C3%A9bitos-de-iptutlp">HS13</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen03---consultar-im%C3%B3veis">CEN03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT16</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep07---parcelamentos-administrativos">EP07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos">HS14</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen06---consultar-parcelamentos-administrativos">CEN06</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT17</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep05---d%C3%ADvida-ativa">EP05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos">HS14</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#consultar">L12</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#dividaativa">L19</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc07-consultar-divida-ativa">UC07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen01---consultar-d%C3%ADvida-ativa">CEN01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT18</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep05---d%C3%ADvida-ativa">EP05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar">HS11</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#dar">L10</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#dividaativa">L19</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen01---consultar-d%C3%ADvida-ativa">CEN01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT19</td>
      <td>RF</td>
      <td>Sim</td>
       <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep07---parcelamentos-administrativos">EP07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos">HS14</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#consultar">L12</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen06---consultar-parcelamentos-administrativos">CEN06</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT20</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep08---fale-conosco">EP08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T04</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs15---enviar-email">HS15</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc14-entrar-em-contato">UC14</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc15-enviar-e-mail">UC15</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen07---fale-conosco">CEN07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
     </tr>
    <tr>
      <td>INT21</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep09---ajuda">EP09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T04</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs16---visualizar-informa%C3%A7%C3%B5es-sobre-o-aplicativo">HS16</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc13-consultar-ajuda">UC13</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#-ajuda-e-documenta%C3%A7%C3%A3o">+AD</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr06---ajuda-e-documenta%C3%A7%C3%A3o">NFR06</a></td>
    </tr>
    <tr>
      <td>INT22</td>
      <td>RF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#saldo">L05</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#consultar">L12</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT23</td>
      <td>RF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#saldo">L05</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT24</td>
      <td>RNF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs04---efetuar-logout">HS04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#r-confiabilidade-reliability">R</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr02---confiabilidade-reliability">NFR02</a></td>
    </tr>
    <tr>
      <td>INT25</td>
      <td>RF</td>
      <td>Sim</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs02-hs02---efetuar-login-com-govbr">HS02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a>, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#r-confiabilidade-reliability">R</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr02---confiabilidade-reliability">NFR02</a></td>
    </tr>
    <tr>
      <td>INT26</td>
      <td>RF</td>
      <td>Não</td>
      <td></td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a></td>
      <td></td>
      <td></td>
      <td>
        <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a>, 
        <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#u-usabilidade-usability">U</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
    </tr>
    <tr>
      <td>INT27</td>
      <td>RNF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#cadastrar">L14</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc12-cadastrar-ve%C3%ADculo">UC12</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#u-usabilidade-usability">U</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
    </tr>
    <tr>
      <td>INT28</td>
      <td>RNF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#cadastrar">L14</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc12-cadastrar-ve%C3%ADculo">UC12</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#u-usabilidade-usability">U</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
    </tr>
    <tr>
      <td>INT29</td>
      <td>RNF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar">HS12</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#cadastrar">L14</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc10-cadastro-im%C3%B3vel">UC10</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen03---consultar-im%C3%B3veis">CEN03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#u-usabilidade-usability">U</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
    </tr>
    <tr>
      <td>INT30</td>
      <td>RF</td>
      <td>Não</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep05---d%C3%ADvida-ativa">EP05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar">HS11</a></td>
      <td>
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#usuario">L03</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#emitir">L13</a>, 
          <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#dividaativa">L19</a>
      </td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen01---consultar-d%C3%ADvida-ativa">CEN01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#f-funcionalidade-functionality">F</a></td>
      <td></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Elos

A tabela 2 mostra os elos entre os requisitos elicitados e os artefatos definidos nos forward-from.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Matriz de rastreabilidade Forward-from</p></font>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>INT01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs01---efetuar-login-com-email-e-senha">HS01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT02<br>INT03</td>
    </tr>
    <tr>
      <td>INT02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs02-hs02---efetuar-login-com-govbr">HS02</a</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT01</td>
    </tr>
    <tr>
      <td>INT03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs03-hs03---recuperar-senha">HS03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT01</td>
    </tr>
    <tr>
      <td>INT04</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs04---efetuar-logout">HS04</a></td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT05</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs05---listar">HS05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen04---consultar-notas-fiscais">CEN04</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT06<br>INT07<br>INT08</td>
    </tr>
    <tr>
      <td>INT06</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs06---pesquisar">HS06</a</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a><br></a><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT05</td>
    </tr>
    <tr>
      <td>INT07</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs07---visualizar-detalhes">HS07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a><br></a><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT05</td>
    </tr>
    <tr>
      <td>INT08</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs08---imprimir-danfe">HS08</a></a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#notafiscal">L01</a><br></a><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc04-consultar-notas-fiscais">UC04</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT05</td>
    </tr>
    <tr>
      <td>INT09</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT10<br>INT11<br></td>
    </tr>
    <tr>
      <td>INT10</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen02---consultar-ve%C3%ADculos">CEN02</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc11-consultar-ve%C3%ADculo">UC11</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT09</td>
    </tr>
    <tr>
      <td>INT11</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs10---consultar-d%C3%A9bitos-de-ipva">HS10</a</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#veiculo">L02</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT09</td>
    </tr>
    <tr>
      <td>INT12</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar">HS11</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT13</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar">HS12</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen03---consultar-im%C3%B3veis">CEN03</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc10-cadastro-im%C3%B3vel">UC10</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT14<br>INT15<br>INT29</td>
    </tr>
    <tr>
      <td>INT14</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar">HS12</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc09-consultar-im%C3%B3vel">UC09</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT13</td>
    </tr>
    <tr>
      <td>INT15</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs13---consultar-d%C3%A9bitos-de-iptutlp">HS13</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#imovel">L04</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT13</td>
    </tr>
    <tr>
      <td>INT16</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos">HS14</a></td>
      <td></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT17</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos">HS14</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen01---consultar-d%C3%ADvida-ativa">CEN01</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc07-consultar-divida-ativa">UC07</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT30</td>
    </tr>
    <tr>
      <td>INT18</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar">HS11</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT19</td>
       <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs14---consultar-d%C3%A9bitos-inscritos">HS14</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen06---consultar-parcelamentos-administrativos">CEN06</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a><td></td>
      <td></td>
      <td>INT16</td>
    </tr>
    <tr>
      <td>INT20</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#-ajuda-e-documenta%C3%A7%C3%A3o">AD03</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr04---suporte">NFR04</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs15---enviar-email">HS15</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#cen07---fale-conosco">CEN07</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc15-enviar-e-mail">UC15</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT21</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/especificacao-suplementar.md#-ajuda-e-documenta%C3%A7%C3%A3o">AD03</a><BR><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr04---suporte">NFR04</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs16---visualizar-informa%C3%A7%C3%B5es-sobre-o-aplicativo">HS16</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc13-consultar-ajuda">UC13</a></td>
      <td><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/telas/05_EconomiaDF-ajuda-1.jpeg?raw=true" style="width: 10%;"></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT22</td>
      <td></td>
      <td></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT23</td>
      <td></td>
      <td></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr><tr>
      <td>INT24</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs04---efetuar-logout">HS04</a></td>
      <td></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT25</td>
     <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs02-hs02---efetuar-login-com-govbr">HS02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc01-fazer-login">UC01, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc02-exibir-erro-de-login">UC02, <a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc03-verificar-dados-de-login">UC03</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT01</td>
    </tr>
    <tr>
      <td>INT26</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
    <tr>
      <td>INT27</td>
     <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr05---restri%C3%A7%C3%B5es-de-design">NFR05</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc12-cadastrar-ve%C3%ADculo">UC12</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT09</td>
    </tr>
    <tr>
      <td>INT28</td>
     <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr05---restri%C3%A7%C3%B5es-de-design">NFR05<br></a><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc12-cadastrar-ve%C3%ADculo">UC12</a></td>
      <td></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT09</td>
    </tr>
    <tr>
      <td>INT29</td>
     <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr05---restri%C3%A7%C3%B5es-de-design">NFR05<br></a><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs12---cadastrar">HS12</a</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc10-cadastro-im%C3%B3vel">UC10</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td>INT13</td>
    </tr>
    <tr>
      <td>INT30</td>
     <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs11---emitir-dar">HS11</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md#uc08-emitir-2%C2%AA-via">UC08</a></td>
      <td></td>
      <td><br><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/nfr-framework.md#nfr01---usabilidade">NFR01</a></td>
      <td></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div>



## Referências Bibliográficas

> [1]SAYÃO, Miriam; DO PRADO LEITE, Julio Cesar Sampaio. Rastreabilidade de requisitos. RITA, v. 13, n. 1, p. 57-86, 2006.
>
> [2]Slides da Aula 26 da Professora Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 15 nov. 2023.


## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|15/11/2023|Criação do documento|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
|`1.1`|15/11/2023| Matriz de rastreabilidade Forward-from|[Zenilda Vieira](https://github.com/zenildavieira)|[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
|`1.2`|16/11/2023| Elos de rastreabilidade |[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|

