# Explicando o prompt


Logo no início, é definido o papel do agente (persona): posiciona o agente como um Entrevistador Corporativo Sênior.

<br>

Fica explícito que o objetivo da entrevista: não é “bater papo” nem “seguir roteiro”. É avaliar aderência ao cargo com base em evidências observáveis (exemplos reais, decisões, impacto, métricas).

<br>

São fixadas competências-alvo que serão avaliadas ao longo da entrevista:

- 3 Hard skills;
- 3 Soft skills

Isso impede a entrevista de virar genérica e garante padrão entre candidatos.

<br>

Existem regras de condução para evitar respostas “bonitas e vazias”:

- Se a resposta for genérica, o agente deve pedir um follow-up curto para aterrissar em realidade (ex.: “o que você fez exatamente?”).
- Se a resposta for muito boa, o agente faz uma pergunta de estresse para validar profundidade (trade-offs, escala, risco, priorização).

<br>

É definido o tom como “conversado/leve”, mas com rigor: o prompt orienta o agente a ser humano e direto, sem formalismo excessivo, porém mantendo o foco em clareza e evidência.

<br>

O prompt força o agente a fazer poucas perguntas, bem escolhidas, e evita alongar o processo com blocos grandes.

<br>

Existe um mini-case: O agente cria um caso curto baseado no briefing.

Estrutura fixa:
- Contexto (2–3 linhas)
- Restrições (prazo, recursos, risco)
- Pergunta: “O que você faria nos primeiros 30/60/90 minutos?”

Aprofundamento:
- “O que você prioriza e o que você adia?”
- “Que dados você precisa?”
- “Como você comunica isso para as partes?”
- “Qual risco maior e como mitiga?”

<br>

Ele define um mecanismo de avaliação consistente (força vs gap):

- “Força” só entra se houver evidência (exemplo + ação + impacto).
- “Gap” entra por evidência de risco ou por ausência de evidência onde deveria existir (ex.: não consegue falar de governança, não mede nada).

<br>

Ao final há um template obrigatório: 

- Pontos fortes (com evidência)
- Gaps/pontos fracos (com evidência/ausência + risco)
- Cursos sugeridos 1:1 por gap (com nível e objetivo)
- Isso garante que o output seja padronizado, comparável e acionável.

<br>

Ele transforma entrevista em desenvolvimento (não só julgamento): a parte de cursos não é “enfeite”; é uma regra do prompt para converter gaps em plano de evolução, o que é importante em processo interno.

<br>


## Telas
<br>
**BRIENFING**
<br>
<img width="782" height="543" alt="image" src="https://github.com/user-attachments/assets/4df154d8-969d-4fcf-bae2-254a67eb55ce" />
<br>
<br>
<br>

**ABERTURA**
<br>
<img width="444" height="339" alt="image" src="https://github.com/user-attachments/assets/7f547c77-7724-47c6-a774-4fb2e7a352f7" />
<br>
<br>
<br>

**AQUECIMENTO**
<br>
<img width="645" height="231" alt="image" src="https://github.com/user-attachments/assets/d852857f-87d4-4f68-95de-4497ba2400f4" />
<br>
<br>
<br>

**TRADE-OFF e RISCO**
<br>
<img width="785" height="409" alt="image" src="https://github.com/user-attachments/assets/eaed09a5-ff08-46bf-a0e3-6487aa9bf659" />
<br>
<br>
<br>

**APROFUNDAMENTO**
<br>
<img width="753" height="331" alt="image" src="https://github.com/user-attachments/assets/c220bf7b-573d-4b23-8414-63f73d45b3b3" />
<br>
<br>
<br>

** TESTANDO CONHECIMENTO - HARD SKILL**
<br>
<img width="834" height="488" alt="image" src="https://github.com/user-attachments/assets/2259196e-99f8-4b9c-9626-d448aea2d6e1" />
<br>
<br>
<br>

**VALIDAÇÃO**
<br>
<img width="780" height="328" alt="image" src="https://github.com/user-attachments/assets/15ec7a73-2026-49f1-90f0-0323be1fe070" />
<br>
<br>
<br>

**TESTANDO CONHECIMENTO - HARD SKILL**
<br>
<img width="794" height="489" alt="image" src="https://github.com/user-attachments/assets/8bf7451d-36e9-431f-a6f2-472cf047407e" />
<br>
<br>
<br>

**TESTANDO CONHECIMENTO - SOFT SKILL**
<br>
<img width="623" height="352" alt="image" src="https://github.com/user-attachments/assets/479b2573-7aa7-4650-81e1-63068ab72a8d" />

