# Copilot Instructions for CI_TestRepo3

## Repository Overview

**CI_TestRepo3** is a minimal test repository owned by `Fabletest4`. It is used for testing GitHub Actions, CI/CD workflows, and GitHub automation processes (such as Copilot coding agent onboarding). The repository currently contains only a `README.md` with a single title line.

## Repository Structure

```
CI_TestRepo3/
├── .github/
│   └── copilot-instructions.md   # This file
└── README.md                     # Project title only
```

## Key Facts

- **Language:** None yet — no source code exists in this repository.
- **Build system:** None configured.
- **Tests:** None configured.
- **Linting:** None configured.
- **CI/CD:** No GitHub Actions workflows exist yet.

## Working in This Repository

Since this is a bare-bones test/CI repository, when adding new features or code:

1. **Choose appropriate tooling** based on what is being added (e.g., if adding a Python project, create `requirements.txt` and follow Python conventions; if adding a Node.js project, create `package.json`).
2. **Add a `.gitignore`** appropriate for any languages or frameworks introduced.
3. **Update `README.md`** to reflect the actual purpose and usage of any code added.
4. **Add GitHub Actions workflows** under `.github/workflows/` if CI/CD is needed.

## Conventions

- Branch naming: use `copilot/<short-description>` for agent-generated branches.
- There are no enforced code style rules yet; follow language-standard best practices for any code added.
- Keep changes minimal and purposeful — this is a test repository.
