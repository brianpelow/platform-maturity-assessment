# platform-maturity-assessment

> Interactive platform maturity assessment for engineering leaders. Six domains, twenty questions, scored report with prioritized recommendations and reference implementations.

## Try it

**[brianpelow.github.io/maturity](https://brianpelow.github.io/maturity)**

## What it covers

Six domains across 20 questions:

| Domain | What it measures |
|--------|-----------------|
| Delivery | Deployment frequency, pipeline automation, change failure rate |
| Reliability | SLOs, MTTR, incident response, error budgets |
| Security | Policy-as-code, compliance automation, audit trail generation |
| Dev Experience | Scaffolding speed, service catalog, PR automation, toil ratio |
| Observability | Correlated telemetry, root cause speed, tech debt tracking |
| Governance | AI decision records, model registry, attribution, automated evidence |

## How it works

Each question is scored 1-5 via slider. The assessment produces:

- An overall maturity score (1.0-5.0) mapped to Initial/Managed/Defined/Measured/Optimizing
- A radar chart across all six domains
- Up to 6 prioritized recommendations with links to reference implementations
- Links to the strategy documents and CTO interview simulator

## Reference implementations

Every recommendation links to a working repo that implements the solution:

- [orbit-platform](https://github.com/brianpelow/orbit-platform) -- policy-as-code, deployment gates
- [cab-automation](https://github.com/brianpelow/cab-automation) -- CAB risk scoring, audit trail
- [IncidentPilot](https://github.com/brianpelow/IncidentPilot) -- automated incident response
- [PlatformSLOBoard](https://github.com/brianpelow/PlatformSLOBoard) -- SLO tracking, error budgets
- [ai-governance-framework](https://github.com/brianpelow/ai-governance-framework) -- replay imperative
- [platform-maturity-model](https://github.com/brianpelow/platform-maturity-model) -- 5-level framework

## License

Apache 2.0