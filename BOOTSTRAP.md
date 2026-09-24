# BOOTSTRAP.md

Compatibility entrypoint for agent-specific bootstraps.

This repo now keeps agent-specific adapters under `claude/`, `codex/`, and `gemini/`. Existing install snippets may still fetch this root file, so do not treat it as the full procedure.

If you are running in Claude Code, fetch the Claude bootstrap procedure with:

```sh
gh api "repos/ddmms/elephant-goldfish/contents/claude/BOOTSTRAP.md?ref=ddmms" -H 'Accept: application/vnd.github.raw'
```

Then follow that procedure to set up the Claude Code elephant/goldfish workflow.

If you are running in Codex, do not install the Claude adapter from this root file. Fetch the Codex bootstrap procedure with:

```sh
gh api "repos/ddmms/elephant-goldfish/contents/codex/BOOTSTRAP.md?ref=ddmms" -H 'Accept: application/vnd.github.raw'
```

For Gemini CLI, fetch:

```sh
gh api "repos/ddmms/elephant-goldfish/contents/gemini/BOOTSTRAP.md?ref=ddmms" -H 'Accept: application/vnd.github.raw'
```
