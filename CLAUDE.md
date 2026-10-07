# OpsAnfaz Platform — Claude Code Context

## What this project is

OpsAnfaz is a personal DevOps portfolio project built as a fictional SaaS company.
The goal is to build a real enterprise-grade cloud platform on AWS while preparing
for certifications (Terraform Associate → AWS Developer → AWS SA → CKA).

Everything here is built as if it were a real company: professional README, conventional
commits, structured phases, and a live portfolio web at
[platform.angelprojects7.workers.dev](https://platform.angelprojects7.workers.dev).

**Owner:** Angel Fajardo Zaplana — Platform Engineer @ Kongsberg, based in Elche, Spain.

---

## Current phase

- [x] Phase 1 — Foundation (repo structure, docs, branding)
- [x] Phase 2 — Portfolio web (HTML + Tailwind CDN, deployed on Cloudflare Workers)
- [ ] Phase 3 — Docker (multi-stage build, Nginx, healthchecks) ← **next**
- [ ] Phase 4 — AWS foundations with Terraform (VPC, IAM, ECR)
- [ ] Phase 5 — EKS cluster and Kubernetes manifests
- [ ] Phase 6 — GitHub Actions CI/CD pipeline
- [ ] Phase 7 — ArgoCD GitOps
- [ ] Phase 8 — Observability (Prometheus, Grafana, CloudWatch)
- [ ] Phase 9 — Security hardening (RBAC, Network Policies, Secrets)

---

## Repository structure

```
platform/
├── apps/
│   └── web/                  # Portfolio web
│       ├── index.html        # Single-file app (Tailwind CDN + Google Fonts)
│       ├── css/styles.css
│       └── js/main.js
├── infra/                    # Terraform modules (Phase 4)
├── k8s/                      # Kubernetes manifests (Phase 5)
├── .github/
│   └── workflows/            # GitHub Actions (Phase 6)
├── docs/
│   └── architecture.md
├── CLAUDE.md
├── README.md
└── CHANGELOG.md
```

---

## Stack

| Layer | Technology |
|---|---|
| Cloud | AWS |
| IaC | Terraform |
| Containers | Docker |
| Orchestration | Amazon EKS |
| GitOps | ArgoCD |
| CI/CD | GitHub Actions |
| Observability | Prometheus · Grafana · CloudWatch |
| Security | IAM · RBAC · Network Policies |
| Static hosting (temporary) | Cloudflare Workers |

---

## Web design system

- **Background:** `#050d1a` con radial-gradients
- **Accent:** `#0FF4C6`
- **Fonts:** Barlow Condensed 800 (hero), Inter (body), JetBrains Mono (mono)
- **Cards:** glass-effect con `backdrop-filter: blur(4px)`
- Todo el frontend lo escribe Claude — Angel no escribe HTML/CSS manualmente

---

## Commit conventions

Conventional Commits siempre:

```
feat(scope): descripción
fix(scope): descripción
docs(scope): descripción
infra(scope): descripción
```

Actualizar `CHANGELOG.md` en cada feature o fix visible.

---

## Certifications roadmap

| Priority | Certification | Status |
|---|---|---|
| ⭐⭐⭐⭐⭐ | Terraform Associate | 🟡 Active |
| ⭐⭐⭐⭐ | AWS Developer Associate | Q1 2027 |
| ⭐⭐⭐⭐ | AWS Solutions Architect Associate | Q2 2027 |
| ⭐⭐⭐ | CKA | Q3 2027 |

---

## Rules for Claude Code

- Todo el repo en **inglés**
- Todo el frontend (HTML/CSS/JS) lo escribe Claude — nunca pedir a Angel que lo escriba manualmente
- Al editar `index.html`, dar siempre el archivo completo
- Antes de cada nueva fase, verificar que la anterior funciona
- Recordar hacer commit después de cada cambio relevante
- Actuar como Tech Lead + Senior DevOps Mentor — ser exigente, hacer pensar, no dar todo de golpe