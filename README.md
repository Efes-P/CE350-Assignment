ask - Bash CLI for LLM Interactionask is a lightweight Bash command-line tool designed to interact with OpenAI-compatible Chat Completion APIs. This project was developed as part of the CE 350 assignment.

Features: Supports both command-line arguments and piped input. Compatible with any OpenAI-compliant API (e.g., Groq, OpenAI, Anthropic via proxy). Output is optimized for CLI usage: concise and plain text.

Prerequisites to run this tool: you must have the following installed: curl jq 

Installation & Setup:
1)Clone the repository.
2)Ensure the script is executable: chmod +x ask
3)Set the required environment variables in your shell (e.g., in .bashrc or .zshrc):
export ASK_API_URL="https://api.your-provider.com/v1/chat/completions"
export ASK_MODEL="your-model-name"
export ASK_API_KEY="your_api_key_here"

Known Limitations 
API Dependency: Requires an active internet connection and a valid OpenAI-compatible API key.
Rate Limits: Subject to the rate limits imposed by your chosen API provider.
Context Length: Large files piped into the tool may exceed the model's token limit.

License 
This project is licensed under the MIT License.

Contributor Guide 
We welcome contributions! To contribute:
Fork the repository.
Create a new branch for your feature or bugfix.
Ensure your code follows standard Bash formatting.
Provide documentation for any new features.

Submit a Pull Request with a clear description of your changes.
