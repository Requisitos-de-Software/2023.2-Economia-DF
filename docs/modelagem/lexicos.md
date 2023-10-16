# Léxicos
## Introdução
Léxicos, no contexto de requisitos de software, referem-se a uma lista ou conjunto de termos, palavras ou frases que são relevantes e específicos para o domínio de um sistema ou aplicativo em desenvolvimento. Eles ajudam a definir a linguagem utilizada para descrever os requisitos e funcionalidades do software de forma precisa e consistente.

## Metodologia
Os léxicos do sistema Economia DF foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/#tabela-de-requisitos-elicitados) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Nome do Léxico | Verbo/Objeto/Estado | Símbolos | Descrição do efeito | Sinônimo(s) |
<div align="center">
<p>Tabela 1 - Modelo dos léxicos. Fonte: Izabella Alves, 2023.</p>
</div>

## Léxicos
### Verbos
Os léxicos do tipo verbo representam ações ou operações que os usuários podem realizar dentro do aplicativo "Economia DF". Essas ações descrevem as funcionalidades disponíveis para os usuários, permitindo interações específicas e operações no aplicativo. Nas tabelas
de 2 até Y, é possível verificar os principais léxicos classificados como Verbo que foram identificados no Economia DF.

#### <a id="consultar">Consultar</a>

|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Consultar | Verbo | Tarefa realizada pelo <a href="#usuario">usuário</a>. Acontece quando o <a href="#usuario">usuário</a> entra no aplicativo para verificar suas informações sobre <a href="#notasfiscais">notas fiscais</a>, <a href="#dividaativa">dívidas ativas</a>, entre outros. | Em alguns casos, o usuário precisa <a href="#cadastrar">cadastrar</a> algo, caso não consiga <a href="#consultar">consultar</a> de imediato. A partir da consulta, é possível <a href="#selecionar">selecionar</a> e <a href="#emitir">emitir</a> o que se estava procurando.| Visualizar, informar-se |

 <div align="center">
    <p> Tabela 2: Léxico do verbo Consultar. Fonte: Izabella Alves, 2023.</p> 
</div>

#### <a id="emitir">Emitir</a> 

|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Emitir | Verbo | Tarefa realizada pelo <a href="#usuario">usuário</a>. Ocorre quando o <a href="#usuario">usuário</a>, após <a href="#consultar">consultar</a>, deseja gerar ou baixar o arquivo PDF de um <a href="# boletobancario">boleto bancário</a>, segunda via de uma <a href="#dividaativa">dívidas ativa</a> ou <a href="#parcelamentoadm">parcelamento administrativo</a>. | O  <a href="#usuario">usuário</a> só consegue  <a href="#emitir">emitir</a> <a href="# boletobancario">boletos bancários</a> de <a href="#veiculo">veículos</a> e <a href="#imovel">imóveis</a> cadastrados. <br> Só é possível emitir segunda via de <a href="#dividaativa">dívidas ativa</a>. <br> Após <a href="#emitir">emitir</a> é possível baixar o arquivo PDF. | Gerar|

 <div align="center">
    <p> Tabela x: Léxico do verbo Emitir Fonte: [Gabriel Zaranza](https://github.com/GZaranza) , 2023. </p>
</div>

#### <a id="cadastrar">Cadastrar</a>

|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Cadastrar | Verbo |O verbo “cadastrar” geralmente se refere ao ato de registrar ou inserir informações em um sistema ou banco de dados para referência futura.</a>|Permite ao usuário registrar seus dados pessoais, como CPF, e-mail e senha, para criar uma conta e acessar o aplicativo,permite ao usuário registrar seus veículos e imóveis, informando o número do RENAVAM ou da inscrição imobiliária, para consultar e emitir boletos bancários e permite ao usuário registrar suas indicações de notas fiscais, informando o número do CPF do destinatário, para participar de sorteios e receber créditos.|  Registrar, inscrever, matricular. |

 <div align="center">
    <p> Tabela 4: Léxico do verbo Cadastrarr. Fonte: Lucas de Oliveira, 2023.</p> 
</div>

### Objetos
Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro do aplicativo "Economia DF". 
Nas tabelas de X até Y, é possível verificar os principais léxicos classificados como Objetos que foram identificados no Economia DF.

#### <a id="notafiscal">Nota Fiscal</a>
|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Nota Fiscal | Objeto | É um documento que registra uma transação comercial ou prestação de serviço. É emitida pelas normas da <a href="#seed">Secretária de Economia do DF</a> quando o <a href="#usuário">usuário</a> realiza uma compra.| É possível <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> notas fiscais. Além disso, através delas o <a href="#usuario">usuário</a> pode <a href="#realizarindicacao">realizar indicações</a>.| Documento comprovativo de compra |
 <div align="center">
    <p> Tabela X: Léxico do objeto Nota Fiscal. Fonte: Izabella Alves, 2023.</p>
</div>

#### <a id="veiculo">Veículo </a>
|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
|Veículo | Objeto | É qualquer meio usado para transportar ou conduzir pessoas de um lugar para outro. | O <a href="#usuario">usuário</a> pode <a href="#cadastrar">cadastrar</a>, <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> <a href="# boletobancario">boletos bancários</a> de <a href="#veiculo">veículos</a>.| Carro, automóvel, tranporte.|
 <div align="center">
    <p> Tabela X: Léxico do objeto Veículo. Fonte: Gabriel Zaranza, 2023.</p>
</div>

#### <a id="usuario">Usuário</a>
|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Usuário | Objeto |  O <a href="#usuario">usuário</a> é geralmente classificado como uma entidade ou objeto em sistemas de informação e tecnologia da informação.| O <a href="#usuario">usuário</a> é fundamental para a personalização e segurança dos sistemas. Ele permite que os sistemas forneçam experiências personalizadas, mantenham o controle de preferências e atividades do usuário e implementem medidas de segurança, como controle de acesso e rastreamento de atividades. .| Cliente, consumidor, operador, end-user (usuário final). |
 <div align="center">
    <p> Tabela X: Léxico do objeto Usuário. Fonte: Lucas de Oliveira, 2023.</p>
</div>


### Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem existir dentro do aplicativo "Economia DF".
Nas tabelas de X até Y, é possível verificar os principais léxicos classificados como Estados que foram identificados no Economia DF.

#### <a id="dividaativa">Dívida ativa</a>
|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: |
| Dívida ativa | Estado | Débito do <a href="#usuario">usuário</a> perante a <a href="#seed">Secretária de Economia do DF</a> encontra-se ativa. Ocorre quando um valor não é pago na data de vencimento, portanto é classificado como <a href="#dividaativa">dívida ativa</a>.|É possível <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> as <a href="#dividaativa">dívidas ativas</a> do <a href="#usuario">usuário</a>. Quando o <a href="#usuario">usuário</a> paga sua dívida, ela sai da situação atual.| - |
<div align="center">
<p>Tabela X - Léxico do estado Dívida Ativa. Fonte: Izabella Alves, 2023.</p>
</div>

## Bibliografia
> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 04 de março de 2022.
>
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/10/2023|Criação do documento e adição dos lexicos consultar, divida ativa e nota fiscal|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|15/10/2023|Adicionando léxicos emitir e veículo|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Ribeiro](https://github.com/lucassouzs)|
