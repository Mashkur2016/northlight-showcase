# Northlight: Governed Agentic AI Operations Platform

> **Showcase repository.** This repo documents the project (architecture, design decisions, results). The source code is private; walkthroughs and code review are available on request.

**Status:** In progress (2026 to present) · Independent portfolio project

## What it is
An MSP-style operations console where governed AI agents triage tickets, diagnose endpoint problems, analyse security alerts and draft reports, while humans keep every consequential decision.

## Tech stack
FastAPI modular monolith · LangGraph agent runtime with tenant-aware checkpointing · PostgreSQL + pgvector with Row-Level Security · React / TypeScript front end · GitHub Actions CI

## Design highlights
- **Autonomy ladders:** agents earn more autonomy in defined steps, and humans approve consequential actions.
- **Policy enforced by code, not by a model:** authorisation, tenancy and budgets are deterministic checks that no model output can override.
- **Append-only, hash-chained audit log** and a separate job-signing service.
- **60+ Architecture Decision Records** and a versioned master specification.
- **Multi-agent software-delivery workflow with Claude Code:** 9 specialist agents (planner, architect, implementer, QA, code / security / architecture reviewers) with enforced gates and CI checks (lint, type-check, tests, dependency and secret scans).

## Links
Portfolio: https://mashkur.denimography.co.uk · LinkedIn: https://linkedin.com/in/mashkur-alam-76330252
