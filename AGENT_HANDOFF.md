# Agent Handoff

Last updated: 2026-06-15

Local project: `/Users/chanceneel/Projects/wireguard-apple`
Current branch snapshot: `cp-tools-version-5-5`
Dirty snapshot before this file: 0 changed/untracked paths

GitHub remotes:

- `origin`: `https://github.com/chanceneel/wireguard-apple`

GitHub push readiness snapshot:

- Antigravity MCP token check: GitHub API lookup for `chanceneel/wireguard-apple` redirects to `DeadStick-Digital/wireguard-apple`, where the token reports `push=true` and `admin=true`.
- Shell auth check: global `gh` default token was invalid on 2026-06-15. Run `gh auth status` before push.
- Remote hygiene note: consider updating the remote URL to the current GitHub owner before future push work.

## Start Here

1. Read `/Users/chanceneel/Projects/SuperAssistant/README.md`.
2. Run `git status -sb` and treat it as current truth.
3. Preserve unrelated local changes.
4. Continue from `Current Handoff` below.

## Handoff Rules

- Update this file before switching between Codex and Antigravity.
- Record active branch, summary, files touched, verification commands, known failures, and whether work is local-only, committed, pushed, or PR-backed.
- Do not store raw secrets, tokens, private keys, cookies, dashboard sessions, or credential-bearing URLs here.
- For GitHub pushes, remember that GitHub password auth is not valid for HTTPS Git operations. Use browser OAuth, SSH, or a PAT with repo/Contents write access.

## Model Routing

- Antigravity architect: `Gemini 3.1 Pro` for release-blocking dependency or signing decisions.
- Antigravity complex coder: `Gemini 3.5 Flash High` for multi-file dependency/build changes.
- Antigravity normal coder: `Gemini 3.5 Flash Medium` for scoped fixes, tests, docs, and routine debugging.
- Antigravity runner: `Gemini 3.5 Flash Low` for inspection, formatting, command interpretation, and low-risk edits.
- Codex routing: use `GPT 5.5 High` as the default architect/lead for first-pass design, scope control, implementation planning, ordinary architecture decisions, and normal final review; escalate to `GPT 5.5 xhigh` only for high-risk architecture, persistence/schema migrations, security-sensitive decisions, App Store/TestFlight/release decisions, major cross-system refactors, production incidents, or final review before risky external actions; use `GPT 5.4-mini` for coding/build/test/debug loops once the plan is settled, escalating only if implementation becomes ambiguous or risky.

## Current Handoff

- Active task: None recorded yet.
- Last agent: Codex created this bridge file.
- Summary: Baseline handoff file added for future Codex/Antigravity collaboration.
- Verification: Repo branch, remotes, dirty count, and GitHub token reachability were inspected.
- Next steps: Replace this section with the next real work item.
- Blockers: Shell `gh` auth must be repaired before terminal-driven pushes are reliable.
