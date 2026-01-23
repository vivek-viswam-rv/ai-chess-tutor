# AI Chess Assistant

This AI-powered chess analytics enables users to discuss game strategies with an LLM in real time. It integrates live chess analysis via [Nibbler](https://github.com/rooklift/nibbler) and the [Stockfish chess engine](https://stockfishchess.org/), alongside an Ollama-hosted language model that answers chess-related questions in context.

Prompt engineering enforces domain-specific guardrails, and the chatbot is continuously provided with the current game state through system prompts.

For setup and configuration details, refer to the documenatation for:
- [Nibbler](https://github.com/rooklift/nibbler)
- [Stockfish chess engine](https://stockfishchess.org/)
- [Ollama](https://docs.ollama.com/)

The following tools/packages are being used:
| Tool             | Version |
|------------------|---------|
| Ollama           | 0.6.5   |
| Nibbler          | 2.5.1   |
| Stockfish Engine | 17.1    |
| Llama            | 3.1     |

![Game discussion](game-discussion.png)
