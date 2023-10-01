# Obeservação
## Introdução

No contexto do aplicativo Economia-DF, a técnica de observação de requisitos desempenha um papel fundamental na coleta de informações. Essa abordagem envolve a observação direta das interações dos usuários com o aplicativo, os processos envolvidos e o ambiente de uso.

Neste caso, o usuário real foi [Gabriel Zaranza](#) , que interagiu com o aplicativo enquanto executava tarefas específicas. Para facilitar a observação e garantir que todos os aspectos fossem registrados com precisão, o desenvolvedor [Lucas Víctor](#) atuou como mediador, acompanhando e registrando as ações de Gabriel.

Essa estratégia permitiu obter insights valiosos sobre a experiência de [Gabriel Zaranza](#) com o aplicativo Economia-DF, identificando desafios, necessidades e oportunidades de melhoria. Mesmo com [Lucas Víctor](#) atuando como mediador, a técnica de observação de requisitos desempenhou um papel fundamental na otimização do aplicativo para atender às demandas dos usuários de forma mais eficaz.



## Metodologia

No dia 28 de setembro de 2023, a equipe se reuniu no local Teamas com o objetivo de realizar uma observação direta do funcionamento do aplicativo Economia-DF. A reunião foi notavelmente curta, com uma duração de aproximadamente 7 minutos, devido à baixa complexidade do aplicativo. Durante esse período, o mediador desempenhou um papel fundamental, orientando e solicitando ações específicas ao usuário, Gabriel Zaranza. Essa metodologia de observação proporcionou uma visão valiosa da interação do usuário com o aplicativo, destacando áreas de eficiência e possíveis melhorias. O curto tempo necessário para a observação demonstra a simplicidade e facilidade de uso do aplicativo, ao mesmo tempo em que ressalta a importância de um mediador para facilitar o processo e garantir uma avaliação abrangente.

### Participantes
<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
| [Lucas Víctor](#)  | Observador               |
| [Gabriel Zaranza](#) | Usuário |

</center>

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>


<font size="3"><p style="text-align: center">Fonte: [Lucas Víctor](#) e [Gabriel Zaranza](#).</p></font>

### [Link para a gravação da observação.](#)

## Requisitos elicitados

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- OBSx: Requisito nºx elicitado pela observação.

### Funcionais

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

| Tipo | Descrição                                                                                                             | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RF01 | O aplicativo filtra os eventos por Estado.                                                                            | OBS01                                                  | Sim          |
| RF02 | O aplicativo permite a busca por eventos.                                                                             | OBS02                                                  | Sim          |
| RF03 | O aplicativo permite compartilhar o evento por meio das redes sociais.                                                | OBS03                                                  | Sim          |
| RF04 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.                                 | OBS04                                                  | Sim          |
| RF05 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | OBS05                                                  | Sim          |
| RF06 | O aplicativo permite selecionar as poltronas especiais.                                                               | OBS06                                                  | Sim          |
| RF07 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                          | OBS07                                                  | Sim          |
| RF08 | Caso o local do evento disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.                        | OBS08                                                  | Sim          |
| RF09 | O aplicativo permite a doação por parte do usuário para fundações.                                                    | OBS09                                                  | Sim          |
| RF10 | O aplicativo permite a realização da compra dos ingressos.                                                            | OBS10                                                  | Sim          |
| RF11 | O aplicativo possui uma função para entrar em contato com o suporte.                                                  | OBS11                                                  | Sim          |
| RF12 | O aplicativo permite ao usuário cancelar o pedido.                                                                    | OBS12                                                  | Sim          |
| RF13 | O aplicativo permite ao usuário alterar seus dados.                                                                   | OBS13                                                  | Sim          |
| RF14 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                        | OBS14                                                  | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

| Tipo  | Descrição                                                                                                                                                                       | <a id="anchor_OBSNF" style="visibility: hidden;"></a>ID | Implementado |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------ |
| RNF01 | O sistema deve alocar os eventos de acordo com a região selecionada a fim de facilitar a busca e a filtragem.                                                                   | OBS15                                                   | Sim          |
| RNF02 | Deve possuir, na página do evento, uma descrição sobre o local, a qual possui data, horário, valor e informações sobre o evento que pode ser acessada em, no máximo, 3 cliques. | OBS16                                                   | Sim          |
| RNF03 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                                                                                           | OBS17                                                   | Sim          |
| RNF04 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                                                                                             | OBS18                                                   | Sim          |
| RNF05 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.                                                                             | OBS19                                                   | Sim          |
| RNF06 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                                                                                             | OBS20                                                   | Sim          |
| RNF07 | Deve apresentar uma página com o histórico de pedidos do usuário em dois cliques.                                                                                               | OBS21                                                   | Sim          |
| RNF08 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                                                                                      | OBS22                                                   | Sim          |

</center>


## Bibliografia
> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.


## Histórico de Versões
| Versão | Data       | Descrição            | Autor                                                      | Revisor                                     |
| :----: | ---------- | -------------------- | :--------------------------------------------------------: | :-----------------------------------------: |
| `1.0`  | 01/10/2023 | Criação do documento |[Lucas Víctor](#)  | [Izabella Alves Pereira](https://github.com/izabellaalves)|
| `1.1`  | 01/10/ 2023 | Adição de metologia |[Lucas Víctor](#)  | [Izabella Alves Pereira](https://github.com/izabellaalves)|
| `1.1`  | 01/10/ 2023 | Adição de tabelas |[Lucas Víctor](#)  | [Izabella Alves Pereira](https://github.com/izabellaalves)|
