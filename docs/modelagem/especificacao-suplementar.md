# Especificação Suplementar

## Introdução

Este documento apresenta a Especificação Suplementar para o aplicativo Economia DF. A Especificação Suplementar é um artefato importante no processo de desenvolvimento de software, pois descreve os requisitos não funcionais do sistema - aqueles que não estão diretamente relacionados com a funcionalidade específica do software, mas com características como desempenho, usabilidade, confiabilidade, entre outros. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário.

## Metodologia

A metodologia utilizada para a elaboração deste documento é baseada no modelo FURPS+, que é uma técnica eficaz para a coleta e organização de requisitos não funcionais. FURPS+ é um acrônimo para Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suporte, que são as principais categorias de requisitos consideradas neste modelo. Além disso, o “+” em FURPS+ representa requisitos adicionais que podem ser relevantes, como restrições de design e requisitos de documentação e ajuda.

Este documento foi estruturado de acordo com as categorias do modelo FURPS+. Cada seção do documento corresponde a uma categoria e apresenta uma descrição detalhada dos requisitos não funcionais relacionados a essa categoria para o aplicativo Economia DF.

## FURPS+

### F: Funcionalidade (Functionality)

Os requisitos funcionais foram elicitados através de uma combinação das seguintes técnicas: [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/instrospeccao.md), [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/brainstorming.md) e [Observação](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/observação.md). Eles podem ser observados no documento [Requisitos Elicitados](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/elicitacao/tecnicas-elicitacao/requisitos-elicitados.md). Os [Casos de Uso](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/casos-de-uso.md) também podem ser considerados como requisitos funcionais.

### U: Usabilidade (Usability)

A usabilidade de um sistema segundo Nielsen é o atributo de qualidade que avalia a facilidade de uso de uma interface. Uma interface com boa usabilidade permite que os usuários realizem suas tarefas de forma eficiente, eficaz e satisfatória.

Na tabela 1, é possível ver os Requisitos Não Funcionais para Usabilidade do aplicativo "Economia DF".

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Requisitos de usabilidade</p></font>
</div>

| ID  | Descrição |
|-----|-----------|
| RU01 | O aplicativo deve ser fácil de usar e intuitivo, permitindo que os usuários realizem suas tarefas com eficiência e sem necessidade de treinamento extensivo. |
| RU02 | O aplicativo deve fornecer feedback imediato após cada ação do usuário, para que eles saibam se a ação foi bem-sucedida ou não. |
| RU03 | O aplicativo deve permitir que os usuários desfaçam ações sempre que possível. Isso pode ser implementado como uma opção “desfazer” no menu ou como um botão de “voltar”. |
| RU04 | O aplicativo deve ser consistente em seu design e comportamento. Isso inclui o uso consistente de cores, fontes, ícones e terminologia, bem como a consistência na localização dos elementos da interface do usuário.. |
| RU05 | O aplicativo deve ser acessível para usuários com diferentes habilidades e necessidades. Isso pode incluir suporte para tecnologias assistivas, como leitores de tela, e conformidade com as diretrizes de acessibilidade da Web Content Accessibility Guidelines (WCAG). |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023</p></font>
</div >

### R: Confiabilidade (Reliability)
A Confiabilidade (Reliability) no aplicativo Economia DF se refere à capacidade do aplicativo de funcionar de forma consistente, estável e sem falhas. Em outras palavras, os usuários podem confiar que o aplicativo funcionará corretamente sempre que o utilizarem. Isso é essencial para garantir uma experiência positiva do usuário, prevenir erros e manter a credibilidade do aplicativo.

Na tabela 2, é possível ver os Requisitos Não Funcionais para Confiabilidade do aplicativo "Economia DF".

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos não funcionais sobre Desempenho</p></font>
</div>

| ID  | Descrição |
|-----|-----------|
| RE01 | O aplicativo deve ser capaz de funcionar sem falhas ou interrupções por um período mínimo de 30 dias consecutivos. Qualquer interrupção não planejada que ocorra deve ser solucionada em até 4 horas a partir do momento da detecção. |
| RE02 | O aplicativo deve ser capaz de lidar com um aumento de 500% na carga de usuários simultâneos sem comprometer a sua estabilidade ou desempenho. |
| RE03 | Os dados do usuário e as informações críticas do aplicativo devem ser armazenados de forma segura e protegidos contra perda de dados. Deve ser realizado backup diário dos dados, e a recuperação de dados deve ser possível em menos de 6 horas em caso de falha. |
| RE04 | O aplicativo deve ter um mecanismo de monitoramento contínuo que alerta a equipe de suporte técnico sobre quaisquer problemas críticos em tempo real. A equipe de suporte deve estar disponível 24/7 para resolver esses problemas. |
| RE05 | As atualizações de software e manutenções planejadas devem ser agendadas fora do horário de pico de uso do aplicativo (por exemplo, durante a noite) e os usuários devem ser notificados com antecedência. |
| RE06 | O aplicativo deve ter a capacidade de se recuperar automaticamente de falhas de hardware, como a substituição de servidores com falha, sem interromper o serviço. |
| RE07 | Em caso de interrupções não planejadas que afetem o funcionamento do aplicativo, os usuários devem ser informados de maneira clara e precisa sobre o problema, o progresso da solução e o tempo estimado de restauração do serviço. |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/Lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div >

### P: Desempenho (Performance)

O desempenho de um sistema é relacionado ao tempo para executar ações e a rapidez que o [usuário](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#objetos) realiza suas tarefas. É importante garantir um alto desempenho para que a produtividade do usuário seja elevada. Na tabela 3 é possível encontrar requisitos não funcionais relacionados ao desempenho do Economia DF.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Requisitos não funcionais sobre Desempenho</p></font>
</div>

| ID  | Descrição |
|-----|-----------|
| PE01  | O tempo de resposta do menu principal do aplicativo deve ser inferior 500 ms |
| PE02  | O tempo para emitir um documento deve ser inferior a 1 segundo  |
| PE03  | O tempo de autenticação do login deve ser inferior a 3 segundos |
| PE04  | O tempo de resposta de uma pesquisa de documentos tem que ser inferior a 1 segundo |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div >

### S: Suporte (Supportability)

#### Suporte e Manutenção

O aplicativo é mantido e atualizado em uma frequência mediana, pois tem um certo tempo de sua última atualização. A última atualização foi em 23 de março de 2021, onde foram atualizados os itens de segurança e a funcionalidade de notícias. Além disso, as atualizações são para garantir que continue funcionando conforme esperado com as versões mais recentes dos sistemas operacionais e para adicionar novas funcionalidades ou corrigir bugs. Isso indica que o aplicativo tem uma boa manutenibilidade.

#### Adaptabilidade

O aplicativo foi projetado para atender aos contribuintes do Distrito Federal, Brasil. No entanto, a falta de informações sobre a capacidade de adaptação para outras regiões ou países sugere que a sua utilidade pode ser limitada fora dessa área geográfica. Para tornar o aplicativo mais versátil e atrativo para uma audiência global, seria necessário considerar a adaptação para outros locais.

#### Internacionalização

O aplicativo atualmente oferece suporte exclusivamente ao idioma português. A ausência de informações sobre planos futuros para adicionar suporte a outros idiomas pode ser uma limitação para atingir uma base de usuários mais ampla, particularmente entre aqueles que não falam português e que vem morar na região de Brasília, se naturalizando brasileiro.

#### Portabilidade

É importante observar que o aplicativo está disponível apenas para dispositivos iOS, uma vez que a versão para Android foi descontinuada. Essa limitação de plataforma restringe o público-alvo do aplicativo, excluindo os usuários de dispositivos Android. Portanto, é importante considerar o desenvolvimento de uma versão para Android ou outras plataformas para aumentar o alcance do aplicativo.

#### Testabilidade

Embora informações específicas sobre os processos de testagem do aplicativo não estejam disponíveis publicamente, a frequência das atualizações indica que os desenvolvedores estão ativamente envolvidos em testes e correções de bugs. A garantia de qualidade é um aspecto fundamental para manter a satisfação dos usuários e a estabilidade do aplicativo.

#### Extensibilidade

A adição de novas funcionalidades em um curto período de tempo sugere que o aplicativo é altamente extensível. Essa abordagem é positiva, pois permite que o aplicativo evolua e atenda às crescentes necessidades dos usuários. A flexibilidade para incorporar recursos adicionais é fundamental para manter o aplicativo relevante no longo prazo.

#### Configurabilidade

Os recursos que permitem aos usuários personalizar sua experiência, como cadastrar veículos e imóveis para consulta de débitos, demonstram uma preocupação em atender às necessidades individuais. Essa configurabilidade torna o aplicativo mais prático e adaptável às preferências e necessidades dos usuários.

#### Instalabilidade

O fato de o aplicativo estar disponível apenas na Apple App Store restringe sua acessibilidade a dispositivos iOS da Apple. Isso significa que os usuários de outras plataformas não têm acesso ao aplicativo, limitando seu alcance. Considerar o desenvolvimento de versões para outras lojas de aplicativos, como o Google Play Store, seria uma estratégia importante para expandir a base de usuários.

### +: Restrições de Design

O sistema deve aderir estritamente aos padrões de boas práticas amplamente aceitos, incluindo os requisitos de interface para iOS. Ele deve ser desenvolvido seguindo os princípios da arquitetura limpa, garantindo não apenas funcionalidade, mas também uma estrutura de código organizada e sustentável. Além disso, é fundamental escolher uma paleta de cores que permita que pessoas com diferentes restrições visuais, como daltonismo, possam distinguir claramente os elementos, sem comprometer a identidade visual da marca. Essa abordagem não apenas promove a acessibilidade, mas também reforça a coesão da marca em todas as plataformas.

### +: Ajuda e Documentação

A "Ajuda e Documentação" em um aplicativo refere-se a um conjunto de recursos elaborados para orientar e fornecer informações aos [usuários](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#objetos) sobre o funcionamento, características e melhores práticas de uso do aplicativo. Essa seção é fundamental para garantir que os usuários possam usar o aplicativo de forma eficaz, resolver dúvidas e aproveitar ao máximo suas funcionalidades.

Na tabela 4, é possível ver os Requisitos Não Funcionais para Ajuda e Documentação elicitados pro aplicativo "Economia DF".

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Requisitos não funcionais sobre Ajuda e Documentação</p></font>
</div>

| ID  | Descrição |
|-----|-----------|
| AD01 | A página de ajuda deve ser acessível em menos de 3 segundos em qualquer dispositivo. |
| AD02 | A documentação deve ser completa e precisa, cobrindo todas as funcionalidades e características relevantes do aplicativo. |
| AD03 | A documentação deve estar disponível em, no mínimo, dois idiomas amplamente falados na região, além do idioma principal do aplicativo. |
| AD04 | A documentação deve ser atualizada e revisada trimestralmente para garantir sua relevância e precisão com as versões mais recentes do aplicativo. |
| AD05 | A maioria dos usuários (pelo menos 80%) deve conseguir encontrar a informação desejada na documentação em menos de 2 minutos de navegação. |
| AD06 | A documentação deve passar em todos os testes de usabilidade em dispositivos móveis, atingindo uma pontuação mínima de 90% em ferramentas de avaliação de responsividade. |
| AD07 | A documentação deve aderir a padrões de acessibilidade, como WCAG 2.0 [1] ou posterior, para garantir que seja utilizável por todos os usuários, incluindo aqueles com deficiências. |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div >

### +: Interfaces

O aplicativo deve fornecer uma interface de usuário simples e padronizada para que os usuários possam interagir com ela de forma fácil e intuitiva.

* Interface de Usuário: o aplicativo deve conter no mínimo tela de login, painéis de controle, telas de configuração, telas de históricos para consultas, menus, entre outras.
* Interface de Hardware: o aplicativo está disponível para plataforma iOS apenas, deveria estar disponível também para Android.
* Interface de Comunicação: o aplicativo necessita de conexão com a internet, seja por dados móveis ou por wifi.

## Referências Bibliográficas

> [1] WORLD WIDE WEB CONSORTIUM. WCAG 2.0: Web Content Accessibility Guidelines. Versão 2.0. World Wide Web Consortium, 2008. Disponível em: https://www.w3.org/WAI/WCAG21/quickref/. Acesso em: 14 de outubro de 2023.

## Bibliografia

> SERRANO, et al. Requisitos - Aula 13. Disponível em: <https://aprender3.unb.br/course/view.php?id=18538&section=6>. Acesso em 14 de outubro 2023.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/10/2023|Criação do documento e adição do tópico ajuda e documentação|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.1`|17/10/2023|Adição do topico Confiabilidade (Reliability)|[Lucas Víctor](https://github.com/Lucas13032003)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.2`|17/10/2023|Adição da introdução e metodologia|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.3`|17/10/2023|Adição da seção de suporte|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.4`|19/10/2023|Adição da seção de desempenho|[Gabriel Zaranza](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.5`|20/10/2023|Adição da seção de Confiabilidade (Reliability)|[Lucas Víctor](https://github.com/Lucas13032003)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.6`|20/10/2023|Adição da seção de Usabilidade (Usability)|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.7`|21/10/2023|Adição da seção de Restrições de Design|[Lucas Ribeiro](https://github.com/lucassouzs)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.8`|22/10/2023|Adição da seção de Funcionalidade e de Interface|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
