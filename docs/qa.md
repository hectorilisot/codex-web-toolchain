# QA Baseline RC1

## Objetivo

Fornecer uma camada independente de validação para sites criados pelo Toolchain.

## Ferramentas

Baseline:

- HTML Validate;
- Axe;
- Playwright;
- Lighthouse;
- Linkinator.

Quando aplicável:

- Security Review.

## Browser QA

Viewports mínimos:

Desktop: 1440 × 900

Mobile: 390 × 844

Verificações do runner incluem:

- HTTP;
- título;
- dimensões;
- console;
- page errors;
- failed requests;
- HTTP errors;
- horizontal overflow.

## QA visual

Obrigatório após QA técnico.

Revisar screenshots full-page verificando:

- hierarquia;
- perceptibilidade do conteúdo;
- contraste;
- clipping;
- overflow;
- espaçamento;
- densidade;
- tipografia;
- CTAs;
- responsividade;
- estados de motion e reveal.

## Limitação conhecida RC1

O runner ainda não identifica com segurança:

- conteúdo essencial em opacity: 0;
- visibility: hidden residual;
- reveal que não concluiu;
- seção visualmente vazia por estado inicial;
- alguns problemas de contraste renderizado.

Por isso:

TECHNICAL PASS != VISUAL PASS

## Política

Self-review de Codex ou Skill é informação auxiliar.

Evidência final vem das ferramentas de QA e revisão independente.

Nenhuma Skill aprova a própria entrega.

## Evolução futura

Avaliar:

- controlled full-page scroll;
- inspeção de estados após animações;
- detecção de conteúdo oculto;
- contraste renderizado;
- elementos perceptíveis por seção.

Essas melhorias não bloqueiam o RC1.
