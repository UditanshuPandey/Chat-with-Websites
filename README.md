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
2. **Set up a virtual environment (optional)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
4. **Set up environment variables**: Create a .env file in the root directory and add your GROQ API key:
   ```bash
   GROQ_API_KEY=your_groq_api_key_here
   
## Usage
1. **Run the application**:
   ```bash
   streamlit run app.py
2.  **Access the app**:Open your browser and navigate to *http://localhost:8501*.
3. **Chat with a website**:
   - Enter a website URL in the sidebar.
   - Type your queries in the chat box to interact with the website content.
  
## Future Enhancements
   - Future Enhancements
   - Add support for handling multiple URLs.
   - Enable conversational memory persistence across sessions.
   - Enhance error handling for unsupported or inaccessible websites.
