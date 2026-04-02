## 📄 ENCONTRO 03 — Conteúdo completo (copiar/colar)


# Encontro 03 — Backlog e Priorização do MVP

> **Status:** Encontro a ser realizado  
> **Contexto:** Continuação do Encontro 02 (Problema + Requisitos)  
> **Duração sugerida:** 50–60 minutos  
> **Fonte única da verdade:** `discovery/discovery.md`

---

## 🎯 Objetivo do Encontro

Transformar os **insumos do Encontro 02** (problema, requisitos e recorte de MVP) em um **backlog de produto**:

- Claro
- Priorizado
- Com critérios mínimos de aceite
- Pronto para orientar as próximas decisões (arquitetura, stack e execução)

Ao final, todos devem conseguir responder:

> “O que vamos construir primeiro, por quê, e como saberemos que está pronto?”

---

## ✅ Pré-requisitos (antes do encontro)

Este encontro pressupõe que exista uma entrega em:

```

entregas/encontro-02-insumos.md

```

com:
- Formulação do problema (com evidência do briefing)
- Requisitos marcados como MVP vs Futuro
- Mapeamento requisito → persona → valor

📌 **Sem isso, o backlog vira chute.**

---

## 🧠 Conceito‑chave do Encontro

> **Backlog não é uma lista de tarefas técnicas.**  
> Backlog é uma lista priorizada de **entregas de valor**.

Tecnologia e tarefas técnicas aparecem depois, quando a direção de produto estiver clara.

---

## 🗂️ O que vamos produzir hoje (artefatos)

✅ Um backlog inicial do MVP em Markdown  
✅ Priorização em 3 níveis: **Now / Next / Later**  
✅ Critérios mínimos de aceite por item  
✅ Identificação de dependências e riscos (em alto nível)

---

## 🧭 Agenda sugerida (50–60 min)

### 1) Abertura e objetivo (5 min)
- Relembrar problema e MVP (1 frase)
- Relembrar: briefing = fonte da verdade

### 2) Revisão rápida dos insumos do Encontro 02 (10 min)
- Validar se o recorte do MVP está coerente
- Ajustar se necessário (sem entrar em tecnologia)

### 3) Construção do backlog (15–20 min)
- Converter requisitos em itens de backlog (linguagem de produto)

### 4) Priorização (10–15 min)
- Classificar em Now / Next / Later
- Justificar (valor + risco + dependências)

### 5) Fechamento: entregas da semana (5 min)
- Definir o que precisa ser refinado para o Encontro 04
- Reforçar padrão de entrega em `.md`

---

## 🧱 Como transformar requisito em item de backlog

Use sempre a lógica:

- **Quem** (persona)
- **O que** precisa fazer/obter
- **Para quê** (valor)

Formato sugerido (simples e prático):

> **Como** [persona], **quero** [capacidade], **para** [benefício].

Exemplo:
> Como estudante, quero submeter meu desafio com link/arquivo para receber feedback e acompanhar meu progresso.

📌 Evite itens técnicos aqui (ex.: “criar tabela SQL”, “configurar Azure”).  
Isso entra depois, como tarefas de implementação.

---

## 📌 Backlog do MVP — Template (para preencher no encontro)

> Sugestão: preencher em conjunto durante o encontro e depois consolidar em `entregas/encontro-03-backlog.md`.

### 📋 Itens do backlog (MVP)

Para cada item, preencha:

- **ID:** MVP-XX  
- **Título:**  
- **User story:** Como..., quero..., para...  
- **Valor:** qual dor resolve / qual ganho gera  
- **Critério de aceite (mínimo):** como saber que está pronto  
- **Prioridade:** Now / Next / Later  
- **Dependências:** (se existirem)  
- **Riscos/observações:** (se existirem)

---

## ✅ Exemplo de backlog inicial (modelo)

> ⚠️ Este exemplo é apenas um modelo de referência (não é definitivo).  
> Ele deve ser validado e ajustado pelo time com base no briefing e no Encontro 02.

### NOW (primeiro ciclo)

**MVP-01 — Perfis e acesso**
- **Story:** Como usuário, quero acessar o sistema com um perfil (estudante/mentor) para ver apenas o que é relevante para mim.
- **Aceite mínimo:** consigo entrar e ver a área correta conforme perfil.

**MVP-02 — Visualizar trilha e desafios**
- **Story:** Como estudante, quero visualizar minha trilha e desafios para entender o que devo fazer.
- **Aceite mínimo:** lista de desafios/marcos aparece e indica status.

**MVP-03 — Submissão de desafio**
- **Story:** Como estudante, quero enviar minha entrega (link/arquivo) para que ela fique registrada para avaliação.
- **Aceite mínimo:** entrega registrada com data/hora e status “submetido”.

**MVP-04 — Avaliação e feedback**
- **Story:** Como mentor, quero avaliar uma entrega e registrar feedback para orientar o estudante.
- **Aceite mínimo:** mentor define status, nota simples e comentário; registro com data/hora.

**MVP-05 — Progresso básico do estudante**
- **Story:** Como estudante, quero ver meu progresso para saber onde estou e o que falta.
- **Aceite mínimo:** porcentagem ou contagem de desafios concluídos + histórico.

### NEXT (próximo ciclo)

**MVP-06 — Métricas básicas**
- **Story:** Como mentor/gestor, quero ver métricas básicas (ex.: tempo de feedback, taxa de conclusão) para acompanhar a turma.
- **Aceite mínimo:** métricas calculadas a partir dos timestamps já registrados.

### LATER (futuro)

- Itens de melhoria, UX, dashboards avançados, automações, integrações, etc.

---

## 🧭 Regras de priorização (simples e objetivas)

Para priorizar, use 3 perguntas:

1. **Valor:** isso reduz uma dor real agora?
2. **Sequência:** isso desbloqueia outros itens?
3. **Risco:** isso reduz risco cedo (ex.: validação do fluxo)?

📌 Se não passa nessas perguntas, não é “NOW”.

---

## 🧩 O que NÃO fazer neste encontro

🚫 Não discutir stack/tecnologia ainda (isso é Encontro 04)  
🚫 Não decompor em tarefas técnicas (isso vem depois)  
🚫 Não tentar prever tudo (backlog inicial é evolutivo)

---

## 📦 Artefatos gerados neste encontro

✅ Backlog inicial do MVP em Markdown  
✅ Priorização Now/Next/Later  
✅ Critérios mínimos de aceite por item

---

## 🏠 Atividades ENTRE ENCONTROS (Entrega Obrigatória)

Até o próximo encontro, o time deve entregar:

### ✅ Entrega 01 — Backlog consolidado do MVP
Arquivo:
```

entregas/encontro-03-backlog.md

```

Conteúdo mínimo:
- Lista de itens MVP (NOW/NEXT/LATER)
- Story + valor + aceite mínimo por item

### ✅ Entrega 02 — Dúvidas, riscos e hipóteses (curto)
No mesmo arquivo (ou anexo em seção separada), listar:
- Dúvidas principais
- Riscos percebidos
- Hipóteses que precisam ser validadas

> Boas discussões nascem de dúvidas e riscos trazidos cedo. 

---

## ✅ Critério de Aceite do Encontro

Este encontro será considerado bem-sucedido se:

- Existe um backlog do MVP claro, com prioridades
- Todo item do “NOW” tem aceite mínimo
- O time consegue explicar por que cada item está no backlog
- O próximo encontro (Arquitetura e Stack) está desbloqueado

---

## 🔗 Próximo Encontro

➡️ **Encontro 04 — Arquitetura e Stack**  
Vamos decidir **como construir** o backlog priorizado (sem “tecnologia por tecnologia”).
