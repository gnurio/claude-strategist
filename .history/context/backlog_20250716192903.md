<!-- backlog.md -->

# 🗂 Initial Backlog — “Repo & MVP Kick-off”

| Priority | Ticket                                                                       | Pillar             | Notes                                            |
| -------- | ---------------------------------------------------------------------------- | ------------------ | ------------------------------------------------ |
| P0       | **Set up monorepo (Nx or Turborepo) with TypeScript linting + commit hooks** | Foundation         | Enables clean cross-service sharing.             |
| P0       | **Create `payroll-core` microservice (Go)**                                  | Product Engine     | Holds tax rules, pay-cycle logic.                |
| P0       | **Bootstrap CI/CD on GitHub Actions**                                        | Foundation         | Auto-build, test, deploy to staging & prod.      |
| P1       | **Define Terraform IaC for AWS + RDS**                                       | Foundation         | “Infra as code” baseline; SOC 2 prep.            |
| P1       | **Seed ‘design-system’ repo (Storybook + Tailwind)**                         | UX Differentiation | Single source of truth for UI.                   |
| P1       | **Integrate Plaid & Stripe test sandboxes**                                  | Competitive Edge   | Fast employee bank-account validation & payouts. |
| P2       | **Implement state-tax rule engine (CA, TX, NY, FL, IL)**                     | Compliance         | Key KR for differentiation.                      |
| P2       | **Add Honeycomb or Datadog tracing**                                         | Reliability        | Perf & error monitoring for payroll runs.        |
| P2       | **Draft sample data import CLI**                                             | Onboarding         | Sales demos / pilot customer onboarding.         |
| P3       | **Prototype public marketing site**                                          | Brand              | Hero copy + lead-capture form.                   |
| P3       | **Spike: ACME 401(k) integration feasibility**                               | Future             | Nice-to-have for mid-market.                     |
