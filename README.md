# local-llm-by-ollama
 This repository contains a Python script for a local AI chatbot using the Chainlit framework and the Ollama API. The chatbot is designed to simulate a helpful assistant, providing responses based on user input. It runs on the DeepSeek-R1 model, offering a local alternative to cloud-based AI services.

# Local LLM Chatbot

This project is a local AI chatbot built using the Chainlit framework and the Ollama API. It simulates a helpful assistant, providing responses based on user input, and runs on the DeepSeek-R1 model.

## Features

- **Local AI Interaction**: Utilizes the DeepSeek-R1 model for local AI processing, ensuring privacy and control over data.
- **Streamed Responses**: Implements token streaming for real-time message delivery.
- **Session Management**: Maintains user interaction history within a session for context-aware responses.
- **Tool Integration**: Supports tool-based steps for modular and extendable functionality.

## Model Information

This program currently uses the DeepSeek-R1 model for AI processing. However, it is designed to be flexible and can be adapted to use other open-source models such as LLaMA, GPT-Neo, and others. This allows users to choose a model that best fits their needs in terms of performance, resource requirements, and licensing.

## Requirements

- Python 3.x
- Chainlit
- Ollama

## Installation

 Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have the necessary API keys and configurations for Chainlit and Ollama.
2. Run the script to start the chatbot:
   ```bash
   python local-llm.py
   ```
3. Interact with the chatbot through the console or a connected interface.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.


## Contact

For questions or support, please open an issue in the repository or contact the maintainer at erfanrahaei5@gmail.com.
