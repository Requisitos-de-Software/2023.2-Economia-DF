# Espeficicação Suplementar

## Introdução

Este documento apresenta a Especificação Suplementar para o aplicativo Economia DF. A Especificação Suplementar é um artefato importante no processo de desenvolvimento de software, pois descreve os requisitos não funcionais do sistema - aqueles que não estão diretamente relacionados com a funcionalidade específica do software, mas com características como desempenho, usabilidade, confiabilidade, entre outros. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário.

## Metodologia

A metodologia utilizada para a elaboração deste documento é baseada no modelo FURPS+, que é uma técnica eficaz para a coleta e organização de requisitos não funcionais. FURPS+ é um acrônimo para Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suporte, que são as principais categorias de requisitos consideradas neste modelo. Além disso, o “+” em FURPS+ representa requisitos adicionais que podem ser relevantes, como restrições de design e requisitos de documentação e ajuda.

Este documento foi estruturado de acordo com as categorias do modelo FURPS+. Cada seção do documento corresponde a uma categoria e apresenta uma descrição detalhada dos requisitos não funcionais relacionados a essa categoria para o aplicativo Economia DF. Os requisitos foram elicitados através de uma combinação de técnicas, análise de documentos e brainstorming entre a equipe de desenvolvimento.

## FURPS+
### F: Funcionalidade (Functionality)
### U: Usabilidade (Usability)
A usabilidade de um sistema segundo Nielsen é o atributo de qualidade que avalia a facilidade de uso de uma interface. Uma interface com boa usabilidade permite que os usuários realizem suas tarefas de forma eficiente, eficaz e satisfatória. 

Na tabela X, é possível ver os Requisitos Não Funcionais para Usabilidade do aplicativo "Economia DF":

<div align="center">
  
| ID  | Descrição |
|-----|-----------|
| RU01 | 	O aplicativo deve ser fácil de usar e intuitivo, permitindo que os usuários realizem suas tarefas com eficiência e sem necessidade de treinamento extensivo. |
| RU02 | O aplicativo deve fornecer feedback imediato após cada ação do usuário, para que eles saibam se a ação foi bem-sucedida ou não. |
| RU03 | 	O aplicativo deve permitir que os usuários desfaçam ações sempre que possível. Isso pode ser implementado como uma opção “desfazer” no menu ou como um botão de “voltar”. |
| RU04 | O aplicativo deve ser consistente em seu design e comportamento. Isso inclui o uso consistente de cores, fontes, ícones e terminologia, bem como a consistência na localização dos elementos da interface do usuário.. |
| RU05 | 	O aplicativo deve ser acessível para usuários com diferentes habilidades e necessidades. Isso pode incluir suporte para tecnologias assistivas, como leitores de tela, e conformidade com as diretrizes de acessibilidade da Web Content Accessibility Guidelines (WCAG). |

  <p>Tabela X - Requisitos não funcionais sobre Usabilidade. Fonte:Lucas de Oliveira, 2023.</p>
</div>

### R: Confiabilidade (Reliability)
A Confiabilidade (Reliability) no aplicativo Economia DF se refere à capacidade do aplicativo de funcionar de forma consistente, estável e sem falhas. Em outras palavras, os usuários podem confiar que o aplicativo funcionará corretamente sempre que o utilizarem. Isso é essencial para garantir uma experiência positiva do usuário, prevenir erros e manter a credibilidade do aplicativo.
<br>
<br>

Na tabela X, é possível ver os Requisitos Não Funcionais para Confiabilidade do aplicativo "Economia DF":

<div align="center">
  
| ID  | Descrição |
|-----|-----------|
| RE01 | O aplicativo deve ser capaz de funcionar sem falhas ou interrupções por um período mínimo de 30 dias consecutivos. Qualquer interrupção não planejada que ocorra deve ser solucionada em até 4 horas a partir do momento da detecção. |
| RE02 | O aplicativo deve ser capaz de lidar com um aumento de 500% na carga de usuários simultâneos sem comprometer a sua estabilidade ou desempenho. |
| RE03 | Os dados do usuário e as informações críticas do aplicativo devem ser armazenados de forma segura e protegidos contra perda de dados. Deve ser realizado backup diário dos dados, e a recuperação de dados deve ser possível em menos de 6 horas em caso de falha. |
| RE04 | O aplicativo deve ter um mecanismo de monitoramento contínuo que alerta a equipe de suporte técnico sobre quaisquer problemas críticos em tempo real. A equipe de suporte deve estar disponível 24/7 para resolver esses problemas. |
| RE05 | As atualizações de software e manutenções planejadas devem ser agendadas fora do horário de pico de uso do aplicativo (por exemplo, durante a noite) e os usuários devem ser notificados com antecedência. |
| RE06 | O aplicativo deve ter a capacidade de se recuperar automaticamente de falhas de hardware, como a substituição de servidores com falha, sem interromper o serviço. |
| RE07 | Em caso de interrupções não planejadas que afetem o funcionamento do aplicativo, os usuários devem ser informados de maneira clara e precisa sobre o problema, o progresso da solução e o tempo estimado de restauração do serviço. |

  <p>Tabela X - Requisitos não funcionais sobre Desempenho. Fonte:Lucas Victor, 2023.</p>
</div>

### P: Desempenho (Performance)
O desempenho de um sistema é relacionado ao tempo para executar ações e a rapidez que o [usuário](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#objetos) realiza suas tarefas. É importante garantir um alto desempenho para que a produtividade do usuário seja elevada. Na tabela x é possível encontrar requisitos não funcionais relacionados ao desempenho do Economia DF.

| ID  | Descrição |
|-----|-----------|
| PE01  | O tempo de resposta do menu principal do aplicativo deve ser inferior 500 ms |
| PE02  | O tempo para emitir um documento deve ser inferior a 1 segundo  |
| PE03  | O tempo de autenticação do login deve ser inferior a 3 segundos |
| PE04  | O tempo de resposta de uma pesquisa de documentos tem que ser inferior a 1 segundo |


<div align="center">
  <p>Tabela X - Requisitos não funcionais sobre Desempenho. Fonte: Gabriel Zaranza, 2023.</p>
</div>


### S: Suporte ( _Supportability_)

#### Suporte e Manutenção
O aplicativo é mantido e atualizado em uma frequência mediana, pois tem um certo tempo de sua última atualização. A última atualização foi em 23 de março de 2021, onde foram atualizados os itens de segurança e a funcionalidade de notícias. Além disso, as atualizações são para garantir que continue funcionando conforme esperado com as versões mais recentes dos sistemas operacionais e para adicionar novas funcionalidades ou corrigir bugs. Isso indica que o aplicativo tem uma boa manutenibilidade.

#### Adaptabilidade
O aplicativo foi projetado para ser usado por contribuintes do Distrito Federal, Brasil. No entanto, não há informações disponíveis sobre se o aplicativo pode ser adaptado para uso em outras regiões ou países.

#### Internacionalização
Atualmente, o aplicativo está disponível apenas em português. Não há informações disponíveis sobre se há planos para adicionar suporte a outros idiomas no futuro.

#### Portabilidade
O aplicativo é portátil, pois está disponível tanto para dispositivos Android quanto iOS. Isso significa que ele pode ser usado em uma ampla gama de dispositivos móveis.

#### Testabilidade
Não há informações disponíveis publicamente sobre a testabilidade do aplicativo. No entanto, a presença de atualizações medianas sugere que os desenvolvedores estão ativamente testando e corrigindo problemas.

#### Extensibilidade
O aplicativo parece ter uma boa extensibilidade, pois novas funcionalidades foram adicionadas em um curto período de tempo.

#### Configurabilidade
O aplicativo permite aos usuários personalizar suas experiências ao permitir que eles cadastrem veículos e imóveis para consulta de débitos entre outras funcionalidades que o próprio aplicativo dispõe.

#### Instalabilidade
O aplicativo pode ser facilmente instalado a partir da Google Play Store ou da Apple App Store.

### +: Restrições de Design

O sistema deve aderir estritamente aos padrões de boas práticas amplamente aceitos, incluindo os requisitos de interface para iOS. Ele deve ser desenvolvido seguindo os princípios da arquitetura limpa, garantindo não apenas funcionalidade, mas também uma estrutura de código organizada e sustentável. Além disso, é fundamental escolher uma paleta de cores que permita que pessoas com diferentes restrições visuais, como daltonismo, possam distinguir claramente os elementos, sem comprometer a identidade visual da marca. Essa abordagem não apenas promove a acessibilidade, mas também reforça a coesão da marca em todas as plataformas.

### +: Ajuda e Documentação
A "Ajuda e Documentação" em um aplicativo refere-se a um conjunto de recursos elaborados para orientar e fornecer informações aos [usuários](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/lexicos.md#objetos) sobre o funcionamento, características e melhores práticas de uso do aplicativo. Essa seção é fundamental para garantir que os usuários possam usar o aplicativo de forma eficaz, resolver dúvidas e aproveitar ao máximo suas funcionalidades.
<br>
<br>
Na tabela X, é possível ver os Requisitos Não Funcionais para Ajuda e Documentação elicitados pro aplicativo "Economia DF":


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
  <p>Tabela X - Requisitos não funcionais sobre Ajuda e Documentação. Fonte: Izabella Alves, 2023.</p>
</div>

### +: Interface
## Referências Bibliográficas
> [1] WORLD WIDE WEB CONSORTIUM. WCAG 2.0: Web Content Accessibility Guidelines. Versão 2.0. World Wide Web Consortium, 2008. Disponível em: https://www.w3.org/WAI/WCAG21/quickref/. Acesso em: 14 de outubro de 2023.

## Bibliografia
> SERRANO, et al. Requisitos - Aula 13. Disponível em: <https://aprender3.unb.br/course/view.php?id=18538&section=6>. Acesso em 14 de outubro 2023.
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/10/2023|Criação do documento e adição do topido ajuda e documentação|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.1`|17/10/2023|Adição do topico Confiabilidade (Reliability)|[Lucas Víctor](https://github.com/Lucas13032003)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.2`|17/10/2023|Adição da introdução e metodologia|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.3`|17/10/2023|Adição da seção de suporte|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.4`|19/10/2023|Adição da seção de desempenho|[Gabriel Zaranza](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.5`|20/10/2023|Adição da seção de Confiabilidade (Reliability)|[Lucas Víctor](https://github.com/Lucas13032003)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.6`|20/10/2023|Adição da seção de Usabilidade (Usability)|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.7`|21/10/2023|Adição da seção de Restrições de Design|[Lucas Ribeiro](https://github.com/lucassouzs)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
