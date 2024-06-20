# 📚 Local RAG

![local-rag-demo](demo.gif)

[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/8588/badge)](https://www.bestpractices.dev/projects/8588)
![GitHub Commit Activity](https://img.shields.io/github/commit-activity/t/jonfairbanks/local-rag)
![GitHub Last Commit](https://img.shields.io/github/last-commit/jonfairbanks/local-rag)
![GitHub License](https://img.shields.io/github/license/jonfairbanks/local-rag)

Offline, Open-Source RAG

Ingest files for retrieval augmented generation (RAG) with open-source Large Language Models (LLMs), all without 3rd parties or sensitive data leaving your network.

You have to have Ollama Server running :)

curl -fsSL https://ollama.com/install.sh | sh



# Install steps (try with WSL Ubuntu 22.04):

1. git clone https://github.com/HyperUpscale/local-rag-ollama-github-url.git
2. sudo apt update && sudo apt install python3-pip python3.10-venv -y
3. cd local-rag-ollama-github-url && source bin/activate
4. pip install -r requirements.txt
5. streamlit run main.py




Features:

- Offline Embeddings & LLMs Support (No OpenAI!)
- Support for Multiple Sources
    - Local Files
    - GitHub Repos
    - Websites
- Streaming Responses
- Conversational Memory
- Chat Export

Learn More:

- [Setup & Deploy the App](docs/setup.md)
- [Using Local RAG](docs/usage.md)
- [RAG Pipeline](docs/pipeline.md)
- [Planned Features](docs/todo.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Known Bugs & Issues](docs/todo.md#known-issues--bugs)
- [Resources](docs/resources.md)
- [Contributing](docs/contributing.md)
