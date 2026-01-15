# GLPI Desktop Support Lab

I deployed GLPI + MariaDB using Docker Compose to practice ITSM workflows for Desktop Support roles.

## What this demonstrates
- Ticket hygiene: intake → triage → resolution → verification → closure
- Clear documentation: symptoms, scope, steps taken, outcome, escalation criteria
- Practical desktop support thinking (Outlook, printers, login/MFA, Windows, network)

## Environment
- GLPI (Docker container)
- MariaDB (Docker container)
- Local access: http://localhost:8080

## Quick start
1) Install Docker Desktop
2) From the repo root:
```bash
docker compose up -d
docker compose ps
