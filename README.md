# LangGraph End-to-End Course

A comprehensive course repository covering LangGraph from fundamentals to advanced agentic patterns. This course provides hands-on implementations of various RAG (Retrieval-Augmented Generation) architectures, agent frameworks, and multi-agent systems using LangGraph.

## 📚 Course Overview

This repository contains a complete learning path for mastering LangGraph, from building agents from scratch to implementing sophisticated multi-agent systems. Each module includes practical Jupyter notebooks with working examples and implementations.

## 🎯 Course Modules

### Prerequisites
- **Pre-requist(Assistant,RAG,Tools,Agents)**: Foundation concepts including assistants, RAG, tools, and agents

### Core LangGraph Concepts
- **langgraph_introudction**: Introduction to LangGraph fundamentals
- **Langgraph_from_scratch**: Building LangGraph implementations from scratch
- **Common_Agentic_Pattern**: Essential agentic patterns including:
  - Tool calling
  - Human-in-the-loop agents
  - Checkpoints and breakpoints
  - Structured output from agents

### RAG Architectures
- **AdaptiveRAG**: Adaptive Retrieval-Augmented Generation implementation
- **AgenticRAG**: Agent-based RAG systems
- **CorrectiveRAG**: Corrective RAG with error detection and correction
- **SelfRAG**: Self-reflective RAG architecture

### Advanced Topics
- **Agents_From_Scratch**: Building AI agents from scratch:
  - Basic agent implementation
  - ReAct (Reasoning + Acting) agent pattern
- **MultiAgent_with_LangGraph**: Multi-agent systems:
  - Collaborative agents
  - Hierarchical agent architectures
  - Supervised agent systems
- **memory**: Memory management in LangGraph agents
- **langgraph_chatbot**: Building chatbots with LangGraph

### Practical Applications
- **Usecase**: Real-world use cases and applications

## 🛠️ Technologies & Dependencies

- **LangGraph**: Core framework for building stateful, multi-actor applications
- **LangChain**: LLM application framework
- **Vector Stores**: ChromaDB, FAISS
- **LLM Providers**: 
  - Google Generative AI
  - Groq
  - Mistral AI
  - Hugging Face
- **Search & Tools**: Tavily, Wikipedia, Google Search
- **Embeddings**: Sentence Transformers, Nomic

## 📋 Prerequisites

- Python >= 3.13
- Jupyter Notebook or JupyterLab
- API keys for LLM providers (as needed)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd LangGraph-End-to-End-Course
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   
   Or using `uv` (recommended):
   ```bash
   uv sync
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add your API keys:
   ```
   OPENAI_API_KEY=your_key_here
   GOOGLE_API_KEY=your_key_here
   GROQ_API_KEY=your_key_here
   TAVILY_API_KEY=your_key_here
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## 📁 Project Structure

```
LangGraph-End-to-End-Course/
├── AdaptiveRAG/              # Adaptive RAG implementations
├── AgenticRAG/               # Agentic RAG systems
├── Agents_From_Scratch/      # Building agents from scratch
├── Common_Agentic_Pattern/   # Common agentic patterns
├── CorrectiveRAG/            # Corrective RAG implementations
├── data/                     # Sample data and documents
├── langgraph_chatbot/        # Chatbot implementations
├── Langgraph_from_scratch/   # LangGraph fundamentals
├── langgraph_introudction/   # Introduction to LangGraph
├── langgraph_presentation/   # Course presentation materials
├── memory/                   # Memory management
├── MultiAgent_with_LangGraph/# Multi-agent systems
├── Pre-requist(...)/         # Prerequisites and foundations
├── SelfRAG/                  # Self-RAG implementations
├── Usecase/                  # Practical use cases
├── requirements.txt          # Python dependencies
├── pyproject.toml           # Project configuration
└── README.md                # This file
```

## 📖 Usage

1. Start with the **Pre-requist** module to understand the foundational concepts
2. Progress through **langgraph_introudction** and **Langgraph_from_scratch** for core concepts
3. Explore **Common_Agentic_Pattern** for essential patterns
4. Dive into specific RAG architectures based on your interests
5. Advance to **MultiAgent_with_LangGraph** for complex multi-agent systems

Each notebook is self-contained and includes:
- Clear explanations of concepts
- Working code examples
- Practical implementations
- Best practices and patterns

## 🔑 Key Features

- **Comprehensive Coverage**: From basics to advanced multi-agent systems
- **Hands-on Learning**: Practical Jupyter notebooks with working examples
- **Multiple RAG Architectures**: Adaptive, Agentic, Corrective, and Self-RAG
- **Real-world Applications**: Use cases and practical implementations
- **Modern Stack**: Latest LangGraph and LangChain features

## 📝 Notes

- Ensure you have the necessary API keys configured before running notebooks
- Some notebooks may require specific data files from the `data/` directory
- The course is designed to be followed sequentially, but modules can be explored independently

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the existing notebooks and suggest improvements or additional examples.

## 📄 License

This course repository is provided for educational purposes. Please refer to the individual dependencies for their respective licenses.

---

**Happy Learning! 🚀**
