# LangChain-for-LLM-Application-Development

## Purpose
This repository is dedicated to the development of applications using LangChain for Large Language Models (LLMs). It provides various examples and tutorials to help users understand and implement LangChain in their projects.

## Installation
To install the required dependencies, run the following command:
```bash
pip install -r requirements.txt
```

## Usage
This repository contains several Jupyter notebooks that demonstrate different aspects of LangChain for LLM application development.

### L1-Model_prompt_parser.ipynb
This notebook covers the following topics:
- Direct API calls to Gemini
- API calls through LangChain:
  - Prompts
  - Models
  - Output parsers

### L2-Memory.ipynb
This notebook covers the following topics:
- ConversationBufferMemory
- ConversationBufferWindowMemory
- ConversationTokenBufferMemory
- ConversationSummaryMemory

### L3-Chains.ipynb
This notebook covers the following topics:
- LLMChain
- Sequential Chains
  - SimpleSequentialChain
  - SequentialChain
- Router Chain

### L4-QnA.ipynb
This notebook covers the following topics:
- Q&A over Documents
- Using embeddings for document retrieval
- Building a retrieval-based QA system

### L5-Evaluation.ipynb
This notebook covers the following topics:
- Example generation
- Manual evaluation (and debugging)
- LLM-assisted evaluation
- LangChain evaluation platform

### L6-Agents.ipynb
This notebook covers the following topics:
- Using built-in LangChain tools: DuckDuckGo search and Wikipedia
- Defining your own tools

## Contribution Guidelines
We welcome contributions to this repository. If you have any improvements or new examples to add, please follow these steps:
1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Commit your changes
4. Push the branch to your fork
5. Create a pull request

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
