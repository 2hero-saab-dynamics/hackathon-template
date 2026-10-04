# Team repository

Created from the hackathon template. Open it in a Codespace: Code → Codespaces → Create.
The machine size is pinned by the devcontainer; the Codespace is billed to the hackathon
organisation, not to your personal allowance.

## Models

Models are reached through 2Hero's OpenRouter, not through Azure directly. The Codespace
carries `OPENROUTER_BASE_URL` (https://openrouter.ai/api/v1, OpenAI-compatible). Your team's
key is `OPENROUTER_API_KEY`: take it from your team page in app.2hero.dev and add it as a
Codespaces secret for this repository (Settings → Secrets and variables → Codespaces), so it is
in the environment and never in the code. Pick a model slug from openrouter.ai/models, for
example `openai/gpt-5.4`, `openai/gpt-5.4-mini`, `openai/gpt-6-astra`, `openai/gpt-5.3-codex`,
`openai/text-embedding-3-large`, or the open-weight `openai/gpt-oss-120b`.
