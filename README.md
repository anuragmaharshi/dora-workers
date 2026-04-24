# dora-workers

Background job workers for the DORA Incident Management platform.

## Future role

This repo will contain the **deadline-checker Lambda** function, extracted from the `dora-api @Scheduled` job introduced in LLD-09. The extraction to a standalone Lambda happens in LLD-16 as part of the AWS migration.

Until LLD-09, this repo contains no runnable code.

## Quickstart

No runnable code yet — see the linked LLD.

## Roadmap

| LLD | Change |
|---|---|
| LLD-09 | Deadline-checker implemented as `@Scheduled` inside `dora-api` (not here yet) |
| LLD-16 | Lambda extracted from `dora-api`, packaged here, deployed to AWS Lambda via Terraform |

## Relevant LLDs

- [LLD-01 — Local Dev Baseline](../dora-docs/low-level-design/LLD-01-local-dev-baseline.md)
- LLD-09 — Deadline Checker (not yet written)
- LLD-16 — AWS Migration (not yet written)
