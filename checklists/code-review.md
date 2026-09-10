# Checklist — code review

- [ ] O PR resolve o problema descrito (não só “passa nos testes”)
- [ ] Nomes e abstrações fazem sentido para quem entra amanhã
- [ ] Sem código morto, `console.log` de debug, ou TODOs sem issue
- [ ] Erros tratados; sem engolir excepções
- [ ] Sem secrets, tokens, ou dados sensíveis
- [ ] Performance óbvia (N+1, loops pesados, payloads enormes)
- [ ] Segurança básica (validação de input, authz, SSRF/XSS se aplicável)
- [ ] Testes cobrem o caminho feliz e pelo menos um falhanço
- [ ] Migrações / feature flags pensadas para rollback
