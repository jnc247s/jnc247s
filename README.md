
<p align="center">
  <!-- Greeting & Headline -->
  <samp>
    <h1>👋 Hi, I'm Jacob Cohen</h1>
    <h3>Senior at Missouri State University</h3>
    <p>Studying Information Technology/Cybersecurity</p>
  </samp>


<p align="center">
  <h2> Featured Projects</h2>
</p>

### [Cloud Security Control Plane](https://github.com/jnc247s/cloud-security-automation)

[![Status: In Progress](https://img.shields.io/badge/status-in%20progress-d97706)](https://github.com/jnc247s/cloud-security-automation/blob/main/ROADMAP.md)
[![CI](https://github.com/jnc247s/cloud-security-automation/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/jnc247s/cloud-security-automation/actions/workflows/ci.yml)

I'm building an AWS security assessment platform that turns cloud configuration data into repeatable security checks, traceable evidence, and historical findings. The goal is to make each result easy to investigate: what was checked, what evidence supports it, and what each scan observed.

**Project highlights**

- **AWS security controls:** Read-only evidence collection across IAM, EC2/EBS, VPC, S3, and CloudTrail, with 25 core controls available in an opt-in catalog and five controls enabled by default.
- **Explainable assessments:** Deterministic security rules, explicit `INSUFFICIENT_EVIDENCE` results, and versioned NIST CSF 2.0 mappings for technical context.
- **Traceable history:** Immutable resource snapshots, stored assessments, finding history, exceptions, and audit records in PostgreSQL.
- **Secure investigation:** OIDC/JWT authentication, role and capability checks, and a read-only React/TypeScript dashboard for exploring findings and supporting evidence.
- **Engineering validation:** Backend, PostgreSQL integration, frontend, and Chromium/Firefox browser tests, with automated linting and container builds in GitHub Actions.

**Tech stack:**

<p>
  <img src="https://skillicons.dev/icons?i=py" alt="Python" title="Python" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=aws" alt="AWS / boto3" title="AWS / boto3" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=fastapi" alt="FastAPI" title="FastAPI" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" title="PostgreSQL" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=react" alt="React" title="React" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" title="TypeScript" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=docker" alt="Docker" title="Docker" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=githubactions" alt="GitHub Actions" title="GitHub Actions" width="40" height="40" />
</p>

**In progress:** Core assessments and the read-only dashboard are implemented. Current work focuses on completing the human-approved remediation workflow and its browser interface. The remediation worker is disabled by default and tested offline; live remediation and production validation remain ahead.

[**Source & setup**](https://github.com/jnc247s/cloud-security-automation) · [**Architecture**](https://github.com/jnc247s/cloud-security-automation/blob/main/ARCHITECTURE.md) · [**Roadmap**](https://github.com/jnc247s/cloud-security-automation/blob/main/ROADMAP.md)



### [BiscuitBudget](https://biscuitbudget.com)

[![Status: In Development](https://img.shields.io/badge/status-in%20development-d97706)](https://biscuitbudget.com)
![Source: Private](https://img.shields.io/badge/source-private-64748b)

I'm building **BiscuitBudget**, a hockey equipment discovery and price-comparison platform designed to help players find gear that fits their game and their budget. The goal is to bring detailed product specifications, exact-variant comparisons, and retailer offers together in one clean, player-focused experience.

**Project highlights**

- **Exact-variant comparisons:** Equipment matching that accounts for size, handedness, flex, and other product-specific specifications so players can compare the right gear—not just similar product names.
- **Reliable catalog workflows:** Structured product data, validated imports, automated matching, and human review to connect retailer listings to the correct equipment.
- **Player-focused roadmap:** Price tracking, alerts, and personalized gear recommendations based on a player's profile, preferences, and budget.
- **Engineering validation:** Linting, strict TypeScript checks, unit tests, database integration tests, and browser testing to validate functionality before release.

**Tech stack:**

<p>
  <img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" title="Next.js" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" title="TypeScript" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" title="PostgreSQL" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=supabase" alt="Supabase" title="Supabase" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=vercel" alt="Vercel" title="Vercel" width="40" height="40" />
  <img src="https://skillicons.dev/icons?i=cloudflare" alt="Cloudflare" title="Cloudflare" width="40" height="40" />
</p>

**In progress — October 2026:** The core catalog, variant selection, offer matching, and listing-review workflows are implemented and tested locally. Current work focuses on production readiness, final validation, and authorized retailer data access ahead of a private beta. The application is not yet beta-ready, live retailer pricing is not available, and the deployed website does not yet reflect all local work.

**Created and developed by Jacob Cohen.** The application source code remains private; this profile provides a public overview as the project moves toward launch.

[**Website**](https://biscuitbudget.com) · **Public launch: Coming soon**

---



