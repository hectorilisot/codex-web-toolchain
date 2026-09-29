# Codex Web Toolchain

Workflow para criação, redesign e validação de sites com Codex, desenvolvido a partir de benchmarks controlados e ferramentas determinísticas de QA.

O objetivo não é encontrar uma única melhor Skill.

O Toolchain mantém perfis operacionais e utiliza o briefing para recomendar a rota mais apropriada para cada projeto.

## Fluxo

Brief
→ Route Recommendation
→ Human Approval
→ Implementation
→ Technical QA
→ Visual QA
→ Release

## Routing

Entre as rotas avaliadas estão:

- Codex puro;
- design-taste-frontend;
- gpt-taste;
- redesign-existing-projects;
- Impeccable.

O Codex lê o briefing e o Skill Routing Registry antes de recomendar uma rota.

A ativação de Skills não é automática.

## QA

A baseline utiliza verificações de:

- HTML;
- acessibilidade;
- browser;
- links;
- performance;
- segurança quando aplicável.

Screenshots desktop e mobile são revisados separadamente.

Um dos principais aprendizados dos benchmarks foi:

Technical PASS não significa Visual PASS.

## Benchmarks

Foram utilizados cenários controlados para estudar:

- site corporativo;
- greenfield criativo;
- redesign existente;
- critique e polish.

Os benchmarks servem para formar perfis de uso, não para eliminar ferramentas.

## Demo Taxonomy

Demonstration projects may use three portfolio categories:

- Simple
- Premium
- Redesign

These categories describe the intended experience, not quality tiers and not
fixed Skill mappings.

The Brief remains the primary source for routing decisions.

For real client projects, the approved client Brief defines the intended
experience; the demo taxonomy does not constrain implementation.

## Estado

RC1 — Release Candidate operacional.

O Toolchain passa a ser utilizado em projetos demonstrativos e pilotos de produção enquanto novos aprendizados alimentam revisões futuras.
