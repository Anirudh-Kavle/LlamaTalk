# LlamaTalk
## Table of Contents

- [Project Description](#Project-Description)
- [Dependencies](#Dependencies)
- [Setup](#Setup)
- [Features](#Features)
- [Usage](#Usage)
- [Contributing](#Contributing)

# Project Description

An interactive chat interface for GitHub repositories using LlamaIndex and Activeloop's Deep Lake. It allows users to query and interact with code repositories using natural language, providing an intuitive way to explore and understand codebases.

## Dependencies

Before you begin, ensure you have the following:

- Python 3.7 or newer
- An OpenAI API key
- An Activeloop Deep Lake account and API key
- A GitHub personal access token (classic)

## Setup 

```
git clone https://github.com/Anirudh-Kavle/LlamaTalk.git
cd LlamaTalk
```
```
pip install -r req.txt
```
Edit the .env file with:
```
GITHUB_TOKEN="your_github_token"
OPENAI_API_KEY="your_openai_key"
ACTIVELOOP_TOKEN="your_activeloop_token"
DATASET_PATH="hub://your_org/repository_vector_store"
```

# Features
- Index GitHub repositories using LlamaIndex
- Store indexed data in Activeloop's Deep Lake for efficient retrieval
- Query repositories using natural language.
- Support for multiple file types (Python, JavaScript, TypeScript, Markdown).
  

# Usage
- Run the main script:
  ```
  python main.py
  ```
- Enter the URL of the GitHub repository you want to chat with when prompted.
- Ask questions about the repository using natural language. The system will provide answers based on the repo.
- Type 'exit' to end the chat session.


# Contributing
Contributions to improve the project are welcome!.
