# 📋 Ficha de Requisitos — Sistema de Estacionamento

**Disciplina:** Análise e Projeto de Sistemas  
**Unidade:** II — Introdução à Análise e Projeto de Sistemas  
**Atividade:** Transformação do levantamento do sistema em requisitos funcionais e não funcionais

---

## 🏷️ Identificação do Sistema

| Campo | Descrição |
|-------|-----------|
| **Nome do sistema** | Sistema de Estacionamento |
| **Objetivo** | Registro e gerenciamento de carros, vagas, usuários e segurança |
| **Público-alvo** | Motoristas |
| **Responsável pelo levantamento** | Grupo |
| **Versão** | 1.0 |

---

## ⚙️ Requisitos Funcionais (RF)

### RF01 — Cadastro de veículos

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | Cadastrar veículos por placa, carro, modelo e placa |
| **Prioridade** | 🔴 Alta |
| **Critérios de aceitação** | • Campos obrigatórios: placa e modelo.<br>• Placa deve ser única no sistema.<br>• Dados salvos em banco de dados. |
| **Exemplo** | Ao entrar no estacionamento, o motorista informa a placa e o sistema registra a entrada com data/hora. |

---

### RF02 — Gerenciamento de vagas

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve mostrar a disponibilidade de vagas |
| **Prioridade** | 🔴 Alta |
| **Critérios de aceitação** | • Atualização automática ao ocupar ou liberar uma vaga.<br>• Impedir ocupação de vaga já ocupada.<br>• Identificação única por vaga. |
| **Exemplo** | Ao estacionar, o sistema marca a vaga como ocupada e associa ao veículo cadastrado. |

---

### RF03 — Registro de entrada e saída

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve registrar a data/hora de entrada e saída de cada veículo, calculando o tempo de permanência. |
| **Prioridade** | 🔴 Alta |
| **Critérios de aceitação** | • Entrada e saída com timestamp preciso.<br>• Cálculo automático do tempo estacionado.<br>• Histórico de permanência por veículo. |
| **Exemplo** | O sistema registra a entrada às 14:00 e, na saída às 16:30, calcula 2h30 de estacionamento. |

---

### RF04 — Cálculo da tarifa

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve calcular o valor a pagar com base no tempo estacionado e na tabela de preços vigente. |
| **Prioridade** | 🟡 Média |
| **Critérios de aceitação** | • Tarifa progressiva (ex: 1ª hora R$10, demais R$5/hora).<br>• Exibição do valor antes do pagamento. |
| **Exemplo** | Veículo estacionou por 2h30 → valor = R$10 (1ª hora) + R$5 + R$5 (2h adicionais) = R$20. |

---

### RF05 — Emissão de comprovante

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve gerar um comprovante de pagamento impresso ou digital contendo os dados da estadia e valor pago. |
| **Prioridade** | 🟡 Média |
| **Critérios de aceitação** | • Comprovante com placa, tempo, valor e data/hora.<br>• Opção de enviar por e-mail. |
| **Exemplo** | Na saída, o sistema imprime um ticket com "Placa ABC-1234, 2h30, R$20,00, 26/08/2026 16:30". |

---

### RF06 — Relatórios

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve gerar relatórios de ocupação, faturamento diário/mensal e histórico de movimentações. |
| **Prioridade** | 🟢 Baixa |
| **Critérios de aceitação** | • Filtros por data, tipo de veículo ou vaga. |
| **Exemplo** | Administrador gera relatório de faturamento de agosto/2026. |

---

## 🛡️ Requisitos Não Funcionais (RNF)

### RNF01 — Tempo de Resposta

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve processar operações críticas (entrada, saída, consulta de vaga) em no máximo 3 segundos sob carga normal de até 50 requisições simultâneas. |
| **Prioridade** | 🔴 Alta |
| **Critérios de aceitação** | • Tempo médio de resposta < 2 segundos.<br>• Pico máximo aceitável: 5 segundos. |
| **Exemplo** | Ao registrar a saída de um veículo, o comprovante deve ser gerado e exibido em menos de 3 segundos. |

---

### RNF02 — Segurança e controle de acesso

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | O sistema deve garantir a segurança dos dados, com criptografia de senhas e registro de todas as ações dos usuários em logs auditáveis. |
| **Prioridade** | 🔴 Alta |
| **Critérios de aceitação** | • Senhas armazenadas com hash (bcrypt ou similar).<br>• Logs com timestamp, usuário e ação realizada.<br>• Apenas administradores podem acessar logs completos.<br>• Sessão expira após 15 minutos de inatividade. |
| **Exemplo** | Um operador tenta alterar uma tarifa, mas o sistema bloqueia e registra a tentativa no log de auditoria. |

---

### RNF03 — Usabilidade

| Propriedade | Descrição |
|-------------|-----------|
| **Descrição** | A interface deve ser simples e intuitiva. |
| **Prioridade** | 🟡 Média |
| **Critérios de aceitação** | • Design responsivo (funciona em desktops e tablets).<br>• Cores e ícones padronizados para indicar vaga livre/ocupada. |
| **Exemplo** | Um novo operador consegue registrar uma entrada sem precisar de treinamento, apenas seguindo os botões visíveis na tela inicial. |

---

## 📌 Orientações

Um bom requisito deve ser:
- ✅ Claro
- ✅ Específico
- ✅ Verificável
- ✅ Relevante

O grupo deve verificar:
- Identificação
- Descrição
- Prioridade
- Critérios de aceitação
- Exemplo

---

## 📦 Entregável

- [x] Identificação do sistema
- [x] Pelo menos 5 requisitos funcionais
- [x] Pelo menos 3 requisitos não funcionais
- [x] Prioridade de cada requisito
- [x] Critérios de aceitação
- [x] Exemplo de utilização

---

## 👥 Integrantes do Grupo

- **Bernardo Carvalho**
- **Rafael Serafin**

---

> **Próxima etapa:** Os requisitos produzidos servirão de base para a identificação e especificação dos casos de uso.
