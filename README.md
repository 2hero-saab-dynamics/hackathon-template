# Team repository

Created from the hackathon template. Open it in a Codespace: Code → Codespaces → Create.
The machine size is pinned by the devcontainer; the Codespace is billed to the hackathon
organisation, not to your personal allowance.

## Models

Models are reached through 2Hero's OpenRouter, not through Azure directly. The Codespace
carries `OPENROUTER_BASE_URL` (https://openrouter.ai/api/v1, OpenAI-compatible). Your team's
key is already in your Codespace as `OPENROUTER_API_KEY`: the organisers set it as a Codespaces
secret on this repository, so it is in the environment and never in the code, and nobody has
to copy it anywhere. Ask in the support channel if it is missing or spent. Pick a model slug from openrouter.ai/models, for
example `openai/gpt-5.4`, `openai/gpt-5.4-mini`, `openai/gpt-6-astra`, `openai/gpt-5.3-codex`,
`openai/text-embedding-3-large`. Build with today's frontier models; on-premises
equivalents follow, so there is no local or open-weight model in this environment.
