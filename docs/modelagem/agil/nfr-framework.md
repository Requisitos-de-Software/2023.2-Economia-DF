# NFR Framework
## Introdução
NFR (Non-Functional Requirements) Framework, ou "Framework de Requisitos Não Funcionais", é uma abordagem essencial no desenvolvimento de software e engenharia de sistemas, que visa definir e gerenciar requisitos que não se relacionam diretamente com as funcionalidades específicas de um sistema, mas sim com suas características de desempenho, segurança, usabilidade e outros aspectos que afetam a qualidade do software. Esses requisitos não funcionais são igualmente críticos para o sucesso de um projeto, pois determinam como o sistema deve se comportar em termos de eficiência, confiabilidade e experiência do usuário.

O Framework faz uso do conceito de "softgoal", que se refere a um objetivo desprovido de uma definição clara e critérios de satisfação precisos. Os softgoals desempenham o papel de representar os Requisitos Não-Funcionais e podem estar conectados entre si, refletindo a influência de um softgoal sobre outro.

O NFR Framework opera por meio da construção de um gráfico chamado "Softgoal Interdependency Graph (SIG)", que registra as considerações do desenvolvedor sobre os softgoals e suas interconexões. Esses gráficos contêm informações detalhadas sobre decisões de desenvolvimento, incluindo Requisitos Não-funcionais, alternativas, e as justificativas por trás das decisões. Isso permite a avaliação de requisitos de alto nível para garantir que sejam atendidos.

Existem três tipos de softgoals, eles estão descritos abaixo e suas representações podem ser vistas na figura 1, que foram tiradas da discertação de mestrado de Reinaldo Antônio da Silva: NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados [1]. Essa figura também servirá como legenda para os NFRs que serão apresentados neste documento.

- Softgoals NFR: Eles representam os Requisitos Não-Funcionais e podem ser organizados hierarquicamente no desenvolvimento do projeto.

- Softgoals de Operacionalização: Representam as soluções de implementação para atender aos softgoals NFR ou outros softgoals de operacionalização. Isso inclui operações, processos, estruturas de dados e restrições no sistema para cumprir as necessidades indicadas pelos softgoals.

- Softgoals de Afirmação: São usados para considerar as características do domínio, como prioridades e carga de trabalho, no processo de tomada de decisão. Eles servem como justificação para apoiar ou negar a priorização e seleção de componentes, facilitando a revisão, a justificação e a melhoria do sistema, bem como o rastreamento das decisões de desenvolvimento.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Representação dos tipos de softgoal.</p></font>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/488b24a3f8030eb09c0b30d82ebe620d2442483b/docs/imagens/nfr-softgoals.png?" style="width: 45%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> (CHUNG et al., 2000).</a></p></font>
</div>

O processo de avaliação determina o nível de satisfação dos requisitos não funcionais por meio de um conjunto de decisões. Em outras palavras, o procedimento de avaliação verifica se cada softgoal ou interdependência no SIG foi satisfatoriamente atendido. Isso é alcançado por meio da atribuição de rótulos aos softgoals, com rótulos possíveis incluindo "satisfeito," "parcialmente satisfeito," "não atendido," "parcialmente não atendido," "conflitante" e "indeterminado". Na imagem 2, podemos ver um exemplo de cada rótulo, tirado do artigo de Reinaldo Antônio da Silva [1]. Essa figura também servirá como legenda para os NFRs que serão apresentados neste documento.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 2:</b> Rótulos da propagação de impactos.</p></font>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/488b24a3f8030eb09c0b30d82ebe620d2442483b/docs/imagens/nfr-impactos.png?raw=true" style="width: 65%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> (CHUNG et al., 2000).</a></p></font>
</div>

## Metodologia
Neste documento, serão apresentads 7 NFRs, que foram definidos a partir do nosso documento de [especificação suplementar](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/), que por sua vez se baseou no modelo FURPS+, e cada membro da equipe fez o NFR de uma categoria do modelo FURPS+.

Para cada categoria, foi feito um SIG (Softgoal Interdependency Graph), um diagrama da propagação de impactos e um cartão de especificação, que possui informações sobre o NFR, como a descrição, a categoria, os conflitos, a origem, os critérios e outras informações.

## NFR Framework

### Desempenho

xxx

#### Softgoal Interdependency Graph

O Softgoal Interdependency Grap do softgoal "Desempenho" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Grap do softgoal "Desempenho".</p></font>

<img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/SIG_desempenho.drawio.png?raw=true" style="width: 75%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Desempenho" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Desempenho"</p></font>

<img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/impacto_desempenho.drawio%20(1).png?raw=true" style="width: 75%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div>

#### Cartão de Especificação

Na tabela X, temos o cartão de especificação do softgoal "Desempenho".

<div align="center">
<p><b>Tabela X:</b> Cartão de Especificação do Softgoal Desempenho</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR0X</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Desempenho</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O desempenho de um sistema é relacionado ao tempo para executar ações e a rapidez que o usuário realiza suas tarefas..</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td> É importante garantir um alto desempenho para que a produtividade do usuário seja elevada.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a atualização da documentação deve ser planejada e coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Ajuda e Documentação" é de alta prioridade, uma vez que influencia diretamente a experiência do usuário e a eficácia do aplicativo.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>03/11/2023</td>
  </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div>

### Ajuda e documentação

A "Ajuda e Documentação" em um aplicativo refere-se a um conjunto de recursos elaborados para orientar e fornecer informações aos [usuários](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#objetos) sobre o funcionamento, características e melhores práticas de uso do aplicativo. Essa seção é fundamental para garantir que os usuários possam usar o aplicativo de forma eficaz, resolver dúvidas e aproveitar ao máximo suas funcionalidades.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Grap do softgoal "Ajuda e documentação" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Grap do softgoal "Ajuda e documentação".</p></font>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/nfr-ad.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Ajuda e documentação" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Ajuda e documentação"</p></font>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/nfr-ajuda-documentacao-analise.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

#### Cartão de Especificação
Na tabela X, temos o cartão de especificação do softgoal "Ajuda e Documentação".

<div align="center">
<p><b>Tabela X:</b> Cartão de Especificação do Softgoal Ajuda e Documentação</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR0X</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Ajuda e Documentação</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Ajuda e Documentação" refere-se à capacidade de fornecer recursos detalhados para orientar e informar os usuários sobre o aplicativo "Economia DF".</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>A qualidade da Ajuda e Documentação é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência, solucionar problemas e tirar o máximo proveito das funcionalidades.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a atualização da documentação deve ser planejada e coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Ajuda e Documentação" é de alta prioridade, uma vez que influencia diretamente a experiência do usuário e a eficácia do aplicativo.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>02/11/2023</td>
  </tr>
</table>
<p><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</p>
</div>

### Interfaces

O aplicativo deve possuir uma interface simples, de fácil navegação e padronizada para que os usuários possam atingir seus objetivos. Os requisitos não-funcionais para interfaces foram classificados em três frentes: interface de usuário, interface de hardware e interface de comunicação.

#### Softgoal Interdependency Graph

Na figura X a seguir, é demonstrado o SIG - Softgoal Interdependency Grap - do softgoal "Interfaces".

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Grap do softgoal "Interfaces".</p></font>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/nfr-interfaces.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

#### Propagação de Impactos

Após a definição do SIG, foi feita a análise de propagação de impactos do softgoal "Interfaces". O resultado dessa análise pode ser visto na Figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Interfaces"</p></font>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/nfr-interfaces-analise.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

#### Cartão de Especificação

Para complementar o estudo do NFR Framework, foi construído o cartão de especificação do softgoal "Interfaces", que pode ser visto na Tabela X a seguir.

<div align="center">
<p><b>Tabela X:</b> Cartão de Especificação do Softgoal Interfaces</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFRXX</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Interfaces de usuário, de hardware e de comunicação.</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Interfaces" refere-se à forma como o usuário interage com o aplicativo, devendo esse apresentar interfaces de usuário de fácil compreensão e navegação, interfaces de hardware em pelo menos duas plataformas: iOS e Android e interfaces de comunicação por dados móveis e wi-fi.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Esse RNF se justifica pela necessidade do usuário interagir com o aplicativo de forma fácil e intuitiva, que ele tenha poder de escolha entre pelo menos duas palataformas e que o aplicativo esteja sempre disponível, a qualquer momento e em qualquer lugar.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/">Especificação Suplementar</a> e <a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/">Requisitos Elicitados</a></td>.
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificados requisistos relacionados a este.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Interfaces" é de alta prioridade (10), pois afeta a experiência do usuário diretamente.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum requisito que entre em conflito com este.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>Data de criação: 04/11/2023</td>
  </tr>
</table>
<p><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</p>
</div>


### Usabilidade 

Usabilidade, segundo Nielsen, é a medida de quão fácil e agradável é usar um sistema para alcançar os objetivos dos usuários.


#### Softgoal Interdependency Graph

O Softgoal Interdependency Grap do softgoal "Usabilidade" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Grap do softgoal "Usabilidade".</p></font>

<img src="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/imagens/diagramausabilidade.png?raw=true" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Usabilidade" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do softgoal "Usabilidade"</p></font>

<img src="" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023</p></font>
</div>

#### Cartão de Especificação
Na tabela X, temos o cartão de especificação do softgoal "Usabilidade".

<div align="center">
<p><b>Tabela X:</b> Cartão de Especificação do Softgoal Usabilidade</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR0X</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Usabilidade</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Usabilidade" refere-se à capacidade do sistema de entregar uma boa usabilidade para os usuários do aplicativo do "Economia DF".</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td>Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir uma satisfação do usuário, aumentando a acessibilidade e por consequência tendo uma redução de erros.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a atualização da documentação deve ser planejada e coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Usabilidade" é de alta prioridade, uma vez que influencia diretamente a satisfação do usuário e a eficácia do aplicativo.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>04/11/2023</td>
  </tr>
</table>
<p><b>Fonte:</b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023.</p>
</div>

### Restrições de Design

As "Restrições de Design" em um aplicativo referem-se às limitações ou condições específicas que os designers e desenvolvedores precisam levar em consideração ao criar a interface do usuário e a experiência dos usuários, sendo fundamentais para garantir a usabilidade, acessibilidade e compatibilidade de um aplicativo.

#### Softgoal Interdependency Graph

O Softgoal Interdependency Graph do Softgoal "Restrições de Design" pode ser visto na imagem X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Softgoal Interdependency Grap do Softgoal "Restrições de Design".</p></font>

<img src="" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

#### Propagação de Impactos

A propagação de impactos do softgoal "Restrições de Design" pode ser visto na figura X.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura X:</b> Propagação de impactos do Softgoal "Restrições de Design"</p></font>

<img src="" style="width: 85%;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

#### Cartão de Especificação
Na tabela X, temos o cartão de especificação do Softgoal "Restrições de Design".

<div align="center">
<p><b>Tabela X:</b> Cartão de Especificação do Softgoal “Restrições de Design”</p>
<table>
  <tr>
    <th>Tópico</th>
    <th>Informação</th>
  </tr>
  <tr>
    <td>ID do NFR</td>
    <td>NFR0X</td>
  </tr>
  <tr>
    <td>Classificação</td>
    <td>Restrições de Design</td>
  </tr>
  <tr>
    <td>Descrição</td>
    <td>O requisito "Restrições de Design" refere-se a limitações ou condições específicas que devem ser consideradas durante o processo de design de um produto, sistema ou projeto.</td>
  </tr>
  <tr>
    <td>Justificativa</td>
    <td> As Restrições de Design são fundamentais pois garantem que um produto ou sistema seja viável, eficiente e de alta qualidade. Elas ajudam a cumprir regulamentações, considerar as necessidades dos usuários e usar recursos de forma sustentável.</td>
  </tr>
  <tr>
    <td>Origem do Requisito</td>
    <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/">Especificação suplementar</a> e <a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/">requisitos elicitados</a></td>
  </tr>
  <tr>
    <td>Dependências</td>
    <td>Não foram identificadas restrições ou dependências específicas, mas a atualização da documentação deve ser planejada e coordenada com as versões do aplicativo.</td>
  </tr>
  <tr>
    <td>Prioridade</td>
    <td>O requisito de "Restrições de Design" é de alta prioridade devido ao seu impacto direto na viabilidade e na qualidade do produto.</td>
  </tr>
  <tr>
    <td>Conflitos</td>
    <td>Não foi identificado nenhum conflito.</td>
  </tr>
  <tr>
    <td>História</td>
    <td>04/11/2023</td>
  </tr>
</table>
<p><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023.</p>
</div>

## Bibliografia

> SERRANO, Maurício;  SERRANO, Milene. Requisitos - Aula 17. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. Disponível em: [Requisitos - Aula 17](https://aprender3.unb.br/pluginfile.php/2692836/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf). Acesso em: 03 de novembro de 2023.
> 

## Referências Bibliográficas

> [1] SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Universidade Federal de Pernambuco, 2019. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692835/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf>. Acesso em: 02 de novembro de 2023.
>
## Histórico de Versões

| Versão | Data       | Descrição                           | Autor(es)                                                                                           | Revisor(es)                                      |
| ------ | ---------- | ----------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| `1.0`  | 02/11/2023 | Criação do documento                 | [Izabella Alves](https://github.com/izabellaalves)  | [Gabriel Rosa](https://github.com/gabrielrosa09)   |
| `1.1`  | 03/11/2023 | Adicionando "desempenho"          | [Gabriel Zaranza](https://github.com/GZaranza)  | [Gabriel Rosa](https://github.com/gabrielrosa09)   |
| `1.2`  | 04/11/2023 | Adicionando "interfaces"          | [Zenilda Vieira](https://github.com/GZaranza)  | [Gabriel Rosa](https://github.com/gabrielrosa09)   |
| `1.3`  | 04/11/2023 | Adicionando "Usabilidade"          | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)  | [Gabriel Rosa](https://github.com/gabrielrosa09)   |

