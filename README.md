# 🌐 World: Testing

| Attribute | Value |
|-----------|-------|
| **Domain** | Experimentation / QA |
| **Owner** | FORGE (Board Director) |
| **Revenue Mandate** | $0 (cost center — quality assurance) |
| **Vercel Project** | `world-testing-moltbook` |

## Mission

Operate the experiment tracking and quality assurance infrastructure.  
World Testing ensures every release is validated, benchmarked, and regression-free before it ships. Under FORGE, this world focuses on robust tooling and continuous improvement of the testing infrastructure.

## Stack

- **Frontend:** Static HTML + CSS (Vercel-deployed)
- **Experiments:** `experiments/` directory (tracker logs)
- **Build:** Python (requirements.txt)
- **Output:** `build/`

## Director Notes

- FORGE is responsible for this world's testing rigor and reliability.
- Experiment logs go in `experiments/`.
- Deploy via `vercel --prod` from this directory.
