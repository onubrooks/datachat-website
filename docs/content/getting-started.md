# Getting Started

1. Install and run `uv run datachat dev`.
2. Configure provider keys and target database in Settings or onboarding wizard.
3. Run onboarding (`connect -> generate metadata -> ask first question`).

## Key requirements

- Target engine: PostgreSQL, MySQL, or ClickHouse.
- `LLM_OPENAI_API_KEY` is currently required for Chroma embeddings.
- System DB is PostgreSQL when you need registry/profiling/pending approvals.
