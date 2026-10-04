<h1 align="center">⚡ VoltiaGrid — Medición Inteligente / Smart Metering</h1>

<p align="center">
  Plataforma de datos para Voltia Energía (1,2M clientes) · Data platform for Voltia Energía (1.2M customers)
</p>

<p align="center">
  <a href="https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-api">API</a> ·
  <a href="https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-data">Data</a> ·
  <a href="https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-analytics">Analytics</a> ·
  <a href="https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-docs">Docs</a>
</p>

---

> **HOW TO INSTALL THIS FILE (org owners only):**
> 1. In the org `VoltiaGrid-Medicion-Inteligente`, create a repo named exactly `.github` (public).
> 2. Inside it create file `profile/README.md` and paste this whole content.
> 3. Pin the 4 repos. This removes the message "You are viewing the README and pinned repositories as a public user..."
>
> **CÓMO INSTALAR (solo owners de la org):**
> 1. En la org crea un repo llamado exactamente `.github` (público).
> 2. Dentro crea `profile/README.md` y pega este contenido.
> 3. Fija (pin) los 4 repos.

## Qué es / What is it

**ES:** Lecturas cada 30 min → limpieza → franjas tarifarias → pérdidas por transformador → eventos de demanda → Power BI + demo AWS. Piloto 5.500 medidores → 200.000 proyectados.

**EN:** 30-min readings → cleaning → time-of-use bands → per-transformer losses → demand-response events → Power BI + AWS demo. Pilot 5,500 meters → 200,000 projected.

## Repos / Repositories

| Repo | Contenido / Content | Owner |
|---|---|---|
| [voltiagrid-api](https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-api) | FastAPI, RabbitMQ, simuladores/simulators, seed F4 | P1 |
| [voltiagrid-data](https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-data) | Spark, Airflow DAGs, reglas/rules RN-01…RN-10 | P2 |
| [voltiagrid-analytics](https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-analytics) | Modelo dimensional/dimensional model, Power BI | P4 |
| [voltiagrid-docs](https://github.com/VoltiaGrid-Medicion-Inteligente/voltiagrid-docs) | Arquitectura/architecture, ADRs, costos/costs, runbook | P4 |

## Empieza aquí / Start here

1. Lee el repo que te toca + su `README` (ES/EN).
2. Lee `docs/CONTRIBUTING.es.md` (ramas `tipo/KAN-XX`, commits `KAN-XX tipo(alcance): ...`, PRs a `dev`).
3. Decisiones globales → `voltiagrid-docs`.

## Equipo / Team

<!-- TODO: names + @github + roles P1-P4 -->
