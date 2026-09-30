Modelo do template: [https://miro.com/app/board/uXjVHo3EFlE=/](https://miro.com/app/board/uXjVHo3EFlE=/?share_link_id=30023053919)

# 📋 Sistema de Gerenciamento de Vagas de Estacionamento

## Levantamento e Priorização de Requisitos

**Etapa:** Levantamento de Requisitos (Utilizar a ficha dos requisitos levantados) 
**Técnica de Priorização:** MoSCoW  
**Data:** 28/09/2026
**Turma:** D2 - Engenharia de Software 

---

# 👥 1. Identificação do Grupo

| Integrante | Nome |
|---|---|
| 1 |[rafaelserafinsousa](https://github.com/rafaelserafinsousa)  |
| 2 |[Bernardo carvalho](https://github.com/bernardo-carvalho001)|


---

# 2. Identificação do Projeto

**Estacionamento de shopping:**  

**Descrição resumida do projeto:**  
O projeto consiste em um sistema de gerenciamento de vagas de estacionamento voltado para shoppings centers, cujo objetivo é realizar o registro e o gerenciamento integrado de carros, vagas, usuários e segurança. A solução permitirá controlar a entrada e saída de veículos de forma ágil (com leitura de placas), monitorar a ocupação de vagas em tempo real, cadastrar e gerenciar usuários (clientes e operadores) e reforçar a segurança por meio de recursos como registro de ocorrências, controle de acesso e monitoramento das áreas do estacionamento. Dessa forma, o sistema busca otimizar a operação, melhorar a experiência dos clientes (guiando-os até as vagas) e garantir maior controle sobre o fluxo de veículos e pessoas no ambiente.

---

# 3. Problema Identificado

## 3.1 Qual problema será resolvido?

**Resposta:**
A dificuldade que os clientes enfrentam para encontrar vagas disponíveis em estacionamentos de shoppings, a falta de controle eficiente sobre a lotação do estacionamento e a ausência de incentivos que recompensem a fidelidade dos usuários. Esses fatores geram tempo de espera elevado, má experiência para o cliente e desaproveitamento da capacidade real de ocupação do estacionamento.

---

## 3.2 Quem é afetado pelo problema?

**Resposta:**
Os principais afetados são: os clientes/motoristas que utilizam o estacionamento do shopping e perdem tempo procurando vagas; os operadores do estacionamento, que não conseguem gerenciar a ocupação de forma eficiente; e a administração do shopping, que sofre impactos negativos na experiência do cliente e no uso dos seus serviços.

---

## 3.3 Como o problema é resolvido atualmente?

**Resposta:**
Atualmente, os clientes precisam circular pelas dependências do estacionamento procurando vagas livres de forma visual e manual, sem qualquer informação prévia sobre a lotação ou disponibilidade de vagas. Os operadores, por sua vez, controlam a entrada e saída de veículos de forma limitada, geralmente sem dados em tempo real sobre a ocupação total. Além disso, não existem programas de fidelidade ou descontos que reconheçam e recompensem clientes frequentes.

---

## 3.4 Principais dificuldades encontradas

Liste pelo menos três dificuldades observadas.

1. Falta de informação em tempo real sobre a lotação e a localização de vagas livres, fazendo com que os motoristas percam tempo circulando pelo estacionamento.
2. Ausência de controle eficiente da ocupação por parte dos operadores e da administração do shopping, dificultando a gestão e o planejamento do espaço.
3. Inexistência de um sistema de fidelidade que ofereça descontos ou benefícios aos clientes frequentes, desestimulando o uso recorrente do estacionamento.

---

# 🎯 4. Objetivo do Projeto

**Objetivo:**
Nosso projeto pretende desenvolver um sistema de estacionamento que exiba em tempo real a lotação e a disponibilidade de vagas livres (através de painéis físicos e aplicativo), além de oferecer descontos baseados na fidelidade do cliente. Isso contribuirá para a melhoria da experiência dos usuários, a otimização da ocupação das vagas e o incentivo ao uso recorrente do estacionamento, tudo sem gerar filas adicionais ou atrito na entrada.

---

# 👤 5. Stakeholders

Identifique as pessoas, grupos ou organizações que possuem interesse ou participação no sistema.

| ID | Stakeholder | Papel | Necessidade/Interesse | Influência |
|---|---|---|---|---|
| ST01 |Cliente/Motorista | Usuário final do estacionamento| Encontrar vagas livres rapidamente, obter descontos por fidelidade e ter boa experiência| Alta |
| ST02 |Administrador do Shopping|Gestor do estacionamento |Controlar lotação, otimizar ocupação e melhorar satisfação dos clientes | Alta  |
| ST03 |Operador de Estacionamento |Funcionário que opera o sistema |Registrar entradas/saídas, consultar vagas e emitir relatórios|Média |
| ST04 |Setor de Segurança |Responsável pela segurança do local |Monitorar acessos, registrar ocorrências e garantir controle de entrada/saída | Média  |
| ST05 |Equipe de TI / Suporte |Responsável técnico pelo sistema |Garantir funcionamento, manutenção e integridade dos dados | Média |

---

## Stakeholder principal

**Stakeholder:**
Cliente/Motorista (ST01)

**Por que ele foi considerado o principal stakeholder?**
Porque é o usuário final que mais sofre com o problema identificado (dificuldade em encontrar vagas e falta de benefícios por fidelidade). O sucesso do sistema depende diretamente da melhoria da experiência desse usuário, já que é ele quem utiliza o estacionamento de forma recorrente e justifica a existência do projeto. Além disso, atender bem esse stakeholder impacta positivamente os demais, como a administração do shopping, que ganha em satisfação e retenção de clientes.

---

# 🗣️ 6. Levantamento de Informações

Registre as principais informações obtidas durante o levantamento.

| Pergunta | Resposta |
|---|---|
| O que o usuário precisa fazer? |Consultar vagas livres (telas físicas ou celular), registrar entrada/saída ágil, acompanhar lotação, acumular pontos e resgatar descontos.|
| Qual problema enfrenta atualmente? |Dificuldade para encontrar vagas livres, falta de informação sobre lotação. |
| Quais informações precisa consultar? |Quantidade de vagas livres, localização das vagas (blocos/andares), histórico de uso, pontos de fidelidade e descontos. |
| Quais informações precisa cadastrar ou alterar? | Cadastro de usuário via CPF (opcional), vinculação de placa do veículo e registro de entrada/saída. |
| Quais tarefas são repetitivas? |Registro de entrada e saída de veículos, consulta de vagas disponíveis e atualização da lotação. |
| Quais tarefas consomem mais tempo? |Procura manual por vagas livres e controle manual da ocupação do estacionamento. |
| Quais erros acontecem atualmente? |Contagem incorreta de vagas ocupadas, perda de informações de entrada/saída e falhas no controle de descontos. |
| Precisa receber notificações? |Sim, sobre vagas disponíveis, lotação máxima, pontos de fidelidade acumulados e descontos disponíveis. |
| Precisa gerar documentos ou relatórios? |Sim, relatórios de ocupação, fluxo de veículos, histórico de uso e relatórios de fidelidade. |
| Existem informações que precisam ser protegidas? |Sim, dados pessoais dos clientes (CPF), histórico de acesso e dados financeiros. |
| O sistema precisará se comunicar com outros sistemas? |Sim, integração com catracas/cancelas (leitura de placas LPR), sensores/câmeras de segurança e sistemas de pagamento. |
| Existem regras obrigatórias que precisam ser respeitadas? |Sim, regras de tempo de permanência, tarifas, critérios de fidelidade e normas de segurança e privacidade de dados (LGPD). |

---

# 💡 7. Necessidades Identificadas

Antes de escrever os requisitos, registre as necessidades identificadas durante o levantamento.

| ID | Stakeholder | Necessidade Identificada | Problema Relacionado |
|---|---|---|---|
| N01 |Cliente/Motorista |Consultar em tempo real a quantidade de vagas livres e a lotação do estacionamento |Dificuldade em encontrar vagas disponíveis |
| N02 |Cliente/Motorista |Receber descontos ou benefícios por fidelidade com o estacionamento |Ausência de incentivos para clientes frequentes |
| N03 |Cliente/Motorista |Localizar com facilidade as vagas livres dentro do estacionamento (blocos/andares) |Tempo elevado procurando vagas |
| N04 | Administrador do Shopping |Monitorar a ocupação do estacionamento em tempo real |Falta de controle eficiente sobre a lotação |
| N05 |Administrador do Shopping |Gerar relatórios de fluxo e ocupação para planejamento |Ausência de dados para tomada de decisão |
| N06 |Operador de Estacionamento |Registrar entradas e saídas de veículos de forma rápida e segura |Processos manuais, geração de filas e sujeitos a erro |
| N07 |Setor de Segurança|Controlar o acesso de veículos e pessoas ao estacionamento |Falta de controle e monitoramento eficiente |
| N08 |Equipe de TI / Suporte |Garantir a integridade, segurança e disponibilidade dos dados |Necessidade de proteção de informações sensíveis (LGPD) |

---

# ⚙️ 8. Requisitos Funcionais

Os requisitos funcionais representam as funcionalidades e os comportamentos esperados do sistema.

## Requisitos Funcionais do Projeto

| ID | Requisito Funcional | Stakeholder/Fonte | Necessidade | Prioridade |
|---|---|---|---|---|
|RF01|O sistema deve identificar os veículos unicamente por sua placa (leitura automática LPR ou inserção manual), sem exigir cor ou modelo.| Cliente/Motorista |N01, N02| Alta|
|RF02| O sistema deve registrar a entrada e saída de veículos com data e hora vinculadas à placa lida.| Operador de Estacionamento |N06| Alta|
|RF03| O sistema deve exibir em tempo real a quantidade de vagas livres e a lotação do estacionamento (em painéis e app).| Cliente/Motorista, Administrador| N01, N04| Alta|
|RF04| O sistema deve identificar e localizar as vagas livres dentro do estacionamento (indicando setor/andar).| Cliente/Motorista| N03 | Alta|
|RF05| O sistema deve calcular automaticamente o tempo de permanência do veículo.| Operador de Estacionamento| N06 | Alta|
|RF06| O sistema deve calcular o valor da tarifa com base no tempo estacionado.| Cliente/Motorista, Administrador| N01|Média|
|RF07| O sistema deve gerenciar um programa de fidelidade vinculado ao CPF do usuário, acumulando pontos e concedendo descontos.|Cliente/Motorista |N02| Média|
|RF08| O sistema deve gerar relatórios de ocupação, faturamento e histórico de movimentações.| Administrador do Shopping |N05 | Baixa|
|RF09| O sistema deve permitir pagamento via totem ou aplicativo e emitir comprovante.| Cliente/Motorista| N01| Média|
|RF10| O sistema deve permitir o cadastro de usuários (clientes via CPF e operadores) e vincular placas aos perfis de forma opcional. |Administrador, Operador| N06, N08| Alta|

---

# ⭐ 9. Requisitos de Qualidade
 
## Requisitos de Qualidade do Projeto

| ID | Característica de Qualidade | Requisito | Como será verificado? |
|---|---|---|---|
|RQ01| Desempenho| O sistema deve processar operações críticas (entrada com leitura de placa, saída, consulta de vaga) em até 3 segundos sob carga normal de até 50 requisições simultâneas. |Testes de carga com ferramentas como JMeter, medindo tempo de resposta.|
|RQ02 |Segurança |O sistema deve armazenar senhas com criptografia (hash bcrypt) e registrar todas as ações de operadores em logs auditáveis. |Testes de segurança e auditoria nos logs; verificação do hash no banco.|
|RQ03| Usabilidade/Interação|O sistema deve ter interface responsiva e intuitiva, guiando o usuário por cores (sinalizadores de vagas) e dispensando treinamentos para clientes.| Teste de usabilidade com usuários reais; análise de tempo de execução da tarefa.|
|RQ04| Confiabilidade |O sistema deve estar disponível 99% do tempo em horário comercial (10h às 22h). |Monitoramento de uptime e registro de indisponibilidades.|
|RQ05 |Compatibilidade/Portabilidade| O sistema deve funcionar em painéis de LED físicos, além de desktops e tablets com design responsivo. |Testes em diferentes navegadores, dispositivos e letreiros.|

---

# 🚧 10. Restrições

Registre as limitações identificadas no projeto.

|RES01| O sistema deve respeitar a LGPD no tratamento de dados pessoais dos clientes, solicitando apenas o estritamente necessário (CPF para fidelidade). |Legislação   Lei nº 13.709/2018 (LGPD).|
|RES02| O projeto deve ser entregue dentro do semestre letivo.| Prazo   Cronograma da disciplina.|
|RES03| O sistema deve integrar-se com catracas/cancelas e câmeras (LPR) já existentes no shopping, sem exigir troca da infraestrutura base. |Infraestrutura   Equipamentos já instalados no local.|
|RES04| O orçamento para desenvolvimento e implantação é limitado. |Orçamento   Recursos disponíveis do grupo/projeto.|

---

# 📜 11. Regras de Negócio

Registre as regras do domínio que precisam ser respeitadas pelo sistema.

| ID | Regra de Negócio | Fonte |
|---|---|---|
|RN01| Cada vaga só pode ser ocupada por um veículo por vez. |RF02 / Administração do shopping|
|RN02 |Clientes acumulam pontos de fidelidade vinculados ao seu CPF, independentemente de qual veículo (placa) cadastrado utilizem. |RF07 / Cliente|
|RN03| A tarifa é progressiva: 1ª hora R$10,00 e demais horas R$5,00. |RF06 / Tabela de preços do shopping|
|RN04 |A entrada no estacionamento não exige cadastro prévio; visitantes não cadastrados operam de forma anônima baseados apenas na leitura da placa na cancela. |RF01 / Melhoria da Operação|
|RN05| Somente administradores podem acessar logs completos e alterar tarifas.| RNF02 / Política de segurança|
|RN06| O comprovante de pagamento deve conter placa, tempo de permanência, valor e data/hora. |RF09 / Cliente|

---

# 🔗 12. Rastreabilidade Inicial

Relacione as necessidades identificadas aos requisitos correspondentes.

| Necessidade | Stakeholder | Requisito(s) relacionado(s) |
|---|---|---|
|N01| Cliente/Motorista| RF01, RF03, RF06, RF09|
|N02|Cliente/Motorista |RF01, RF07|
|N03|Cliente/Motorista| RF04, RQ03|
|N04 |Administrador do Shopping |RF03, RF08|
|N05 |Administrador do Shopping |RF08|
|N06| Operador de Estacionamento| RF02, RF05, RF10|
|N07 |Setor de Segurança |RF10, RQ02|
|N08| Equipe de TI / Suporte| RQ02, RES01|

---

# 🏷️ 13. Priorização dos Requisitos — Técnica MoSCoW

Utilize as seguintes categorias:

| ID | Requisito | MoSCoW | Justificativa |
|---|---|---|---|
| RF01 | Identificação por placa | M | Base automatizada para todas as operações do sistema sem gerar filas. |
| RF02 | Registro de entrada e saída | M | Essencial para controle e cobrança do estacionamento. |
| RF03 | Exibir vagas livres e lotação | M | Resolve o problema central identificado (painéis na entrada evitam frustração). |
| RF04 | Localizar vagas livres | M | Complementa RF03 guiando o usuário por setores/blocos internamente. |
| RF05 | Cálculo do tempo de permanência | M | Necessário para tarifação. |
| RF06 | Cálculo da tarifa | S | Importante, mas pode ser ajustado depois (cálculo fixo inicial). |
| RF07 | Programa de fidelidade | S | Agrega muito valor, mas não é impeditivo para abrir o estacionamento. |
| RF08 | Relatórios | C | Desejável para os gestores, mas o controle ao vivo já ajuda inicialmente. |
| RF09 | Emissão de comprovante | S | Importante para o cliente, mas o sistema base foca em gerir as vagas primeiro. |
| RF10 | Cadastro de usuários | M | Necessário para segurança do sistema e vinculação futura da fidelidade. |
| RQ01 | Desempenho | M | Impacta diretamente a experiência de não gerar filas na cancela. |
| RQ02 | Segurança | M | Requisito legal e crítico (LGPD). |
| RQ03 | Usabilidade | S | Importante, a sinalização visual precisa ser instintiva. |
| RQ04 | Confiabilidade | S | Relevante para não parar a operação do shopping. |
| RQ05 | Compatibilidade | C | Desejável, mas não impede a 1ª versão funcionar no sistema local. |

# 🚀 14. Requisitos da Primeira Versão

Após aplicar a técnica MoSCoW, selecionem os **5 requisitos considerados indispensáveis para a primeira versão**.

| Ordem | ID | Requisito | Por que deve estar na primeira versão? |
|:---:|---|---|---|
| 1 | RF03 | Exibir vagas livres e lotação | Resolve o problema central do projeto (cliente sabe antes de entrar se há vaga). |
| 2 | RF01 | Identificação unicamente por placa | Remove o atrito, agiliza a cancela e serve de base para controle. |
| 3 | RF02 | Registro de entrada e saída | Essencial para o funcionamento lógico de ocupação. |
| 4 | RF04 | Localizar vagas livres | Direciona o fluxo lá dentro (sinalização de blocos e andares). |
| 5 | RF10 | Cadastro de usuários | Cria a base de perfis e segurança da operação para o Administrador. |

---

# ⏭️ 15. Requisitos para Versões Futuras

Selecionem pelo menos três requisitos que poderão ser adiados.

| ID | Requisito | Motivo para adiar | Impacto |
|---|---|---|---|
| RF07 | Programa de fidelidade (CPF) | Complexidade adicional de banco de dados e regras de negócio. | Médio — agrega valor, mas a operação principal funciona sem ele. |
| RF08 | Relatórios avançados | Não é estritamente essencial para a operação em tempo real fluir. | Baixo — útil para gestão estratégica, mas pode esperar. |
| RQ05 | Compatibilidade/Portabilidade | O sistema foca primeiro nas cancelas locais e telas do shopping. O app responsivo vem depois. | Baixo — melhora alcance, mas não impede o sistema de rodar. |

---
# 🔍 16. Revisão por Pares

**Grupo responsável pela revisão:** Grupo Revisor (a definir)

Registre os problemas identificados durante a revisão.

| ID do Requisito | Problema Encontrado | Sugestão de Melhoria |
|---|---|---|
| RF01 | Exigência inicial de cadastro, cor e modelo geraria filas absurdas na entrada. | Modificado: Removido cor/modelo. Uso exclusivo de placa de forma passiva (LPR). Visitante entra anônimo. |
| RF07 | A fidelidade atrelada ao carro limitaria famílias ou aluguéis. | Modificado: Fidelidade vinculada ao CPF do usuário, podendo ter 'n' placas associadas. |
| RNF02 | Não especifica tempo de retenção dos logs. | Definir período de armazenamento (ex: 6 meses) respeitando políticas de privacidade. |
| RF06 | Não define o que acontece em caso de sistema inoperante LPR. | Incluir inserção manual de placa caso a câmera falhe na entrada/saída. |

---

# ✅ 17. Checklist de Qualidade dos Requisitos

Antes da entrega, verifique:

- [X] Os requisitos estão completos?
- [X] Os requisitos estão corretos em relação às necessidades?
- [X] Cada requisito representa uma única capacidade ou característica?
- [X] Os requisitos são necessários?
- [X] Os requisitos são viáveis?
- [X] Todos possuem prioridade?
- [X] Termos ambíguos foram eliminados?
- [X] Os requisitos podem ser verificados ou testados?
- [X] A fonte ou stakeholder está identificado?
- [X] As necessidades estão relacionadas aos requisitos?
- [X] Os requisitos de qualidade são mensuráveis sempre que possível?
- [X] As prioridades MoSCoW possuem justificativa?

---# 💭 18. Reflexão do Grupo

## 18.1 Qual requisito gerou mais discussão durante o levantamento? Por quê?

> **Resposta do grupo:** O requisito RF01 (Cadastro de veículos). Nós discutimos a necessidade de cadastrar modelo e cor do carro logo de cara, chegamos a conclusão que exigir dados adicionais na entrada geraria atrito, filas enormes e prejudicaria a usabilidade, logo, enxugamos o requisito para usar exclusivamente a placa do veículo como chave de identificação, priorizando a agilidade.

---

## 18.2 Qual necessidade inicialmente parecia simples, mas gerou vários requisitos?

> **Resposta do grupo:** A necessidade de "oferecer descontos/fidelidade" (N02). Inicialmente parecia ser apenas uma funcionalidade isolada, mas puxou a necessidade de desvincular a fidelidade da placa do veiculo e atrelá-la ao CPF do motorista, isso gerou novos requisitos, como a criação de perfis de usuários (RF10), integração de pagamentos e o gerenciamento de pontos separados da operação de entrada e saída.

---

## 18.3 O grupo identificou algum requisito implícito durante a discussão?

> **Resposta do grupo:** Sim. Identificamos a regra de negócio de acesso anônimo/visitante (RN04). Na ideia de focar no usuário frequente, quase esquecemos de quem visita pela primeira vez como turistas, idosos ou quem não tem o app. Percebemos implicitamente que o sistema não pode bloquear ou atrasar quem não tem cadastro, necessitando de uma via de acesso transparente via leitura passiva da placa na cancela (LPR).

---

## 18.4 Qual requisito foi mais difícil de priorizar utilizando MoSCoW? Por quê?

> **Resposta do grupo:** O Programa de Fidelidade (RF07). Como ele traz muito valor comercial e seve como incentivo ao cliente, a vontade inicial era colocá-lo como *Must*. No entanto, ao aplicarmos a técnica, notamos que o estacionamento consegue abrir as portas e operar fisicamente sem ele, logo, foi classificado como *Should*.

---

## 18.5 Houve algum requisito inicialmente considerado Must que mudou de prioridade?

> **Resposta do grupo:** O cadastro completo de cliente e veículo, achávamos que ter os dados totais de quem entrava era indispensável (*Must*). Após avaliarmos o quão fluido seria, percebemos que o estacionamento só precisa da "Placa" e da "Data/Hora" para funcionar. O cadastro completo e detalhado do cliente mudou de prioridade, virando um pré-requisito atrelado apenas a quem deseja aderir ao programa de fidelidade futuramente.

---

# 📝 19. Conclusão

**Conclusão:**

> O presente projeto investigou os atritos enfrentados diariamente em estacionamentos de shoppings, focando na dificuldade dos motoristas em encontrar vagas livres e na falta de controle analítico por parte da administração. Através do levantamento, identificamos que nossos principais stakeholders (Clientes e Administradores) compartilhavam necessidades complementares: enquanto o cliente precisa de agilidade e orientação visual para estacionar, a gestão precisa de automação e dados de ocupação em tempo real.
> 
> A partir dessas complicações, listamos os requisitos essenciais focados na eliminação de filas e na autonomia do usuário, como o registro de acesso por leitura automática de placas e a exibição de lotação e localização de vagas através de sinalização inteligente. 
>
> A técnica MoSCoW foi fundamental para dar viabilidade à primeira versão do sistema (MVP). Ela nos ajudou a separar o que era "desejável" (como relatórios complexos e o programa de fidelidade via app) do que era "indispensável", nos permitindo focar os esforços na infraestrutura física e sistêmica básica: garantir que qualquer carro consiga entrar rapidamente e que o motorista saiba exatamente para qual setor se dirigir, validando assim a entrega de valor imediata.

---

# 📦 Entregável

O repositório deverá apresentar, no mínimo:

- identificação do projeto e dos integrantes;
- descrição do problema;
- objetivo do projeto;
- stakeholders;
- levantamento das necessidades;
- **8 requisitos funcionais**;
- **5 requisitos de qualidade**;
- **3 restrições**;
- **3 regras de negócio**;
- rastreabilidade entre necessidades e requisitos;
- priorização utilizando **MoSCoW**;
- definição dos requisitos da primeira versão;
- revisão dos requisitos;
- reflexão e conclusão do grupo.

---

# 📚 Referência

REINEHR, Sheila. **Requisitos de Software**. Material de apoio utilizado na disciplina Engenharia de Requisitos.

---

**Disciplina:** Engenharia de Requisitos  
**Projeto:** Levantamento e Priorização de Requisitos  
**Profª Kadidja Valéria**
