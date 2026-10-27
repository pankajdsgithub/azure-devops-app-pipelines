# Azure DevOps App Pipelines

This repository contains application delivery templates for build, test, security scanning, and release automation in Azure-based workloads.

```mermaid
flowchart LR
    A[Code Commit] --> B[Build]
    B --> C[Test]
    C --> D[Security Scan]
    D --> E[Package]
    E --> F[Deploy]
```
