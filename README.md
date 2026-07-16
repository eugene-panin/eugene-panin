# Eugene Panin

## DevOps / SRE / MLOps

I build the parts of a system that have to keep working after the first deploy:
repeatable infrastructure, safer releases, useful monitoring, and a recovery
path that people can actually follow.

Most of my work sits somewhere between application teams and production:
Terraform, Kubernetes, CI/CD, observability, networking, and the day-to-day
decisions that make a platform easier to run.

## What I work on

- **Platform engineering** — infrastructure as code, Kubernetes environments,
  delivery automation, networking, and developer-friendly deployment paths.
- **Reliability engineering** — monitoring that leads to action, release safety,
  incident readiness, backups, access, and operational ownership.
- **MLOps and AI runtime** — where models run, what data can cross a boundary,
  how inference is observed, and how a team can change or stop it safely.

I care less about whether a system uses a fashionable stack than whether the
people responsible for it can understand, change, and recover it.

## Work you can inspect

- [**Kind Lab**](https://github.com/eugene-panin/kind-lab) — a local Kubernetes
  environment with automated DNS and TLS.
- [**Terraform HCloud K3s Cluster**](https://github.com/eugene-panin/terraform-hcloud-k3s-cluster)
  — Terraform for a K3s cluster on Hetzner Cloud.
- [**Terraform HCloud Network**](https://github.com/eugene-panin/terraform-hcloud-network)
  and [**Terraform HCloud Instance**](https://github.com/eugene-panin/terraform-hcloud-instance)
  — reusable infrastructure building blocks.
- [**Grafana Alloy Ansible Role**](https://github.com/eugene-panin/ansible-role-grafana-alloy)
  — deployment automation for an observability component.
- [**Deployer image**](https://github.com/eugene-panin/deployer) — a CI/CD image
  with Terraform and related cloud tooling.

## Current direction

I am putting more public work into running AI systems in production: placement
of inference, access and data boundaries, observability, cost, and controlled
changes. The useful question is not "can we call a model?" but "can a team run
this reliably after it reaches production?"

## Applied work

One applied systems vertical is [Beavers Solutions](https://github.com/beavers-solutions),
where I work on technical delivery for Odoo. The Odoo services and their public
reference material live there; this profile remains about the wider platform and
reliability work.
