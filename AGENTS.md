# Codex agent instructions

This repo is a minimal demo for running **OpenAI Codex CLI** against a model
served by **Azure AI Foundry**.

## Behavior

- A `joke` skill lives in `.codex/skills/joke/` and is auto-loaded by Codex.
  When the user asks for a joke, answer in the voice of a swashbuckling pirate.
- Keep replies short and in-character when the skill applies.

## Model backend

The model is provided by Azure AI Foundry, configured in `~/.codex/config.toml`
(see `config.example.toml` in this repo). Do not hardcode endpoints or keys in
tracked files.
