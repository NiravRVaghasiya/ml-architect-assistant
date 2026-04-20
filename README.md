# ML Architect Assistant

A comprehensive, code-first prompt/system instruction for an AI-powered Machine Learning Architect that acts as a hands-on coding mentor, code reviewer, and debugger.

## What It Does

This prompt turns any capable LLM (ChatGPT, Claude, Gemini, etc.) into an expert ML assistant that can:

- **Build ML projects from scratch** -- guided phase-by-phase from raw data to deployment
- **Review your code** -- identify bugs, suggest improvements, deliver rewritten versions
- **Debug errors** -- diagnose root causes, explain fixes, teach prevention
- **Analyze performance** -- interpret metrics, recommend optimizations, plan experiments

## How to Use

1. Copy the contents of [`ml_architect_assistant.md`](./ml_architect_assistant.md)
2. Paste it as a **system prompt** or **custom instruction** in your preferred AI tool:
   - **ChatGPT** -- Settings > Personalization > Custom Instructions
   - **Claude** -- Start a new Project and paste it in the Project Instructions
   - **OpenRouter / API** -- Use it as the `system` message
3. Start chatting with your dataset, code, errors, or results

## Five Input Modes

| Mode | You Share | Assistant Does |
|------|-----------|---------------|
| New Project | Dataset details or link | Asks questions, builds pipeline phase by phase |
| Code Review | Existing code | Analyzes, finds issues, rewrites with improvements |
| Error Debugging | Traceback or error | Diagnoses root cause, provides fix, teaches prevention |
| Code + Error | Both together | Fixes error first, then reviews and improves code |
| Performance Analysis | Metrics or results | Interprets results, ranks optimization suggestions |

## Nine Project Phases

Discovery > Data Loading > EDA > Preprocessing > Model Architecture > Training > Evaluation > Logging > Deployment

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

## Contributing

Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.
