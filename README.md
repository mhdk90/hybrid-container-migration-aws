# Hybrid Container Migration (On-Prem → AWS)

## Overview
This project demonstrates the AWS target side of a hybrid container migration from on-premises infrastructure to AWS.

## Goal
Design a migration-ready AWS foundation for containerized workloads, with hybrid connectivity and storage integration patterns.

## Current Scope
- VPC
- Public subnets
- ECS Cluster
- ECS Task Definition
- ECS Service

## Planned Hybrid Components
- Site-to-Site VPN or Direct Connect
- RDS PostgreSQL
- Storage Gateway
- Architecture and migration documentation

## Repository Structure
- `cloudformation/` – CloudFormation templates
- `docs/` – architecture and migration notes

## Deployment Notes
This repo currently focuses on the AWS-side landing zone for migrated containers. Hybrid network details are documented separately.

## Security Notes
- No secrets are stored in this repository
- Environment-specific values should be passed as parameters
- Real enterprise network details are intentionally omitted

## Roadmap
- Add working ECS foundation template
- Add architecture diagram
- Add migration strategy
- Add CI workflow

## What I Learned
- How to prepare AWS as a migration target for containerized workloads
- How to structure a hybrid migration repo for GitHub
- How to document migration design clearly for recruiters
