# Instrospecção

## Introdução

A introspecção, como técnica de elicitação de requisitos, é um processo profundo e enriquecedor que visa compreender as propriedades cruciais para o sucesso de um sistema. Requer que o Engenheiro de Requisitos mergulhe em uma análise reflexiva, imaginando-se executando tarefas específicas com os recursos e equipamentos disponíveis, para conceber as funcionalidades e características desejadas do sistema.

Neste documento, apresentaremos os resultados da aplicação da técnica de introspecção para a elicitação de requisitos do aplicativo "Economia DF". Este aplicativo visa proporcionar aos usuários o acesso aos serviços oferecidos pelo programa Nota Legal por meio de dispositivos móveis.

## Metodologia

Como visto na introdução, a metodologia da Instrospecção consiste no Engenheiro de Requisitos se imaginar executando uma tarefa, e assim, elicitando os requisitos necessários para
que o aplicativo seja um sucesso e atenda as necessidades da tarefa. Sendo assim, a situação hipotética está descrita abaixo e os resultados estão na seção "Desenvolvimento".

- #### Situação hipotética

Eu sou uma cidadã que deseja acessar os serviços do programa Nota Legal, como verificar créditos acumulados e histórico de notas fiscais, mas não possuo acesso a um computador no momento. Decido utilizar o aplicativo "Economia DF" em meu smartphone para obter essas informações de maneira rápida e conveniente. 

Para realizar a sessão de brainstorming, os membros [Izabella Alves](https://github.com/izabellaalves) e [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira) se reuniram de forma presencial no dia 23/09/2023, às 11:00 da manhã.

## Desenvolvimento

Na elicitação de requisitos para o aplicativo "Economia DF" (Nota Legal), utilizaremos códigos para classificar e organizar os requisitos de maneira clara e estruturada. Dois desses códigos frequentemente usados são RF (Requisitos Funcionais) e RNF (Requisitos Não Funcionais). Além disso, cada requisito elicitado terá um ID.

**RF (Requisitos Funcionais):** Representam funcionalidades específicas que o aplicativo deve oferecer, descrevendo as ações que o sistema deve executar em resposta a entradas.

**RNF (Requisitos Não Funcionais):** Englobam aspectos que não estão diretamente relacionados às funcionalidades específicas do aplicativo, mas afetam sua eficiência, usabilidade, segurança e outros atributos.

**ID:** Cada requisito será identificado por um ID composto da seguinte forma: INTXX (onde XX é um número sequencial). Por exemplo, o primeiro requisito funcional seria INT01 e assim por diante.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> - Requisitos elicitados</p></font>
</div>

| ID   | Código | Descrição                                                                                      | Implementado |
|------|--------|------------------------------------------------------------------------------------------------|--------------|
| INT01| RF     | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |   Sim        |
| INT02| RF     | Deve ser possível acessar os dados diretamente da secretaria de estado de economia do distrito federal | Sim         |
| INT03| RF     | O aplicativo deve permitir a recuperação de senha por meio de um processo seguro e validado.  |     Sim      |
| INT04| RF     | Os usuários devem poder acessar e visualizar informações sobre créditos acumulados.           |      Não     |
| INT05| RF     | O aplicativo deve possibilitar a consulta do histórico de notas fiscais associadas à conta do usuário. |    Sim      |
| INT06| RF     | Permitir que os usuários consultem estabelecimentos comerciais parceiros do programa Nota Legal. |     Não      |
| INT07| RF     | Os usuários devem poder resgatar os créditos acumulados de forma clara e fácil.               |    Não       |
| INT08| RF     | Deve ser possível visualizar promoções e descontos oferecidos em estabelecimentos participantes. |      Sim     |
| INT09| RF     | O aplicativo deve ter uma interface intuitiva, fácil de navegar e que proporcione uma boa experiência ao usuário. |    Sim       |
| INT10| RF     | Deve ser oferecido suporte para diferentes tamanhos de tela e dispositivos móveis.           |     Não      |
| INT11| RF    | Deve ser disponibilizada uma forma de entrar em contato com a Secretária de Estado de Economia no caso de algum problema específico do usuário                 |  Sim        |
| INT12| RNF    | Garantir a segurança das informações dos usuários durante a transmissão e armazenamento de dados. |     Sim      |
| INT13| RNF    | Assegurar conformidade com regulamentações de proteção de dados vigentes no Brasil.          |     Sim      |
| INT14| RNF    | Garantir uma resposta rápida e eficiente, minimizando o tempo de carregamento das páginas.   |    Não      |
| INT15| RNF    | Manter a disponibilidade do aplicativo, minimizando tempo de inatividade para garantir uma experiência contínua. |     Não      |
| INT16| RNF    | Garantir uma interface de usuário amigável, facilitando a interação e a compreensão das funcionalidades do aplicativo. |      Sim     |
| INT17| RNF    | Certificar-se de que o aplicativo é compatível com uma ampla variedade de dispositivos móveis e sistemas operacionais. |      Não     |
| INT18| RNF    | Garantir que o aplicativo seja otimizado para diferentes navegadores web.                   |     Não      |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a> e <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023</p></font>
</div>

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 23/09/2023.
>

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|:-----:|:-------:|
|`1.0`|23/09/2023|Criação do documento|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Víctor](https://github.com/Lucas13032003)|
|`1.1`|23/09/2023|Preenchimento da tabela com a adição dos resultados da Introspecção|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.2`|29/10/2023|Correção|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Víctor](https://github.com/Lucas13032003)|
