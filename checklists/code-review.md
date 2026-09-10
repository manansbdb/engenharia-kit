# Checklist — code review / revisão de código

- [ ] PR solves the stated problem (not just “tests pass”) / O PR resolve o problema descrito
- [ ] Names and abstractions make sense tomorrow / Nomes e abstrações fazem sentido amanhã
- [ ] No dead code, debug logs, or TODOs without an issue
- [ ] Errors handled; no swallowed exceptions / Erros tratados
- [ ] No secrets, tokens, or sensitive data / Sem secrets
- [ ] Obvious performance issues checked (N+1, heavy loops)
- [ ] Basic security (input validation, authz, XSS/SSRF if applicable)
- [ ] Tests cover happy path + at least one failure
- [ ] Migrations / feature flags thought through for rollback
