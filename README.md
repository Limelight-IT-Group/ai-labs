# AI Labs

## Overview
Experimental AI tooling, prompt engineering, agent workflows and LLM integrations for Limelight IT Group.

## Purpose
A sandboxed research and development environment for AI-powered tooling. Covers prompt engineering, Claude API integrations, AI-assisted automation and prototype SaaS features — all tested here before graduating to production repos.

## Structure
```
ai-labs/
├── prompts/       # Prompt libraries and engineering experiments
├── agents/        # Agentic workflow prototypes
├── notebooks/     # Jupyter notebooks for research and testing
├── integrations/  # API integrations (Claude, OpenAI, etc.)
├── .gitignore
└── README.md
```

## Usage
Experiments live in `notebooks/` and `agents/`. Stable, reusable components graduate to the `automation` or `internal-tools` repos.
```bash
cd notebooks
jupyter notebook
```

## Standards
- Label all experiments clearly with status: `[PROTOTYPE]` `[STABLE]` `[ARCHIVED]`
- No production credentials in notebooks — use environment variables
- Document model versions and prompt versions used in each experiment
- Commit messages follow Conventional Commits

## License
MIT License — Copyright (c) 2026 Limelight IT Group