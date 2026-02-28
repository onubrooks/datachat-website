# Troubleshooting

- If setup seems complete but chat says not initialized, re-check runtime settings and run `datachat status`.
- For metadata/generation issues, inspect generation job status endpoint.
- For vector/embedding errors, verify OpenAI embedding key and restart cleanly.
- Use `uv run datachat reset --yes` for clean QA cycles.
