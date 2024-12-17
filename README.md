# Hindi Chatbot for Law and Medical Assistance

## Project Overview

This project introduces a Hindi chatbot designed to assist users with Law and Medical queries. The system employs an Ollama LLM as the primary conversational interface and integrates two domain-specialized AI Tools, fine-tuned using LoRA (Low-Rank Adaptation). These tools, trained on OpenAI MMMLU Hindi datasets for Law and Medicine, provide precise and context-aware answers in their respective fields.
The chatbot seamlessly combines the versatility of the base Ollama LLM with the specialized knowledge of the fine-tuned LLMs, creating a robust, interactive solution for Hindi-speaking users.

---

## Features

- **Central LLM Orchestration**  
  A llama-3.2-90b-vision-preview LLM acts as the primary LLM, dynamically routing queries to specialized tools.

- **Domain-Specific Expertise**  
  Separate fine-tuned LLM tools for:
  - **Law**: Handles legal procedures, documentation, and rights-related queries.
  - **Medicine**: Addresses diagnostic, treatment, and health-related questions.

- **LoRA Fine-Tuning**  
  Both AI Tools are fine-tuned using **LoRA**, providing computationally efficient and targeted domain adaptation.

- **Hindi Language Support**  
  Entirely designed for native Hindi speakers, ensuring accessibility to legal and medical knowledge.

---

## Technologies Used

- **Model Architecture**  
  - **Basic Ollama LLM**: Serves as the primary conversational model.  
  - **LoRA Fine-Tuned Tools**: Dedicated models for Law and Medicine.  

- **Datasets**  
  - **OpenAI MMMLU Hindi - Law**  
  - **OpenAI MMMLU Hindi - Medicine**

- **Programming Languages**  
  - Python for backend and integration logic.
