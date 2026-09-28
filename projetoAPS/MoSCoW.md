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
|RF01|O sistema deve permitir o cadastro de veículos por placa, modelo e cor.|	Cliente/Motorista	|N01, N02| Alta|
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
 
## Requisitos de Qualidade do Projeto

| ID | Característica de Qualidade | Requisito | Como será verificado? |
|---|---|---|---|
|RQ01|	Desempenho|	O sistema deve processar operações críticas (entrada, saída, consulta de vaga) em até 3 segundos sob carga normal de até 50 requisições simultâneas.	|Testes de carga com ferramentas como JMeter, medindo tempo de resposta.|
|RQ02	|Segurança	|O sistema deve armazenar senhas com criptografia (hash bcrypt) e registrar todas as ações em logs auditáveis.	|Testes de segurança e auditoria nos logs; verificação do hash no banco.|
|RQ03|	Usabilidade/Interação|O sistema deve ter interface responsiva e intuitiva, permitindo que um novo operador registre uma entrada sem treinamento prévio.|	Teste de usabilidade com usuários reais; análise de tempo de execução da tarefa.|
|RQ04|	Confiabilidade	|O sistema deve estar disponível 99% do tempo em horário comercial (10h às 22h).	|Monitoramento de uptime e registro de indisponibilidades.|
|RQ05	|Compatibilidade/Portabilidade|	O sistema deve funcionar em desktops e tablets, com design responsivo.	|Testes em diferentes navegadores e dispositivos.|

---

# 🚧 10. Restrições

Registre as limitações identificadas no projeto.

|RES01|	O sistema deve respeitar a LGPD no tratamento de dados pessoais dos clientes.	|Legislação	Lei nº 13.709/2018 (LGPD).|
|RES02|	O projeto deve ser entregue dentro do semestre letivo.|	Prazo	Cronograma da disciplina.|
|RES03|	O sistema deve integrar-se com catracas/cancelas e câmeras já existentes no shopping.	|Infraestrutura	Equipamentos já instalados no local.|
|RES04|	O orçamento para desenvolvimento e implantação é limitado.	|Orçamento	Recursos disponíveis do grupo/projeto.|

---

# 📜 11. Regras de Negócio

Registre as regras do domínio que precisam ser respeitadas pelo sistema.

| ID | Regra de Negócio | Fonte |
|---|---|---|
|RN01|	Cada vaga só pode ser ocupada por um veículo por vez.	|RF02 / Administração do shopping|
|RN02	|Clientes acumulam pontos de fidelidade a cada uso do estacionamento, que podem ser convertidos em descontos.	|RF07 / Cliente|
|RN03|	A tarifa é progressiva: 1ª hora R$10,00 e demais horas R$5,00.	|RF06 / Tabela de preços do shopping|
|RN04	|Somente administradores podem acessar logs completos e alterar tarifas.|	RNF02 / Política de segurança|
|RN05|	O comprovante de pagamento deve conter placa, tempo de permanência, valor e data/hora.	|RF09 / Cliente|
---

# 🔗 12. Rastreabilidade Inicial

Relacione as necessidades identificadas aos requisitos correspondentes.

| Necessidade | Stakeholder | Requisito(s) relacionado(s) |
|---|---|---|
|N01|	Cliente/Motorista|	RF03, RF06|
|N02|Cliente/Motorista	|RF07|
|N03|Cliente/Motorista|	RF04|
|N04	|Administrador do Shopping	|RF03, RF08|
|N05	|Administrador do Shopping	|RF08|
|N06|	Operador de Estacionamento|	RF02, RF05, RF10|
|N07	|Setor de Segurança	|RF10, RNF02|
|N08|	Equipe de TI / Suporte|	RNF02, RQ02|

---

# 🏷️ 13. Priorização dos Requisitos — Técnica MoSCoW

Utilize as seguintes categorias:

| ID | Requisito | MoSCoW | Justificativa |
|---|---|---|---|
| RF01 | Cadastro de veículos | M | Base para todas as operações do sistema. |
| RF02 | Registro de entrada e saída | M | Essencial para controle do estacionamento. |
| RF03 | Exibir vagas livres e lotação | M | Resolve o problema central identificado. |
| RF04 | Localizar vagas livres | M | Complementa RF03 e melhora a experiência. |
| RF05 | Cálculo do tempo de permanência | M | Necessário para tarifação. |
| RF06 | Cálculo da tarifa | S | Importante, mas pode ser ajustado depois. |
| RF07 | Programa de fidelidade | S | Agrega valor, mas não é crítico na 1ª versão. |
| RF08 | Relatórios | C | Desejável, mas pode ser adiado. |
| RF09 | Emissão de comprovante | S | Importante para o cliente, mas pode ser simplificado. |
| RF10 | Cadastro de usuários | M | Necessário para controle de acesso. |
| RQ01 | Desempenho | M | Impacta diretamente a experiência. |
| RQ02 | Segurança | M | Requisito legal e crítico. |
| RQ03 | Usabilidade | S | Importante, mas pode ser refinada. |
| RQ04 | Confiabilidade | S | Relevante, mas pode ser monitorada depois. |
| RQ05 | Compatibilidade | C | Desejável, mas não impede a 1ª versão. |


# 🚀 14. Requisitos da Primeira Versão

Após aplicar a técnica MoSCoW, selecionem os **5 requisitos considerados indispensáveis para a primeira versão**.

| Ordem | ID | Requisito | Por que deve estar na primeira versão? |
|:---:|---|---|---|
| 1 | RF03 | Exibir vagas livres e lotação | Resolve o problema central do projeto. |
| 2 | RF02 | Registro de entrada e saída | Essencial para o funcionamento do estacionamento. |
| 3 | RF01 | Cadastro de veículos | Base para identificação e controle. |
| 4 | RF04 | Localizar vagas livres | Complementa a funcionalidade principal. |
| 5 | RF10 | Cadastro de usuários | Necessário para controle de acesso e segurança. |

---

# ⏭️ 15. Requisitos para Versões Futuras

Selecionem pelo menos três requisitos que poderão ser adiados.

| ID | Requisito | Motivo para adiar | Impacto |
|---|---|---|---|
| RF07 | Programa de fidelidade | Complexidade adicional de regras e integração. | Médio — agrega valor, mas não é crítico. |
| RF08 | Relatórios | Não é essencial para operação básica. | Baixo — útil para gestão, mas pode esperar. |
| RQ05 | Compatibilidade/Portabilidade | Pode ser refinada após validação da 1ª versão. | Baixo — melhora alcance, mas não impede uso. |

---
# 🔍 16. Revisão por Pares

**Grupo responsável pela revisão:** Grupo Revisor (a definir)

Registre os problemas identificados durante a revisão.

| ID do Requisito | Problema Encontrado | Sugestão de Melhoria |
|---|---|---|
| RF01 | Descrição ambígua ("carro, modelo e placa"). | Especificar campos obrigatórios e formato da placa. |
| RF06 | Não define o que acontece em caso de perda de ticket. | Incluir regra para veículos sem registro de entrada. |
| RNF02 | Não especifica tempo de retenção dos logs. | Definir período de armazenamento (ex: 6 meses). |
| RF07 | Falta detalhar como os pontos são acumulados e resgatados. | Criar regra de negócio específica para fidelidade. |
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
