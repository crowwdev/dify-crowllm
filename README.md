# CrowLLM for Dify

[CrowLLM](https://crowllm.com) is an OpenAI-compatible AI gateway: one endpoint and one key for 180+ models, with a zero-rated `:free` shelf next to the paid ids.

This plugin adds CrowLLM as a model provider in Dify.

## Setup

1. Create an account at [crowllm.com](https://crowllm.com) and copy an API key from the console.
2. In Dify, open **Settings → Model Provider → CrowLLM**, paste the key and save.
3. Pick one of the preset models, or add any other served id with **Add Model** (customizable model).

## Models

The plugin ships these presets:

- `deepseek-v4-flash`
- `glm-5.3`
- `kimi-k3`
- `claude-opus-4-7`
- `gemini-3.7-flash`

Any other id from `GET https://crowllm.com/v1/models` works through the customizable-model flow, including the free shelf (`qwen-3.8-27b:free`, ...). Free ids bill at zero and need no card; they are rate-limited.

## Connection

- Base URL (set by the plugin): `https://crowllm.com/v1`
- Auth: `Authorization: Bearer <your CrowLLM key>`
- Tools/function calling: supported (`tool_call`)
- Streaming: supported

## Links

- Website: https://crowllm.com
- Docs: https://crowllm.com/docs
- Source: https://github.com/crowwdev/dify-crowllm

## License

MIT for this plugin's code; the service itself is governed by CrowLLM's terms.
