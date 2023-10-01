# First Thing First

## Introdução

Neste documento, apresentamos o resultado da técnica First Thing First para a priorização dos requisitos elicitados pela equipe. Essa técnica consiste em equilibrar os benefícios de cada funcionalidade com o custo de sua implementação. É necessário envolver representantes dos clientes e do desenvolvimento para alinhar requisitos e regras de negócios. é também levado em conta o risco técnico de cada requisito.

## Metodologia

Em uma reunião com a Gerente do projeto ([Izabella Alves](https://github.com/izabellaalves)), o representante dos desenvolvedores ([Gabriel Rosa](https://github.com/gabrielrosa09)) e a representante dos clientes ([Zenilda Vieira](https://github.com/zenildavieira) no papel da [persona Maria](/docs/elicitacao/personas.md)), foi preenchida uma tabela com as seguintes colunas: "Benefício Relativo", "Penalidade Relativa", "Custo Relativo" e "Risco Relativo". 

Cada linha da tabela representava um requisito elicitado. Após a Gerente ler o requisito, a cliente Maria classificava de 1 a 9 o benefício relativo (onde 1 é menos significativo e 9 o máximo) e a penalidade relativa (onde 1 significa que não há penalidade se o requsito não for implementado e 9 indica uma grande desvantagem). 

Em seguida, o desenvolvedor Gabriel classificava de 1 a 9 o custo relativo (considerando a complexidade da implementação, a interface de usuário necessária, a capacidade potencial de reutilização de telas ou código e os testes e documentações necessários) e o risco relativo (onde 1 significa muito fácil de programar e 9 indica sérias preocupações sobre viabilidade, disponibilidade de pessoal com o conhecimento necessário ou uso de ferramentas e tecnologias desconhecidas).

Após o preenchimento dessa tabela para todos os requisitos elicitados, foram calculados:
> o valor total: 
   - ( benefício relativo * peso relativo ) + ( penalidade relativa * peso relativo )
   - Foi usado o peso relativo dos benefícios igual a 2 e o peso relativo das penalidades igual a 1, para dar maior importância aos benefícios.
> o valor %: 
   - ( valor total / soma de todos os valores totais ) * 100 %
> o custo %: 
   - ( custo relativo / soma de todos os custos relativos ) * 100 %
> o risco %: 
   - ( risco relativo / soma de todos os riscos relativos ) * 100 %
> a prioridade: 
   - valor % / ( ( custo % * peso custo ) +  ( risco % * peso risco ) )

E, por fim, a tabela foi reordenada em ordem decrescente de prioridade resultando no que é mostrado na Figura 1 abaixo.

<img src="/docs/imagens/tabela-first-thing-first.png">

**Figura 1:** Tabela utilizada na priorização dos requisitos utilizando a técnica First Thing First  <br>
Fonte: Autores.


## Bibliografia
> SERRANO, Milene; SERRANO, Maurício. Aula 07 - Requisitos - UnB Gama - Slides.


## Histórico de Versões
| Versão | Data       | Descrição            | Autor                                                      | Revisor                                     |
| :----: | ---------- | -------------------- | :--------------------------------------------------------: | :-----------------------------------------: |
| `1.0`  | 30/09/2023 | Criação do documento | [Zenilda Vieira](https://github.com/zenildavieira) | [Izabella Alves](https://github.com/izabellaalves) |
| `1.1`  | 01/10/2023 | Inclusão dos resultados e tabela dos cálculos | [Zenilda Vieira](https://github.com/zenildavieira) | [Gabriel Rosa](https://github.com/gabrielrosa09) <br> [Izabella Alves](https://github.com/izabellaalves) |
