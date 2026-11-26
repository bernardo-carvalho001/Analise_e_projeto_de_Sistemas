# Vazee — Sistema de Gerenciamento de Vagas de Estacionamento

<p align="center">
  <strong>Estacione com praticidade. Sua experiência no shopping começa aqui.</strong>
</p>

## Sobre o Projeto

**Vazee** é uma proposta de sistema de gerenciamento de vagas de estacionamento voltado para shopping centers. O projeto tem como objetivo otimizar a experiência dos motoristas e melhorar o controle operacional dos estacionamentos, oferecendo informações sobre a disponibilidade e a localização de vagas.

A solução busca automatizar o registro de entrada e saída de veículos, monitorar a ocupação do estacionamento e facilitar a identificação de vagas livres, contribuindo para uma operação mais ágil e organizada.

## Problema Identificado

Atualmente, os clientes precisam circular pelo estacionamento procurando vagas disponíveis de forma visual e manual, sem informações prévias sobre a lotação ou a localização dos espaços livres.

Essa situação provoca:
- Perda de tempo na procura por vagas;
- Aumento da circulação desnecessária de veículos;
- Dificuldade no controle da ocupação do estacionamento;
- Falta de informações em tempo real para clientes e administradores.

## Objetivo do Projeto

Desenvolver um sistema que permita consultar a disponibilidade e a localização de vagas em tempo real, registrar a entrada e saída de veículos e oferecer maior controle sobre a ocupação do estacionamento.

Com isso, pretende-se melhorar a experiência dos motoristas, otimizar o uso das vagas e facilitar o gerenciamento por parte da administração do shopping.

## Funcionalidades do MVP

A primeira versão do sistema prioriza as funcionalidades consideradas indispensáveis após a aplicação da técnica MoSCoW.

| ID | Funcionalidade | Descrição |
|---|---|---|
| RF03 | Consulta de vagas disponíveis | Exibir a quantidade de vagas livres e a lotação do estacionamento. |
| RF01 | Identificação por placa | Identificar os veículos unicamente por meio da placa, utilizando leitura automática ou inserção manual. |
| RF02 | Registro de entrada e saída | Registrar a entrada e saída dos veículos com data e hora vinculadas à placa. |
| RF04 | Localização de vagas | Identificar e indicar a localização das vagas livres por setor ou andar. |
| RF10 | Cadastro de usuários | Permitir o cadastro de usuários e operadores, com possibilidade de vincular placas aos perfis. |

## Tecnologias e Recursos

O documento de levantamento de requisitos prevê a integração com recursos como:
- Leitura automática de placas (LPR);
- Câmeras e sensores;
- Catracas e cancelas;
- Painéis físicos de consulta;
- Aplicativo para consulta de vagas.

*As tecnologias efetivamente utilizadas na implementação deverão ser atualizadas conforme o desenvolvimento do MVP.*

## Equipe de Desenvolvimento

| Integrante | GitHub |
|---|---|
| Rafael Serafim Sousa | [@rafaelserafinsousa](https://github.com/rafaelserafinsousa) |
| Bernardo Carvalho | [@bernardo-carvalho001](https://github.com/bernardo-carvalho001) |

## Links do Projeto

- [Documentação](../Documentação/)
- [Documentos do Projeto](../Docs/)
- [Levantamento e Priorização de Requisitos — MoSCoW](../MoSCoW.md)
- [README principal](../readme.md)

## Próximas Etapas

Após a implementação das funcionalidades essenciais, o projeto poderá evoluir com recursos adicionais previstos no levantamento de requisitos:

- Programa de fidelidade com acúmulo de pontos e descontos;
- Geração de relatórios de ocupação e movimentação;
- Compatibilidade ampliada com dispositivos e painéis;
- Aprimoramentos na experiência de consulta e utilização do sistema.

## Considerações Finais

O Vazee busca solucionar um problema recorrente nos estacionamentos de shopping centers: a dificuldade de encontrar vagas disponíveis e a falta de informações sobre a ocupação do espaço.

O MVP concentra-se nas funcionalidades fundamentais para validar a proposta do sistema, priorizando a identificação dos veículos, o controle de entrada e saída e a consulta e localização de vagas disponíveis.
