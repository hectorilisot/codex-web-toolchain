# Architecture

## Objetivo

O Hetech Web Toolchain separa quatro responsabilidades:

1. requisitos;
2. decisão de rota;
3. implementação;
4. validação.

Uma camada não substitui a responsabilidade da outra.

## Fluxo lógico

CLIENT / INTERNAL INPUT
→ BRIEF.md
→ SKILL ROUTER
→ HUMAN APPROVAL
→ SELECTED ROUTE
→ IMPLEMENTATION
→ TECHNICAL QA + VISUAL QA
→ HOMOLOGATION
→ RELEASE

## Briefing Layer

O briefing contém:

- negócio;
- objetivos;
- público;
- conteúdo;
- identidade;
- arquitetura;
- restrições;
- funcionalidades;
- acessibilidade;
- performance;
- stack;
- escopo;
- critérios de aceitação.

Ele possui prioridade superior às recomendações das Skills.

## Demo Taxonomy Layer

Simple, Premium and Redesign are planning metadata for demonstration projects.

They describe the type of portfolio experience being demonstrated but do not
directly select a Skill, framework, dependency or implementation strategy.

Routing continues to interpret the actual Brief.

Real client projects are governed by the approved client Brief rather than
the demo taxonomy.

## Routing Layer

O Skill Routing Registry não funciona como uma tabela fixa.

Ele registra:

- contextos em que uma rota foi eficiente;
- forças observadas;
- tendências;
- riscos;
- requisitos adicionais de QA.

No modo AUTO-RECOMMEND, o Codex interpreta o briefing e recomenda uma rota.

A decisão permanece humana.

Nenhuma Skill é ativada automaticamente.

## Creative Skill Isolation

Por padrão, nenhuma Skill criativa subjetiva permanece ativa.

Durante um projeto:

briefing
→ routing
→ aprovação
→ ativação de uma Skill
→ trabalho
→ encerramento
→ desativação

A combinação simultânea de Skills criativas subjetivas não é o comportamento padrão.

## Project Layer

Novos projetos começam no skeleton neutro.

O skeleton fornece somente:

- HTML mínimo;
- CSS técnico mínimo;
- JavaScript neutro;
- briefing;
- checklist;
- registro da recomendação da rota.

A direção visual deve nascer do projeto.

## QA Layer

QA técnico e visual são independentes.

Um PASS técnico não implica aprovação visual.

Os benchmarks demonstraram situações em que viewport, HTTP, requests e overflow estavam corretos, enquanto o resultado visual permanecia inadequado.

Por isso, screenshots full-page continuam obrigatórios no RC1.

## Release Layer

Release e deploy são ações separadas.

Quando houver publicação por allowlist, somente arquivos explicitamente aprovados podem entrar no artefato.

Não utilizar cópia da raiz do repositório como processo de publicação.
