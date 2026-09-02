# Skill Registry — RC1

## Política

Skills funcionam como orientação, não autoridade.

Prioridade:

briefing
> identidade e conteúdo aprovados
> requisitos funcionais
> projeto existente e decisões aprovadas
> acessibilidade
> QA
> Skill

Uma Skill criativa principal é utilizada por vez, salvo decisão explícita.

Codex puro é uma rota de produção válida.

## Codex Pure

Uso:

- briefings claros;
- sites corporativos;
- baixa interferência metodológica;
- criação ou redesign com direção bem definida.

Observado:

- forte em contexto corporativo;
- boa capacidade de redesign;
- baixo overhead operacional.

Risco:

- qualidade de acabamento varia conforme briefing e execução.

## design-taste-frontend

Status:

EXPERIMENTAL / USABLE

Uso:

- greenfield com liberdade visual;
- interfaces editoriais;
- tipografia e composição;
- redesign com autorização para reinterpretar.

Tendências:

- composição editorial;
- spacing generoso;
- intervenção visual maior.

Riscos:

- espaço vertical excessivo;
- visual states e motion exigem revisão independente.

QA visual obrigatório.

## gpt-taste

Status:

EXPERIMENTAL / CONTROLLED

Uso:

- exploração conceitual;
- projetos de alto impacto;
- briefing com elevada liberdade visual.

Forças:

- alta variância;
- forte identidade;
- evita soluções excessivamente genéricas.

Riscos observados:

- spacing;
- contraste;
- legibilidade;
- visual states;
- motion decorativo;
- maior custo de revisão.

Requer revisão aumentada.

## redesign-existing-projects

Status:

SPECIALIZED / USABLE

Uso:

- sites funcionais existentes;
- forte requisito de preservação;
- modernização incremental.

Comportamento observado:

- maior preservação entre as rotas testadas;
- intervenção controlada;
- boa disciplina mobile.

Risco:

- pode ser conservadora quando a transformação esperada é maior.

## Impeccable — new-work

Status:

SPECIALIZED / USABLE

Uso:

- criação greenfield autoral;
- projetos em que um sistema visual estruturado é desejável.

Forças:

- construção conceitual;
- consistência desktop/mobile;
- código final relativamente enxuto.

Características:

- workflow estruturado;
- arquivos auxiliares;
- maior overhead operacional.

Self-review não substitui Hetech QA.

## Impeccable — redesign

Status:

SPECIALIZED / USABLE

Uso:

- redesign com evolução visual significativa permitida.

Forças:

- direção conceitual;
- relação entre estética e contexto;
- sistemas visuais coerentes.

Risco:

- pode alterar significativamente a gramática visual original.

## Impeccable — critique

Status:

SPECIALIZED / USABLE

Uso:

- diagnóstico;
- UX;
- acessibilidade;
- responsividade;
- análise antes de refinamento.

Forças:

- boa detecção estrutural;
- achados específicos de CSS e interação.

Limitações:

- não é autoridade final;
- rendering degradado reduz cobertura visual;
- pode confundir dependência de briefing com defeito de implementação.

## Impeccable — polish

Status:

SPECIALIZED / USABLE WITH QA

Uso:

- acabamento;
- responsividade fina;
- interaction states;
- acessibilidade localizada.

Forças:

- preservação;
- baixo redesign;
- correções locais.

Limitações:

- pode preservar problemas estruturais;
- não encontra necessariamente os mesmos problemas do critique.

## Outros componentes

### web-quality-skills

Status:

FUNCTIONALLY QUALIFIED

### security-review

Status:

FUNCTIONALLY QUALIFIED

### skill-scanner

Status:

POSTPONED

Motivo:

durante teste isolado foi observado comportamento de exposição literal de um segredo sintético.

### Superpowers

Status:

ISOLATED EXPERIMENTAL

### Trail of Bits

Status:

POSTPONED

### Higgsfield

Status:

FUTURE CREATIVE TOOLCHAIN
