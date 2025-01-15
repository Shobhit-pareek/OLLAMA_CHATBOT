# OLLAMA_CHATBOT
Enhanced Q&amp;A Chatbot With Ollama

This project is a Streamlit-based web application for interacting with a sophisticated Q&A chatbot. Powered by the OLLAMA open-source LLM and LangChain, this chatbot provides intelligent and contextual responses to user queries. The app supports customizable response parameters for enhanced flexibility.

**Features**

**- Flexible Model Selection:** Choose between supported open-source models (e.g., phi3).
  
**- Customizable Responses:** Adjust response parameters such as temperature and max tokens via an intuitive sidebar.
  
**- Interactive Q&A Interface:** Provides real-time answers to user questions in natural language.
  
**- LangSmith Tracking:** Tracks and monitors the API calls and project details using LangSmith integration.

**How It Works**

**Prompt Engineering:**
A structured prompt guides the chatbot's responses.
The system role ensures consistent and helpful behavior.

**LangChain Integration:**
Combines LangChain's pipeline capabilities for clean input-to-output flow.
Tracks API calls using LangSmith for monitoring and debugging.

**User Interaction:**
Users ask questions via a simple interface, and the chatbot generates a response using the selected model.

**Parameter Tuning:**
Temperature: Controls response creativity.

Max Tokens: Determines the maximum length of the response

**Dependencies**
Install the required libraries: 
pip install streamlit langchain-core langchain-community python-dotenv

