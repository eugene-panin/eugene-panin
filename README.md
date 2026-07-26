# Eugene Panin

## Senior DevOps / SRE / Platform Engineer

I automate infrastructure and build the operational paths around it: repeatable
environments, safer releases, actionable monitoring, incident diagnosis, and
verified recovery.

My core tools are Terraform/OpenTofu, Kubernetes, AWS, Hetzner Cloud, CI/CD,
Prometheus, Grafana, Loki, Linux, networking, Python, and Bash.

## Runnable proof

| Repository | What it demonstrates | Automated verification |
| --- | --- | --- |
| [**Kubernetes Troubleshooting Lab**](https://github.com/eugene-panin/kubernetes-troubleshooting-lab) | Four deterministic failures covering Services, EndpointSlices, readiness probes, ports, and CrashLoop diagnosis | A real Kind cluster, failure assertions, recovery, and HTTP smoke tests |
| [**AWS EKS Environment**](https://github.com/eugene-panin/aws-eks-environment) | A three-AZ VPC, private EKS, IAM access, Pod Identity, encrypted PostgreSQL and S3, plus explicit cost/HA trade-offs | Terraform validation and four mocked positive/negative guardrail cases |
| [**Observability Incident Lab**](https://github.com/eugene-panin/observability-incident-lab) | Prometheus SLO alerts, Grafana, Loki, Alloy, structured logs, runbooks, and a controlled checkout failure | Break → alert and log correlation → recovery → alert clearance |

Each repository is deliberately small enough to review, runs from documented
commands, and distinguishes automated proof from production claims.

## How I work

- automate repeatable infrastructure and delivery paths;
- make security, availability, cost, and ownership trade-offs explicit;
- test failure paths and recovery, not only the happy path;
- leave diagnostics, runbooks, and rollback boundaries for the next operator.

I am open to remote Senior DevOps, SRE, and Platform Engineering roles on a B2B
basis.

## Applied work

One applied systems vertical is [Beavers Solutions](https://github.com/beavers-solutions),
where I work on technical delivery for Odoo. The Odoo services and their public
reference material live there; this profile remains about the wider platform and
reliability work.
