---
name: sas-create-and-retrieve-job
description: Create a new job and then retrieve its details.
api: openapi/sas-jobs-api-openapi.yml
operations:
- createJob
- getJob
- listJobs
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sas-jobs-api-openapi.yml ; every operationId checked against the contract
---

# sas-create-and-retrieve-job

Create a new job and then retrieve its details.

## Steps

1. 1. Use `createJob` with the request body fields defined in the contract.
2. 2. Use `getJob` with the `id` path parameter returned from `createJob`.
3. 3. Optionally, use `listJobs` to view all jobs.

## Rules

- Auth: Include an OAuth2 bearer token in the `Authorization` header.
- Rate limiting: No rate limit is defined; no special handling on exhaustion.
