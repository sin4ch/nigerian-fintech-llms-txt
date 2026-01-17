# Nigerian Fintech llms.txt

A collection of [llms.txt](https://llmstxt.org/) files for Nigerian fintech APIs, designed to help Large Language Models better understand and work with these platforms.

## What is llms.txt?

[llms.txt](https://llmstxt.org/) is a standard for helping LLMs understand your documentation. Companies place it at the root of their docs site (e.g., `docs.example.com/llms.txt`) so AI tools can quickly find and use the right resources.

Each provider in this repository has a single **llms.txt** file containing:

- Documentation overview with guides, concepts, and SDKs
- Complete API reference with endpoints and methods

## Why did I make this?

While building the [Mono MCP server](https://github.com/sin4ch/mono-mcp) with coding agents, I found that LLMs struggled to extract relevant information from large documentation sites. These llms.txt files solve that problem - they're open source so these companies can adopt them to help developers build faster with AI.

Note: [Flutterwave already has llms.txt](https://developer.flutterwave.com/llms.txt) via Mintlify's [automatic generation](https://www.mintlify.com/docs/ai/llmstxt).

## Included Fintechs

| Provider | Category | Description |
|----------|----------|-------------|
| [Mono](https://mono.co) | Open Banking | Financial data access, payments, and identity verification APIs |
| [OPay](https://opayweb.com) | Payments | Payment gateway with cards, bank transfers, USSD, wallet, and POS solutions |
| [Paystack](https://paystack.com) | Payments | Payment processing, transfers, subscriptions, and terminal solutions |

## Usage

These files can be used with AI coding assistants, chatbots, or any LLM-powered tool that supports the llms.txt standard. I am really creating this so these companies adopt these into their product.

**With AI tools:** Point your LLM tool to the relevant llms.txt file to give it context about the API before asking integration questions.

## Contributing

Contributions are welcome! To add a new Nigerian fintech provider:

1. Create a new directory with the provider name
2. Add `llms.txt` with documentation overview and API reference (separated by `---`)
3. Follow the existing file format structure
4. Submit a pull request

## License

MIT License - see [LICENSE](LICENSE) for details.
