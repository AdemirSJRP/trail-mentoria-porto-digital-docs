# Encontro 05 — Execução Guiada da Semana
## Projeto Trail — Review do Incremento 1, Destravamento Técnico e Planejamento do Incremento 2

> **Importante:** este material substitui a sessão ao vivo desta semana.  
> O objetivo é permitir que a squad avance **com autonomia**, mantendo foco, clareza e consistência técnica.

---

# 1. Contexto do Projeto

O **Projeto Trail** tem como objetivo validar, em um MVP, um fluxo mínimo mas robusto que comprove:

- uma entrega **full stack funcional**
- o ciclo completo de **desafio → entrega → feedback → atualização de métricas**
- geração de valor mensurável para estudantes, mentores e empresas parceiras [1](https://avanade-my.sharepoint.com/personal/m_de_sousa_furlan_avanade_com/_layouts/15/Doc.aspx?sourcedoc=%7B9A66FA9B-DA84-4F6B-900B-2CB08922F4F5%7D&file=Delivery%20Hub%20Model%202026.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1)

Ao longo dos encontros anteriores, já foi definido:
- o problema do produto
- o escopo do MVP
- o backlog inicial
- a stack técnica
- a divisão inicial de entidades, fluxos e diagramas

Agora o projeto entra de vez na fase de **execução**.

---

# 2. Objetivo desta Semana

O objetivo desta semana é **avaliar o progresso atual**, **destravar bloqueios reais** e **avançar no próximo incremento de código**.

Ao final desta semana, a squad deve:

- revisar o que já foi implementado
- identificar com clareza o que ainda está faltando
- corrigir desvios de escopo ou arquitetura
- definir e executar o **Incremento 2**
- registrar o progresso no repositório

---

# 3. Resultado Esperado

Ao final das atividades da semana, a squad deve ter:

- [ ] validado o que já está implementado
- [ ] identificado bloqueios técnicos ou de entendimento
- [ ] definido o escopo do próximo incremento
- [ ] distribuído tarefas entre os participantes
- [ ] atualizado o arquivo de status da semana
- [ ] avançado o código do MVP com foco em fluxo funcional, não em perfeição

---

# 4. Como conduzir este encontro sem mentor ao vivo

A squad deve fazer esta atividade em grupo, usando este documento como guia.

## Dinâmica sugerida
- Fazer a leitura desse guia
- Seguir os blocos na ordem
- Discutir o que for necessário utilizando as ferramentas de comunicação disponíveis (chat, video, áudio)
- Registrar as decisões e o progresso no arquivo de status
- Sempre que houver dúvida entre duas opções, escolham a **mais simples**

---

# 5. Blocos e Atividades da Semana

---

## Bloco 1 — Abertura e alinhamento 

### Leitura desse guia
O foco desta semana não é discutir teoria nova.  
O foco é **entender onde estamos**, **o que já foi feito** e **o que precisamos entregar em seguida**.

### Pergunta de alinhamento
> O que já existe de concreto no projeto hoje?

---

## Bloco 2 — Review do Incremento 1

Cada pessoa ou subgrupo deve mostrar rapidamente:

- o que conseguiu implementar
- o que ainda está incompleto
- o que não conseguiu começar
- o que está quebrando ou travando

### Exemplos do que pode ser mostrado
- API rodando
- login funcionando
- entidade criada
- migration criada
- endpoint respondendo
- tela inicial funcionando
- formulário de submissão criado
- dashboard mockado
- integração ainda não concluída

### Regras deste momento
- Não transformar isso em apresentação longa
- Não justificar demais
- Mostrar o que existe de real

### Saída esperada
Uma visão honesta do estado atual do projeto.

---

## Bloco 3 — Identificação de bloqueios

Agora o grupo deve listar os bloqueios encontrados.

## Classifiquem os bloqueios em 3 tipos

### 1. Bloqueio de entendimento do domínio
Exemplos:
- não sabemos como modelar avaliação
- não sabemos se KPI deve ser salvo ou calculado
- não sabemos o que exatamente entra no MVP

### 2. Bloqueio técnico
Exemplos:
- JWT não funciona
- migration falha
- CORS impede integração
- frontend não consome backend
- controller retorna erro 400

### 3. Bloqueio de organização
Exemplos:
- ninguém pegou a parte X
- duas pessoas fizeram a mesma coisa
- há dependências não alinhadas

### Regra
Listem apenas os bloqueios que realmente impedem avanço.  
Não confundam “dificuldade” com “travamento”.

### Saída esperada
Uma lista curta e priorizada de bloqueios reais.

---

## Bloco 4 — Destravamento orientado pelo princípio da simplicidade 

Sem a presença do mentor, o grupo deve seguir esta regra:

> Sempre escolher a solução mais simples que permita continuar avançando no MVP.

### Exemplos de decisões simples
- usar apenas `DeliveryUrl` em vez de upload de arquivo
- manter avaliação dentro da própria `Submission`
- manter dashboard simples, sem visual avançado
- calcular métricas no backend, sem persistir no banco
- evitar criar novas entidades se não forem obrigatórias

### Perguntas que o grupo deve fazer
- Isso ajuda o MVP a funcionar?
- Isso está no backlog NOW?
- Isso destrava o time?
- Isso evita complexidade desnecessária?

Se a resposta for “não”, **não façam agora**.

### Saída esperada
Um caminho técnico claro para seguir, sem travar em perfeccionismo.

---

## Bloco 5 — Planejamento do Incremento 2

Com base no que já existe e no que travou, o grupo deve definir o próximo incremento.

## O que é um bom incremento?
Um bloco pequeno, validável e com valor claro.

### Exemplo de foco do Incremento 2
Se o Incremento 1 avançou em:
- login
- trilha
- submissão

Então o Incremento 2 deve focar em:
- avaliação
- feedback
- atualização da submission
- primeiros KPIs
- integração entre camadas

### Para cada item, definir:
- o que será feito
- quem será responsável
- qual dependência existe
- como saber que ficou pronto

### Regra
Não planejem a semana inteira em nível detalhado excessivo.  
Planejem apenas o suficiente para executar com clareza.

---

# 6. Checklist de decisão da Squad

Antes de encerrar a sessão, validem:

- [ ] sabemos exatamente o que já está implementado
- [ ] sabemos o que ainda não funciona
- [ ] sabemos quais são os bloqueios principais
- [ ] escolhemos a alternativa mais simples para seguir
- [ ] definimos o Incremento 2
- [ ] distribuímos responsáveis
- [ ] todos sabem qual é seu próximo passo

---

# 7. Entregas obrigatórias da semana

A squad deve atualizar o arquivo:

```text
entregas/encontro-05-status.md
```

## Estrutura mínima esperada

### 1. O que já foi implementado
Descrever objetivamente:
- backend
- frontend
- banco
- integração

### 2. O que ainda está pendente
Listar o que falta para o próximo incremento.

### 3. Principais bloqueios
Separar por:
- domínio
- técnico
- organização

### 4. Decisões tomadas pela squad
Exemplo:
- vamos manter `DeliveryUrl`
- não teremos upload neste momento
- review continua dentro de `Submission`

### 5. Incremento 2
Listar:
- item
- responsável
- status esperado

---

# 8. Template pronto para copiar no arquivo de status

```md
# Encontro 05 — Status da Semana

## 1. O que já foi implementado
- Backend:
- Frontend:
- Banco:
- Integração:

## 2. O que ainda está pendente
- 
- 
- 

## 3. Principais bloqueios
### Domínio
- 

### Técnico
- 

### Organização
- 

## 4. Decisões tomadas
- 
- 
- 

## 5. Incremento 2
| Item | Responsável | Resultado esperado |
|------|-------------|-------------------|
|      |             |                   |
|      |             |                   |
|      |             |                   |
```

---

# 9. Regras da semana para desenvolvimento

## Regras obrigatórias

### 1. Não aumentar escopo
Se não estiver no backlog NOW, não entra.

### 2. Não travar em beleza
Tela feia funcionando vale mais que tela bonita parada.

### 3. Não criar abstrações sem necessidade
Se uma solução simples resolve, use a simples.

### 4. Validar sempre que possível
Cada avanço deve ser testado localmente.

### 5. Registrar o progresso
Tudo importante precisa ir para o arquivo de status.

---

# 10. Uso de IA nesta semana

A squad pode e deve usar o GitHub Copilot Free no VS Code para acelerar o trabalho.

## Usem IA para
- boilerplate
- DTOs
- classes
- endpoints
- formulários
- testes básicos
- commits
- descrições de PR

## Mas lembrem:
> IA acelera o teclado.  
> O entendimento continua sendo responsabilidade de vocês.

### Regra prática
Antes de commitar qualquer coisa:
- leia
- entenda
- teste
- adapte ao projeto

---

# 11. Perguntas de autoavaliação da squad

Antes de encerrar a semana, perguntem:

1. O projeto avançou de forma visível?
2. Conseguimos destravar o que estava impedindo o time?
3. O próximo incremento está menor e mais claro?
4. O que aprendemos esta semana?
5. O que precisamos simplificar ainda mais?

---

# 12. Mensagem final

> Melhor um MVP simples funcionando  
> do que uma arquitetura perfeita sem entrega real.

O objetivo desta semana não é impressionar.  
É **continuar construindo**.

---