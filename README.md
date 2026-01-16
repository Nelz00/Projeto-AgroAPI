# Projeto-AgroAPI

A plataforma é concebida desde a origem como uma solução multiplataforma, composta por uma aplicação web e uma aplicação móvel, ambas suportadas por uma API central e serviços independentes.


## Roadmap (visão geral)

O desenvolvimento é organizado em fases concisas para permitir entregas incrementais e validação contínua:

- Fase 1 — Planeamento & Prototipagem
  - Definição de módulos, UX/UI mockups e arquitetura base.
  - Objetivo: ter um protótipo navegável e a especificação de APIs.
- Fase 2 — Backend Base
  - Implementação de autenticação, modelos de dados e CRUD principal.
  - Objetivo: API estável para suportar as primeiras funcionalidades do frontend.
- Fase 3 — Integrações Externas
  - Integração com serviços meteorológicos, mapas e dados de apoios agrícolas (IFAP).
  - Objetivo: enriquecer dados e permitir previsões básicas.
- Fase 4 — Inteligência & IA
  - Desenvolvimento de modelos de previsão (produção, riscos climáticos) e serviço FastAPI de inferência.
  - Objetivo: disponibilizar previsões, alertas e recomendações.
- Fase 5 — Escala & Mobile
  - Optimização, deploy em produção, e lançamento de app móvel.
  - Objetivo: escalabilidade e maior alcance a utilizadores finais.

## Diagramas e artefactos

As imagens e diagramas que suportam a arquitetura, fluxos de utilizador e práticas de desenvolvimento estão em:

- docs/architectures/ — diagramas de arquitetura (API Gateway, microserviços, serviços IA).
- docs/workflows/ — fluxos de utilizador, ciclo de vida das tarefas e pipeline de desenvolvimento.
- docs/practices/ — práticas de desenvolvimento, testes e CI/CD.

Abra os ficheiros dessas pastas no VS Code ou no visualizador de ficheiros do repositório para ver os diagramas (SVG/PNG/MD inseridos). Se preferir, faça referência direta aos ficheiros no repositório para incluir imagens no README conforme necessário.

## Contribuir

Siga o fluxo de trabalho definido nos diagramas (Issues → branches → implementação → testes → merge/deploy). 

Para novas funcionalidades, abra uma issue com descrição, critério de aceitação e rótulos; crie uma branch por issue e submeta PRs para revisão.
