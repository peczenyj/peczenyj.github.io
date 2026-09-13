---
title: "CV"
type: page
---

**Software Architect · Go & Distributed Systems · 20+ Years Experience** — Paris, France

Download: [English PDF](/cv-en.pdf) · [French PDF](/cv-fr.pdf)

I build and run event-driven, high-volume data platforms in Go, and I carry the pager for what I design. My speciality is modernising systems under live traffic — taking legacy services off the critical path and rebuilding them in Go on hybrid multicloud Kubernetes while holding low-millisecond p99. I fix the upstream libraries production depends on rather than working around them.

## Technical Skills

- **Languages** — Go, Perl, Python, TypeScript / JavaScript, Ruby, Lua, C
- **Infrastructure** — Kubernetes (GKE, Yandex Cloud, on-premise Proxmox), Docker, Helm, Terraform, GitOps (Flux, Argo CD), Grafana, CI/CD
- **Data & Messaging** — Kafka, Redpanda Connect / Benthos, RabbitMQ, AWS (S3, SQS), Couchbase, MySQL, Redis, Elasticsearch, Snowflake
- **Practices** — Distributed systems design, stream processing, observability, 24/7 on-call & incident response, Scrum, AI-assisted development (Claude Code, Gemini, Spec Kit)

## Experience

### Software Architect — Weborama
*Feb 2019 – Present · Paris*

- Lead the architecture and hands-on development of the migration of Weborama's collect services from Perl to Go on fasthttp — the highest-traffic path, sustaining tens of thousands of requests per second and millions of events per day at low-millisecond p99.
- Drive the adoption of AI-assisted development at Weborama (Claude Code, Gemini, Spec Kit), defining the practices the engineering team works with today.
- Own design decisions end to end and implement them personally, working as an individual contributor or leading teams of up to five engineers.
- Operate over 90 Go services across hybrid Kubernetes — on-premise datacenters on Proxmox, GKE, and Yandex Cloud — deployed by GitOps with Flux and Argo CD, on Docker, Helm and Terraform.
- Share the 24/7 production on-call rotation for the platform — incident response, root-cause analysis and postmortems, plus the Grafana dashboards and alerting design that keep the pager meaningful.
- Design event-driven, high-volume data processing across several backend systems on Kafka and Redpanda Connect, backed by Couchbase, MySQL, Redis, RabbitMQ and AWS S3/SQS.
- Build the internal gRPC APIs (geolocation, ID sync) and the Weborama Contextual API, which derives audience profiles from page URLs.
- Architect the privacy layer: IAB TCF v2.3 consent handling including disclosed vendors, built in Go on prebid/go-gdpr alongside custom decoding.
- Own the client-side JavaScript: the browser collect tags deployed across client sites, and the Weborama Real-Time Data module contributed upstream to Prebid.js.

### Backend / Software Engineer — Weborama
*Apr 2013 – Feb 2019 · Paris*

- Rebuilt the collect layer from Perl to Go and moved it onto Kubernetes, starting the migration later directed as architect.
- Built real-time bidding integrations with Google Audience Manager, Xandr, Yahoo, Criteo and The Trade Desk among 10+ ad-tech partners — over SOAP/REST, Protocol Buffers, cookie-matching pixels and FTP feeds for DMP and DCO.
- Built Weborama's first queue-based service on the existing Redis deployment using rpush/lpop, adding no new infrastructure — the company's first move to asynchronous processing, later carried onto RabbitMQ.
- Cut latency across the Big Data infrastructure with Riak, Redis, Lua and Bloom filters; added cardinality monitoring using Elasticsearch, Kibana and HyperLogLog.
- Delivered GDPR support across backend and frontend, and built the Weborama CrossDevice identity graph.

## Open Source

**174 merged pull requests to projects maintained by others.**

- **Redpanda Connect** — Sustained upstream maintenance across three areas: new and extended connectors (Elasticsearch v9, SQLite driver, Couchbase scopes, kafka_franz topic control, cache components); remediation of roughly nine Go security advisories; and codebase-wide quality work including linter enablement and the mapstructure migration.
- **Go ecosystem** — valyala/fasthttp — the HTTP engine behind Weborama's collect path — plus google/go-cloud, redis/go-redis, gofiber/fiber, twmb/franz-go, grpc-ecosystem/go-grpc-middleware, testcontainers-go, rabbitmq/amqp091-go, hamba/avro, go-playground/validator, googleapis/google-cloud-go.
- **Own tools** — structalign (struct field-alignment savings as a diff) and xpool (type-safe generic object pool), both accepted into awesome-go; go-claimcheck (claim-check pattern over blob storage and Pub/Sub); runtimevar-consul (Go CDK driver for Consul KV).
- **Perl / CPAN** — MooX::Role::Parameterized, Riak::Light (a fast, lightweight Riak client), GDPR-IAB-TCFv2 consent parsers in Perl and Lua. Stack Overflow: top 5% in bash and perl.

## Earlier Experience

### Adobe Flash Plugins Developer — Cognitive Match
*2012 – 2013 · Palo Alto, CA*

Flash plugins built with Adobe CS Extension Builder to enable Dynamic Creative Optimization (DCO); J2EE, Hibernate and Jersey services.

### Senior Software Engineer — Globo.com
*2008 – 2012 · Rio de Janeiro*

Video production and delivery platform for Brazil's largest media group — live streaming for four editions of Big Brother Brasil and the 2010 FIFA World Cup, peaking at 300k simultaneous viewers and over 5 PB of video served from an in-house CDN across two datacenters; the HTML5 iPad/iPhone player; and a redesign of the live and on-demand delivery architecture. Delivered with Scrum, TDD, BDD and continuous integration. FFmpeg, Wowza, Flash Media Server, nginx, Python, Ruby on Rails, MongoDB.

### Software Development Engineer in Test — Hewlett-Packard
*2004 – 2008 · Porto Alegre*

Automated functional, performance and regression testing for LaserJet embedded firmware in Perl, Java and C#; embedded Java platform (ChaiVM), SOAP/ORB services and the device web server, including IPv6 support and digital signing.

### QA Analyst — CWI Software
*2003 – 2004 · São Leopoldo*

Manual testing for logistics, financial, CMS, CRM and ERP products, plus a J2ME application for PDA devices (ASP, J2EE).

## Education

- **Universidade Gama Filho** (2008 – 2010) — BTech, Information Technology Management
- **Federal University of Rio Grande do Sul (UFRGS)** (1998 – 2006) — Physics coursework and three years of undergraduate research in Monte Carlo simulation of ferromagnetic systems (Ising, Potts, spin glasses) in ANSI C, on CNPq and FAPERGS research scholarships

**Languages:** Portuguese (native) · English (professional) · French (limited working)

[GitHub](https://github.com/peczenyj) · [LinkedIn](https://linkedin.com/in/tiagopeczenyj) · tiago.peczenyj+cv@gmail.com
