\# CI/CD Pipeline Threat Model



\## Identified Risks



\### Secret Exposure

\- Secrets echoed in logs

\- Hardcoded credentials in pipeline files

\- Secrets accessible to all jobs



\### Over-Privileged Access

\- Broad repository permissions

\- Tokens with write/admin access

\- No separation between build and publish stages



\### Lack of Validation

\- Pipelines execute without security checks

\- No enforcement of least-privilege principles



\## Impact

\- Credential leakage

\- Unauthorized artifact publication

\- Supply-chain compromise



