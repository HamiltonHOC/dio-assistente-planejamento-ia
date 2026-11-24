# Demonstração Prática - Caso de Teste Fictício

Todos os dados abaixo são fictícios. O objetivo deste teste foi validar as 6 habilidades e as 5 bases do Planner sem expor metas pessoais nem informação real.

## Cenário do Teste Fictício
- **Perfil:** Alguém que trabalha presencialmente 44h por semana em horário comercial, gasta 1h30 por dia no trânsito e só tem **6 horas livres brutas na semana** (terça 20h00-21h30, quinta 20h00-21h30 e sábado 09h00-12h00).
- **Pedido inicial solto:** *"Quero aprender automação com IA para mudar de área nos próximos meses."*

---

## Turno 1 - Habilidade 01: Esclarecer e Registrar Objetivo (Modo Divergente)

**Entrada:** *"Rode a Habilidade 01 para: 'Quero aprender automação com IA para mudar de área nos próximos meses', com teto de 6h por semana."*

**Saída:**

> `MESA MATRIX PLANNER — [DESTRUIDOR] · [CONSTRUTOR SELVAGEM] · [CALIBRADOR]`

**`[DESTRUIDOR]`:**  
Isso não é objetivo, é desejo vago sem prazo nem prova de entrega. "Aprender automação" é coisa sem fim: dá para assistir a 60 aulas em seis meses e terminar sem nada funcionando para mostrar. Pior ainda: com 6 horas livres por semana depois de um turno CLT de 44h, tentar estudar teoria ampla, linguagem de programação e mercado ao mesmo tempo quebra na segunda semana.

**`[CONSTRUTOR SELVAGEM]`:**  
Três recortes diferentes para sair do discurso e virar entrega concreta:
1. **Recorte A - Dois fluxos funcionando no GitHub (8 semanas):** Instalar n8n, conectar IA via prompt estruturado com JSON e publicar 2 automações práticas usando dados de teste e documentação limpa.
2. **Recorte B - Uma automação de rotina interna (4 semanas):** Resolver um gargalo real de triagem de planilhas/e-mail usando ferramenta visual e transformar num estudo anônimo.
3. **Recorte C - Protótipo comercial (10 semanas):** Criar sistema completo com site, cadastro de usuário e painel pago.

**`[CALIBRADOR]`:**  
O Recorte C é suicídio de agenda para 6h por semana. O **Recorte A (8 semanas)** fecha melhor risco e prova prática. Antes de ir para tarefas, fecho os 5 campos obrigatórios da base `Objetivos`:

| Campo | Definição |
| :--- | :--- |
| **Nome do objetivo** | Construir e publicar 2 automações práticas com IA no GitHub |
| **Prazo fechado** | 8 semanas (56 dias) |
| **Critério binário de pronto** | Ter 2 repositórios públicos com o fluxo `.json`, massa fictícia de teste e README explicando como rodar (`SIM/NÃO`) |
| **Teto semanal** | 6h brutas (5h úteis + 1h de folga para imprevisto) |
| **Não-Escopo** | Não criar site pago nem login; não estudar matemática de redes neurais agora; não tentar aprender 3 linguagens ao mesmo tempo |

*Standby. Aguardando Veto Soberano do Diretor para aprovar o Recorte A com esse Não-Escopo.*

---

## Turno 2 - Habilidade 02: Montar Plano de Ação (3 Rotas e Poda)

**Entrada:** *"Aprovado o Recorte A. Pode rodar a Habilidade 02."*

**Saída:**

> `MESA MATRIX PLANNER — [DESTRUIDOR] · [CONSTRUTOR SELVAGEM] · [CALIBRADOR]`

**`[CONSTRUTOR SELVAGEM]` — Três rotas opostas:**
- **Rota 1 (Tradicional):** 4 semanas vendo aulas e teoria antes de abrir a ferramenta; deixa os projetos para as duas últimas semanas.
- **Rota 2 (Fluxo Reverso por Entrega):** Já instala o n8n no Dia 1 e constrói o Projeto 1 rodando com dados fictícios nas Semanas 1-4; Projeto 2 nas Semanas 5-7; revisão final na Semana 8.
- **Rota 3 (Código Puro do Zero):** Escrever todo o motor e as integrações na mão sem ferramenta visual.

**Avaliação:**

| Rota | Prós reais | Onde quebra | Dose Mínima Efetiva | Nota |
| :--- | :--- | :--- | :---: | :---: |
| **Rota 1** | Teoria arrumada no começo | Passa 5 semanas sem nada pronto; o cansaço derruba antes do primeiro fluxo | 8h/sem. | **4/10** |
| **Rota 2** | Projeto 1 no ar já na metade do prazo; aprendizado direto no erro real | Exige cortar frescura visual e ir direto para o que funciona | **5h/sem.** | **9/10** |
| **Rota 3** | Liberdade total de código | Trava na Semana 2 tentando resolver detalhe de API que o n8n já resolve pronto | 12h/sem. | **3/10** |

**Poda na mesa (`[DESTRUIDOR]` + `[CALIBRADOR]`):**  
Fora **Rota 1** (muita aula antes de botar a mão na massa) e **Rota 3** (impossível caber em 6h livres). Fica a **Rota 2**.

**Quebra inicial para a base `Plano de Ação`:**
- **T-01** *(Sem. 1-2 · 2,5h · P1)*: Instalar n8n e montar 1 fluxo mínimo recebendo JSON de teste (`Pronto`: fluxo salva 1 linha em planilha fictícia).
- **T-02** *(Sem. 1-2 · 2,5h · P1)*: Ligar etapa de IA para classificar 5 chamados fictícios e devolver JSON estruturado.
- **T-03** *(Sem. 3-4 · 5,0h · P1)*: Tratar erro básico, exportar fluxo `.json` e subir Repositório 1 no GitHub.
- **T-04** *(Sem. 5-7 · 12,0h · P1)*: Construir Projeto 2 (leitor de prazos e resumo semanal).
- **T-05** *(Sem. 8 · 4,0h · P1)*: Documentar Projeto 2 e testar os 2 links em aba anônima.

*(Aguardando Veto Soberano para distribuir na semana.)*

---

## Turno 3 - Habilidade 03: Adaptar Plano à Rotina Real (Modo Convergente)

**Entrada:** *"Ok. Quero fechar T-01 e T-02 já na Semana 1 usando as 6h inteiras (terça 1,5h, quinta 1,5h e sábado 3h) mais 1h extra de revisão."*

**Saída:**

> `MESA MATRIX PLANNER — [MODO CONVERGENTE · CONTA DIRETA DE ROTINA]`

**Conta de capacidade:**
- Horas brutas informadas: `1,5h (Ter) + 1,5h (Qui) + 3,0h (Sáb) = 6,0h`
- Margem mínima obrigatória (cerca de 20%): `1,0h` protegida para imprevisto
- **Capacidade real útil:** `5,0h na semana`
- **Corte necessário:** Você pediu `6,0h` de tarefa (`T-01` + `T-02` + `1h` extra). A hora extra sai fora da semana e a última hora de sábado (`11h00-12h00`) fica protegida como margem sem tarefa nova.

| Dia | Horário | Livre | Tarefa | Carga | Margem? |
| :--- | :--- | :---: | :--- | :---: | :---: |
| **Terça** | 20h00-21h30 | 1,5h | `T-01`: Instalar n8n + fluxo inicial | 1,5h | Não |
| **Quinta** | 20h00-21h30 | 1,5h | `T-01` (1h final) + começar `T-02` (0,5h) | 1,5h | Não |
| **Sábado** | 09h00-11h00 | 2,0h | `T-02`: Fechar prompt JSON e testar 5 casos | 2,0h | Não |
| **Sábado** | 11h00-12h00 | 1,0h | *Folga protegida para atrasos e imprevistos* | 0,0h | **Sim** |

---

## Turno 4 - Habilidade 04: Antecipar Obstáculos e Definir Plano B (Modo Divergente)

**Entrada:** *"Rode a Habilidade 04."*

**Saída:**

> `MESA MATRIX PLANNER — [DESTRUIDOR] · [CONSTRUTOR SELVAGEM] · [CALIBRADOR]`

| ID | O que pode travar de verdade | Prob. / Imp. | Gatilho de Alerta | Plano B (15 minutos) |
| :--- | :--- | :---: | :--- | :--- |
| `OBS-01` | Chegar cansado às 20h na terça/quinta e perder meia hora sem saber o próximo passo | Alta / Médio | Abrir vídeo longo às 20h15 | Sessão curta de 15 min: rodar apenas 1 teste num único nó e deixar anotado o ponto exato para sábado |
| `OBS-02` | Erro de JSON ou chave de API travar o bloco inteiro | Alta / Alto | Passar de `25 minutos` no mesmo erro | Travar cronômetro, jogar erro + JSON no Claude/Gemini ou trocar por dado fixo (`mock`) para não parar o fluxo |
| `OBS-03` | Imprevisto no trabalho ou em casa comer o sábado de manhã | Média / Alto | Ver até sexta à noite que sábado furou | Mover só a tarefa P1 principal para o bloco de margem ou testar 2 casos em vez de 5 |
| `OBS-04` | Inventar função nova na Semana 3 e não subir o Projeto 1 | Média / Alto | Vontade de fazer tela bonita antes do commit | Reler o `nao_escopo` do `OBJ-01` e anotar a ideia num bloco separado para depois |

---

## Turno 5 - Habilidade 05: Tribunal Fênix de Viabilidade (Turno Isolado)

**Entrada:** *"Antes do Dia 1, rode a Habilidade 05."*

**Saída:**

> `MESA MATRIX PLANNER — [DESTRUIDOR] · [CONSTRUTOR SELVAGEM] · [CALIBRADOR]`

**Pergunta do Protocolo Fênix:** *"Se todo este plano estiver errado do começo ao fim, o que é verdade aqui e vai fazer ele quebrar numa semana ruim?"*

**Ata do Tribunal (proibido consertar o plano nesta resposta):**
1. **Acusação 1 (`T-04` grande demais):** O bloco `T-04` está marcado com `12h` direto para o Projeto 2. Em blocos picados de `1,5h`, tarefa grande sem sub-etapa faz perder o fio da meada toda terça-feira e vira facilmente `20h`.
2. **Acusação 2 (Dependência de cota gratuita externa):** Se uma API gratuita cair ou pedir configuração chata no meio do sábado, a manhã inteira morre em burocracia.
3. **Acusação 3 (Rendimento irreal à noite):** Contar `1,5h` às 20h depois de um dia inteiro de trabalho pesado como se rendesse igual a `1,5h` no sábado de manhã é erro de conta.

**Veredito:** `T-01` e `T-02`: **`SOBREVIVEM`** | `T-04` (bloco único de 12h): **`FRÁGIL (FATIAR)`**.

*Turnos separados respeitados. Aguardando Veto Soberano do Diretor sobre o que cortar ou fatiar antes da Semana 1.*

*(Decisão do Diretor: fatiar `T-04` em blocos máximos de `2,5h` e usar `mock.json` sempre que configuração de API passar de `25` minutos.)*

---

## Turno 6 - Habilidade 06: Revisão Semanal (Semana 1)

**Entrada:** *"Check-in Semana 1: na terça fiz 1,5h e fechei T-01. Na quinta cheguei atrasado do trabalho e fiz só 1h. No sábado travei num erro de JSON por 45 min e rendi 1h útil de T-02."*

**Saída:**

> `MESA MATRIX PLANNER — [DESTRUIDOR] · [CONSTRUTOR SELVAGEM] · [CALIBRADOR]`

**1. Conta fria da semana:**
- Planejado útil: `5,0h`
- Executado real: `1,5h + 1,0h + 1,0h = 3,5h`
- Taxa de execução: `70%` (`Desvio controlável`)
- Entregas fechadas: `T-01` (`Concluído`) e `T-02` (`Em Andamento`, faltam 3 de 5 testes).

**2. Causa raiz (`[DESTRUIDOR]`):**  
Terça funcionou porque o passo era pequeno e claro. O sábado perdeu rendimento porque você **não cumpriu o gatilho de 25 minutos do `OBS-02`**: ficou `45` minutos brigando com erro de JSON na mão em vez de puxar o Plano B.

**3. Ajuste da Semana 2 (`[CALIBRADOR]`):**
- Não tente empurrar `6,5h` para a Semana 2 querendo "pagar atraso". Mantenha o teto real de **5h úteis + 1h de margem**.
- Terça (`1,5h`): fechar os 3 testes que faltam de `T-02` com `mock.json`.
- Quinta (`1,5h`) + Sábado (`2,0h`): começar `T-03` (tratamento de erro e rascunho do README).
- Regra para a próxima semana: cronômetro de `25` minutos visível na mesa sempre que der erro técnico.
