# __PROJECT_NAME__

__DESCRIPTION__

<!-- template:start -->
> [!IMPORTANT]
> **This is embergershared/repo-template**, the starting point for new embergershared
> projects. Create a repository with **Use this template**, clone it, then run once
> (PowerShell, in its folder):
> ```powershell
> ./scripts/Initialize-Repo.ps1 -Description '<one line about the project>' -Stacks dotnet,python
> ```
> It fills in the placeholders, moves the description into **Overview** and the note below to
> the bottom, removes the stack you don't use, sets the repository and its security features
> up, and opens the first issue and PR. See [docs/template.md](docs/template.md) for
> everything the template contains.
<!-- template:end -->

> [!NOTE]
> This is a personal project, shared as is to help others. It is not an official Microsoft
> product and is not supported by Microsoft. Review and test it before using any part of it
> in your environment. See [docs/SUPPORT.md](docs/SUPPORT.md).

## Overview

<!-- Keep this section: a few lines on what the project does and for whom. Initialize-Repo.ps1
     puts the project's description first. The details go in docs/. -->

## Quick start

<!-- Keep this section: the few commands that take a new user from a clone to a first run,
     each with where it runs. The full walkthrough stays in docs/getting-started.md. -->

## Contents

<!-- Keep this README short: the Overview and Quick start above, then this table of contents of
     the pages, the license and the personal-project note. Background, how-tos and long
     explanations go in docs/, one page per topic. -->

**Use it**

| Page | What it covers |
|---|---|
| [docs/getting-started.md](docs/getting-started.md) | **Start here:** build, run and test the project locally |
| [docs/SUPPORT.md](docs/SUPPORT.md) | Questions, bugs, and what support to expect |
| [docs/CHANGELOG.md](docs/CHANGELOG.md) | Changes |

**Contribute**

Every change starts with an issue, gets its own `<type>/<issue>-<slug>` branch, and reaches
`main` only through a PR that closes the issue.

| Page | What it covers |
|---|---|
| [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md), [docs/CODE_OF_CONDUCT.md](docs/CODE_OF_CONDUCT.md) | How to contribute |
| [.github/copilot-instructions.md](.github/copilot-instructions.md) | The full rules, for people and AI coding assistants |
| [docs/ci-cd.md](docs/ci-cd.md) | CI/CD workflows, public logs, ruleset, security settings, repository variables |
| [docs/supply-chain.md](docs/supply-chain.md) | Package feeds, age gate, lock files |
| [docs/database.md](docs/database.md) | Database migrations, backups, rollback |
| [docs/decisions/](docs/decisions/) | Decision records |
| [docs/SECURITY.md](docs/SECURITY.md) | Reporting a vulnerability |

## License

[MIT](LICENSE)
