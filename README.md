# Claude Build Planner

A free, single-file tool that routes any project to the right Claude model
(Haiku / Sonnet / Opus), the right app (Chat / Cowork / Code), and — for
Claude Code — the right /effort level, then writes the paste-ready prompt.
Runs entirely in the browser: no server, no API key, no account.

**Live site:** https://camprotiva1234-cmyk.github.io/AI-Helper-Tool/?v=1

## Testing
Append `?test` to the URL to run the built-in regression suite.
All tests must pass before pushing changes.

## Releasing a change
1. Edit `index.html`
2. Open it with `?test` — must be all green
3. Bump the version in the footer (and `SCHEMA_VERSION` in the JS if
   routing logic or the saved-state shape changed)
4. Commit and push — GitHub Pages redeploys automatically in ~1 minute
