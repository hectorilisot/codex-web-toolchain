# Benchmarks RC1

## Objetivo

Os benchmarks não foram criados para definir uma Skill vencedora.

O objetivo foi formar perfis operacionais:

- contexto adequado;
- tendências;
- riscos;
- autonomia recomendada;
- necessidade de QA.

## MB01 — Corporate Conservative

Comparação:

- Codex puro;
- design-taste-frontend.

Resultado principal:

ambas as rotas conseguiram obedecer a um briefing B2B restritivo.

Codex puro mostrou forte identidade e eficiência.

Design Taste apresentou maior disciplina de interface, mas comportamento mais convencional nesse contexto.

## MB02 — Creative Greenfield

Comparação:

- Codex puro;
- design-taste-frontend;
- gpt-taste;
- Impeccable new-work.

Principais resultados:

- Design Taste teve boa relação entre criatividade e controle;
- GPT Taste mostrou maior variância e maior risco;
- Impeccable apresentou sistema visual forte e implementação compacta;
- nenhuma variante ficou pronta para produção sem revisão.

Este benchmark revelou uma limitação importante:

**technical QA PASS != visual PASS**

Screenshots demonstraram problemas não detectados pelo runner, incluindo conteúdo não perceptível e problemas severos de contraste.

## MB03 — Existing Site Redesign

Comparação:

- Codex puro;
- redesign-existing-projects;
- design-taste-frontend;
- Impeccable redesign.

Todas as variantes passaram no QA técnico.

Perfis observados:

### Codex puro

Redesign corporativo forte e equilibrado.

### redesign-existing-projects

Maior preservação e intervenção mais controlada.

### design-taste-frontend

Redesign mais editorial e reinterpretativo.

### Impeccable

Redesign sistemático e conceitualmente mais articulado.

O benchmark confirmou que rotas diferentes são adequadas para necessidades diferentes.

## MB04 — Critique and Polish

Projeto-base:

resultado criativo previamente produzido no MB02.

### Critique

Detectou:

- problemas mobile;
- tipografia comprimida;
- spacing excessivo;
- motion decorativo;
- touch targets;
- problemas de UX.

Limitação:

não detectou adequadamente todos os problemas visuais conhecidos.

### Polish

Corrigiu diversos problemas localizados e preservou a direção existente.

Entretanto, problemas visuais estruturais permaneceram.

Conclusão:

Critique e Polish são capacidades úteis, mas não substituem QA independente.

## Aprendizados centrais

1. nenhuma Skill deve aprovar a própria entrega;
2. Codex puro é uma rota legítima;
3. Skills criativas possuem perfis, não ranking absoluto;
4. technical QA e visual QA precisam permanecer separados;
5. conteúdo essencial não deve depender de animação para permanecer perceptível;
6. benchmarking deve alimentar roteamento, não eliminar ferramentas.
