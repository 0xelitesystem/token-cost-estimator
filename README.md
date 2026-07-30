# Token Cost Estimator

This tool estimates the token count of a prompt and the API cost of running it at any provider's rates, with no API key and no calls. It counts input tokens from the pasted text, takes an expected output size and the per-million-token prices, and returns the cost per call and across many calls.

**Live demo:** https://0xelitesystem.github.io/token-cost-estimator/

## What it does

Paste the prompt you would send. The tool estimates input tokens using a rough four-characters-per-token rule, takes your expected output tokens and the number of calls, and applies the input and output prices per million tokens that you enter. It returns tokens per call, cost per call, and the total across all calls, split into input and output.

Because you enter the rates, it works for any provider. Token counts are estimates; the true count depends on the model's tokenizer, so treat the result as a planning figure, not a bill. This fits the bring-your-own-key approach: you control the provider and the cost.

## Aesthetic

A yellow telegram wire form: banded header, monospace body, and stop markers between the character count and the token estimate.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright (c) 2026 0xelitesystem.
