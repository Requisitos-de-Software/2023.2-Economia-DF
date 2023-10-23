# First Thing First

## Introdução

Neste documento, apresentamos o resultado da técnica First Thing First para a priorização dos requisitos elicitados pela equipe. Essa técnica consiste em equilibrar os benefícios de cada funcionalidade com o custo de sua implementação. É necessário envolver representantes dos clientes e do desenvolvimento para alinhar requisitos e regras de negócios. É também levado em conta o risco técnico de cada requisito.

## Cronograma da Reunião

Na tabela 1 abaixo consta o cronograma da reunião.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Cronograma da Reunião.</p></font>
</div>

| Data | Hora | Local | Assunto | Participantes |
| :--: | :--: | :---: | ------- | ------------ |
| 30/09/2023 | 16h | Teams | Priorização de requisitos elicitados utilizando a técnica First Thing First | Desenvolvedor [Gabriel Rosa](https://github.com/gabrielrosa09) <br> Gerente [Izabella Alves](https://github.com/izabellaalves) <br> Persona Maria ([Zenilda Vieira](https://github.com/zenildavieira))

<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</p></font>
</div>

## Metodologia

A reunião foi marcada pela gerente de projeto [Izabella Alves](https://github.com/izabellaalves) para ser realizada pelo teams, no dia 30/09/2023 às 16h e foram convocados um representante dos desenvolvedores ([Gabriel Rosa](https://github.com/gabrielrosa09)) e uma representante dos clientes ([Zenilda Vieira](https://github.com/zenildavieira) no papel da [persona Maria](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/personas.md)).

Essa reunião foi gravada e foi preenchida uma tabela com as seguintes colunas: "Benefício Relativo", "Penalidade Relativa", "Custo Relativo" e "Risco Relativo".

Cada linha da tabela representava um requisito elicitado. Após a gerente ler o requisito, a cliente Maria classificava de 1 a 9 o benefício relativo (onde 1 é menos significativo e 9 o máximo) e a penalidade relativa (onde 1 significa que não há penalidade se o requsito não for implementado e 9 indica uma grande desvantagem). 

Em seguida, o desenvolvedor Gabriel classificava de 1 a 9 o custo relativo (considerando a complexidade da implementação, a interface de usuário necessária, a capacidade potencial de reutilização de telas ou código e os testes e documentações necessários) e o risco relativo (onde 1 significa muito fácil de programar e 9 indica sérias preocupações sobre viabilidade, disponibilidade de pessoal com o conhecimento necessário ou uso de ferramentas e tecnologias desconhecidas).

Após o preenchimento dessa tabela para todos os requisitos elicitados, foram calculados:

### O valor total

- ( benefício relativo * peso relativo ) + ( penalidade relativa * peso relativo )
- Foi usado o peso relativo dos benefícios igual a 2 e o peso relativo das penalidades igual a 1, para dar maior importância aos benefícios.

### O valor %

- ( valor total / soma de todos os valores totais ) * 100 %

### O custo %

- ( custo relativo / soma de todos os custos relativos ) * 100 %

### O risco %

- ( risco relativo / soma de todos os riscos relativos ) * 100 %

### O prioridade

- valor % / ( ( custo % * peso custo ) +  ( risco % * peso risco ) )
- Foi usado o peso relativo do custo e o peso relativo do risco iguais a 1.

E, por fim, a tabela foi reordenada em ordem decrescente de prioridade resultando no que é mostrado na Figura 1 abaixo.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Tabela utilizada na priorização dos requisitos utilizando a técnica First Thing First.</p></font>

<img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/tabela-first-thing-first.png?raw=true">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</p></font>
</div>

## Link da Gravação

[Priorização - First Thing First](https://youtu.be/bedI9YdRKF8)

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 30/09/2023.

## Histórico de Versões

| Versão | Data       | Descrição            | Autor                                                      | Revisor                                     |
| :----: | ---------- | -------------------- | :--------------------------------------------------------: | :-----------------------------------------: |
| `1.0`  | 30/09/2023 | Criação do documento | [Zenilda Vieira](https://github.com/zenildavieira) | [Izabella Alves](https://github.com/izabellaalves) |
| `1.1`  | 01/10/2023 | Inclusão dos resultados e tabela dos cálculos | [Zenilda Vieira](https://github.com/zenildavieira) | [Gabriel Rosa](https://github.com/gabrielrosa09) <br> [Izabella Alves](https://github.com/izabellaalves) |
| `1.2`  | 02/10/2023 | Adiçao do link da gravação | [Lucas Ribeiro de Souza](https://github.com/lucassouzs) | [Gabriel da Silva Rosa](https://github.com/gabrielrosa09) |
