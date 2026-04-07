# BuildWithClaudeAPI

This is a repository for my exercises of the course **Building with the Claude API** provided by Anthropic.

## Setup

### Create and activate the conda environment:

```bash
conda create -n claude_env python=3.11 -y
conda activate claude_env
```

### Install dependencies:

```bash
pip install -r requirements.txt
```

## Dependencies

This project uses the following Python packages:

- **anthropic** - The official Python SDK for Anthropic's Claude API, allowing you to interact with Claude models (Claude 3, Claude 3.5 Sonnet, etc.) programmatically
- **python-dotenv** - A library for reading environment variables from `.env` files, used to securely manage API keys and configuration without hardcoding them in source code