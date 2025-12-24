# Copilot Agent Instructions (Project Rules)

- Do not change CSV column names or formats without explicit migration notes.
- Keep changes small and safe. Prefer adding new files over rewriting old ones.
- Every change must include:
  1) clear logs
  2) basic smoke test steps in the PR description
- Never hardcode secrets/keys. Use environment variables.
- If a change can break existing runs, explain it and add a fallback.
