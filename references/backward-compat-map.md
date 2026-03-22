# Backward compatibility map

## Naming

- Public/local OpenClaw skill command: `/claw-notebooklm`
- Compatibility alias: `/notebooklm`
- Upstream project/CLI name: `notebooklm`

## Compatibility rule

When a user says any of the following, route to this skill:
- `/claw-notebooklm`
- `/notebooklm`
- `NotebookLM`
- `notebooklm`
- `notebook lm`

## Command compatibility

- Actual shell command stays `notebooklm`
- Wrapper command is `claw-notebooklm`
- Upstream docs/examples using `notebooklm ...` remain valid as-is

## Breaking changes

None for existing direct `notebooklm` CLI usage.

## Migration note

This repo standardizes the local skill surface as `claw-notebooklm` so the naming matches `NotebookLM` / `notebooklm` consistently.
