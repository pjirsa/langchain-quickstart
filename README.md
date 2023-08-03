# Langchain Quickstart
Use this template repo to quickly create a devcontainer enabled environment for experimenting with [Langchain](https://python.langchain.com/docs/get_started/quickstart) 
and [OpenAI](https://openai.com/).

Included are several Jupyter notebooks that implement sample code found in the Langchain Quickstart guide.
1. demo.ipynb - Basic sample, verifies you have valid API key and can call the OpenAI service.
1. chains.ipynb - Your first (simple) chain.
1. embeddings.ipynb - Sample of generating embeddings for given prompt (from [Getting Started with LangChain: A Beginner’s Guide to Building LLM-Powered Applications](https://towardsdatascience.com/getting-started-with-langchain-a-beginners-guide-to-building-llm-powered-applications-95fc8898732c)).


## Setup
- Click [Use this template](https://github.com/pjirsa/langchain-quickstart/generate)
- Clone to your local machine -OR- open in Codespace
- In a terminal, run `pip install -r requirements.txt`
- Create a '.env' file at root of repo
- Add `OPENAI_API_KEY="<your key here>"` to .env file

## .env setup
### For OpenAI
- Create a '.env' file at root of repo
- Add `OPENAI_API_KEY="<your key here>"` to .env file

### For Azure OpenAI
```
# Use for Azure OpenAI
OPENAI_API_KEY="<your key>"
OPENAI_API_BASE="https://<your instance name>.openai.azure.com/"
OPENAI_API_TYPE="azure"
OPENAI_API_VERSION= "2023-05-15"
```
