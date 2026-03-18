# Search query generation experiment

Attempting evolutionary prompt improvement with [`valere`](https://github.com/guylemon/valere). Use a "strong" LLM to propose "weak" LLM prompt improvements; score and provide the results to the strong LLM for a new hypothesis to optimize the score.

- Task: Given a topic, generate a JSON array of 5 relevant search queries.

## Prerequisites

- XAI_API_KEY set for XAI LLM provider
- `ollama serve` running on the same machine as the experiment
- [`valere`](https://github.com/guylemon/valere) available in path

## Run

- **Llama 3.2:1b**: `./run_llama3_2_1b.sh`


