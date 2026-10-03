---
name: hcl-ast-audit
description: Specialized capability for Static AST parser for HashiCorp HCL Terraform configurations that blocks IAM privilege escalations and unencrypted storage before commit.
license: MIT
allowed-tools: ""
metadata:
  author: "Rucha Salpure"
  version: "1.0.0"
  category: devtools
---

# Terraform Posture Sentinel Agent — Hcl Ast Audit Skill

## Purpose
The `hcl-ast-audit` capability provides high-assurance execution routines for `Terraform Posture Sentinel Agent`.

## Execution Workflow
1. Validate input parameters against typed schemas and invariant constraints.
2. Ingest contextual metrics and establish a deterministic baseline.
3. Formulate candidate recommendations with explicit confidence intervals.
4. Submit draft plans to the independent checker agent for verification.

## Boundary Conditions
- **Input validation:** Reject non-conforming or malformed payloads before evaluation.
- **Fail-safe:** Escalate immediately if telemetry indicators exhibit critical anomalies.
