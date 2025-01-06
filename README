# 🤖 How to Build a Simple Chatbot with Stored Memory using LangChain

This project will guide you through building a **simple chatbot LLM app** that can have conversations, remember previous interactions, and store the memory in a **JSON file**. 🚀

### 🗣️ Features of the Chatbot:
- **Conversation**: The chatbot will interact with users like a human.
- **Memory**: The chatbot will remember previous conversations.
- **Persistent Storage**: The chatbot will store memory in a **JSON file** for future interactions.

### 💡 What is a Chatbot?

A **chatbot** is a software application designed to simulate a conversation with human users. It uses **artificial intelligence (AI)** to understand what someone is saying and to respond with appropriate answers. Chatbots can be used for various purposes such as:
- Customer support 🤝
- Providing information ℹ️
- Entertainment 🎮

Think of it as texting with a program that can help you with tasks and answer questions.

## 🧠 Key Concepts Included:
### 🗣️ Chat Model vs. LLM Model:
- **Chat Model**: Focuses on messages (conversation-based).
- **LLM Model**: Uses raw text (language model-based).

### ⏳ Chat History:
- The **Chat Model** can store the conversation history, allowing it to remember previous interactions. This memory helps the chatbot make more meaningful and relevant responses.

## ⚠️ Trick to Avoid Deprecation Warnings from LangChain:
In this exercise, we will use the LangChain legacy chain `LLMChain`, which works well but throws a deprecation warning. To avoid this, use the following code snippet:

```python
# Example code to avoid deprecation warnings
from langchain.chains import LLMChain

# Setup LangChain LLMChain with the correct parameters
llm_chain = LLMChain(...)

# Run your chatbot
response = llm_chain.run("Your query here")
