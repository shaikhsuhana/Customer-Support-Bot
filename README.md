# Customer-Support-Bot
AI Customer Support Chatbot This is a **GenAI-powered chatbot** designed for handling customer support queries.   It classifies user queries, analyzes sentiment, and provides AI-generated responses based on the category (*Technical, Billing, or General*).

## Features
- **Query Categorization**: Automatically detects whether the query is *Technical, Billing, or General*.
- **Sentiment Analysis**: Determines if a customer query is *Positive, Neutral, or Negative*.
- **AI-powered Responses**: Uses LLaMA-3 via Groq API for dynamic answers.
- **Modular & Extendable**: Built with LangGraph, making it easy to expand.

## Installation
### Prerequisites
- Python 3.x
- Git installed
- API Key for Groq (LLaMA model)


---

## Dependencies
- **LangChain**: AI model interaction
- **LangGraph**: Graph-based workflow handling
- **Groq API**: Uses LLaMA-3 for responses
- **Dotenv**: Securely loads API keys

## Usage
- Run the chatbot and input a customer query.
- The bot will classify the query and analyze its sentiment.
- Based on classification, the bot generates a response.
- Example:
