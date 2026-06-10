**What's covered in the doc**

Triggers (on:) — push, pull_request with all filter options (branches, paths, tags, types), schedule with cron syntax, workflow_dispatch with all input types (string, boolean, choice), plus a complete table of all 24 available events including workflow_run, release, repository_dispatch, and more.

Jobs — runs-on with every GitHub-hosted runner spec, needs: with parallel vs sequential patterns and how to pass outputs between jobs, if: with every condition pattern (branch checks, event types, previous job results, actor checks, combined logic), matrix strategy with exclude/include, environment: for deployment gates, and permissions: for least-privilege token control.

Steps — uses: with all 5 source formats and a table of 20 essential actions, run: with multi-line scripts, shell selection, working-directory, GITHUB_OUTPUT, GITHUB_ENV, and continue-on-error, plus with: and env: at step/job/workflow level.

Contexts & expressions — full table of every ${{ }} context value (github.*, runner.*, secrets.*, needs.*, steps.*, matrix.*), all built-in functions (contains, startsWith, hashFiles, toJSON, success, failure, always), and secrets vs variables comparison.

Full example — a complete working workflow using everything: matrix CI, auto-PR, Docker multi-platform build, environment approval gate, SSH deploy.
Official docs links — 13 direct links to the exact GitHub docs pages for each topic.
