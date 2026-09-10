<p align="center">
  <img src="docs/banner.svg" alt="CODEOWNERS Patterns banner" width="100%" />
</p>

<h1 align="center">codeowners-patterns</h1>

<p align="center">
  <strong>EN</strong> Team-based CODEOWNERS patterns & examples<br/>
  <strong>PT</strong> Padrões CODEOWNERS por equipa e exemplos
</p>

<p align="center">
  <a href="https://github.com/manansbdb/codeowners-patterns/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-CODEOWNERS-24292f?style=for-the-badge" alt="CODEOWNERS" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Patterns and an example **CODEOWNERS** file for path-based review ownership. | Padrões e um exemplo **CODEOWNERS** para ownership de review por path. |
| Copy to `.github/CODEOWNERS` and replace `@org/team` handles. | Copia para `.github/CODEOWNERS` e substitui os `@org/team`. |

```mermaid
flowchart LR
  A["📂 Path change"] --> B["📜 CODEOWNERS"]
  B --> C["👥 Required reviewers"]
  C --> D["✅ Approved merge"]
  style A fill:#0969da,stroke:#0550ae,color:#fff
  style B fill:#24292f,stroke:#000,color:#fff
  style C fill:#cf222e,stroke:#a40e26,color:#fff
  style D fill:#1a7f37,stroke:#116329,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/codeowners-patterns.git
cd codeowners-patterns
```

### 2) Apply / Aplica

```bash
mkdir -p /path/to/your-project/.github
cp examples/CODEOWNERS /path/to/your-project/.github/CODEOWNERS
cp patterns.md /path/to/your-project/docs/codeowners-patterns.md
# edit @handles to match your org/teams
```

### Requirements / Requisitos

- `git`
- GitHub (or compatible) CODEOWNERS support

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/codeowners-patterns.git
mkdir -p .github
cp codeowners-patterns/examples/CODEOWNERS .github/CODEOWNERS
# replace placeholder teams with yours
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `examples/CODEOWNERS` | Example ownership file |
| `patterns.md` | Pattern guidance |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
codeowners-patterns/
├── docs/banner.svg
├── examples/CODEOWNERS
├── patterns.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
