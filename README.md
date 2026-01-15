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
```

**Containers running:**

![Docker Compose Status](https://github.com/EdwinBAI/glpi-desktop-support-lab/blob/main/01-docker-compose-ps.png)

## Screenshots

**GLPI Login Page:**

![GLPI Login](https://github.com/EdwinBAI/glpi-desktop-support-lab/blob/main/02-glpi-login-page.png)

**GLPI Dashboard:**

![GLPI Dashboard](https://github.com/EdwinBAI/glpi-desktop-support-lab/blob/main/03-glpi-dashboard.png)
