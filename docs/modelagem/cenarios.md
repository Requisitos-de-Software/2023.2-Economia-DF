# Cenários

## Introdução

Os cenários são conhecidos como uma estratégia para a compreensão da interface entre o ambiente e o sistema, bem como um meio de extrair e especificar o comportamento do software descrevendo as situações do ambiente, de acordo com as principais ações realizadas fora do sistema de software. Os cenários também ajudam a esclarecer a inter-relação entre requisitos funcionais e não funcionais [1].

## Metodologia

A elaboração dos cenários foi realizada a partir da identificação das principais tarefas do aplicativo Economia DF, em que cada membro da equipe ficou responsável por um cenário (Tabela 1). Os cenários são descritos por [1]:

- título: o título do cenário
- objetivo: o objetivo a ser alcançado pela tarefa
- contexto: descreve a localização geográfica e o estado inicial da tarefa
- recursos: meios de apoio e dispositivos que necessecitam estar disponíveis para o cenário
- atores: pessoa que realiza a tarefa descrita no cenário
- episódios: frases que descrevem como o cenário acontece e seu comportamento
- restrição: caracteríssticas que o cenário deve seguir
- exceção: situações que impedem a realização do cenário
<br>


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Definição de membro da equipe que trabalhou em determinado cenário</p></font>

<table>
  <thead>
    <tr>
      <th>Membro da Equipe</th>
      <th>Cenário</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/gabrielrosa09">Gabriel Rosa</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#consultar-imóveis">Consultar imóveis</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GZaranza">Gabriel Zaranza</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#consultar-veículos">Consultar veículos</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/izabellaalves">Izabella Alves</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#consultar-dívida-ativa">Consultar dívida ativa</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#consultar-outros-tributos">Consultar outros tributos</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#consultar-parcelamentos-administrativos">Consultar parcelamentos administrativos</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Lucas13032003">Lucas Víctor</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#consultar-notas-fiscais">Consutlar notas fiscais</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/cenarios.md#fale-conosco">Fale conosco</a></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a></p></font>
</div>

## Cenários

### Consultar dívida ativa

O cenário em questão diz respeito ao objetivo "Consultar dívida ativa", sua descrição detalhada está disponível na tabela 1.

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Cenário referente ao objetivo "Consultar dívida ativa". </p></font>
</div>

| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Consultar dívida ativa através do aplicativo Economia DF                          |
| Contexto    | Local: em casa<br>Tempo: Aproximadamente 30 segundos<br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF                                     |
| Atores      | Usuário brasileiro com CPF ativo                                                  |
| Episódios   | O *usuário* seleciona a opção Dívida Ativa na tela inicial<br>O aplicativo exibe uma tela com as informações da dívida ativa e uma opção para emitir segunda Via<br>O *usuário* visualiza as informações de seus débitos ativos<br>O *usuário* seleciona a opção Emitir Segunda Via |
| Restrição   | As informações só aparecem se o usuário tiver alguma dívida                         |
| Exceção     | Erro de conexão com a internet<br>Celular com sistema Android                        |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

### Consultar veículos

O cenário em questão diz respeito ao objetivo "Consultar veículos", sua descrição detalhada está disponível na tabela 2.

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Cenário referente ao objetivo "Consultar Veículos"</p></font>
</div>


| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Consultar débitos e boletos bancários de um veículo através do aplicativo Economia DF                          |
| Contexto    | Local: em casa<br>Tempo: Aproximadamente 1 minuto<br> Pré-condições: Usuário brasileiro com CPF ativo e RENAVAM do veículo a ser consultado, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF                                     |
| Atores      | Usuário brasileiro com CPF ativo                                                  |
| Episódios   | O *usuário* seleciona a opção "Veículos" na tela inicial<br>O aplicativo exibe uma tela com uma lista de veículos cadastrados e uma opção para cadastrar um novo veículo<br>O *usuário* seleciona um veículo cadastrado<br>O aplicativo exibe uma tela com os débitos relacionados ao veículo<br>O *usuário* seleciona a opção Emitir Segunda Via do boleto nacário |
| Restrição   | Os veículos só aparecem se já tiverem sido cadastrados<br>Os débitos só aparecem caso o veículo possua alguma dívida ativa                          |
| Exceção     | Erro de conexão com a internet<br>Celular com sistema Android                        |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div>

### Consultar imóveis

O cenário em questão diz respeito ao objetivo "Consultar imóveis", sua descrição detalhada está disponível na tabela 3.

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Cenário referente ao objetivo "Consultar Imóveis"</p></font>
</div>

| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Consultar imóveis através do aplicativo Economia DF                          |
| Contexto    | Local: em casa<br>Tempo: Aproximadamente 1 minuto<br> Pré-condições: Usuário brasileiro com CPF, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF                                     |
| Atores      | Usuário brasileiro com CPF ativo                                                  |
| Episódios   | O *usuário* seleciona a opção "Imóveis" na tela inicial<br>O aplicativo exibe uma tela com uma lista de imóveis cadastrados e uma opção para cadastrar um novo imóvel<br>O *usuário* seleciona um imóvel cadastrado<br>O aplicativo exibe uma tela com os débitos relacionados ao imóvel<br>O *usuário* seleciona a opção Emitir Segunda Via do boleto bancário |
| Restrição   | Os imóveis só aparecem se já tiverem sido cadastrados<br>Os débitos só aparecem caso o imóvel possua alguma dívida ativa                          |
| Exceção     | Erro de conexão com a internet<br>Celular com sistema Android                        |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>

</div>

### Consultar notas fiscais

Esse cenário corresponde ao objetivo "Consultar notas fiscais", sua descrição detalhada está disponível na tabela 4.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Cenário referente ao objetivo "Consultar Notas Fiscais"</p></font>
</div>


| Elemento    | Descrição                                                                            |
|-------------|------------------------------------------------------------------------------------- |
| Objetivo    | Consultar notas fiscais através do aplicativo Economia DF      |
| Contexto    | Local: em casa <br> Tempo: Aproximadamente 30 segundos  <br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado, ser usuário do programa Nota Legal |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF           | 
| Atores      | Usuário brasileiro com CPF ativo                                                     |
| Episódios   | O *usuário* seleciona a opção "Notas Fiscais" na tela inicial<br>O aplicativo redireciona o *usuário* para a página "Notas Fiscais"<br>O *usuário* pode visualizar, exportar e imprimir <br>  |
| Restrição   | Aplicativo de e-mail deve estar instalado no celular que possua um sistema IOS                                 |
| Exceção     | Erro de conexão com a internet<br> Celular com sistema Android 

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div>

### Consultar outros Tributos

Esse cenário corresponde ao objetivo "Consultar outros tributos", sua descrição detalhada está disponível na tabela 5.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Cenário referente ao objetivo "Consultar outros Tributos"</p></font>
</div>
  
| Elemento    | Descrição                                                                            |
|-------------|------------------------------------------------------------------------------------- |
| Objetivo    |  O objetivo é permitir que os usuários consultem outros tributos no aplicativo Economia DF, proporcionando uma visão clara de suas obrigações fiscais.     |
| Contexto    | Local: em casa <br> Tempo: Aproximadamente 40 segundos  <br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado, ser usuário do programa Nota Legal e ter uma conta no aplicativo |
| Recursos    | Internet<br>Sistema IOS<br>Dispositivo móvel com o aplicativo Economia DF instalado           | 
| Atores      | Usuário do aplicativo Economia DF                                                      |
| Episódios   | O *usuário* O usuário abre o aplicativo Economia DF em seu dispositivo móvel.l<br> O usuário faz login em sua conta.<br>O *usuário* navega até a seção “Outros Tributos”.<br><br>O *usuário* seleciona o tipo de tributo que deseja consultar.<br>O aplicativo exibe as informações detalhadas sobre o tributo selecionado. |
| Restrição   | Aplicativo de e-mail deve estar instalado no celular que possua um sistema IOS                                 |
| Exceção     | Se o aplicativo não estiver funcionando corretamente ou se o usuário não tiver acesso à internet, ele não poderá consultar outros tributos.<br> Celular com sistema Android|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023</p></font>
</div>

### Consultar Parcelamentos Administrativos

Esse cenário corresponde ao objetivo "Consultar Parcelamentos Administrativos", sua descrição detalhada está disponível na tabela 6.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Cenário referente ao objetivo "Consultar Parcelamentos Administrativos"</p></font>
</div>

| Elemento    | Descrição                                                                            |
|-------------|------------------------------------------------------------------------------------- |
| Objetivo    |Obter informações sobre acordos de pagamento de dívidas ou obrigações fiscais com órgãos governamentais ou outras entidades.|
| Contexto    |Local: Residência ou algum lugar confortável para mexer no aplicativo.</br>Tempo: Aproximadamente 30 segundos</br>Pré-condições: Ser um usuário brasileiro com CPF ativo, possuir um dispositivo com o sistema iOS, ter o aplicativo Economia DF instalado em seu dispositivo e</br>ter parcelamentos ativos.|
| Recursos    |Internet</br>Sistema IOS</br>Aplicativo Economia DF| 
| Atores      |Usuário brasileiro com CPF ativo|
| Episódios   |O usuário seleciona a opção ‘Parcelamentos administrativos’ na tela inicial</br>O aplicativo exibe uma tela com uma lista de parcelamentos ativos</br>O usuário seleciona um parcelamento ativo cadastrado para obter mais informações|
| Restrição   |As informações só estarão disponíveis para consulta se o usuário tiver algum parcelamento ativo.|
| Exceção     |Erro de conexão com a internet</br>Celular com sistema Androi|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Fale conosco

Esse cenário corresponde ao objetivo "Fale conosco", sua descrição detalhada está disponível na tabela 7.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Cenário referente ao objetivo "Fale conosco"</p></font>
</div>


| Elemento    | Descrição                                                                            |
|-------------|------------------------------------------------------------------------------------- |
| Objetivo    | Entrar em contato com a Secretaria de Economia do DF, responsável pelo aplicativo    |
| Contexto    | Local: em qualquer lugar <br> Tempo: Aproximadamente 1 minuto e meio <br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado, ter um aplicativo de correio eletrônico instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF <br> Aplicativo de correio eletrônico           | 
| Atores      | Usuário brasileiro com CPF ativo                                                     |
| Episódios   | O *usuário* seleciona a opção "Fale conosco" na tela inicial <br>O *usuário* clica no botão "preparar e-mail" <br> O aplicativo apresenta uma mensagem na tela informando que o *usuário* será redirecionado para o aplicativo de correio eletrônico e espera confirmação do *usuário*<br>O aplicativo redireciona o *usuário* para o aplicativo de correio eletrônico padrão instalado no celular, abrindo uma nova mensagem já com alguns campos preeenchidos<br>O *usuário* pode escrever o correio eletrônico com dúvidas, sugestões ou reclamações e enviar <br>  |
| Restrição   | Celular com sistema Android <br> Celular sem bateria                                |
| Exceção     | Erro de conexão com a internet<br> O *usuário* não tem correio eletrônico |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Referência Bibliográfica
> [1] Leite, Julio & Rossi, Gustavo & Balaguer, Federico & Maiorana, Vanesa & Kaplan, Gladys & Hadad, Graciela & Oliveros, Alejandro. (1997). Enhancing a requirements baseline with scenarios. Requirements Engineering. 2. 184-198. 10.1007/BF02745371. 

## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> Bilheteria Digital. Cenários. Grupo Bilheteria Digital da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em: 08 de outubro de 2023.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|08/10/2023|Criação de documento e adição do cenário sobre "consultar dívida ativa"|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.1`|09/10/2023|Adição do cenário sobre "consultar veículos"|[Gabriel Zaranza](https://github.com/GZaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.2`|11/10/2023|Adição do cenário sobre "consultar veículos"|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.3`|11/10/2023|Adição do cenário sobre "fale conosco" | [Zenilda Vieira](https://github.com/zenildavieira)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.4`|11/10/2023|Adição do cenário sobre "Consultar notas fiscais" | [Lucas Víctor](https://github.com/Lucas13032003)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.5`|11/10/2023|Adição do cenário sobre "Consultar outros Tributos" | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Lucas Víctor](https://github.com/Lucas13032003)|
|`1.6`|12/10/2023|Adição do cenário sobre "Consultar Parcelamentos Administrativos" | [Lucas Ribeiro](https://github.com/lucassouzs)|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
|`1.7`|22/10/2023|Padronizando localização dos nomes das figuras/tabelas e das fontes nas legendas|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.8`|22/10/2023|Revisão geral do documento|[Zenilda Vieira](https://github.com/zenildavieira)| - (revisão não precisa de revisor) |
