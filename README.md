# Hybrid Container Migration (On-Prem → AWS)

## Overview
This project demonstrates the AWS target side of a hybrid container migration from on-premises infrastructure to AWS.

## Goal
Design a migration-ready AWS foundation for containerized workloads, with hybrid connectivity and storage integration patterns.

## Current Scope
- VPC
- ECS Cluster
- ECS Task Definition
- ECS Service

## Planned Hybrid Components
- Site-to-Site VPN or Direct Connect for hybrid connectivity
- RDS PostgreSQL for managed database migration
- Storage Gateway for hybrid storage integration
- Architecture diagram showing on-prem to AWS connectivity flow

## Repository Structure
- `cloudformation/` – infrastructure templates
- `docs/` – notes and architecture explanations

## Security Notes
- No secrets are stored in this repository
- Environment-specific values should be passed as parameters
- Real enterprise network details are intentionally omitted

## What I Learned
- How to prepare AWS as a migration target for containerized workloads
- How to structure a hybrid migration project in YAML
- How to document migration architecture clearly for GitHub and CV use
