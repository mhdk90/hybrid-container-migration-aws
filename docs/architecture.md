# Architecture

```mermaid
flowchart LR
  OP[On-Prem Containers] --> NET[VPN / Direct Connect]
  NET --> ECS[Amazon ECS / Fargate]
  ECS --> RDS[(RDS PostgreSQL)]
  OP --> SGW[Storage Gateway]
