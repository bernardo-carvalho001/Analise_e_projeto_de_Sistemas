Modelo do template: https://miro.com/app/board/uXjVHo3EFlE=/

# 📋 Estacionamento de shopping

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
O projeto consiste em um sistema de estacionamento voltado para shoppings centers, cujo objetivo é realizar o registro e o gerenciamento integrado de carros, vagas, usuários e segurança. A solução permitirá controlar a entrada e saída de veículos, monitorar a ocupação de vagas em tempo real, cadastrar e gerenciar usuários (clientes e operadores) e reforçar a segurança por meio de recursos como registro de ocorrências, controle de acesso e monitoramento das áreas do estacionamento. Dessa forma, o sistema busca otimizar a operação, melhorar a experiência dos clientes e garantir maior controle e segurança sobre o fluxo de veículos e pessoas no ambiente.



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
Nosso projeto pretende desenvolver um sistema de estacionamento que exiba em tempo real a lotação e a disponibilidade de vagas livres, além de oferecer descontos baseados na fidelidade do cliente, para os clientes e administradores de shoppings, contribuindo para a melhoria da experiência dos usuários, a otimização da ocupação das vagas e o incentivo ao uso recorrente do estacionamento.

---

# 👤 5. Stakeholders

Identifique as pessoas, grupos ou organizações que possuem interesse ou participação no sistema.

| ID | Stakeholder | Papel | Necessidade/Interesse | Influência |
|---|---|---|---|---|
| ST01 |Cliente/Motorista | Usuário final do estacionamento| Encontrar vagas livres rapidamente, obter descontos por fidelidade e ter boa experiência| Alta |
| ST02 |Administrador do Shopping|Gestor do estacionamento |Controlar lotação, otimizar ocupação e melhorar satisfação dos clientes | Alta  |
| ST03 |Operador de Estacionamento |Funcionário que opera o sistema	 |Registrar entradas/saídas, consultar vagas e emitir relatórios|Média |
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
| O que o usuário precisa fazer? |Consultar vagas livres, registrar entrada/saída, acompanhar lotação, acumular pontos de fidelidade e resgatar descontos.|
| Qual problema enfrenta atualmente? |Dificuldade para encontrar vagas livres, falta de informação sobre lotação |
| Quais informações precisa consultar? |Quantidade de vagas livres, localização das vagas, nível de lotação, histórico de uso, pontos de fidelidade e descontos disponíveis. |
| Quais informações precisa cadastrar ou alterar? | Dados do veículo, dados pessoais do cliente, registro de entrada/saída, cadastro de usuários |
| Quais tarefas são repetitivas? |Registro de entrada e saída de veículos, consulta de vagas disponíveis e atualização da lotação. |
| Quais tarefas consomem mais tempo? |Procura manual por vagas livres e controle manual da ocupação do estacionamento. |
| Quais erros acontecem atualmente? |Contagem incorreta de vagas ocupadas, perda de informações de entrada/saída e falhas no controle de descontos. |
| Precisa receber notificações? |Sim, sobre vagas disponíveis, lotação máxima, pontos de fidelidade acumulados e descontos disponíveis. |
| Precisa gerar documentos ou relatórios? |Sim, relatórios de ocupação, fluxo de veículos, histórico de uso e relatórios de fidelidade. |
| Existem informações que precisam ser protegidas? |Sim, dados pessoais dos clientes, informações de veículos, registros de acesso e dados financeiros. |
| O sistema precisará se comunicar com outros sistemas? |Sim, possivelmente com sistemas de pagamento, catracas/cancela, câmeras de segurança e sistemas do shopping. |
| Existem regras obrigatórias que precisam ser respeitadas? |Sim, regras de tempo de permanência, tarifas, critérios de fidelidade e normas de segurança e privacidade de dados (LGPD). |

---

# 💡 7. Necessidades Identificadas

Antes de escrever os requisitos, registre as necessidades identificadas durante o levantamento.

| ID | Stakeholder | Necessidade Identificada | Problema Relacionado |
|---|---|---|---|
| N01 |Cliente/Motorista |Consultar em tempo real a quantidade de vagas livres e a lotação do estacionamento |Dificuldade em encontrar vagas disponíveis |
| N02 |Cliente/Motorista |Receber descontos ou benefícios por fidelidade com o estacionamento |Ausência de incentivos para clientes frequentes |
| N03 |Cliente/Motorista |Localizar com facilidade as vagas livres dentro do estacionamento |Tempo elevado procurando vagas |
| N04 |	Administrador do Shopping |Monitorar a ocupação do estacionamento em tempo real |Falta de controle eficiente sobre a lotação |
| N05 |Administrador do Shopping |Gerar relatórios de fluxo e ocupação para planejamento |Ausência de dados para tomada de decisão |
| N06 |Operador de Estacionamento |Registrar entradas e saídas de veículos de forma rápida e segura |Processos manuais e sujeitos a erro |
| N07 |Setor de Segurança|Controlar o acesso de veículos e pessoas ao estacionamento |Falta de controle e monitoramento eficiente |
| N08 |Equipe de TI / Suporte |Garantir a integridade, segurança e disponibilidade dos dados |Necessidade de proteção de informações sensíveis (LGPD) |

---

# ⚙️ 8. Requisitos Funcionais

Os requisitos funcionais representam as funcionalidades e os comportamentos esperados do sistema.

## Requisitos Funcionais do Projeto

| ID | Requisito Funcional | Stakeholder/Fonte | Necessidade | Prioridade |
|---|---|---|---|---|
|RF01|	|O sistema deve permitir o cadastro de veículos por placa, modelo e cor.|	Cliente/Motorista	|N01, N02| Alta|
|RF02|	O sistema deve registrar a entrada e saída de veículos com data e hora.|	Operador de Estacionamento	|N06| Alta|
|RF03|	O sistema deve exibir em tempo real a quantidade de vagas livres e a lotação do estacionamento.|	Cliente/Motorista, Administrador|	N01, N04| Alta|
|RF04|	O sistema deve identificar e localizar as vagas livres dentro do estacionamento.|	Cliente/Motorista|	N03	| Alta|
|RF05|	O sistema deve calcular automaticamente o tempo de permanência do veículo.|	Operador de Estacionamento|	N06	| Alta|
|RF06|	O sistema deve calcular o valor da tarifa com base no tempo estacionado.|	Cliente/Motorista, Administrador|	N01|Média
|RF07|	O sistema deve gerenciar um programa de fidelidade, acumulando pontos e concedendo descontos aos clientes frequentes.	|Cliente/Motorista	|N02|	Média|
|RF08|	O sistema deve gerar relatórios de ocupação, faturamento e histórico de movimentações.|	Administrador do Shopping	|N05	| Baixa|
|RF09|	O sistema deve emitir comprovante de pagamento impresso ou digital.|	Cliente/Motorista|	N01| Média|
|RF10|	O sistema deve permitir o cadastro e gerenciamento de usuários (clientes e operadores).	|Administrador, Operador|	N06, N08|	Alta|

---

# ⭐ 9. Requisitos de Qualidade

Os requisitos de qualidade devem ser escritos de forma clara e, sempre que possível, **mensurável e verificável**.

Evite:

> ❌ O sistema deve ser rápido.

Prefira:

> ✅ O sistema deve apresentar o resultado das consultas em até 2 segundos para 95% das requisições.

---

## Requisitos de Qualidade do Projeto

| ID | Característica de Qualidade | Requisito | Como será verificado? |
|---|---|---|---|
| RQ01 | Desempenho | | |
| RQ02 | Segurança | | |
| RQ03 | Usabilidade/Interação | | |
| RQ04 | Confiabilidade | | |
| RQ05 | Compatibilidade/Portabilidade | | |

---

# 🚧 10. Restrições

Registre as limitações identificadas no projeto.

As restrições podem estar relacionadas a:

- tecnologia;
- prazo;
- orçamento;
- legislação;
- infraestrutura;
- processo;
- recursos disponíveis.

| ID | Restrição | Categoria | Justificativa/Fonte |
|---|---|---|---|
| RES01 | | | |
| RES02 | | | |
| RES03 | | | |

---

# 📜 11. Regras de Negócio

Registre as regras do domínio que precisam ser respeitadas pelo sistema.

## Exemplo

**RN01**

> Somente estudantes regularmente matriculados podem solicitar o serviço acadêmico.

---

| ID | Regra de Negócio | Fonte |
|---|---|---|
| RN01 | | |
| RN02 | | |
| RN03 | | |

---

# 🔗 12. Rastreabilidade Inicial

Relacione as necessidades identificadas aos requisitos correspondentes.

| Necessidade | Stakeholder | Requisito(s) relacionado(s) |
|---|---|---|
| N01 | | |
| N02 | | |
| N03 | | |
| N04 | | |
| N05 | | |
| N06 | | |
| N07 | | |
| N08 | | |

---

# 🏷️ 13. Priorização dos Requisitos — Técnica MoSCoW

Utilize as seguintes categorias:

| Categoria | Significado |
|---|---|
| 🔴 **M — Must Have** | Requisito indispensável |
| 🟠 **S — Should Have** | Muito importante, mas pode esperar temporariamente |
| 🟢 **C — Could Have** | Desejável se houver tempo e recursos |
| ⚪ **W — Won't Have Now** | Não será implementado nesta entrega |

---

## Matriz de Priorização

| ID | Requisito | MoSCoW | Justificativa |
|---|---|:---:|---|
| RF01 | | M / S / C / W | |
| RF02 | | M / S / C / W | |
| RF03 | | M / S / C / W | |
| RF04 | | M / S / C / W | |
| RF05 | | M / S / C / W | |
| RF06 | | M / S / C / W | |
| RF07 | | M / S / C / W | |
| RF08 | | M / S / C / W | |
| RQ01 | | M / S / C / W | |
| RQ02 | | M / S / C / W | |
| RQ03 | | M / S / C / W | |
| RQ04 | | M / S / C / W | |
| RQ05 | | M / S / C / W | |

---

# 🚀 14. Requisitos da Primeira Versão

Após aplicar a técnica MoSCoW, selecionem os **5 requisitos considerados indispensáveis para a primeira versão**.

| Ordem | ID | Requisito | Por que deve estar na primeira versão? |
|:---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |
| 5 | | | |

---

# ⏭️ 15. Requisitos para Versões Futuras

Selecionem pelo menos três requisitos que poderão ser adiados.

| ID | Requisito | Motivo para adiar | Impacto |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

---

# 🔍 16. Revisão por Pares

**Grupo responsável pela revisão:** __________________________

Registre os problemas identificados durante a revisão.

| ID do Requisito | Problema Encontrado | Sugestão de Melhoria |
|---|---|---|
| | | |
| | | |
| | | |
| | | |

---

# ✅ 17. Checklist de Qualidade dos Requisitos

Antes da entrega, verifique:

- [ ] Os requisitos estão completos?
- [ ] Os requisitos estão corretos em relação às necessidades?
- [ ] Cada requisito representa uma única capacidade ou característica?
- [ ] Os requisitos são necessários?
- [ ] Os requisitos são viáveis?
- [ ] Todos possuem prioridade?
- [ ] Termos ambíguos foram eliminados?
- [ ] Os requisitos podem ser verificados ou testados?
- [ ] A fonte ou stakeholder está identificado?
- [ ] As necessidades estão relacionadas aos requisitos?
- [ ] Os requisitos de qualidade são mensuráveis sempre que possível?
- [ ] As prioridades MoSCoW possuem justificativa?

---

# 💭 18. Reflexão do Grupo

## 18.1 Qual requisito gerou mais discussão durante o levantamento? Por quê?

> Resposta do grupo.

---

## 18.2 Qual necessidade inicialmente parecia simples, mas gerou vários requisitos?

> Resposta do grupo.

---

## 18.3 O grupo identificou algum requisito implícito durante a discussão?

> Resposta do grupo.

---

## 18.4 Qual requisito foi mais difícil de priorizar utilizando MoSCoW? Por quê?

> Resposta do grupo.

---

## 18.5 Houve algum requisito inicialmente considerado Must que mudou de prioridade?

> Resposta do grupo.

---

# 📝 19. Conclusão

Elabore uma breve conclusão apresentando:

- o problema investigado;
- os principais stakeholders;
- as necessidades mais relevantes;
- os requisitos considerados essenciais;
- como a técnica MoSCoW auxiliou na definição da primeira versão.

**Conclusão:**

> Escreva aqui a conclusão do grupo.

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
