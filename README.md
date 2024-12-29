# Chat with Websites

A Streamlit application that allows you to interact with website content using conversational AI. By inputting a website URL, the app retrieves its content, processes it into manageable chunks, and enables you to ask questions or have a conversation based on the website's content.

## Features

- **Conversational Interface**: Chat with website content using a user-friendly interface.
- **GROQ-powered LLM**: Utilizes the `llama-3.1-70b-versatile` model via the GROQ API for intelligent responses.
- **Dynamic Context Retrieval**: Employs a history-aware retriever chain to maintain contextual conversation.
- **Website Content Parsing**: Extracts and processes content from websites using `WebBaseLoader`.
- **Embeddings with HuggingFace**: Leverages `HuggingFaceInstructEmbeddings` for semantic search and context.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/chat-with-websites.git
   cd chat-with-websites
