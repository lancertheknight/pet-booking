# Pet Booking API
Learning project following TestDriven.io "Scalable FastAPI Applications on AWS" (v3.0.0),
adapted from conference-talk booking to pet-sitting bookings, and from GitLab to GitHub.

## Stack (use these, not older alternatives)
Python 3.14, FastAPI, uv (not Poetry/pip), pytest, Ruff (not Black/Flake8/isort),
Docker, GitHub Actions for CI/CD, Terraform, AWS ECS Fargate, ECR,
RDS Postgres 16, SQLAlchemy 2.0 + psycopg3, Alembic.

## Repo layout
services/  lib/  infrastructure/  ci_cd/  tools/

## How to work with me
- I'm learning: briefly explain what you change and why.
- Small changes; write or update tests first.
- Never run `terraform apply` or `terraform destroy` yourself. Show me the command; I run it after reviewing the plan.
- Never commit secrets (.env, AWS keys, *.tfstate).