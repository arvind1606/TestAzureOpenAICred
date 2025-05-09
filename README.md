# TestAzureOpenAICred
This repository demonstrates how to integrate Azure OpenAI with LangChain using environment-based configuration.



---

## 🚀 Features

- Loads secure credentials from a `.env` file using `python-dotenv`
- Uses LangChain’s `AzureChatOpenAI` wrapper for LLM interaction
- Supports direct API access via `AzureOpenAI` client
- Demonstrates how to pass a system prompt and question
- Output is parsed and cleaned for presentation

---

## 🧪 Requirements

Install dependencies:

```bash
pip install openai langchain-openai python-dotenv
