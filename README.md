# InCareReg: Sistema de Regulação em Saúde

> Estudo de caso. O código-fonte é privado e pertence à **RJF Consultoria**. Este repositório apresenta o projeto e a minha participação nele. As imagens usam **dados fictícios**.

## O problema
Na saúde pública, consultas, exames e leitos são limitados. A **regulação** organiza quem é atendido, onde e quando, de acordo com critérios clínicos e com a capacidade disponível. Sem um sistema, esse controle fica em planilhas, telefonemas e filas sem transparência.

## A solução
O **InCareReg** centraliza a regulação do município:
- Recebe as solicitações das unidades de saúde
- Organiza a fila conforme prioridade e critérios definidos pela regulação
- Faz o agendamento e o encaminhamento para os serviços disponíveis
- Permite acompanhar a situação de cada solicitação
  <!-- confira se a lista corresponde às funcionalidades reais e ajuste -->

## Arquitetura
```
[ Painel web (unidades / reguladores) ]  ←  Angular
                    │
               API REST (.NET / C#)
                    │
               SQL Server
```

## Minha participação
<!-- descreva o que você fez, por exemplo:
- Desenvolvimento de telas e APIs do fluxo de solicitação e agendamento
- Tela de login e controle de acesso
-->

## Tecnologias
C# · .NET · Angular · TypeScript · SQL Server

## Telas
<!-- prints com dados fictícios na pasta /prints -->
