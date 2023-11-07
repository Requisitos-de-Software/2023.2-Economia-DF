## Introdução 

As histórias de usuário representam o alicerce das metodologias de desenvolvimento ágil e desempenham um papel central na definição de requisitos. Em linhas gerais, as histórias de usuário consistem em descrições concisas e diretas das funcionalidades desejadas, vistas a partir da perspectiva do cliente. Além disso, cada história de usuário deve ser acompanhada por critérios de aceitação minuciosamente delineados, que servem como critérios sólidos para avaliar com precisão o sucesso da implementação. Vamos explorar mais a fundo a vital importância das histórias de usuário no contexto deste aplicativo dedicado à Economia-DF.

## Objetivo 
O objetivo das histórias de usuário no aplicativo Economia-DF é definir e comunicar as necessidades dos usuários de maneira clara e direta. Elas são essenciais para priorizar funcionalidades, manter o foco no valor para o usuário, facilitar a comunicação da equipe de desenvolvimento e estabelecer critérios para determinar quando uma funcionalidade está completa. Em resumo, as histórias de usuário são a base para garantir que o aplicativo atenda às expectativas dos usuários e forneça funcionalidades valiosas e relevantes.

## Metodologia

A princípio, durante o projeto foram elicitados os requisitos do aplicativo através de tecnicas como:

- [Brainstorming](#)
- [Observação](#)
- [Instrospecção](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md)
- [Personas](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/personas.md)
- [Questionário](https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/elicitacao/questionario.md)


Posteriormente, foi efetuado a priorização dos requisitos elicitados com as tecnicas de:

- [100$](#)
- [First Thing First](#)
- [In our Out](#)

Dessa forma, as funcionalidades foram documentadas de maneira ágil e padronizada, alinhadas com as especificações definidas no [Backlog](https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#backlogs). Por fim, realizou-se uma validação do documento em uma reunião com o representante do cliente no projeto, assegurando a conformidade com as necessidades do usuário.

## Participantes

Para a criação do artefacto, foi efetuado uma reunião com os membros disponíveis na tabela 1.

<div style="text-align: center">

<p><b>Tabela 1:</b> Participantes da reunião de histórias do usuário.</p>

<table>
  <tr>
    <th>Nome</th>
    <th>Cargo</th>
  </tr>
  <tr>
    <td><a href="https://github.com/Lucas13032003">Lucas Víctor</a></td>
    <td>Desenvolvedor</td>
  </tr>
  <tr>
    <td>Lucas Oliveira</td>
    <td>Desenvolvedor</td>
  </tr>
  <tr>
    <td><a href="https://github.com/itsmewall">Wallace Oliveira</a></td>
    <td>PO</td>
  </tr>
</table>


<p><b>Fonte:</b> Lucas Victor, 2023.</p>

</div>


## Padrão de História de Usuário

Ao escrever as histórias de usuário para este projeto, é crucial seguir as diretrizes especificadas neste documento. Para modelar as histórias de usuário de forma consistente, devemos incluir as seguintes informações:

- **ID:** Este é o identificador único das histórias de usuário. Os IDs estão presentes nos títulos das histórias, que foram organizadas em toggles.

- **História de Usuário:** Cada história de usuário deve seguir a estrutura "Eu, como [usuário], desejo [realizar algo] para que [alcance algum objetivo]".

- **Tema:** É importante indicar a qual tema ou categoria a história de usuário está relacionada, proporcionando um contexto mais amplo.

- **Critérios de Aceitação:** Aqui, devemos listar um conjunto de atributos ou condições que uma funcionalidade deve atender para ser considerada "aceita" ou concluída com sucesso.

- **Prioridade:** A prioridade ajuda a determinar o nível de importância da história de usuário no projeto. Pode ser classificada como alta, média ou baixa, levando em consideração fatores como o valor para o usuário, facilidade de implementação, dependências técnicas e restrições de prazo.

- **Dificuldade de Implementação (DI):** Essa métrica está relacionada à dificuldade de implementar a funcionalidade e pode ser categorizada como baixa, média ou alta.

## Exemplo de tabela:

Na tabela 2 é possível ver um exemplo da tabela para as histórias de usuário.

### HS0X - [Nome da história]

<div style="text-align: center">

<p><b>Tabela 2:</b> Exemplo de tabela de História de Usuário</p>

</div>

| História de Usuário | Tema | Critérios de Aceitação | Prioridade | (DI) |
|---------------------|------|------------------------|------------|------|
| Eu, como [usuário], desejo [realizar algo] para que [alcance algum objetivo] | [Tema] | - [Critério 1] | Alta | Baixa |
| Eu, como [usuário], desejo [realizar algo] para que [alcance algum objetivo] | [Tema] | - [Critério 1] | Média | Média |
| Eu, como [usuário], desejo [realizar algo] para que [alcance algum objetivo] | [Tema] | - [Critério 1] | Baixa | Alta |

<div style="text-align: center">

<p><b>Fonte:</b> Lucas Victor, 2023.</p>

</div>

Seguir este padrão ao criar as histórias de usuário garantirá uma documentação clara e consistente, facilitando o entendimento e a execução eficiente das tarefas do projeto.



## História de Usuário

Em seguida, temos as histórias de usuário:

### HS01 - Efetuar login com email e senha

<div style="text-align: center">

<p><b>Tabela 3:</b> História de Usuário 1</p>

</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu quero fazer login seguro no aplicativo com meu e-mail e senha para usar todas as funcionalidades com proteção dos meus dados pessoais.| Login | - O sistema deve verificar se o email e a senha informados pelo usuário são válidos e correspondem a um usuário cadastrado. </br> - Caso contrário, deve exibir uma mensagem de erro e solicitar que o usuário tente novamente. | Alta | Baixa |

<div style="text-align: center">

<p><b>Fonte</b> Lucas Víctor e Lucas Oliveira, 2023.</p>
   
</div>

### HS02 HS02 - Efetuar login com gov.br

<div style="text-align: center">

<p><b>Tabela 4:</b> História de Usuário 2</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como  usuário, desejo  entrar no aplicativo usando minha integração gov.br para acessar todas as funcionalidades de forma conveniente. | Login | - O sistema deve permitir que o usuário realize o login no aplicativo através da integração com o gov.br. </br> - O sistema deve redirecionar o usuário para a tela do gov.br, onde ele poderá escolher uma das opções de identificação disponíveis, como CPF, certificado digital, QR code ou login com banco.| Média |Média  |

<div style="text-align: center">

<p><b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.</p>

</div>

### HS03 HS03 - Recuperar senha

<div style="text-align: center">

<p><b>Tabela 5:</b> História de Usuário 3 </p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo ter a capacidade de recuperar minha senha de acesso no aplicativo no caso de perda.| Login | - O sistema deve oferecer uma opção para o usuário recuperar sua senha caso ele a tenha esquecido. </br> - Ao clicar nessa opção, o usuário deve ser levado para uma tela onde ele poderá informar seu email e receber um link para redefinir sua senha.| Alta | Baixa |

<div style="text-align: center">

<p><b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.</p>

</div>

### HS04 - Efetuar logout 

<div style="text-align: center">
<p><b>Tabela 6:</b> História de Usuário 3 </p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo realizar logout no aplicativo após o uso, garantindo a segurança da minha conta e a privacidade das minhas informações.| Login | O sistema deve permitir que o usuário faça logout do aplicativo a qualquer momento, encerrando sua sessão e retornando para a tela de login. | Alta | Baixa  |

<div style="text-align: center">

<p><b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.</p>

</div>

### HS05 - Listar

<div style="text-align: center">

<p><b>Tabela 7:</b> História de Usuário 5</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo listar informações sobre notas fiscais no aplicativo, permitindo que eu confira e acompanhe minhas compras.  | Nota Fiscal | - Ver uma lista de notas fiscais ordenadas por data de emissão com informações essenciais. </br> - Visualizar detalhes de uma nota fiscal, incluindo produtos, impostos e opção de baixar o XML/PDF. </br> - Filtrar notas fiscais por período, valor, fornecedor ou status. </br> - Sincronizar notas fiscais com o portal da NF-e e alertar sobre inconsistências.| Alta | Alta  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS06 - Pesquisar

<div style="text-align: center">

<p><b>Tabela 8:</b> História de Usuário 6</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo pesquisar informações sobre notas fiscais no aplicativo, proporcionando-me a capacidade de conferir e rastrear minhas compras de forma eficaz e personalizada. | Nota Fiscal | - O sistema deve permitir que o usuário digite uma palavra-chave relacionada às notas fiscais que deseja pesquisar, como o nome do fornecedor, o produto ou serviço adquirido, o valor, a data, etc. </br> - O sistema deve retornar uma lista de notas fiscais que contenham a palavra-chave informada, ordenadas por relevância ou similaridade.| Alta |  Alta |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS07 - Visualizar detalhes 

<div style="text-align: center">

<p><b>Tabela 9:</b> História de Usuário 7 </p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo visualizar detalhes completos sobre as notas fiscais no aplicativo, permitindo-me uma conferência minuciosa de minhas compras e facilitando o acompanhamento de todas as informações relevantes. | Nota Fiscal | - Ver detalhes completos de uma nota fiscal selecionada, com a opção de baixar o XML ou PDF. </br> - Verificar a autenticidade da nota fiscal comparando com o portal da NF-e e alertar sobre inconsistências.  </br> - Compartilhar a nota fiscal via e-mail, WhatsApp, Telegram, etc., escolhendo o formato de compartilhamento, X(ML, PDF ou imagem). </br> Avaliar a nota fiscal com 1 a 5 estrelas e comentário opcional, mostrando a média e o número de avaliações. | Alta | Média |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS08 - Imprimir DANFE

<div style="text-align: center">

<p><b>Tabela 10:</b> História de Usuário 8</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo ter a opção de imprimir o DANFE, (Documento Auxiliar da Nota Fiscal Eletrônica) das notas fiscais no aplicativo. | Nota Fiscal | - Imprimir o DANFE das notas fiscais em formato PDF. </br> - Visualizar o DANFE antes de imprimir, com código de barras e QR code. </br> - Escolher notas fiscais para impressão e cancelar a operação, se necessário. | Média | Média |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### US09 - Cadastrar

<div style="text-align: center">

<p><b>Tabela 11:</b> História de Usuário 9</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo cadastrar informações sobre meu(s) veículo(s) no aplicativo, permitindo-me verificar se há quaisquer débitos associados. | Débitos | - Cadastrar veículos com dados obrigatórios, validando a propriedade. </br> - Ver uma lista de veículos cadastrados e acessar as funcionalidades de um veículo selecionado. </br> - Editar informações de um veículo com confirmação. </br> - Excluir um veículo com confirmação, exibindo mensagens de sucesso ou erro.| Alta | Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS10 - Consultar débitos de IPVA 

<div style="text-align: center">

<p><b>Tabela 12:</b> História de Usuário 10</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo consultar os débitos de IPVA associados ao(s) meu(s) veículo(s) no aplicativo, a fim de verificar a existência de quaisquer pendências financeiras. | Débitos | Consultar e visualizar os débitos de IPVA dos seus veículos. </br> - Exporta, compartilhar e imprimir documento de débito. </br> Receber notificações sobre débitos novos. | Alta | Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS11 - Emitir DAR

<div style="text-align: center">

<p><b>Tabela 13:</b> História de Usuário 11</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo a capacidade de emitir o Documento de Arrecadação de Receitas, (DAR) no aplicativo para meu(s) veículos, ou imóveis, ou dívidas Ativa, ou outros tributos, ou parcelamentos administrativos  permitindo-me identificar e quitar possíveis débitos associados. | Débitos | - Emitir o DAR para todos os seus débitos, como IPVA, IPTU, seguro DPVAT e multas, etc. </br> - Consultar débitos, incluindo valor, data de vencimento, código de barras e status, pago, atrasado, parcelado.  | Alta | Baixa  | 

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS12 - Cadastrar

<div style="text-align: center">

<p><b>Tabela 14:</b> História de Usuário 12</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo cadastrar informações sobre meu(s) imóvel(eis) no aplicativo, a fim de verificar a existência de possíveis débitos e, assim, facilitar o acompanhamento e a gestão eficaz da situação dos meus imóveis. | Débitos | - O usuário deve conseguir cadastrar informações sobre seus imóveis no aplicativo. </br> - O aplicativo deve validar e armazenar com segurança as informações cadastradas. </br> - O usuário deve poder visualizar e editar os dados de seus imóveis a qualquer momento. </br> - Após o cadastro bem-sucedido, o usuário receberá uma confirmação. | Alta  | Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS13 - Consultar débitos de IPTU/TLP

<div style="text-align: center">

<p><b>Tabela 16:</b> História de Usuário 13 </p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo consultar os débitos de IPTU/TLP relacionados ao(s) meu(s) imóvel(eis) no aplicativo, com o objetivo de identificar possíveis pendências financeiras. | Débitos | - Consultar facilmente débitos de IPTU/TLP. </br> - Visualizar detalhes dos débitos, incluindo valores, datas de vencimento e descrições. </br - Diferenciar débitos em aberto de vencidos. </br> - Oferecer a opção de imprimir ou gerar um relatório dos débitos. </br> - Garantir a segurança das informações pessoais durante a consulta de débitos. | Alta | Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS14 - Consultar débitos inscritos

<div style="text-align: center">

<p><b>Tabela 17:</b> História de Usuário 14 </p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo consultar os débitos inscritos na dívida ativa, ou  em outros tributos, ou em parcelamentos administrativos, no aplicativo, para verificar a existência de pendências financeiras, proporcionando-me uma visão clara da situação dos débitos pendentes. | Débitos | - Encontrar facilmente a opção de consulta de débitos inscritos. </br> - Exibir claramente os débitos inscritos, incluindo valores e datas de vencimento. </br> - Facilitar a identificação visual dos débitos em aberto e vencidos. </br> - Garantir a segurança das informações pessoais do usuário durante a consulta de débitos. | Média | Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS15 - Enviar email

<div style="text-align: center">

<p><b>Tabela 18:</b> História de Usuário 15</p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo ter a opção de entrar em contato com a Secretaria de Economia do Distrito Federal por meio do aplicativo para estabelecer comunicação eficaz e obter assistência ou informações necessárias. | Contato | - O usuário deve encontrar facilmente a opção de enviar um email para a Secretaria de Economia do Distrito Federal no aplicativo. </br> - O aplicativo deve permitir ao usuário enviar o email de forma simples. </br> - O usuário deve receber uma confirmação após o envio bem-sucedido do email. </br> - A comunicação via email deve ser segura. | Média | Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.

</div>

### HS16 - Visualizar informações sobre o aplicativo

<div style="text-align: center">

<p><b>Tabela 19:</b> História de Usuário 16 </p>
</div>

|   História de Usuário   |    Tema    |      Critérios de aceitação     |    Prioridade    |   DI   |
| ----------------------- | ---------- | ------------------------------- | ---------------- | ------ |
| Eu, como usuário, desejo acessar informações detalhadas sobre o aplicativo para aprender a utilizá-lo de forma eficaz e aproveitar ao máximo suas funcionalidades. | Contato | - As informações detalhadas sobre o aplicativo devem ser facilmente encontradas no menu ou tela inicial. </br> - O aplicativo deve oferecer guias claros sobre como usar suas funcionalidades. </br> - Os usuários devem poder entrar em contato com o suporte, se necessário. </br> - A navegação e busca de informações devem ser simples. | Baixa |  Baixa  |

<div style="text-align: center">

<b>Fonte:</b> Lucas Víctor e Lucas Oliveira, 2023.


</div>

## Validação das histórias de usuário

Para validar as histórias de usuário, conduzimos uma entrevista com o nosso [representante-chave](https://github.com/itsmewall) disponível para consulta [neste link](https://youtu.be/N9drF4rqA88). A reunião foi realizada através da plataforma Teams no dia 03 de novembro de 2023, às 21:00 hrs. Após a entrevista, procedemos com as modificações necessárias para garantir que as histórias estejam alinhadas com as expectativas e necessidades do usuário. 

### Bibliografia


> [1] 2023.1-Simplenote, User_story. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-Simplenote/blob/main/docs/modelagem/agil/User_story.md#hist%C3%B3rias-de-usu%C3%A1rio>. 

> [2] DIOGO. Guia definitivo para Histórias de Usuário - Product Management. YouTube, 11 jul. 2022. Disponível em: <https://www.youtube.com/watch?v=pLJ3LxR292w>.

| Versão | Data       | Descrição                                                 | Autor(es)                                               | Revisor(es)                                    |
| ------ | ---------- | --------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------- |
| `1.0`  | 03/11/2023 | Criação do documento                                      | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.1`  | 03/11/2023 | Adição introdução, objetivo, metodologia, padrão de história de usuário            | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.2`  | 03/11/2023 | Adição das estruturas de história de usuário              | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.3`  | 03/11/2023 | Adição das Validação das histórias de usuário             | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.4`  | 03/11/2023 | Adição dos titulos e dos temas da Historia do usuário            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.5`  | 03/11/2023 | Adição das Histórias de usuários            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.6`  | 03/11/2023 | Adição dos criterios de aceitação do 1 ao 11            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.7`  | 03/11/2023 | Adição dos criterios de aceitação do 12 ao 22            | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.8`  | 03/11/2023 | Adição das prioridades            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `1.9`  | 03/11/2023 | Adição das correções com o PO            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `2.0`  | 04/11/2023 | Conserto de todas as tabelas            | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `2.1`  | 04/11/2023 | Adição de vídeo           | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `2.2`  | 05/11/2023 | Adição das dificuldades de implementação "DI"            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
| `2.3`  | 05/11/2023 | Atualização de tabela           | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](https://github.com/gabrielrosa09)  |
