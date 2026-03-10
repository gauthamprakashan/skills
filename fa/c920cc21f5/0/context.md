# Session Context

## User Prompts

### Prompt 1

Implement the following plan:

# Security Fixes for aws-bedrock-evals Skill

## Context

Security audits from Gen Agent Trust Hub and Snyk identified 5 vulnerabilities in the `aws-bedrock-evals` skill (risk level: HIGH). The skill guides an AI agent through building Bedrock evaluation pipelines but lacks input sanitization, uses overly broad IAM policies, generates unvalidated shell commands, has no auditable code, and loads S3 datasets without integrity verification.

## Vulnerabilities Address...

