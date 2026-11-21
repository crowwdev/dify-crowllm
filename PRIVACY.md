# Privacy Policy — CrowLLM Dify Plugin

This plugin is a thin client for the CrowLLM API at https://crowllm.com.

## What the plugin sends

- Your CrowLLM API key, in the `Authorization` header of each request.
- The prompt messages, model parameters and (if provided) tool definitions you configure in Dify.

These are sent only to `https://crowllm.com/v1`. The plugin keeps no local storage, no telemetry and no logs beyond the Dify runtime's own console output.

## What CrowLLM stores

Requests are processed and billed by CrowLLM under its own privacy policy at https://crowllm.com/privacy. Usage metadata (tokens, model, timestamp) is retained for billing and abuse prevention; prompt content handling is described there.

## Data you should not send

Do not send secrets or personal data you are not permitted to share with a third-party inference provider. Use the provider's data controls and your own compliance review.

## Contact

support@crowllm.com
