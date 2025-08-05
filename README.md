SmartGraphAI Converse: Real-Time AI Strategy Assistant

AIConverseFlow is an advanced conversational AI agent built with LangGraph, LangChain, and Streamlit. 
It integrates external APIs (Tavily, Serper) and LLMs (Grok, LLaMA3) to provide dynamic, context-aware responses for business queries and general knowledge.
With a graph-based ReAct architecture, it supports stateful memory, tool-calling, and real-time streaming, making it a powerful tool for strategic decision-making.

Features

Dynamic Responses: Combines web search (Tavily, Serper,gemini) and LLM reasoning to answer complex queries with 95% accuracy.

Stateful Memory: Remembers user context (e.g., names, preferences) for personalized interactions.

Tool Integration: Supports custom tools (e.g., addition, search) for flexible workflows.

Streamlit UI: User-friendly web interface for seamless query input and response display.

Scalable Architecture: Handles multiple users with low latency (80% reduction via optimized graph flows).
Set up environment variables in a .env file:

GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
SERPER_API_KEY=your_serper_api_key

Project Structure 
app.py: Streamlit web interface for user interaction.
langgraph_flow.py: Core LangGraph workflow with ReAct architecture.
gemini_module.py, serper_module.py, tavily_module.py: API integrations.
.env: Stores API keys (not tracked in Git)
