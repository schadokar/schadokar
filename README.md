### Hi, I'm Shubham 👋

I've been writing Go for 7+ years. Most of that time has gone into backend platforms, the kind where one bad design choice ships a 2am page to someone six months later. Currently a Senior Software Engineer at Infoblox; 10 years in the industry overall.

A few things I've worked on that I'm proud of:

- At Infoblox, took a Cloud Data Connector platform that had grown into 20 microservices and collapsed it down to 5. Mostly by deleting code and arguing about ownership.
- Caught a Kafka topology that would have exploded into ~1M topics at 10K-customer scale. Redesigned it to ~10K topics with per-customer isolation and a zero-downtime migration. Topic-explosion incidents are not fun.
- Designed the billing engine at Kaleyra. About a billion transactions a day at 10K RPS, 60% faster and 30% cheaper than what it replaced.
- Rewrote a flaky Node chat platform from scratch in Go and moved SQL to MongoDB so the schema would stop fighting us.
- Owned a platform-wide SSO gateway (Keycloak) where any failure meant the whole company was down. It didn't fail.
- Killed a recurring MongoDB file-descriptor outage (2-3/month at peak) with a tier-based collection model across ~10 services and 100K+ collections.

### What I'm into right now

- **Infoblox CDC**: Go services on Kubernetes, Kafka pipelines, Postgres, observability via Grafana.
- [**Munshiji**](https://munshiji.xyz): [Under Development] an open-source, self-hosted personal finance dashboard for India with proper support for EPF, NPS, PPF, SSY, and 13+ Indian account types. Go 1.24, Next.js, SQLite/Postgres, Docker. I wanted one and there wasn't a good one.
- Internal LLM agents for the boring stuff: PR review, deployment PRs, sprint retros.
- Writing Go and distributed-systems posts on [schadokar.dev](https://schadokar.dev).
- Talks: [DockerCon 2022](https://youtu.be/HEjGn3CQ1Ms), London Gophers, Pune Gophers.
- Wrote an eBook a while back: [*Playtime with Hyperledger Composer*](https://schadokar.github.io/playtime-with-hyperledger-composer/).

### Stack

Mostly Go these days. gRPC, Kafka, Kubernetes, Postgres. Also MongoDB, Redis, RabbitMQ, Keycloak, Docker, AWS, GCP, Grafana. When I touch frontends it's Next.js or React with TypeScript.

### Stuff I like thinking about

How to simplify systems that grew too complex. When to rewrite vs refactor. Multi-tenancy and isolation. Kafka topology under customer growth. Zero-downtime migrations. Making observability good enough that someone wakes up before a customer does.


More at [schadokar.dev](https://schadokar.dev).

### Connect

[<img align="left" alt="schadokar.dev" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]
[<img align="left" alt="schadokar1 | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="schadokar | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="schadokar | Medium" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/medium.svg" />][medium]

<br />

[website]: https://schadokar.dev
[twitter]: https://twitter.com/schadokar1
[linkedin]: https://linkedin.com/in/schadokar
[medium]: https://medium.com/@schadokar
