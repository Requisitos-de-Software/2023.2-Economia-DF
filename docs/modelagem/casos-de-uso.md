# Casos de Uso

## Introdução

O Caso de uso é ferramenta que se mostra útil na representação gráfica dos requisitos funcionais. Este diagrama oferece uma maneira simples de se comunicar com os stakeholders em relação às funcionalidades e aos serviços que serão disponibilizados aos usuários. Pode ser empregado desde as fases iniciais da coleta de requisitos, servindo como um recurso auxiliar para entrevistas, reuniões ou workshops. Além disso, pode ser uma forma de documentação gráfica do escopo funcional para gerentes de projetos [1].

## Metodologia

A construção dos casos de uso do aplicativo Economia DF foi feita através do uso da persona [Maria](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/personas.md#persona-prim%C3%A1ria-2-maria-dos-santos-aveiro-administradora) para entender melhor as tarefas que o usuário realiza no sistema. Primeiro, foi definido quem são os atores do sistema, usuário do Economia DF e a Secretária de Economia do Distrito Federal, e logo em seguida foi elencado os casos de uso seguindo a ordem com que acontecem durante a realização das tarefas dentro do aplicativo. Após a definição de todos os casos de uso, criou-se o diagrama na plataforma [Draw.io](https://app.diagrams.net) com os elementos gráficos padrões de um Caso de Uso (Tabela 1) e seus respectivos relacionamentos seguindo o guia da plataforma Lucid Chart [2].

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda do diagrama de caso de uso</p></font>

<table>
  <thead>
    <tr>
      <th>Elemento</th>
      <th>Nome</th>
      <th>Função</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><figure class="usecaseElement" style="width: 20%; display: flex;"><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-ator.drawio.png?raw=true" alt="Ator"></figure></td>
      <td>Ator</td>
      <td>Representam os diferentes tipos de usuários externos que interagem com o sistema</td>
    </tr>
    <tr>
      <td><figure class="usecaseElement" style="width: 40%; display: flex;"><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-caso-de-uso.drawio.png?raw=true" alt="Elipse (Caso de Uso)"></figure></td>
      <td>Elipse (Caso de Uso)</td>
      <td>É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso</td>
    </tr>
    <tr>
      <td><figure class="usecaseElement" style="width: 40%; display: flex;"><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-limites.drawio.png?raw=true" alt="Retângulo (Sistema)"></figure></td>
      <td>Retângulo (Sistema)</td>
      <td>Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados</td>
    </tr>
    <tr>
      <td><figure class="usecaseElement" style="width: 40%; display: flex;"><img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-relacionamentos.drawio.png?raw=true" alt="Flecha (Relações)"></figure></td>
      <td>Flecha (Relações)</td>
      <td>As flechas são usadas para representar as relações ou interações entre atores e casos de uso</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Diagrama de Casos de Uso

A figura 1 demonstra o diagrama de casos de uso.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama de caso de uso do aplicativo Economia DF</p></font>

<img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/diagrama-caso-de-uso.drawio.png?raw=true" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>

</div>

## Especificação dos Casos de Uso

### UC01. Fazer login

A tabela 2 demonstra a especificação do caso de uso UC01 Fazer login.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Especificação do caso de uso UC01</p></font>
</div>

| UC01 |  Fazer login |
| --- | --- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. Dispor de uma conexão à internet;<br> PRE02. Usuário abrir o aplicativo deslogado.|
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário fornece seus dados de login. Aciona o caso de uso UC03. <li> O sistema envia um código de validação no SMS do usuário <li> O usuário fornece o código de validação e clica em validar. <li> O usuário é logado. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | <b>FA01: Logar pelo Nota Legal</b> <ol> <li> O usuário clica em "Usar dados do Nota Legal" <li> O usuário fornece os dados de login do Nota Legal e clica em validar. Aciona o caso de uso UC03. <li> O usuário é logado. <li> Fim do caso de uso. </ol> <b> FA02: Validar o login pelo email</b> <ol> <li> O usuário fornece seus dados de login. Aciona o caso de uso UC03. <li> O usuário clica em "Enviar o código de validação para o email. <li> O sistema envia o código de validação para o email de cadastro do usuário. <li> O usuário fornece o código de validação e clica em validar. <li>O usuário é logado. <li>Fim do caso de uso. </ol>  |
| **Fluxos de exceção** | <b>FE01: Dados do login errados </b> <ol> <li> O usuário fornece algum dado do login errado <li> O sistema informa em qual campo está com o dado inválido. </ul> </ol> <b> FE02:Código de validação errado </b> <ol> <li> O usuário fornece o código de validação errado <li> O sistema informa que o código inserido é invalido </ol> |
| **Pós-condições** |POS01. O usuário é logado em sua conta do aplicativo. |
| **Data da criação** | 10/10/2023 |
| **Rastreabilidade** | [BS08](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [INT01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md#desenvolvimento) |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div >

### UC02. Exibir erro de login

A tabela 3 demonstra a especificação do caso de uso UC02 Exibir erro de login.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Especificação do caso de uso UC02</p></font>
</div>

| UC02 | Exibir erro de login |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O usuário forneceu algum dado errado no login.|
| **Fluxo básico** |<b>FB01. </b> <ol> <li> O usuário fornece seus dados de login. Aciona o caso de uso UC03. <li> O sistema informa em qual campo o usuário forneceu um dado inválido </ol> |
| **Fluxos alternativos** |   |
| **Fluxos de exceção** |  |
| **Pós-condições** |POS01. O usuário deve colocar novamente suas credenciais de login  |
| **Data da criação** | 10/10/2023 |
| **Rastreabilidade** | [BS01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div >

### UC03. Verificar dados de login

A tabela 4 demonstra a especificação do caso de uso UC03 Verificar dados de login.

<div align="center">  
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Especificação do caso de uso UC03</p></font>
</div>

| UC03 |  Verificar dados de login |
| -: | :- |
| **Atores** | Sistema |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O usuário fornceceu os dados de login.|
| **Fluxo básico** |<b>FB01. </b> <ol> <li> O sistema recebe os dados que o usuário forneceu <li> O sistema verifica os dados de login <li> O sistema libera o login do usuário <li> Fim do caso de uso. |
| **Fluxos alternativos** |   |
| **Fluxos de exceção** | <b>FE01: Dados do login errados </b> <ol> <li> O usuário fornece algum dado do login errado <li> O sistema verifica os dados de login <li> O sistema não permite o login do usuário. Aciona o caso de uso UC01. <li> Fim do caso de uso </ul> </ol> |
| **Pós-condições** |POS01. O usuário é logado em sua conta do aplicativo. |
| **Data da criação** | 10/10/2023 |
| **Rastreabilidade** | [BS01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [INT01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md#desenvolvimento) |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div >

### UC04. Consultar notas fiscais

A tabela 5 demonstra a especificação do caso de uso UC04 Consultar notas fiscais.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Especificação do caso de uso UC04</p></font>
</div>

| UC04 |  Consultar notas fiscais |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. Dispor de uma conexão à internet; <br>PRE02. Usuário estar na tela inicial.|
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário clica em "Notas fiscais". <li> O sistema emite o aviso sobre os documentos fiscais. <li> O usuário clica em "Continuar". <li> O sistema mostra a lista de documentos fiscais do usuário <li> O usuário seleciona um documento fiscal <li> O sistema abre o documento fiscal. <li> Fim do caso de uso.  </ol> |
| **Fluxos alternativos** | <b>FA01: Pesquisar por um documento fiscal</b> <ol> <li>  O usuário clica em "Notas fiscais". <li> O sistema emite o aviso sobre os documentos fiscais. <li> O usuário clica em "Continuar". <li> O usuário clica no ícone de busca. <li> O usuário fornece alguma informação do documento <li> O sistema mostra a lista de documentos fiscais que apresentam a informação que o usuário forneceu <li> O usuário seleciona um documento fiscal <li> O sistema abre o documento fiscal <li> Fim do caso de uso </ol>  |
| **Fluxos de exceção** | <b>FE01: O usuário não possue documentos fiscais </b> <ol> <li> O usuário clica em "Notas fiscais". <li> O sistema emite uma mensagem dizendo que não há notas fiscais <li> Fim do caso de uso. </ol> |
| **Pós-condições** |POS01. O usuário tem acesso ao documento fiscal. |
| **Data da criação** | 10/10/2023 |
| **Rastreabilidade** | [BS04](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md), [BS10](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md), [INT05](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md#desenvolvimento) e [OBS01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observação.md) |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div >

### UC05. Imprimir Danfe

A tabela 6 demonstra a especificação do caso de uso UC05 Imprimir Danfe.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Especificação do caso de uso UC05</p></font>
</div>

| UC05 | Imprimir Danfe |
| -: | :- |
| **Atores** | Usuário |https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md#desenvolvimento
| **Frequência de uso** | Média |
| **Pré-condições** |PRE01. Dispor de uma conexão à internet; <br>PRE02. Possuir o aplicativo. |
| **Fluxo básico** | <ol> <li> O usuário acessa o aplicativo. <li> O usuário clica na opção "Notas Fiscais".<li> Seleciona uma nota fiscal. </ol>  <li> O aplicativo abre a nota fiscal, onde é possível ter Danfe para impressão. </ol> |
| **Fluxos alternativos** | <b>Fluxo 1: Impressão Bem-Sucedida</b> <ol> <li> O usuário seleciona a opção de impressão. <li> O sistema verifica a conectividade com a impressora. <li> O Danfe é impresso com sucesso. <ul> <li> O usuário recebe o Danfe impresso. </ul> </ol> <b> Fluxo 2: Cancelamento da Impressão</b> <ol> <li> O usuário decide cancelar a impressão. <li> O processo de impressão é interrompido. </ol> <b> Fluxo 3: Erro na Impressão</b> <ol> <li> O usuário tenta imprimir o Danfe. <li> O sistema detecta um problema na impressão. <li> O usuário recebe uma mensagem de erro. </ol> |
| **Fluxos de exceção** |<b>FE01: O usuário não possue documentos fiscais </b> <ol> <li> O usuário clica em "Notas fiscais". <li> O sistema emite uma mensagem dizendo que não há notas fiscais <li> Fim do caso de uso. </ol>  |
| **Pós-condições** | O usuário tem acesso ao Danfe e a opção de imprimir o documento. |
| **Data da criação** | 13/10/2023 |
| **Rastreabilidade** | [INT05](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md#desenvolvimento), [OBS01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md#funcionais)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div >

### UC06. Visualizar NFC-e detalhada

A tabela 7 demonstra a especificação do caso de uso UC06 Visualizar NFC-e detalhada.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Especificação do caso de uso UC06</p></font>
</div>
  

| UC06 | Visualizar NFC-e detalhada |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. Dispor de uma conexão à internet; <br>PRE02. Possuir o aplicativo. |
| **Fluxo básico** | <ol> <li> O usuário acessa o aplicativo. <li> O usuário clica na opção "Notas Fiscais". <li> Seleciona uma nota fiscal. <li> O aplicativo abre a nota fiscal selecionada, onde é possível visualizar. </ol> |
| **Fluxos alternativos** | <b>Fluxo 2: Sem Notas Fiscais Cadastradas</b> <ol> <li> Ao acessar a seção "Notas Fiscais", o usuário percebe que não possui nenhuma nota fiscal cadastrada em sua conta. <li> O aplicativo exibe uma mensagem informando que não há notas fiscais disponíveis para visualização. <ul> <li> O usuário pode optar por retornar à tela inicial do aplicativo ou realizar o cadastro de uma nova nota fiscal. <li> Se o usuário optar por retornar à tela inicial, o processo continua a partir desse ponto. <li> Se o usuário optar por cadastrar uma nova nota fiscal, o processo de cadastro é iniciado. </ul> </ol> |
| **Fluxos de exceção** | <b>Fluxo 1: Nota Fiscal Indisponível</b> <ol> <li> Após escolher uma nota fiscal, o usuário pode receber uma mensagem informando que os detalhes da NFC-e não estão disponíveis no momento. <li> O usuário pode optar por voltar à lista de notas fiscais ou tentar novamente mais tarde. <ul> <li> Se o usuário voltar à lista de notas fiscais, o processo continua a partir desse ponto. <li> Se o usuário optar por tentar novamente, o processo retorna ao ponto de seleção da nota fiscal. </ul> </ol> |
| **Pós-condições** | O usuário pode visualizar os detalhes da NFC-e. |
| **Data da última atualização** | 13/10/2023 |
| **Rastreabilidade** | [INT05](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md#desenvolvimento), [OBS01](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md#funcionais)|
 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div >

### UC07. Consultar divida Ativa

A tabela 8 demonstra a especificação do caso de uso UC07 Consultar divida Ativa.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8:</b> Especificação do caso de uso UC07</p></font>
</div>

| UC07 | Consultar Dívida Ativa |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Pré-condições** | O usuário precisa estar autenticado no aplicativo. |
| **Fluxo básico** | <ol> <li> O usuário acessa o aplicativo. <li> O usuário escolhe a opção "Consultar Dívida Ativa". <li> O aplicativo exibe os detalhes da dívida ativa do usuário. </ol> |
| **Fluxos alternativos** | <b>Fluxo Alternativo: Não Possuir Dívida Ativa</b> <ol> <li> Após escolher a opção "Consultar Dívida Ativa", o usuário é redirecionado para a páginna de dividas ativas onde recebe uma mensagem informando que não possui dívida ativa registrada em sua conta. <li> O aplicativo oferece a opção de retornar à tela inicial. <ul> <li> Se o usuário optar por retornar à tela inicial, o processo continua a partir desse ponto.</ol> |
| **Fluxos de exceção** |<ol> <li> Fluxo de Exceção 1: Falha na Autenticação <li> Após escolher a opção "Consultar Dívida Ativa", o usuário pode receber uma mensagem informando que houve uma falha na autenticação.<li> O aplicativo oferece a opção de tentar novamente ou contatar o suporte.<li> Se o usuário optar por tentar novamente, o processo retorna ao ponto de autenticação <li> Se o usuário optar por contatar o suporte, o processo é encaminhado para o suporte técnico.    <ol>|
| **Pós-condições** | O usuário pode visualizar os detalhes da dívida ativa, se aplicável. |
| **Data da criação** | 13/10/2023 |
| **Rastreabilidade** | [OBS05](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md#funcionais)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div >

### UC08. Emitir 2ª via
  
A tabela 9 demonstra a especificação do caso de uso UC08 Emitir 2ª via.

<div align="center"> 
<font size="3"><p style="text-align: center"><b>Tabela 9:</b> Especificação do caso de uso UC08</p></font>
</div>

| UC08 | Emitir 2ª via |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Pré-condições** | O usuário precisa estar autenticado no aplicativo e possuir uma dívida ativa. |
| **Fluxo básico** | <ol> <li> O usuário acessa o aplicativo. <li> O usuário escolhe a opção "Emitir 2ª via". <li> O aplicativo permite que o usuário seleciona a divida para o qual deseja emitir a 2ª via <li> O aplicativo gera a 2ª via do documento escolhido. </ol> |
| **Fluxos alternativos** | <b>Fluxo Alternativo: Não Possuir Dívida Ativa</b> <ol> <li> Após escolher a opção "Consultar Dívida Ativa", o usuário é redirecionado para a páginna de dividas ativas onde recebe uma mensagem informando que não possui dívida ativa registrada em sua conta. <li> O aplicativo oferece a opção de retornar à tela inicial. <ul> <li> Se o usuário optar por retornar à tela inicial, o processo continua a partir desse ponto.</ol> |
| **Fluxos de exceção** |<ol> <li> Fluxo de Exceção 1: Falha na Autenticação <li> Após escolher a opção "Consultar Dívida Ativa", o usuário pode receber uma mensagem informando que houve uma falha na autenticação.<li> O aplicativo oferece a opção de tentar novamente ou contatar o suporte.<li> Se o usuário optar por tentar novamente, o processo retorna ao ponto de autenticação <li> Se o usuário optar por contatar o suporte, o processo é encaminhado para o suporte técnico.    <ol>|
| **Pós-condições** | O usuário obtém a 2ª via do documento escolhido. |
| **Data da criação** | 13/10/2023 |
| **Rastreabilidade** | [OBS05](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observa%C3%A7%C3%A3o.md#funcionais)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div >

### UC09. Consultar imóvel

A tabela 10 demonstra a especificação do caso de uso UC09 Consultar imóvel.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 10:</b> Especificação do caso de uso UC09</p></font>
</div>


| UC09 |  Consultar imóvel no aplicativo Economia DF |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O usuário está logado em sua conta no aplicativo Economia DF.|
| **Fluxo básico** |<b>FB01. </b> <ol> <li> O usuário seleciona a opção "Imóveis" na tela inicial <li> O aplicativo exibe uma tela com uma lista de imóveis cadastrados e uma opção para cadastrar um novo imóvel <li> O usuário seleciona um imóvel cadastrado <li> O aplicativo exibe uma tela com os débitos relacionados ao imóvel <li> Fim do caso de uso. |
| **Fluxos alternativos** |   |
| **Fluxos de exceção** | <b>FE01: Imóvel não cadastrado </b> <ol> <li> O usuário seleciona a opção "Imóveis" na tela inicial <li> O aplicativo exibe uma tela com uma lista de imóveis cadastrados e uma opção para cadastrar um novo imóvel <li> O usuário tenta selecionar um imóvel não cadastrado <li> O aplicativo exibe uma mensagem de erro informando que o imóvel não está cadastrado. Aciona o caso de uso UC11 para cadastrar um novo imóvel. <li> Fim do caso de uso </ul> </ol> |
| **Pós-condições** |POS01. O usuário visualiza os débitos relacionados ao imóvel selecionado. |
| **Data da criação** | 10/10/2023 |
| **Rastreabilidade** | - |


<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>
</div >

### UC10. Cadastro imóvel

A tabela 11 demonstra a especificação do caso de uso UC10 Cadastro imóvel.

<div align="center">  
<font size="3"><p style="text-align: center"><b>Tabela 11:</b> Especificação do caso de uso UC10</p></font>
</div>

| UC10 |  Cadastrar imóvel no aplicativo Economia DF |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O usuário está logado em sua conta no aplicativo Economia DF.|
| **Fluxo básico** |<b>FB01. </b> <ol> <li> O usuário seleciona a opção "Imóveis" na tela inicial <li> O aplicativo exibe uma tela com uma lista de imóveis cadastrados e uma opção para cadastrar um novo imóvel <li> O usuário seleciona a opção para cadastrar um novo imóvel <li> O usuário preenche os campos necessários para o cadastro do imóvel <li> O usuário confirma o cadastro do imóvel <li> Fim do caso de uso. |
| **Fluxos alternativos** |   |
| **Fluxos de exceção** | <b>FE01: Dados do imóvel incompletos ou inválidos </b> <ol> <li> O usuário seleciona a opção "Imóveis" na tela inicial <li> O aplicativo exibe uma tela com uma lista de imóveis cadastrados e uma opção para cadastrar um novo imóvel <li> O usuário seleciona a opção para cadastrar um novo imóvel <li> O usuário preenche os campos necessários para o cadastro do imóvel de forma incompleta ou com dados inválidos <li> O aplicativo exibe uma mensagem de erro informando que os dados estão incompletos ou inválidos. Aciona o caso de uso UC02 para corrigir os dados. <li> Fim do caso de uso </ul> </ol> |
| **Pós-condições** |POS01. O imóvel é cadastrado e aparece na lista de imóveis do usuário. |
| **Data da criação** | 11/10/2023 |
| **Rastreabilidade** | - |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>
</div >

### UC11. Consultar veículo

A tabela 12 demonstra a especificação do caso de uso UC11 Consultar veículo.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 12:</b> Especificação do caso de uso UC11</p></font>
</div>
  

| UC11 |  Consultar veículo no aplicativo Economia DF |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O usuário está logado em sua conta no aplicativo Economia DF.|
| **Fluxo básico** |<b>FB01. </b> <ol> <li> O usuário seleciona a opção "Veículos" na tela inicial <li> O aplicativo exibe uma tela com uma lista de veículos cadastrados e uma opção para cadastrar um novo veículo <li> O usuário seleciona um veículo cadastrado <li> O aplicativo exibe uma tela com os débitos relacionados ao veículo <li> Fim do caso de uso. |
| **Fluxos alternativos** |   |
| **Fluxos de exceção** | <b>FE01: Veículo não cadastrado </b> <ol> <li> O usuário seleciona a opção "Veículos" na tela inicial <li> O aplicativo exibe uma tela com uma lista de veículos cadastrados e uma opção para cadastrar um novo veículo <li> O usuário tenta selecionar um veículo não cadastrado <li> O aplicativo exibe uma mensagem de erro informando que o veículo não está cadastrado. Aciona o caso de uso UC13 para cadastrar um novo veículo. <li> Fim do caso de uso </ul> </ol> |
| **Pós-condições** |POS01. O usuário visualiza os débitos relacionados ao veículo selecionado. |
| **Data da criação** | 10/10/2023 |
| **Rastreabilidade** | - |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>
</div >

### UC12. Cadastrar veículo

A tabela 13 demonstra a especificação do caso de uso UC12 Cadastrar veículo.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 13:</b> Especificação do caso de uso UC12</p></font>
</div>
  
| UC12 | Cadastrar veículo |
| -: | :- |
| **Atores** | Consumidor |
| **Frequência de uso** | Média |
| **Pré-condições** |PRE01. Dispor de uma conexão à internet;</br>PRE02. Possuir um dispositivo com o sistema operacional iOS instalado;</br>PRE03. Ter o aplicativo do Economia DF baixado e instalado no seu dispositivo;</br>PRE04. Possuir um cadastro ativo no aplicativo;</br>PRE05. Possuir um veículo com documentos para ser cadastrado.|
| **Fluxo básico** |<b>FB01. O usuário inicia o aplicativo.</b> <ol> <li> O usuário navega até a seção 'Veículos'.<li>  No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".<li> O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam.<li>O usuário clica no botão 'Adicionar', para adicionar o veículo e suas informações.<li>Finaliza fluxo.</ol>|
| **Fluxos alternativos** |<b>FA01. Dados incorretos</b><ol><li>O usuário inicia o aplicativo.<li>O usuário navega até a seção 'Veículos'.<li>No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".<li> O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam.<li>O usuário clica no botão “Adicionar', para adicionar o veículo e suas informações.<li> O sistema exibe uma mensagem de alerta “Veículo não encontrado”.<lir>Finaliza fluxo.</ol></br></br><b>FA02. Campos em branco</b><ol><li>O usuário inicia o aplicativo.<li> O usuário navega até a seção 'Veículos'.<li> No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".<li> O usuário deixa um ou todos os campos (Apelido, Placa e Renavam) em branco.<li> O usuário clica no botão 'Adicionar', para adicionar o veículo e suas informações.<li> O sistema exibe uma mensagem de alerta indicando "Campo obrigatório" para cada campo vazio durante o processo de inserção de dados.<li> Finaliza fluxo.</ol></br></br><b>FA03. Acesso à Seção 'Veículos' pelo Menu</b><ol><li> O usuário inicia o aplicativo.<li> No canto superior esquerdo da tela, o usuário clica no botão 'Menu', indicado pelas 3 barras paralelas horizontais.<li> O usuário navega até a seção 'Veículos'.<li> No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".<li> O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam.<li> O usuário clica no botão 'Adicionar', para adicionar o veículo e suas informações.<li> Finaliza fluxo.</ol>|
| **Fluxos de exceção** |<b>FE01. Sem internet </b><ol><li> O usuário inicia o aplicativo. <li> O usuário nageva até a seção 'Veículos' (pela tela principal ou pelo menu). <li> No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+". <li> O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam. <li> O sistema exibe uma mensagem de alerta “Não foi possível conectar com os servidores da SEEC DF”. <li> Finaliza fluxo.</ol>|
| **Pós-condições** |POS01. O veículo está registrado com sucesso no sistema.</br>POS02. O veículo está associado à conta do usuário que realizou o cadastro.</br>POS03. O apelido (Nome de identificação), número da placa e Renavam estão corretamente armazenados no sistema para referência futura.</br>POS04. O veículo está acessível para funcionalidades adicionais oferecidas pelo aplicativo, como rastreamento, manutenção ou renovação de licença, dependendo das características do serviço.|
| **Data da criação** |10/10/2023|
| **Rastreabilidade** |[INT27](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md), [INT28](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div >

### UC13. Consultar ajuda

A tabela 14 demonstra a especificação do caso de uso UC13 Consultar ajuda.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 14:</b> Especificação do caso de uso UC13</p></font>
</div>
  
| UC13 | Consultar ajuda |
| -: | :- |
| **Atores** |Consumidor|
| **Frequência de uso** |Média|
| **Pré-condições** |PRE01. Possuir um dispositivo com o sistema operacional iOS instalado;</br>PRE02. Ter o aplicativo do Economia DF baixado e instalado no seu dispositivo;</br>PRE03. Possuir um cadastro ativo no aplicativo;</br>PRE04. Possuir dúvidas ou necessitar de assistência com algum problema específico.|
| **Fluxo básico** |<b>FB01. O usuário inicia o aplicativo.</b><ol><li>O usuário navega até a seção 'Ajuda'.<li> Finaliza fluxo.</ol>|
| **Fluxos alternativos** |<b>FA1. Acesso à Seção ‘Ajuda’ pelo Menu</b><ol><li> O usuário inicia o aplicativo.<li> No canto superior esquerdo da tela, o usuário clica no botão 'Menu', indicado pelas 3 barras paralelas horizontais.<li> O usuário navega até a seção 'Ajuda'.<li> Finaliza fluxo.</ol>|
| **Fluxos de exceção** | - |
| **Pós-condições** |POS01. O usuário tem acesso a uma variedade de tópicos que podem ajudar a esclarecer suas dúvidas e atender às suas necessidades.|
| **Data da criação** |10/10/2023|
| **Rastreabilidade** | - |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div >

### UC14. Entrar em contato

A tabela 15 demonstra a especificação do caso de uso UC14 Entrar em contato.

<div align="center"> 
<font size="3"><p style="text-align: center"><b>Tabela 15:</b> Especificação do caso de uso UC14</p></font>
</div>
  
| UC14 | Entrar em contato |
| -: | :- |
| **Atores** | Consumidor |
| **Frequência de uso** | Média |
| **Pré-condições** |PRE01. Possuir um dispositivo com o sistema operacional iOS instalado;</br>PRE02. Ter o aplicativo do Economia DF baixado e instalado no seu dispositivo;</br>PRE03. Possuir um cadastro ativo no aplicativo;</br>PRE04. Possuir sugestões ou necessitar de assistência com algum problema específico.|
| **Fluxo básico** |<b>FB01. O usuário inicia o aplicativo.</b><ol><li> O usuário navega até a seção "Fale conosco".<li> Finaliza fluxo.</ol>|
| **Fluxos alternativos** |<b>FA01. Acesso à Seção ‘Fale conosco’ pelo Menu</b><ol><li> O usuário inicia o aplicativo.<li>No canto superior esquerdo da tela, o usuário clica no botão 'Menu', indicado pelas 3 barras paralelas horizontais.<li> O usuário navega até a seção 'Fale conosco'.<li> Finaliza fluxo.</ol>|
| **Fluxos de exceção** | - |
| **Pós-condições** |POS01. O usuário terá acesso a um botão ‘Preparar e-mail’, que permitirá que ele entre em contato com o atendimento do aplicativo Economia DF.|
| **Data da criação** |10/10/2023|
| **Rastreabilidade** |[INT11](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div >

### UC15. Enviar e-mail

A tabela 16 demonstra a especificação do caso de uso UC15 Enviar e-mail.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 16:</b> Especificação do caso de uso UC15</p></font>
</div>

| UC15 | Enviar e-mail |
| -: | :- |
| **Atores** |Consumidor|
| **Frequência de uso** |Média|
| **Pré-condições** |PRE01. Dispor de uma conexão à internet;</br>PRE02. Possuir um dispositivo com o sistema operacional iOS instalado;</br>PRE03. Ter o aplicativo do Economia DF baixado e instalado no seu dispositivo;</br>PRE04. Possuir um cadastro ativo no aplicativo;</br>PRE05. Possuir sugestões ou necessitar de assistência com algum problema específico.|
| **Fluxo básico** |<b>FB1. O usuário inicia o aplicativo.</b><ol><li> O usuário navega até a seção "Fale conosco".<li> O usuário clica no botão ‘Preparar e-mail’ <li> O sistema informará ao usuário que será redirecionado para o seu correio eletrônico no dispositivo e perguntará se deseja continuar.<li> Se o usuário selecionar:</br><ol><li>. 'Não', ele será redirecionado de volta à seção 'Fale conosco'. <li> 'Sim', ele será encaminhado para o seu correio eletrônico no dispositivo.”</ol><li> Finaliza fluxo.</ol>|
| **Fluxos alternativos** |FA1. Acesso à Seção ‘Fale conosco’ pelo Menu</br><ol><li> O usuário inicia o aplicativo.<li> No canto superior esquerdo da tela, o usuário clica no botão 'Menu', indicado pelas 3 barras paralelas horizontais.<li> O usuário navega até a seção 'Fale conosco'.<li> O usuário clica no botão ‘Preparar e-mail’ <li>. O sistema informará ao usuário que será redirecionado para o seu correio eletrônico no dispositivo e perguntará se deseja continuar.</br><li>. Se o usuário selecionar:</br><ol><li> 'Não', ele será redirecionado de volta à seção 'Fale conosco'. </br><li> 'Sim', ele será encaminhado para o seu correio eletrônico no dispositivo.”</ol><li> Finaliza fluxo.</ol>|
| **Fluxos de exceção** | - |
| **Pós-condições** |POS01. O usuário será encaminhado para o seu correio eletrônico no dispositivo.|
| **Data da criação** |10/10/2023|
| **Rastreabilidade** |[INT11](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

## Referências Bibliográficas

> [1] REINEHR, Sheila. Engenharia de requisitos. Porto Alegre: Grupo A, 2020. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 15 out. 2023.
> 
> [2] Lucid Software Português. Tutorial de Caso de Uso UML [Recurso eletrônico: vídeo], 2019.  Disponível em: <https://www.youtube.com/watch?v=ab6eDdwS3rA>.  Acesso em: 09 de outubro ed 2023.

## Bibliografia

> VLC. Casos de Uso. Grupo VLC da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso>. Acesso em: 10 de outubro de 2023.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|09/10/2023|Criação do documento e diagrama de caso de uso|[Izabella Alves](https://github.com/izabellaalves) <br> [Zenilda Vieira](https://github.com/zenildavieira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|10/10/2023|Adicionando a tabela exemplo da especificação dos casos de uso|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.2`|10/10/2023|Adicionando a tabela UC13 da especificação dos casos de uso|[Lucas Ribeiro](https://github.com/lucassouzs)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.3`|10/10/2023|Adicionando a tabela UC14 da especificação dos casos de uso|[Lucas Ribeiro](https://github.com/lucassouzs)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.4`|10/10/2023|Adicionando a tabela UC15 da especificação dos casos de uso|[Lucas Ribeiro](https://github.com/lucassouzs)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.5`|10/10/2023|Adicionando a tabela UC16 da especificação dos casos de uso|[Lucas Ribeiro](https://github.com/lucassouzs)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.6`|10/10/2023|Adicionando a tabela especificação dos casos de uso dos cenários 1,2,3 e 4|[Gabriel Zaranza](https://github.com/GZaranza)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.7`|10/10/2023|revisão tabela especificação dos casos de uso dos cenários 13,14,15,16|[Lucas Ribeiro](https://github.com/lucassouzs)|- (revisão não precisa de revisor)|
|`1.8`|10/10/2023|Adicionando a tabela especificação dos casos de uso dos cenários 10,11,12|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.9`|11/10/2023|Adicionando a tabela especificação dos casos de uso dos cenários 5,6,7,8|[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.10`|13/10/2023|Atualização das tabelas de especificação dos casos de uso dos cenários 5,6,7,8|[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.11`|13/10/2023|Adicionando introdução e metodologia|[Gabriel Zaranza](https://github.com/GZaranza)| [Zenilda Vieira](https://github.com/zenildavieira)|
|`1.12`|22/10/2023|Inclusão da citação das tabelas no texto|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.13`|22/10/2023|Padronizando localização dos nomes das figuras/tabelas e das fontes nas legendas|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.14`|22/10/2023|Revisão geral do documento|[Zenilda Vieira](https://github.com/zenildavieira)| - (revisão não precisa de revisor) |
