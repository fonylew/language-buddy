# Language Buddy

## Set up

If you use Python `uv`
```bash
uv sync
uv run adk web
```

## SSL Setup
For HTTPS setup, we need to export `SSL_CERT_FILE`
```bash
export SSL_CERT_FILE=$(python -m certifi)
```

## Reference
Official documentation for ADK Streaming: https://google.github.io/adk-docs/get-started/streaming/quickstart-streaming

Documentation on ADK Streaming: https://google.github.io/adk-docs/streaming/

For more information about Gemini Live API model: https://ai.google.dev/gemini-api/docs/models#live-api
