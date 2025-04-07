# Run Gemma3:12B LLM locally with Ollama and Langchain

These Jupyter Notebooks allow you to easily run the Gemma3:12B LLM or any others locally using Ollama and Langchain.  It's a convenient way to experiment with this powerful model without relying on external APIs.
Note : The contents of READMe file is also available in Lovely Persian via README_FA.md file.

## List of Projects
*   **Simple ChatBot based on gemma3:12b (or any other)**
*   **RAG ChatBot using a knowledge base with persian contexts for answering accuratly**
*   **Maybe Continue...**

## Setup

It does not have any seprated setup. just run every notebook cells sequentially from the first.

## Usage

Feel free to use it for good purposes. these are for you without any api call for security of data and requests without any pay.

## Screenshot

![chat_history](LLM-RAG/Screenshots/RAG.png)

## Potential Issues & Troubleshooting

*   **Ollama Not Found:**  Ensure Ollama is installed correctly and accessible in your system's PATH.  Verify Ollama is running.
*   **Download Errors:** If you encounter errors during the model download, check your internet connection and available disk space.  Try clearing your Ollama cache: `ollama cache clean`.
*   **Resource Constraints:** Running large language models requires significant computational resources (CPU, RAM, GPU).  If you experience performance issues or errors, try using a smaller model of gemma3 or another.
*   **Model Version Conflicts:**  Make sure the model name used in the notebook (`gemma3:12b`) matches the version you have pulled with Ollama.

## Contributing

Feel free to fork this repository and submit pull requests for improvements or bug fixes.

## License

MIT License
