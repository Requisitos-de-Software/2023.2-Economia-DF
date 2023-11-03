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

Para a criação do artefacto, foi efetuado uma reunião com os seguintes membros:

| Nome                                          | Cargo                     |
| --------------------------------------------- | ------------------------- |
| -                                             | -                         |
| -                                             | -                         |
| -                                             | -                         |


## Padrão de História de Usuário

Ao escrever as histórias de usuário para este projeto, é crucial seguir as diretrizes especificadas neste documento. Para modelar as histórias de usuário de forma consistente, devemos incluir as seguintes informações:

- **ID:** Este é o identificador único das histórias de usuário. Os IDs estão presentes nos títulos das histórias, que foram organizadas em toggles.

- **História de Usuário:** Cada história de usuário deve seguir a estrutura "Eu, como [usuário], desejo [realizar algo] para que [alcance algum objetivo]".

- **Tema:** É importante indicar a qual tema ou categoria a história de usuário está relacionada, proporcionando um contexto mais amplo.

- **Critérios de Aceitação:** Aqui, devemos listar um conjunto de atributos ou condições que uma funcionalidade deve atender para ser considerada "aceita" ou concluída com sucesso.

- **Prioridade:** A prioridade ajuda a determinar o nível de importância da história de usuário no projeto. Pode ser classificada como alta, média ou baixa, levando em consideração fatores como o valor para o usuário, facilidade de implementação, dependências técnicas e restrições de prazo.

- **Dificuldade de Implementação (DI):** Essa métrica está relacionada à dificuldade de implementar a funcionalidade e pode ser categorizada como baixa, média ou alta.

Seguir este padrão ao criar as histórias de usuário garantirá uma documentação clara e consistente, facilitando o entendimento e a execução eficiente das tarefas do projeto.

## História de Usuário

Em seguida, temos as histórias de usuário:

<details>
   
   <summary>US01 - Efetuar login com email e senha </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td> Eu, como usuário, desejo realizar um login seguro no aplicativo utilizando meu endereço de email e senha, a fim de acessar e desfrutar de todas as funcionalidades disponíveis com tranquilidade e proteção dos meus dados pessoais.</td>
           <td>Login</td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 1: História de Usuário 1 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US02 HS02 - Efetuar login com gov.br </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo realizar login no aplicativo através da integração com o gov.br, para simplificar o acesso e utilizar todas as funcionalidades com a comodidade de minhas credenciais governamentais. </td>
           <td> Login </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 2: História de Usuário 2 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US03 HS03 - Recuperar senha </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td> Eu, como usuário, desejo ter a capacidade de recuperar minha senha de acesso no aplicativo no caso de perda, garantindo a conveniência e a segurança contínua de minha conta.</td>
           <td> Login </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 3: História de Usuário 3 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS04 - Efetuar logout </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo realizar logout no aplicativo após o uso, garantindo a segurança da minha conta e a privacidade das minhas informações. </td>
           <td> Login </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 4: História de Usuário 4 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS05 - Listar </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo listar informações sobre notas fiscais no aplicativo, permitindo que eu confira e acompanhe minhas compras de forma conveniente e organizada. </td>
           <td> Nota Fiscal </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 5: História de Usuário 5 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS06 - Pesquisar</summary>
   <table>
      <thead>
         <tr>
           <td> História de Usuário </td>
           <td> Tema </td>
           <td> Critérios de aceitação </td>
           <td> Prioridades  </td>
           <td> DI </td>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo pesquisar informações sobre notas fiscais no aplicativo, proporcionando-me a capacidade de conferir e rastrear minhas compras de forma eficaz e personalizada.</td>
           <td> Nota Fiscal </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 6: História de Usuário 6 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS07 - Visualizar detalhes </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo visualizar detalhes completos sobre as notas fiscais no aplicativo, permitindo-me uma conferência minuciosa de minhas compras e facilitando o acompanhamento de todas as informações relevantes.</td>
           <td> Nota Fiscal </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 7: História de Usuário 7 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>	HS08 - Imprimir DANFE </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo ter a opção de imprimir o DANFE (Documento Auxiliar da Nota Fiscal Eletrônica) das notas fiscais no aplicativo, para que eu possa conferir minhas compras de forma mais conveniente e organizada.</td>
           <td> Nota Fiscal</td>
           <td> </td>
           <td> </td>
           <td> </td>
        </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 8: História de Usuário 8 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>US09 - Cadastrar</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo cadastrar informações sobre meu(s) veículo(s) no aplicativo, permitindo-me verificar se há quaisquer débitos associados, facilitando assim o controle e a gestão eficaz da situação dos meus veículos. </td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 9: História de Usuário 9 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS10 - Consultar débitos de IPVA </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo consultar os débitos de IPVA associados ao(s) meu(s) veículo(s) no aplicativo, a fim de verificar a existência de quaisquer pendências financeiras, proporcionando-me uma visão clara da situação de pagamento relacionada aos meus veículos. </td>
           <td> Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 10: História de Usuário 10 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS11 - Emitir DAR</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td> Eu, como usuário, desejo a capacidade de emitir o Documento de Arrecadação de Receitas (DAR) no aplicativo para meu(s) veículo(s), permitindo-me identificar e quitar possíveis débitos associados, tornando o processo de regularização mais acessível e prático.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 11: História de Usuário 11 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS12 - Cadastrar </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo cadastrar informações sobre meu(s) imóvel(eis) no aplicativo, a fim de verificar a existência de possíveis débitos e, assim, facilitar o acompanhamento e a gestão eficaz da situação dos meus imóveis.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 12: História de Usuário 12 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS13 - Consultar débitos de IPTU/TLP </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo consultar os débitos de IPTU/TLP relacionados ao(s) meu(s) imóvel(eis) no aplicativo, com o objetivo de identificar possíveis pendências financeiras, oferecendo-me uma visão clara da situação de pagamento associada aos meus imóveis.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 13: História de Usuário 13 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS14 - Emitir DAR</summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo ter a capacidade de emitir o Documento de Arrecadação de Receitas (DAR) no aplicativo para meu(s) imóvel(eis), permitindo-me identificar e quitar possíveis débitos associados, tornando o processo de regularização mais acessível e prático.</td>
           <td> Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 14: História de Usuário 14 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS15 - Consultar débitos inscritos </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo consultar os débitos inscritos na dívida ativa no aplicativo, para verificar a existência de pendências financeiras, proporcionando-me uma visão clara da situação dos débitos pendentes e permitindo-me tomar as medidas necessárias para regularização.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 15: História de Usuário 15 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS16 - Emitir DAR </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo ter a capacidade de emitir o Documento de Arrecadação de Receitas (DAR) no aplicativo referente à dívida ativa, permitindo-me identificar e quitar possíveis débitos pendentes, tornando o processo de regularização mais acessível e prático.</td>
           <td> Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 16: História de Usuário 16 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS17 - Consultar débitos inscritos </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo consultar os débitos inscritos em outros tributos no aplicativo, a fim de verificar a existência de pendências financeiras em relação a outros impostos, proporcionando-me uma visão clara da situação dos débitos pendentes e permitindo-me tomar as medidas necessárias para regularização.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 17: História de Usuário 17 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS18 - Emitir DAR </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo ter a capacidade de emitir o Documento de Arrecadação de Receitas (DAR) no aplicativo referente a outros tributos, permitindo-me identificar e quitar possíveis débitos pendentes em relação a esses impostos, tornando o processo de regularização mais acessível e prático.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 18: História de Usuário 18 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS19 - Consultar débitos inscritos </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo consultar os débitos inscritos em parcelamentos administrativos no aplicativo, a fim de verificar a existência de pendências financeiras em relação a esses acordos de pagamento, proporcionando-me uma visão clara da situação dos débitos pendentes e permitindo-me tomar as medidas necessárias para a regularização.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 19: História de Usuário 19 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS20 - Emitir DAR </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo ter a capacidade de emitir o Documento de Arrecadação de Receitas (DAR) no aplicativo referente aos parcelamentos administrativos, permitindo-me identificar e quitar possíveis débitos pendentes em relação a esses acordos de pagamento, tornando o processo de regularização mais acessível e prático.</td>
           <td>Débitos </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 20: História de Usuário 20 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS21 - Enviar email </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td> Eu, como usuário, desejo ter a opção de entrar em contato com a Secretaria de Economia do Distrito Federal por meio do aplicativo para estabelecer comunicação eficaz e obter assistência ou informações necessárias.</td>
           <td>Contato </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 21: História de Usuário 21 (Fonte: Autores, 2023).</p>
   </div>
</details>

<details>
   <summary>HS22 - Visualizar informações sobre o aplicativo </summary>
   <table>
      <thead>
         <tr>
            <th>História de usuário</th>
            <th>Tema</th>
            <th>Critérios de aceitação</th>
            <th>Prioridade</th>
            <th>DI</th>
         </tr>
      </thead>
      <tbody>
         <tr>
           <td>Eu, como usuário, desejo acessar informações detalhadas sobre o aplicativo para aprender a utilizá-lo de forma eficaz e aproveitar ao máximo suas funcionalidades.</td>
           <td>Contato </td>
           <td> </td>
           <td> </td>
           <td> </td>
         </tr>
      </tbody>
   </table>
   <div style="text-align: center">
      <p> Tabela 22: História de Usuário 22 (Fonte: Autores, 2023).</p>
   </div>
</details>

## Validação das histórias de usuário

Para validar as histórias de usuário, conduzimos uma entrevista com o nosso [representante-chave](#) disponível para consulta [neste link](#). A reunião foi realizada através da plataforma Teams no dia 03 de novembro de 2023, às [inserir horário]. Após a entrevista, procedemos com as modificações necessárias para garantir que as histórias estejam alinhadas com as expectativas e necessidades do usuário.

### Bibliografia

## Histórico de versões

| Versão | Data       | Descrição                                                 | Autor(es)                                               | Revisor(es)                                    |
| ------ | ---------- | --------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------- |
| `1.0`  | 03/11/2023 | Criação do documento                                      | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](#)  |
| `1.1`  | 03/11/2023 | Adição introdução, objetivo, metodologia, padrão de história de usuário            | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](#)  |
| `1.2`  | 03/11/2023 | Adição das estruturas de história de usuário              | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](#)  |
| `1.3`  | 03/11/2023 | Adição das Validação das histórias de usuário             | [Lucas Víctor](https://github.com/Lucas13032003)| [Gabriel Rosa](#)  |
| `1.4`  | 03/11/2023 | Adição dos titulos e dos temas da Historia do usuário            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](#)  |
| `1.5`  | 03/11/2023 | Adição das Histórias de usuários            | [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)| [Gabriel Rosa](#)  |
