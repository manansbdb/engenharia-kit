<p align="center">
  <img src="docs/banner.png" alt="Engineering Kit banner" width="100%" />
</p>

<h1 align="center">engenharia-kit</h1>

<p align="center">
  <strong>EN</strong> PR/issue templates, CODEOWNERS &amp; engineering checklists — copy into any repo<br/>
  <strong>PT</strong> Templates de PR/issue, CODEOWNERS e checklists — copia para qualquer repositório
</p>

<p align="center">
  <a href="https://github.com/manansbdb/engenharia-kit/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/type-kit-a855f7?style=for-the-badge" alt="kit" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A **drop-in engineering kit** so teams start with solid PR/issue hygiene and review/release rituals. | Um **kit de engenharia pronto a copiar** para PR/issues e rituais de review/release. |
| No runtime dependencies — only Markdown files. | Sem dependências de runtime — só ficheiros Markdown. |

```mermaid
flowchart LR
  A["📋 Checklists"] --> B["🔀 Pull Request"]
  B --> C["🛡️ CODEOWNERS"]
  C --> D["🚀 Release"]
  style A fill:#f97316,stroke:#c2410c,color:#fff
  style B fill:#ef4444,stroke:#b91c1c,color:#fff
  style C fill:#3b82f6,stroke:#1d4ed8,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone this kit / Clona este kit

```bash
git clone https://github.com/manansbdb/engenharia-kit.git
cd engenharia-kit
```

### 2) Copy into your project / Copia para o teu projeto

```bash
# from your application repository root:
cp -R /path/to/engenharia-kit/.github .
cp -R /path/to/engenharia-kit/checklists ./docs/checklists

# optional CODEOWNERS
cp .github/CODEOWNERS.example .github/CODEOWNERS
# edit handles / edita os @usernames
```

### 3) Commit / Faz commit

```bash
git add .github docs/checklists
git commit -m "chore: add engineering kit templates"
git push
```

### Requirements / Requisitos

- `git`
- Any GitHub (or compatible) repository
- No Node/Python install required

---

## What's included / O que inclui

| Path | Purpose / Função |
|------|------------------|
| `.github/PULL_REQUEST_TEMPLATE.md` | PR template EN+PT |
| `.github/ISSUE_TEMPLATE/*` | Bug + feature templates |
| `.github/CODEOWNERS.example` | Ownership starter |
| `checklists/code-review.md` | Review checklist |
| `checklists/release.md` | Release checklist |
| `checklists/incidente.md` | Incident checklist |

---

## Support / Apoio

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
