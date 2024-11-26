# Hindi Chatbot for Law and Medical Assistance

## Project Overview

This project is a **Hindi chatbot** designed to provide expert assistance in the domains of **Law** and **Medicine**. It employs a **basic Ollama LLM** as the central orchestrator, while two fine-tuned Ollama models (specialized using **LoRA**) act as **AI Agents**. These agents are trained on the **OpenAI MMMLU Hindi datasets** for Law and Medicine, ensuring accurate, domain-specific responses. The chatbot utilizes the **Ollama framework**, enabling seamless interaction between the basic LLM and the specialized agents.

---

## Features

- **Central LLM Orchestration**  
  A basic Ollama LLM acts as the primary interface, dynamically routing queries to specialized agents.

- **Domain-Specific Expertise**  
  Separate fine-tuned agents for:
  - **Law**: Handles legal procedures, documentation, and rights-related queries.
  - **Medicine**: Addresses diagnostic, treatment, and health-related questions.

- **LoRA Fine-Tuning**  
  Both AI Agents are fine-tuned using **LoRA**, providing computationally efficient and targeted domain adaptation.

- **Hindi Language Support**  
  Entirely designed for native Hindi speakers, ensuring accessibility to legal and medical knowledge.

- **Interactive Chatbot**  
  Smooth integration of AI Agents through Ollama's framework for natural, responsive conversation.

---

## Technologies Used

- **Model Architecture**  
  - **Basic Ollama LLM**: Serves as the primary conversational model.  
  - **LoRA Fine-Tuned Agents**: Dedicated models for Law and Medicine.  

- **Datasets**  
  - **OpenAI MMMLU Hindi - Law**  
  - **OpenAI MMMLU Hindi - Medicine**

- **Programming Languages**  
  - Python for backend and integration logic.
