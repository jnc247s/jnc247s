
<p align="center">
  <!-- Greeting & Headline -->
  <samp>
    <h1>👋 Hi, I'm Jacob Cohen</h1>
    <h3>Senior at Missouri State University🐻</h3>
    <p>Studying Information Technology/Cybersecurity</p>
    <p>I enjoy learning new things about coding and working on new cool projects</p>
  </samp>


<p align="center">
  <h2>🎯 Featured Projects</h2>
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

**Tech stack:** `Python` · `AWS / boto3` · `FastAPI` · `PostgreSQL` · `React / TypeScript` · `Docker` · `GitHub Actions`

**In progress:** Core assessments and the read-only dashboard are implemented. Current work focuses on completing the human-approved remediation workflow and its browser interface. The remediation worker is disabled by default and tested offline; live remediation and production validation remain ahead.

[**Source & setup**](https://github.com/jnc247s/cloud-security-automation) · [**Architecture**](https://github.com/jnc247s/cloud-security-automation/blob/main/ARCHITECTURE.md) · [**Roadmap**](https://github.com/jnc247s/cloud-security-automation/blob/main/ROADMAP.md)


