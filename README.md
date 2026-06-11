# JOX IT

**Process automation for complex IT environments.**

JOX is a Java-based job scheduler and workflow engine, in productive use
since 2001 — originally built for billing automation at Talkline GmbH,
today running at [freenet DLS GmbH](https://www.freenet.ag/) and
in further projects across industries.

---

## What JOX does

- **One configuration, every environment** — define a process once,
  run it unchanged across DEV, UAT and production. JOX manages
  servers, databases and variables per environment; the process
  definition stays identical.
- **Workflows** — dependencies, parallel execution, replay of
  sub-chains without re-running the whole pipeline.
- **Database-agnostic** — proven connectors for Oracle, Snowflake,
  PostgreSQL, DB2, Informix and others. JOX talks to the database
  directly: no client tools installed on application servers.
- **Fully traceable** — every run captured with status, timestamps
  and complete output, down to environment variables for OS jobs.
  Historical data automatically archived after a configured
  retention period.

## Architecture in one sentence

A central repository and distributed server processes that
coordinate **through the database** — control, status and results
flow transactionally through the repository. One source of truth,
many autonomous execution nodes. No message broker, no cluster
manager, no service mesh.

## In production at

- **freenet DLS GmbH** — since 2001, originally Talkline GmbH
- Read the [customer story](https://jox-it.de/en/customer-story)

## Learn more

- Website: <https://jox-it.de/en/>
- Capabilities and fit: <https://jox-it.de/en/fit>
- Transparency and traceability: <https://jox-it.de/en/transparency>

## Contact

**JOX IT · Alexander Odesser**
Hamburg, Germany
[info@jox-it.de](mailto:info@jox-it.de)
