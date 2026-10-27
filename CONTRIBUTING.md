# Contributing

1. `git checkout main && git pull`
2. `git checkout -b MSP-<number>-<short-name>` (the Jira key is required)
3. Commit small and often: `MSP-40: what changed (FR-010, FR-012)`
4. `git fetch origin && git rebase origin/main`, then `git push -u origin <branch>`
5. Open a PR titled `MSP-40: ... (FR-010)`. The assigned member raises it; fill in the template and tick the unit-test evidence box.
6. A different repo owner reviews and merges (Squash and merge) once CI is green. Never merge your own PR.
7. Never commit `.env`, secrets, model weights, pickle files or real molecular structures.

Shared files (docker-compose.yml, requirements*.txt, OpenAPI, config, migrations): tell the team in chat first. Only Ayushi creates database migrations.
