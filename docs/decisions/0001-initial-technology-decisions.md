# 0001: Initial technology decisions

Status: Accepted (revisit at the end of Phase 1 if needed)

- **Backend:** ASP.NET Core on .NET (current LTS) with EF Core.
- **Database:** SQL Server.
- **Frontend:** React + TypeScript with Vite.
- **Tenancy:** shared database and schema, with a TenantId on every tenant-owned table.
- **Hosting:** Azure.
- **Repository:** one monorepo for backend, frontend, docs and infrastructure.
- **Branching:** `main` for releases, `develop` for integration, short-lived feature branches.