# LangChain Project Showcase

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/LangChain-0.1.19-brightgreen.svg" alt="LangChain Version">
  <img src="https://img.shields.io/badge/Streamlit-1.33.0-orange.svg" alt="Streamlit Version">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Released under the MIT license." />
  </a>
</p>

## Overview

This repository is a comprehensive collection of hands-on examples demonstrating the power and versatility of the LangChain framework. Each example is a self-contained application showcasing a specific use case, from question-answering with documents to text summarization and web search integration. This project serves as a practical guide and a starting point for building sophisticated applications powered by Large Language Models (LLMs).

## ✨ Features

This showcase includes a variety of examples, each in its own directory:

*   **📄 All-in-One:** A comprehensive application combining multiple LangChain features.
*   **💾 Chroma Summary:** Summarize documents using ChromaDB for vector storage and retrieval.
*   **💬 Gemini Chat PDF:** Chat with your PDF documents using Google's Gemini models.
*   **🔍 Helicone Monitoring:** Integrate Helicone to monitor and analyze LLM requests.
*   **📰 News Summary:** Summarize the latest news articles from various sources.
*   **🌲 Pinecone QA:** Build a Question-Answering system using Pinecone as the vector store.
*   **📝 Pinecone Summary:** Summarize text using Pinecone for efficient indexing.
*   **🌐 Search:** A generic search application powered by LangChain.
*   **🕵️‍♂️ Search with Tavily:** Enhance search capabilities with the Tavily Search API.
*   **✍️ Text Summary:** A straightforward example of text summarization.
*   **🔗 URL Summary:** Provide a URL and get a concise summary of its content.

## 🛠️ Tech Stack

This project is built with a modern, Python-based stack:

*   **[LangChain](https://www.langchain.com/):** The core framework for developing applications powered by language models.
*   **[Streamlit](https://streamlit.io/):** For creating and sharing beautiful, custom web apps for machine learning and data science.
*   **[OpenAI](https://openai.com/):** Leverages powerful models like GPT-3.5 and GPT-4.
*   **[ChromaDB](https://www.trychroma.com/):** Open-source embedding database.
*   **[Pinecone](https://www.pinecone.io/):** Managed vector database for high-performance AI applications.
*   **[Google Gemini](https://deepmind.google.com/technologies/gemini/):** Google's next-generation multimodal models.
*   **And many more...** (see `requirements.txt` in each example directory).

## 🚀 Getting Started

To get started with these examples, follow these steps:

### Prerequisites

*   Python 3.9 or higher
*   An API key from OpenAI (and other services like Pinecone or Helicone, depending on the example).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/tarak6984/langchain-examples.git
    cd langchain-examples
    ```

2.  **Navigate to an example directory:**
    Each example is self-contained. Choose one to start with.
    ```bash
    cd all-in-one
    ```

3.  **Install the dependencies:**
    Each example has its own `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up your environment variables:**
    Most examples will require API keys. It's best practice to store these as environment variables. You can create a `.env` file in the example's directory and add your keys:
    ```
    OPENAI_API_KEY="your_openai_api_key"
    PINECONE_API_KEY="your_pinecone_api_key"
    PINECONE_ENVIRONMENT="your_pinecone_environment"
    ```

## 💡 Usage

Once the setup is complete, you can run the Streamlit application for any of the examples:

```bash
streamlit run app.py
```

This will start a local web server and open the application in your browser, allowing you to interact with the LangChain-powered app.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
