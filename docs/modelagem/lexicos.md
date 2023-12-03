# Léxicos

## Introdução

Léxicos, no contexto de requisitos de software, referem-se a uma lista ou conjunto de termos, palavras ou frases que são relevantes e específicos para o domínio de um sistema ou aplicativo em desenvolvimento. Eles ajudam a definir a linguagem utilizada para descrever os requisitos e funcionalidades do software de forma precisa e consistente.

## Metodologia

Os léxicos do sistema Economia DF foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/#tabela-de-requisitos-elicitados) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Modelo dos léxicos</p></font>
</div>


|     Léxico     |   Classificação     |   Noção  |       Impacto       |   Sinônimo  |   Autor                                  |
| :------------: | :-----------------: | :------: | :-----------------: | :---------: | :--------------------------------------: |
| Nome  | Objeto/Verbo/Estado | Significado do símbolo (denotação) | Descrição do efeito/uso/ocorrência (conotação) | Termo(s) alternativo(s) | Integrante do grupo que realizou essa descrição |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Objetos

Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro do aplicativo "Economia DF". Na tabelas 2, é possível verificar os principais léxicos classificados como Objetos que foram identificados no Economia DF.

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Léxicos classificados como Objetos</p></font>
</div>



|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |   Autor                                  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: | :--------------------------------------: |
| <a id="notafiscal">L01 - Nota Fiscal</a> | Objeto | É um documento que registra uma transação comercial ou prestação de serviço. É emitida pelas normas da <a href="#seed">Secretária de Economia do DF</a> quando o <a href="#usuário">usuário</a> realiza uma compra.| É possível <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> notas fiscais. Além disso, através delas o <a href="#usuario">usuário</a> pode <a href="#realizarindicacao">realizar indicações</a>.| Documento comprovativo de compra | <a href="https://github.com/izabellaalves">Izabella Alves</a> |
|<a id="veiculo">L02 - Veículo </a> | Objeto | É qualquer meio usado para transportar ou conduzir pessoas de um lugar para outro. | O <a href="#usuario">usuário</a> pode <a href="#cadastrar">cadastrar</a>, <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> <a href="# boletobancario">boletos bancários</a> de <a href="#veiculo">veículos</a>.| Carro, automóvel, transporte.| <a href="https://github.com/GZaranza">Gabriel Zaranza</a> |
| <a id="usuario">L03 - Usuário</a> | Objeto |  O <a href="#usuario">usuário</a> é geralmente classificado como uma entidade ou objeto em sistemas de informação e tecnologia da informação.| O <a href="#usuario">usuário</a> é fundamental para a personalização e segurança dos sistemas. Ele permite que os sistemas forneçam experiências personalizadas, mantenham o controle de preferências e atividades do usuário e implementem medidas de segurança, como controle de acesso e rastreamento de atividades. .| Cliente, consumidor, operador, end-user (usuário final). | <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a> |
| <a id="imovel">L04 - Imóvel</a> | Objeto | Refere-se a uma propriedade física, como uma casa, apartamento, terreno ou edifício. | O <a href="#usuario">usuário</a> pode <a href="#cadastrar">cadastrar</a>, <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> <a href="#boletobancario">boletos bancários</a> relacionados a <a href="#imovel">imóveis</a> no aplicativo Economia DF. | Propriedade, residência, casa. |  <a href="https://github.com/Lucas13032003">Lucas Víctor</a> |
| <a id="saldo">L05 - Saldo</a> | Objeto | É a quantidade total de créditos que um <a href="#usuario">usuário</a> possui no sistema do Economia DF. |  O <a href="#saldo">Saldo</a> é usado para acompanhar a quantidade de créditos que um <a href="#usuario">usuário</a> pode resgatar ou transferir.| Créditos, Quantia | <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> |
| <a id="seedf">L06 - Secretaria de Estado de Economia do DF</a> | Objeto | Órgão do governo do Distrito Federal responsável por formular, coordenar e executar a política econômica, tributária e fiscal do estado. | Responsável pelo desenvolvimento e manutenção do aplicativo 'Economia DF' | SEE-DF | <a href="https://github.com/lucassouzs">Lucas Ribeiro</a> |
| <a id="nfe">L07 - NFe</a> | Objeto | É um documento fiscal digital que substitui a antiga nota fiscal em papel. Ela é utilizada para registrar a venda de produtos ou a prestação de serviços e é emitida eletronicamente, cumprindo as regulamentações fiscais. | Registra vendas e serviços eletronicamente, atendendo às regulações fiscais. | Nota Fiscal Eletrônica |<a href="https://github.com/zenildavieira">Zenilda Vieira</a> |
| <a id="nfce">L08 - NFCe</a> | Objeto | É um tipo de nota fiscal eletrônica destinada a registrar a venda de produtos ou a prestação de serviços diretamente ao consumidor final.| Registra vendas diretas a consumidores, simplificando o processo de emissão. | Nota Fiscal de Consumidor Eletrônica |<a href="https://github.com/zenildavieira">Zenilda Vieira</a> |
| <a id="bpe">L09 - BPe</a> | Objeto | É um documento fiscal eletrônico que é utilizado para registrar a prestação de serviços de transporte de passageiros.| Registra serviços de transporte de passageiros eletronicamente. | Bilhete de Passagem Eletrônico |<a href="https://github.com/zenildavieira">Zenilda Vieira</a> |
| <a id="dar">L10 - DAR</a> | Objeto | É um documento utilizado para efetuar o pagamento de tributos e outras receitas públicas, como taxas e contribuições. É emitido pela Receita Federal, Secretarias da Fazenda Estaduais e outros órgãos governamentais. | Permite o pagamento de tributos e outras receitas públicas. | Documento de Arrecadação de Receitas |<a href="https://github.com/zenildavieira">Zenilda Vieira</a> |
| <a id="danfe">L11 - DANFE</a> | Objeto | É um documento auxiliar que acompanha a NFe quando a mesma é impressa em papel. Ele contém informações resumidas da NFe e é utilizado para acompanhar o transporte das mercadorias e cumprir requisitos legais.| Acompanha NFe impressa, fornecendo informações resumidas. | Documento Auxiliar da Nota Fiscal Eletrônica|<a href="https://github.com/zenildavieira">Zenilda Vieira</a> |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> Autores das descrições dos léxicos classificados como Objetos, 2023</p></font>

</div>

## Verbos

Os léxicos do tipo verbo representam ações ou operações que os usuários podem realizar dentro do aplicativo "Economia DF". Essas ações descrevem as funcionalidades disponíveis para os usuários, permitindo interações específicas e operações no aplicativo. Na tabela 3, é possível verificar os principais léxicos classificados como Verbo que foram identificados no Economia DF.

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Léxicos classificados como Verbos</p></font>
</div>


|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |   Autor                                  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: | :--------------------------------------: |
| <a id="consultar">L12 - Consultar</a> | Verbo | Tarefa realizada pelo <a href="#usuario">usuário</a>. Acontece quando o <a href="#usuario">usuário</a> entra no aplicativo para verificar suas informações sobre <a href="#notasfiscais">notas fiscais</a>, <a href="#dividaativa">dívida ativas</a>, entre outros. | Em alguns casos, o usuário precisa <a href="#cadastrar">cadastrar</a> algo, caso não consiga <a href="#consultar">consultar</a> de imediato. A partir da consulta, é possível <a href="#selecionar">selecionar</a> e <a href="#emitir">emitir</a> o que se estava procurando.| Visualizar, informar-se | <a href="https://github.com/izabellaalves">Izabella Alves</a> |
| <a id="emitir">L13 - Emitir</a> | Verbo | Tarefa realizada pelo <a href="#usuario">usuário</a>. Ocorre quando o <a href="#usuario">usuário</a>, após <a href="#consultar">consultar</a>, deseja gerar ou baixar o arquivo PDF de um <a href="# boletobancario">boleto bancário</a>, segunda via de uma <a href="#dividaativa">dívida ativa</a> ou <a href="#parcelamentoadm">parcelamento administrativo</a>. | O  <a href="#usuario">usuário</a> só consegue  <a href="#emitir">emitir</a> <a href="# boletobancario">boletos bancários</a> de <a href="#veiculo">veículos</a> e <a href="#imovel">imóveis</a> cadastrados. <br> Só é possível emitir segunda via de <a href="#dividaativa">dívida ativa</a>. <br> Após <a href="#emitir">emitir</a> é possível baixar o arquivo PDF. | Gerar| <a href="https://github.com/GZaranza">Gabriel Zaranza</a> |
| <a id="cadastrar">L14 - Cadastrar</a> | Verbo |O verbo “cadastrar” geralmente se refere ao ato de registrar ou inserir informações em um sistema ou banco de dados para referência futura.</a>|Permite ao usuário registrar seus dados pessoais, como CPF, e-mail e senha, para criar uma conta e acessar o aplicativo, permite ao usuário registrar seus veículos e imóveis, informando o número do RENAVAM ou da inscrição imobiliária, para consultar e emitir boletos bancários e permite ao usuário registrar suas indicações de notas fiscais, informando o número do CPF do destinatário, para participar de sorteios e receber créditos.|  Registrar, inscrever, matricular. | <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a> |
| <a id="selecionar">L15 - Selecionar</a> | Verbo | Ação realizada pelo [usuário](#usuario) no aplicativo Economia DF. Refere-se à escolha ou marcação de opções, itens ou configurações disponíveis no aplicativo para personalizar a experiência do [usuário](#usuario). | Permite ao [usuário](#usuario) escolher entre diversas opções e configurar preferências dentro do aplicativo, adaptando-o às suas necessidades e interesses. | Escolher, marcar, optar por | <a href="https://github.com/Lucas13032003">Lucas Víctor</a> |
| <a id="participar">L16 - Participar</a> | Verbo | Tarefa realizada pelo <a href="#usuario">usuário</a> quando ele se inscreve em um Sorteio no sistema do Economia DF. |  Quando um <a href="#usuario">usuário</a> <a href="#participar">participa</a> de um Sorteio, ele tem a chance de ganhar prêmios com base em suas notas fiscais registradas.| Inscrever-se, Entrar | <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> |
| <a id="visualizar">L17 - Visualizar</a> | Verbo | A ação de visualizar permite aos <a href="#usuarios">usuários</a> explorarem dados contidos no aplicativo Economia DF de forma interativa, fornecendo uma compreensão visual e detalhada de suas informações, facilitando análises e tomadas de decisão.|Quando um <a href="#usuario">usuário</a> registra um objeto, ele consegue <a href="#visualizar">visualizar</a> uma lista desses objetos registrados.|Ver, observar| <a href="https://github.com/lucassouzs">Lucas Ribeiro</a> |
| <a id="lançar">L18 - Lançar</a> | Verbo | Inclusão de informações dos <a href="#usuarios">usuários</a> em registros.| Registra transações financeiras ou fiscais de um <a href="#usuario">usuário</a> em um sistema.|Registrar| <a href="https://github.com/zenildavieira">Zenilda Vieira</a> |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> Autores das descrições dos léxicos classificados como Verbos, 2023</p></font>

</div>

## Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem existir dentro do aplicativo "Economia DF". Na tabela 4, é possível verificar os principais léxicos classificados como Estados que foram identificados no Economia DF.

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Léxicos classificados como Estados</p></font>
</div>



|     Léxico     |   Classificação   |   Noção  |       Impacto       |   Sinônimo  |   Autor                                  |
| :------------: | :---------------: | :------: | :-----------------: | :---------: | :--------------------------------------: |
| <a id="dividaativa">L19 - Dívida ativa</a> | Estado | Débito do <a href="#usuario">usuário</a> perante a <a href="#seed">Secretária de Economia do DF</a> encontra-se ativo. Ocorre quando um valor não é pago na data de vencimento, portanto é classificado como <a href="#dividaativa">dívida ativa</a>.|É possível <a href="#consultar">consultar</a> e <a href="#emitir">emitir</a> as <a href="#dividaativa">dívidas ativas</a> do <a href="#usuario">usuário</a>. Quando o <a href="#usuario">usuário</a> paga sua dívida, ela sai da situação atual.| Débito corrente | <a href="https://github.com/izabellaalves">Izabella Alves</a> |
| <a id="notificacao">L20 - Notificação</a> | Estado | Representa o status de uma mensagem ou aviso enviado ao [usuário](#usuario). Pode estar nos estados de lida, não lida, ou arquivada, indicando se a notificação foi ou não visualizada pelo [usuário](#usuario). | O [usuário](#usuario) pode verificar o [estado das notificações](#notificacao) para acompanhar mensagens importantes e as que ainda não foram lidas. Quando uma notificação é marcada como "lida" ou "arquivada", seu [estado](#notificacao) é atualizado. | Status de mensagem, aviso. | <a href="https://github.com/Lucas13032003">Lucas Víctor</a> |
| <a id="inscrito">L21 - Inscrito</a> | Estado | É quando um <a href="#usuario">usuário</a> se inscreveu em um Sorteio no sistema Nota Legal |  Um <a href="#usuario">usuário</a> <a href="#inscrito">inscrito</a> tem a chance de ganhar prêmios com base em suas notas fiscais registradas.| Participante, Ingressado | <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> |
| <a id="situacaofiscal">L22 - Situação Fiscal</a> | Estado | Estado tributário de uma entidade ou <a href="#usuario">usuário</a> |  Reflete a conformidade ou irregularidade do <a href="#usuario">usuário</a> ou entidade perante as autoridades fiscais | Condição fiscal | <a href="https://github.com/zenildavieira">Zenilda Vieira</a> |


<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> Autores das descrições dos léxicos classificados como Estados, 2023</p></font>

</div>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 04 de março de 2022.
>
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/10/2023|Criação do documento e adição dos lexicos consultar, divida ativa e nota fiscal|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|15/10/2023|Adicionando léxicos emitir e veículo|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.2`|16/10/2023|Adicionando léxicos cadastrar e usuário|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.3`|17/10/2023|Adicionando léxicos Selecionar e Imóvel|[Lucas Víctor](https://github.com/Lucas13032003) |[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.4`|17/10/2023|Adicionando léxicos Notificação|[Lucas Víctor](https://github.com/Lucas13032003) |[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.5`|17/10/2023|Adicionando léxicos inscrito, saldo e participar|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.6`|18/10/2023|Adicionando léxicos visualizar e Secretaria de Estado de Economia do DF|[Lucas Ribeiro](https://github.com/lucassouzs)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.7`|18/10/2023|Adicionando léxicos lançar, NFe, NFCe, BPe, DAR, DANFE e Situação Fiscal|[Zenilda Vieira](https://github.com/zenildavieira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.8`|22/10/2023|Padronizando localização dos nomes das figuras/tabelas e das fontes nas legendas|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.9`|22/10/2023|Revisão geral do documento|[Zenilda Vieira](https://github.com/zenildavieira)| - (revisão não precisa de revisor) |
