# Cenários
## Introdução
## Metologia
## Cenários
### Consultar dívida ativa
O cenário em questão diz respeito ao objetivo "Consultar dívida ativa", sua descrição detalhada está disponível na tabela 1.

<div align="center">

| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Consultar dívida ativa através do aplicativo Economia DF                          |
| Contexto    | Local: em casa<br>Tempo: Aproximadamente 30 segundos<br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF                                     |
| Atores      | Usuário brasileiro com CPF ativo                                                  |
| Episódios   | O *usuário* seleciona a opção Dívida Ativa na tela inicial<br>O aplicativo exibe uma tela com as informações da dívida ativa e uma opção para emitir segunda Via<br>O *usuário* visualiza as informações de seus débitos ativos<br>O *usuário* seleciona a opção Emitir Segunda Via |
| Restrição   | As informações só aparecem se o usuário tiver alguma dívida                         |
| Exceção     | Erro de conexão com a internet<br>Celular com sistema Android                        |

**Tabela 1:** Cenário referente ao objetivo "Consultar dívida ativa". Fonte: [Izabella Alves](https://github.com/izabellaalves), 2023.

</div>

### Consultar veículos
O cenário em questão diz respeito ao objetivo "Consultar veículos", sua descrição detalhada está disponível na tabela 2.
<div align="center">
  
| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Consultar débitos e boletos bancários de um veículo através do aplicativo Economia DF                          |
| Contexto    | Local: em casa<br>Tempo: Aproximadamente 1 minuto<br> Pré-condições: Usuário brasileiro com CPF ativo e RENAVAM do veículo a ser consultado, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF                                     |
| Atores      | Usuário brasileiro com CPF ativo                                                  |
| Episódios   | O *usuário* seleciona a opção "Veículos" na tela inicial<br>O aplicativo exibe uma tela com uma lista de veículos cadastrados e uma opção para cadastrar um novo veículo<br>O *usuário* seleciona um veículo cadastrado<br>O aplicativo exibe uma tela com os débitos relacionados ao veículo<br>O *usuário* seleciona a opção Emitir Segunda Via do boleto nacário |
| Restrição   | Os veículos só aparecem se já tiverem sido cadastrados<br>Os débitos só aparecem caso o veículo possua alguma dívida ativa                          |
| Exceção     | Erro de conexão com a internet<br>Celular com sistema Android                        |

**Tabela 2:** Cenário referente ao objetivo "Consultar Veículos". Fonte: [Gabriel Zaranza](https://github.com/GZaranza), 2023.
</div>

<center>

### Consultar imóveis
| Elemento    | Descrição                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| Objetivo    | Consultar imóveis através do aplicativo Economia DF                          |
| Contexto    | Local: em casa<br>Tempo: Aproximadamente 1 minuto<br> Pré-condições: Usuário brasileiro com CPF, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF                                     |
| Atores      | Usuário brasileiro com CPF ativo                                                  |
| Episódios   | O *usuário* seleciona a opção "Imóveis" na tela inicial<br>O aplicativo exibe uma tela com uma lista de imóveis cadastrados e uma opção para cadastrar um novo imóvel<br>O *usuário* seleciona um imóvel cadastrado<br>O aplicativo exibe uma tela com os débitos relacionados ao imóvel<br>O *usuário* seleciona a opção Emitir Segunda Via do boleto bancário |
| Restrição   | Os imóveis só aparecem se já tiverem sido cadastrados<br>Os débitos só aparecem caso o imóvel possua alguma dívida ativa                          |
| Exceção     | Erro de conexão com a internet<br>Celular com sistema Android                        |

**Tabela 3:** Cenário referente ao objetivo "Consultar Imóveis". Fonte: [Gabriel Rosa](https://github.com/gabrielrosa09), 2023.

</center>

### Fale conosco
Esse cenário corresponde ao objetivo "Fale conosco", sua descrição detalhada está disponível na tabela 4.

<div align="center">

| Elemento    | Descrição                                                                            |
|-------------|------------------------------------------------------------------------------------- |
| Objetivo    | Entrar em contato com a Secretaria de Economia do DF, responsável pelo aplicativo    |
| Contexto    | Local: em casa <br> Tempo: Aproximadamente 1 minuto e meio <br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado, ter aplicativo de e-mail instalado |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF <br> Aplicativo de email           | 
| Atores      | Usuário brasileiro com CPF ativo                                                     |
| Episódios   | O *usuário* seleciona a opção "Fale conosco" na tela inicial<br>O aplicativo redireciona o *usuário* para o aplicativo de email padrão instalado no celular<br>O *usuário* pode escrever o e-mail com dúvidas, sugestões ou reclamações e enviar <br>  |
| Restrição   | Aplicativo de e-mail deve estar instalado no celular                                 |
| Exceção     | Erro de conexão com a internet<br> Não há aplicativo de e-mail instalado no celular <br> Celular com sistema Android 

**Tabela 4:** Cenário referente ao objetivo "Fale conosco". Fonte: [Zenilda Vieira](https://github.com/zenildavieira), 2023.

</div>

### Consultar notas fiscais
Esse cenário corresponde ao objetivo "Consultar notas fiscais", sua descrição detalhada está disponível na tabela 5.

<div align="center">

| Elemento    | Descrição                                                                            |
|-------------|------------------------------------------------------------------------------------- |
| Objetivo    | Consultar notas fiscais através do aplicativo Economia DF      |
| Contexto    | Local: em casa <br> Tempo: Aproximadamente 30 segundos  <br> Pré-condições: Usuário brasileiro com CPF ativo, possuir um celular com sistema IOS, ter o aplicativo Economia DF instalado, ser usuário do programa Nota Legal |
| Recursos    | Internet<br>Sistema IOS<br>Aplicativo Economia DF           | 
| Atores      | Usuário brasileiro com CPF ativo                                                     |
| Episódios   | O *usuário* seleciona a opção "Notas Fiscais" na tela inicial<br>O aplicativo redireciona o *usuário* para a página "Notas Fiscais"<br>O *usuário* pode visualizar, exportar e imprimir <br>  |
| Restrição   | Aplicativo de e-mail deve estar instalado no celular que possua um sistema IOS                                 |
| Exceção     | Erro de conexão com a internet<br> Celular com sistema Android 

**Tabela 5:** Cenário referente ao objetivo "Consultar notas fiscais". Fonte: [Lucas Víctor](https://github.com/Lucas13032003), 2023.

</div>


## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> Bilheteria Digital. Cenários. Grupo Bilheteria Digital da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em: 08 de outubro de 2023.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|1.0|08/10/2023|Criação de documento e adição do cenário sobre "consultar dívida ativa"|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|1.1|09/10/2023|Adição do cenário sobre "consultar veículos"|[Gabriel Zaranza](https://github.com/GZaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|1.2|11/10/2023|Adição do cenário sobre "consultar veículos"|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|1.3|11/10/2023|Adição do cenário sobre "fale conosco" | [Zenilda Vieira](https://github.com/zenildavieira)|[Izabella Alves](https://github.com/izabellaalves)|
|1.4|11/10/2023|Adição do cenário sobre "Consultar notas fiscais" | [Lucas Víctor](https://github.com/Lucas13032003)|[Gabriel Zaranza](https://github.com/GZaranza)|
