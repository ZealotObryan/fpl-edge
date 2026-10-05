# FPL Edge — Source of Truth Status

Date: 2026-10-05

## GitHub
Repository: `ZealotObryan/fpl-edge`

A protected working branch `mobile-first-production` has been created. The repository currently began as a placeholder repository with an initialization commit; the branch is being used to establish the canonical production workflow without overwriting unknown source.

## Vercel
Production project: `fpl_edge`

The current production deployment is healthy, but the Vercel Git deployment context available to this session reports no linked Git project. Attempts to inspect the existing project under the deployment's owning scope are blocked with a Vercel authorization/scope error.

## Next required authorization
Re-authorize the Vercel connection for the account/team that owns `fpl_edge` (`obriensibande-7013`). After authorization, link the existing Vercel project to `ZealotObryan/fpl-edge` rather than creating a duplicate project.

## Release workflow
GitHub -> Preview deployment -> QA -> Production.
