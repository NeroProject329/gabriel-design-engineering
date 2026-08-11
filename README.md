# Gabriel Design Engineering

Plugin/marketplace pessoal para usar o **Gabriel Design Engineering** como orquestrador de trabalhos premium de frontend, UI/UX, motion, 3D e validação visual no ChatGPT Desktop.

## Estrutura V2

```text
.agents/plugins/marketplace.json
plugins/gabriel-design-engineering/
  .codex-plugin/plugin.json
  skills/gabriel-design-engineering/SKILL.md
```

Esta V2 é intencionalmente mínima: ela empacota apenas a skill de orquestração. Skills pessoais, apps e MCPs já instalados no ambiente podem ser selecionados pelo orquestrador quando estiverem disponíveis na sessão.

## Objetivo da V2

Validar primeiro o fluxo completo:

Marketplace Git → instalação → `@gabriel-design-engineering` → runtime → skill carregada.

Depois dessa validação, integrações adicionais podem ser incorporadas ao plugin de forma incremental.
