# runner

Orquestador central público de CI/CD. Recibe `repository_dispatch` desde cualquier repo privado de cualquier organización, descarga `templates_cicd`/`templates_iac` y ejecuta build + deploy siempre en este repo (público = $0 minutos de Actions).

Ver el patrón completo, el contrato del payload y el checklist de onboarding en [`CICD-ARCHITECTURE.md`](./CICD-ARCHITECTURE.md).

Mantenido por el agente `CICD` (`.claude/agents/devops-cicd.md`).
