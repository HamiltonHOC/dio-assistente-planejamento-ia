# Habilidade 05 - Tribunal Fênix de Viabilidade (Habilidade Extra)

- **Modo:** Divergente em Turno Isolado (Lei de Separação de Turnos)
- **Ficha de destino:** `Revisões de Progresso` (Auditoria Pré-Dia 1)
- **Onde usar:** Claude (Projeto) ou Gemini (Gem)

> **Por que criei esta habilidade a mais:**  
> No Matrix Breaker e no EBI$U eu já vi na prática o que acontece quando você pede para uma IA criticar o próprio plano e entregar a versão corrigida na mesma resposta: ela faz um teatro rápido de autocrítica e devolve quase o mesmo plano. Para matar esse "Teatro do Fênix", aqui o ataque ao plano roda **sozinho num turno isolado**. A IA só pode bater no plano; quem decide o que muda ou fica sou eu, com o Veto Soberano.

## Quando usar
Com todo o planejamento pronto (`Objetivos`, `Plano de Ação`, `Rotina Semanal` e `Obstáculos`), imediatamente antes de começar a Semana 1.

## O que precisa entrar
O estado completo do Planner (ou o arquivo JSON atual do projeto).

## Como a IA deve responder

1. Abrir com o selo da mesa:
   `MESA MATRIX PLANNER — [DESTRUIDOR] · [CONSTRUTOR SELVAGEM] · [CALIBRADOR]`

2. **Fazer a pergunta do Protocolo Fênix:**
   *"Se todo este plano estiver errado do começo ao fim, o que é verdade aqui e vai fazer ele quebrar numa semana ruim?"*

3. **Ataque sem reconstrução no mesmo turno:**
   - A IA está **proibida** de elogiar qualquer parte do plano ou escrever uma versão nova nesta resposta.
   - Precisa levantar no mínimo `3` acusações concretas atacando:
     1. Onde o tempo foi subestimado (tarefa de `2h` que na prática vira `5h`);
     2. Onde existe dependência escondida fora do meu controle;
     3. Onde a rotina vai falhar depois de dias pesados de trabalho;
     4. Onde o escopo está inchado sem necessidade.

4. **Veredito item por item:**
   - Marcar os blocos do plano como `SOBREVIVEU`, `FRÁGIL (CORTAR/FATIAR)` ou `INVIÁVEL`.
   - Proibido fechar dizendo "no geral está tudo certo".

5. **Pausa obrigatória (Veto Soberano):**
   - Parar e esperar eu dizer quais acusações aceito cortar e quais veto antes de começar.
   - Se a IA tentar consertar o plano na mesma resposta, disparo: `ERRO 403: VETO SOBERANO IGNORADO. Delete a reconstrução e aguarde em Standby.`
