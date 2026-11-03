# Security policy

Report vulnerabilities privately through GitHub's
**Security → Report a vulnerability** on the affected repository. If the
repository does not show a reporting form, report through the
[framework's advisory form](https://github.com/Lisa-Harness/lisa/security/advisories/new).

Include the affected version/commit, configuration, prerequisites, impact,
and a minimal reproduction with synthetic data. Do not post exploit details,
credentials, or private conversation data in public issues or pull requests.
No response-time or bounty commitment is currently made.

## Trust and deployment boundaries

- Installed packs and in-process tools execute Python. Treat them as trusted
  code; catalog restrictions are not a process sandbox.
- Model/provider requests can contain session instructions, conversation,
  evidence, and tool results. Apply your provider's data-processing policy.
- Approval policy and containment are distinct. A policy decision does not
  create an OS sandbox, and a missing or degraded sandbox must not be treated
  as contained.

See the [framework security policy](https://github.com/Lisa-Harness/lisa/blob/main/SECURITY.md)
for the full trust and deployment guidance.