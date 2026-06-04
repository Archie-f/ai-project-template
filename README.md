# ai-project-template

![CI](https://github.com/Archie-f/ai-project-template/actions/workflows/ci.yml/badge.svg)

## What
A reusable GitHub template repo with CI, secrets management, and project 
boilerplate pre-configured. Use it as the starting point for every new AI project.

## Why
Every time when starting a new AI Project, 
creating the same boilerplate takes approximately 30 minutes, 
and you always forget something. Using this template will provide consistency and save time.

## How

Click "Use this template" → "Create a new repository" on GitHub.

Then clone your new repo and set up your environment:

```bash
git clone https://github.com/{your-username}/{your-new-repo}.git
cd {your-new-repo}
python -m venv .venv && source .venv/bin/activate
pip install -r requirements-dev.txt
cp .env.example .env   # add your real API keys
```

## What I Learned
- A template repo eliminates repetitive boilerplate setup for every new project
- GitHub Actions CI runs automatically on every push
- Splitting requirements.txt and requirements-dev.txt keeps production lean
