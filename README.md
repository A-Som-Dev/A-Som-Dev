# Artur Sommer

**Freelance Senior Software Engineer**

Java/Spring Boot im Beruf, Python und alles andere daneben. Hab in den letzten Jahren hauptsächlich Telko-Systeme gebaut und Legacy-Plattformen migriert. Privat laufen eigene Services auf meinem Homelab. Code ist privat, aber hier ein Überblick was drauf ist.

## Aktuelles Open-Source-Projekt

**[AInonymity](https://github.com/A-Som-Dev/ainonymous)** · TypeScript · Apr 2026

Lokaler Proxy zwischen IDE und LLM-API. Anonymisiert Quellcode, Secrets, Personennamen und Code-Identifier bevor sie zu Anthropic/OpenAI gehen, mappt Antworten zurück. Damit Konzerne Claude Code, Cursor und Aider nutzen können ohne DSGVO-Konflikte.

3-Layer-Pipeline (Secrets/Identity/Code-Semantik via Tree-sitter AST), Audit-Log mit Hash-Chain, MIT-Lizenz, läuft auf localhost. 501 Tests, ~100ms p50.

## Private Projekte (Code nicht öffentlich)

**Immobilien-Aggregator** · Spring Boot, Python
Scrapt 9 Portale, dedupliziert, bewertet per AI-Scoring. Enrichment über POIs, Heizungstyp, Wasserqualität. Cronjob alle 3h, aktuell 337 Inserate unter Beobachtung.

**Audio & Music Management** · Spring Boot
Eigener Service mit 6 Enrichment-APIs, Player, Multi-User, automatischem Housekeeping. 401 Tests, 56 Module.

**Job-Matching-Plattform** · Spring Boot, Python
Scraping über mehrere Portale mit Anti-Detection, Profil-Matching, Benachrichtigungen per ntfy.

**SpaceDerps** · Java, libGDX
Sci-Fi Strategiespiel inspiriert von einem alten Browserspiel. 22 Game Engines, prozedurale Generierung, 616+ Tests. Langzeitprojekt.

**Homelab** · Docker, K8s, Tailscale
~29 Container auf einem Mini-PC. Pi-hole, Home Assistant, Grafana, Nginx Proxy Manager, CrowdSec, und die ganzen Services oben drauf. Alles mit Monitoring und Disaster Recovery.

## Stack

**Backend:** Java, Kotlin, Spring Boot, Python, FastAPI
**Messaging:** Apache Kafka, Camunda BPM, RabbitMQ
**Infra:** Docker, Kubernetes, Helm, Azure DevOps, CI/CD
**Datenbanken:** PostgreSQL, MariaDB, Oracle, SQLite
**APIs:** REST, OpenAPI, TMF Open APIs (Telko-Standard)
**Security:** Keycloak, OAuth2, Spring Security
**Frontend:** Vue.js, Vaadin, TypeScript, Playwright
**Sonstiges:** Android (Kotlin), PineScript v6, Tree-sitter

## AI & Automation

Nutze KI täglich zum Entwickeln. Eigene Agents, MCP-Server, Prompt Engineering. Kein Hype-Thema für mich, eher Werkzeug wie git oder docker. Setze ich für Scraping, Datenaufbereitung, Code Reviews und Automatisierung ein. AInonymous ist aus dieser Praxis entstanden.

## Beruflich

| Zeitraum | Kunde | Rolle |
|---|---|---|
| 2023 - heute | NetCom BW (EnBW) | Senior Engineer / Technical Lead |
| 2020 - 2023 | Deutsche Telekom AG | Full Stack Developer |
| 2017 - 2020 | Fraunhofer ITWM | Software Entwickler |

Details auf [Freelancermap](https://www.freelancermap.de/profil/artur-sommer) und [LinkedIn](https://www.linkedin.com/in/a-som-dev).
