# Casos de Uso
## Introdução

## Metodologia

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda do diagrama de caso de uso.</p></font>
| Elemento | Nome | Função |
|:-------:|------|------|
| <figure class="usecaseElement" style="width: 20%; display: flex;">![actor](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-ator.drawio.png?raw=true)</figure> | Ator | Representam os diferentes tipos de usuários externos que interagem com o sistema |
| <figure class="usecaseElement" style="width: 40%; display: flex;">![elipse](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-caso-de-uso.drawio.png?raw=true)</figure> | Elipse (Caso de Uso) | É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso |
| <figure class="usecaseElement" style="width: 40%; display: flex;">![retangulo](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-limites.drawio.png?raw=true)</figure> | Retângulo (Sistema) | Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados |
| <figure class="usecaseElement" style="width: 40%; display: flex;">![flechas](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/uc-relacionamentos.drawio.png?raw=true)</figure> | Flecha (Relações) | As flechas são usadas para representar as relações ou interações entre atores e casos de uso |

**Fonte:** [Izabella Alves](https://github.com/izabellaalves) e [Zenilda Vieira](https://github.com/zenildavieira), 2023.
</div>

## Diagrama de Casos de Uso
A figura 1 demonstra o diagrama de casos de uso.
<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama de caso de uso do aplicativo Economia DF.</p></font>

<img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/diagrama-caso-de-uso.drawio.png?raw=true" class="usecaseElement">

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/zenildavieira">Zenilda Vieira</a></b></p></font>

</div>

## Especificação dos Casos de Uso

### UC0X. "EXEMPLO"

<div align="center">

| UC0X | "EXEMPLO" |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta/Média/Baixa |
| **Pré-condições** | O usuário xxxxxxxx |
| **Fluxo básico** | <ol> <li> O usuário XXXXXX <li> O usuário escolhe XXXXXX <li> Abrir XXXXXX </ol> |
| **Fluxos alternativos** | <b>Fluxo 1: XXXXXXXX</b> <ol> <li> XXXXXXXX <li> XXXXXXX <li> XXXXXXXX <ul> <li> XXXXXXXXX </ul> </ol> <b> Fluxo 2:XXXXXX</b> <ol> <li> XXXXXX <li> XXXXXX </ol> <b> Fluxo 3: XXXXXX</b> <ol> <li> |
| **Fluxos de exceção** | <b>Fluxo 1: XXXXXXXX</b> <ol> <li> XXXXXXXX <li> XXXXXXX <li> XXXXXXXX <ul> <li> XXXXXXXXX </ul> </ol> <b> Fluxo 2:XXXXXX</b> <ol> <li> XXXXXX <li> XXXXXX </ol> <b> Fluxo 3: XXXXXX</b> <ol> <li>|
| **Pós-condições** | O usuário tem acesso a XXXXXX |
| **Data da criação** | dd/mm/aaaa |
| **Rastreabilidade** | ST01, ST02, ST03, ST12, ST13, INT03 |

**Tabela X:** Especificação do caso de uso UC0X. Fonte: [Gabriel Zaranza](https://github.com/GZaranza), 2023.
</div>

### UC13. Cadastrar veículo

<div align="center">

| UC13 | Cadastrar veículo |
| -: | :- |
| **Atores** | Consumidor |
| **Frequência de uso** | Média |
| **Pré-condições** |PRE01. Dispor de uma conexão à internet;</br>PRE02. Possuir um dispositivo com o sistema operacional iOS instalado;</br>PRE03. Ter o aplicativo do Economia DF baixado e instalado no seu dispositivo;</br>PRE04. Possuir um cadastro ativo no aplicativo;</br>PRE05. Possuir um veículo com documentos para ser cadastrado.|
| **Fluxo básico** |FB1. O usuário inicia o aplicativo.</br>FB2. O usuário navega até a seção 'Veículos'.</br>FB3. No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".</br>FB4. O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam.</br>FB5. O usuário clica no botão 'Adicionar', para adicionar o veículo e suas informações.</br>FB6. Finaliza fluxo.|
| **Fluxos alternativos** |FA1. Dados incorretos</br>FA1.1. O usuário inicia o aplicativo.</br>FA1.2. O usuário navega até a seção 'Veículos'.</br>FA1.3. No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".</br>FA1.4. O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam.</br>FA1.5. O usuário clica no botão “Adicionar', para adicionar o veículo e suas informações.</br>FA1.6. O sistema exibe uma mensagem de alerta “Veículo não encontrado”.</br>FA1.7. Finaliza fluxo.</br></br>FA2. Campos em branco</br>FA2.1. O usuário inicia o aplicativo.</br>FA2.2. O usuário navega até a seção 'Veículos'.</br>FA2.3. No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".</br>FA2.4. O usuário deixa um ou todos os campos vazios.</br>FA2.5. O usuário clica no botão 'Adicionar', para adicionar o veículo e suas informações.</br>FA2.6. O sistema exibe uma mensagem de alerta indicando "Campo obrigatório" para cada campo vazio durante o processo de inserção de dados.</br>FA2.7. Finaliza fluxo.</br></br>FA3. Acesso à Seção "Veículos" pelo Menu</br>FA3.1. O usuário inicia o aplicativo.</br>FA3.2. No canto superior esquerdo da tela, o usuário clica no botão 'Menu', indicado pelas 3 barras paralelas horizontais.</br>FA3.3. O usuário navega até a seção 'Veículos'.</br>FA3.4. No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+".</br>FA3.5. O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam.</br>FA3.6. O usuário clica no botão 'Adicionar', para adicionar o veículo e suas informações.</br>FA3.7. Finaliza fluxo.|
| **Fluxos de exceção** |FE1. Sem internet </br>FE1.1. O usuário inicia o aplicativo. </br>FE1.2. O usuário nageva até a seção 'Veículos'. </br>FE1.3. No canto inferior direito da tela, o usuário clica no botão azul com o símbolo "+". </br>FE1.4. O usuário insere os dados do veículo, incluindo apelido (Nome de identificação), Placa e Renavam. </br>FE1.5. O sistema exibe uma mensagem de alerta “Não foi possível conectar com os servidores da SEEC DF”. </br>FE1.6. Finaliza fluxo.|
| **Pós-condições** |POS01. O veículo está registrado com sucesso no sistema.</br>POS02. O veículo está associado à conta do usuário que realizou o cadastro.</br>POS03. O apelido (Nome de identificação), número da placa e Renavam estão corretamente armazenados no sistema para referência futura.</br>POS04. O veículo está acessível para funcionalidades adicionais oferecidas pelo aplicativo, como rastreamento, manutenção ou renovação de licença, dependendo das características do serviço.|
| **Data da criação** |10/10/2023|
| **Rastreabilidade** |[INT27](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md), [INT28](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/requisitos-elicitados.md)|

**Tabela X:** Especificação do caso de uso UC13. Fonte: [Lucas Ribeiro de Souza](https://github.com/lucassouzs), 2023.
</div>

### UC14. Consultar ajuda

<div align="center">

| UC14 | Consultar ajuda |
| -: | :- |
| **Atores** ||
| **Frequência de uso** ||
| **Pré-condições** ||
| **Fluxo básico** ||
| **Fluxos alternativos** ||
| **Fluxos de exceção** ||
| **Pós-condições** ||
| **Data da criação** ||
| **Rastreabilidade** ||

**Tabela X:** Especificação do caso de uso UC14. Fonte: [Lucas Ribeiro de Souza](https://github.com/lucassouzs), 2023.
</div>

### UC15. Entrar em contato

<div align="center">

| UC15 | Entrar em contato |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** ||
| **Pré-condições** ||
| **Fluxo básico** ||
| **Fluxos alternativos** ||
| **Fluxos de exceção** ||
| **Pós-condições** ||
| **Data da criação** ||
| **Rastreabilidade** ||

**Tabela X:** Especificação do caso de uso UC15. Fonte: [Lucas Ribeiro de Souza](https://github.com/lucassouzs), 2023.
</div>

### UC16. Enviar e-mail

<div align="center">

| UC16 | Enviar e-mail |
| -: | :- |
| **Atores** ||
| **Frequência de uso** ||
| **Pré-condições** ||
| **Fluxo básico** ||
| **Fluxos alternativos** ||
| **Fluxos de exceção** ||
| **Pós-condições** ||
| **Data da criação** ||
| **Rastreabilidade** ||

**Tabela X:** Especificação do caso de uso UC16. Fonte: [Lucas Ribeiro de Souza](https://github.com/lucassouzs), 2023.
</div>

## Referências Bibliográficas
## Bibliografia
> Lucid Software Português. Tutorial de Caso de Uso UML [Recurso eletrônico: vídeo], 2019.  Disponível em: <https://www.youtube.com/watch?v=ab6eDdwS3rA>.  Acesso em: 09 de outubro ed 2023.
>
> VLC. Casos de Uso. Grupo VLC da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso>. Acesso em: 10 de outubro de 2023.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|09/10/2023|Criação do documento e diagrama de caso de uso|[Izabella Alves](https://github.com/izabellaalves) e [Zenilda Vieira](https://github.com/zenildavieira)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|10/10/2023|Adicionando a tabela exemplo da especificação dos casos de uso|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.2`|10/10/2023|Adicionando a tabela UC13 da especificação dos casos de uso|[Lucas Ribeiro de Souza](https://github.com/lucassouzs)|[Gabriel Zaranza](https://github.com/GZaranza)|
