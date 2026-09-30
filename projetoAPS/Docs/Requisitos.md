# Ficha de Elicitação de Requisitos

**Curso:** Engenharia de Software  
**Disciplina:** Análise e Projeto de Sistemas  
**Instituição:** UDF Centro Universitário  
**Grupo/integrantes:** https://github.com/bernardo-carvalho001 / https://github.com/rafaelserafinsousa  

**Turma: D2 - Engenharia de Software**   **Data:** 27/09/2026   **Versão:** 1.2

## 1. Identificação do projeto

| Campo | Preenchimento |
|---|---|
| Nome do projeto | Sistema de Gerenciamento de Vagas de Estacionamento (Shopping) |
| Objetivo do projeto | Otimizar o controle de lotação, guiar o motorista até vagas livres e reduzir filas na entrada por meio de automação e integração com câmeras. |
| Contexto e escopo | Controle de fluxo (entrada e saída) e monitoramento em tempo real da ocupação do estacionamento do shopping. |

## 2. Stakeholder e fonte

| Campo | Preenchimento |
|---|---|
| Stakeholder (nome ou papel) | Cliente/Motorista (Usuário Final) e Operador de Estacionamento. |
| Relação com o projeto | Cliente sofre com as filas; Operador realiza o controle de acesso. |
| Contato ou setor (se aplicável) | Operação / Administração do Shopping. |
| Técnica e data da elicitação | Análise de cenário, discussão de arquitetura de usabilidade e observação (27/09/2026). |
| Responsável pelo registro | Bernardo Carvalho e Rafael Serafin. |

## 3. Requisito elicitado

| Campo | Preenchimento |
|---|---|
| ID do requisito | REQ-001 *(Mapeia os requisitos RF01 e RF02 do levantamento MoSCoW)* |
| Necessidade relatada pelo stakeholder | "Não quero enfrentar fila na entrada preenchendo cadastros ou informando modelo e cor do meu carro; quero apenas entrar rapidamente." |
| Descrição consolidada | O sistema deve registrar a entrada de veículos identificando-os unicamente por sua placa, preferencialmente via leitura automática (LPR) integrada às câmeras, sem exigir o cadastro prévio de modelo, cor ou dados do condutor. |
| Justificativa ou benefício esperado | Reduzir drasticamente o tempo de espera na cancela (evitando atrito para visitantes e idosos) e viabilizar o controle automatizado da lotação. |
| Tipo | Funcional. |
| Dependências ou dúvidas | Depende da integração com a infraestrutura física já existente no shopping (câmeras LPR e cancelas). |

## 4. Regras de negócio

| ID | Regra de negócio relacionada | Fonte ou responsável pela validação |
|---|---|---|
| RN-001 | A entrada no estacionamento não exige cadastro prévio; visitantes operam de forma anônima baseados apenas na leitura da placa. | Administração do Shopping / Gestão de Fluxo |
| RN-002 | Cada vaga subtraída da lotação geral deve corresponder a uma entrada registrada com sucesso vinculada a uma placa. | Administração do Shopping / TI |

> Descreva políticas, condições e limites do domínio. Caso nenhuma regra tenha sido identificada, registre “Não identificada nesta etapa”.

## 5. Prioridade

**Classificação MoSCoW (marque uma):** 
[X] Must have (essencial)  [ ] Should have (importante)  [ ] Could have (desejável)  [ ] Won't have nesta versão (fora do escopo atual)

**Justificativa da prioridade:** É a porta de entrada do sistema. Sem a identificação ágil do veículo pela placa, todo o fluxo posterior de contagem de vagas, cálculo de tarifa e liberação de cancela fica inviabilizado.

## 6. Critérios de aceitação

Escreva condições verificáveis que permitam decidir se o requisito foi atendido.

| ID | Dado/Quando | Então (resultado esperado) | Evidência ou forma de verificação |
|---|---|---|---|
| CA-01 | Dado que um veículo se aproxima da cancela, quando a câmera realizar a leitura (LPR) com sucesso | Então o sistema registra a placa, data e hora, e abre a cancela instantaneamente. | Log de entrada no banco de dados com os dados corretos em menos de 3 segundos. |
| CA-02 | Dado que o sistema falhe na leitura automática da placa | Quando o operador inserir a placa manualmente, o sistema deve registrar a entrada normalmente. | Teste de falha forçada e inserção manual no painel do operador. |
| CA-03 | Dado que o visitante não possua cadastro no programa de fidelidade | Quando ele entrar, o sistema deve registrar o acesso apenas com a placa de forma anônima. | Acesso liberado sem exibição de erros de "usuário não encontrado". |

## 7. Validação e rastreabilidade

| Campo | Preenchimento |
|---|---|
| Situação | [ ] Pendente de validação  [X] Validado  [ ] Necessita revisão |
| Validado por / data | Bernardo e Rafael (Grupo Revisor) em 28/09/2026 |
| Observações e decisões | Decidiu-se abandonar a coleta de modelo e cor do veículo, pois o processamento gerava alto atrito de usabilidade e fila. |
| Links relacionados | Issue #1, Ficha baseada no arquivo `MoSCoW.md` (RF01 e RF02). |
