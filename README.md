# QA-Chatbot-HuggingFace
# 🤖 Chatbots with Hugging Face

This repository contains two chatbot projects built using Hugging Face Transformers. Both demonstrate how to leverage pretrained NLP models for interactive conversational AI.

---

## 1. 📝 Question Answering Chatbot
A chatbot that answers user questions based on a provided context paragraph (e.g., news snippet, Wikipedia article, or Hugging Face blog excerpt).

### Features
- Uses a pretrained Hugging Face Question-Answering model.  
- Accepts custom context text and multiple user questions.  
- Returns precise answers grounded in the given context.  
- Verified with 3–5 test questions per context.  

### Example
**Context:**  
*"Hugging Face is a company specializing in natural language processing (NLP) models and open-source AI tools."*

**Q&A:**  
- **Q:** What does Hugging Face specialize in?  
  **A:** Natural language processing (NLP) models and open-source AI tools.  
- **Q:** Is Hugging Face open-source?  
  **A:** Yes, it provides open-source AI tools.  
- **Q:** What kind of company is Hugging Face?  
  **A:** A company specializing in NLP models and AI tools.  

---

## 2. 💬 Conversational Chatbot (BlenderBot Small)
An interactive chatbot built using **Facebook’s BlenderBot Small (90M parameters)**. Runs on CPU, making it lightweight and accessible in Colab.  

### Features
- Open-domain conversational AI.  
- Built with Hugging Face `transformers` library.  
- Deployable in Google Colab with Gradio for interaction.  
- Demonstrates use of dialogue generation models.  

---

## 🚀 How to Run
1. Open any notebook in **Google Colab**.  
2. Install dependencies:
   ```bash
   pip install transformers gradio

📌 Skills Demonstrated

Hugging Face Transformers (Question Answering + Dialogue models)

Building interactive chatbots

Model deployment in Google Colab
