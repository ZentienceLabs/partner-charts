## AlchemiStudio Platform

AlchemiStudio is a sovereign AI control plane that runs entirely inside your own
Kubernetes cluster. It bundles an AI copilot, an agent/console governance layer
(Cockpit), a compute sandbox tier (AIOS), and workflow automation — with Keycloak
single sign-on, per-account seats and audit logging, all served through a single
gateway. Everything the platform needs (PostgreSQL/pgvector, Redis, object
storage, and observability) is deployed in-cluster by default, so no external
cloud services are required to evaluate it.

Provide your base domain and an admin email at install; the platform derives its
web, auth, and console hostnames from that domain and seeds your first admin
account. For production deployments (your own registry, database, object store,
and a full license) contact support@alchemistudio.ai.
