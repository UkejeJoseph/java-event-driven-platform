# Portfolio Overview

Production-oriented Java 21 / Spring Boot backend for a multi-tenant mobility
marketplace. The system covers tenant provisioning, access control, pricing,
dispatch, ride lifecycle management, provider-neutral payments, immutable
ledger entries, settlements, notifications, support workflows, and signed
webhooks.

Key architecture: PostgreSQL/PostGIS is authoritative; Redis holds ephemeral
live-location and dispatch indexes; a transactional inbox/outbox protects
external side effects; Flyway manages schema evolution; and OIDC secures
tenant provisioning and operator access.

See [PROVENANCE.md](PROVENANCE.md) for upstream source and licensing details.
